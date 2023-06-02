# Friday Night Funkin' - DOGEngine

DOGEngine is a [Friday Night Funkin'](https://ninja-muffin24.itch.io/funkin) engine made in [Godot 4.0](https://godotengine.org/). To use this engine, you must have knowledge about Godot and GDScript.
If you want to learn how to use DOGEngine properly, you should read this file, which contains information about everything you should know before starting to create your mod.

# Sound System
DOGEngine handles sound and music in a different way than Friday Night Funkin' and Godot.


# ***play_sound(sound: String, volume_db: float)***

Plays a sound, having *sound* as the sound path, and *volume_db* as the sound volume.
It's important to note that you don't have to add *"res://Assets/Sounds/"* and *".ogg"* in *sound*
