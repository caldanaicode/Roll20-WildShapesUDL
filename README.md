# Roll20-WildShapesUDL
UDL update for ocangelo's WildShapes script, located at https://github.com/ocangelo/roll20

Because this is not an official update at the moment, it is not ready for public consumption. It is more of a starting point for people who would like to have WildShapes work properly with UDL.

**_Important_**: If you use this with existing WildShapes data it will not work out of the box, because the old state data does not match the state data that this code utilizes. You can force an update to the state settings by looping through existing shapes and setting their "SETTINGS.SENSES" to the default config. The best place to do that is in the script's "start" function near the bottom. If there is enough interest in this, perhaps I'll come back and make it officially updateable, with ocangelo's blessing, of course.
