# Procedural Saver/Loader
GDScript saver_loader.gd can save and load scene trees of arbitrary structure. It persists data from procedural and non-procedural objects – but only what you tell it to persist! Saves and loads are very fast because we don't save whole objects.

This system is used in [I, Voyager](https://ivoyager.dev) to save/load a procedurally built Solar System with >100 planets & moons and up to 600,000+ asteroids. Our save/load times with an ssd drive are on the order of ~1 second!

For detailed how-to-guide, see [here](https://ivoyager.dev/forum/index.php?p=/discussion/26/how-to-guide-save-load-persistence-in-your-project).
