# Global Conflict Visualization

## the story

My colleague (Jeffrey Scarmazzi)[https://github.com/Jwmazzi] and I presented a talk called "Leveling Up as a Unity 3D Developer" @ (Esri Developer Summit 2022.)[https://devsummit2024.esri.com/flow/esri/24epcdev/deveventportal/page/detailed-agenda?rsource=https%3A%2F%2Fwww.esri.com%2Fen-us%2Fabout%2Fevents%2Fdevsummit%2Fagenda%2Fagenda%2Fdetail&date=2022-03-10&Type=Demo+Theater+Presentation&Topic=3D] Our goal was to share what we had learned about learning Unity with an audience of traditional GIS developers-- people interested in game engines, but unsure of how to start building apps. As part of the presentation, we created a data visualization of real-time mentions of conflict around the world, by:
- Requesting the latest records from the GDELT Project when the scene loads
- Rendering a particle system to represent each record, placed at its real-world location, using the global viewing mode in the ArcGIS Maps SDK for Unity
- Displaying attributes of the records on hover
- Modeling a globe arm + base in Blender, and modifying the built-in ArcGIS Camera Controller to spin the globe underneath the arm.

## coming soon

After the success of the talk, we're currently at work enriching the visualization by connecting to the GDELT Mentions table to show when events describe each other, and building out the UI in the very last image below. We intend to share the repo publicly soon, and until then, here's an early prototype of the (arm controller.)[https://github.com/lillie-bahrami/old-fashioned-globe]

## gallery