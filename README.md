Thanks to original creator: [https://www.reddit.com/r/GlobalOffensive/comments/17bvxvy/cs2_map_spawns_all_premier_maps_for_practice/](https://www.reddit.com/r/GlobalOffensive/comments/1b383vm/cs2_map_spawns_all_premier_maps_for_practice_new/)

 Current version: 1.6

[New Update v1.6]

    Included Dust 2
    Mirage,Anubis,Inferno,Ancient:Positions updated to most up to date.

[New Update v1.5]

    Based on the spawn changes from the last patch (28/2/2024), The Changes are:

        Mirage:

            CT now have only 5 Spawns.

            T 5 spawns has been removed & 2 new ones has been added.

        Anubis:

            T 2 spawns has been removed & 8 new ones has been added.

            A new order for the spawns to look better when switching.

        Nuke:

            CT now have only 5 Spawns.

        Inferno

            T now have only 5 Spawns, 2 of them are new ones.

            A new order for the spawns to look better when switching.

        Overpass

            CT now have only 5 Spawns.

    New on execute chat message: "CS2 Spawns location has been loaded."

[New Update v1.4]

    Update the map positions to have only premier maps.

        Ancient

            5 T spawns | 5 CT Spawns

        Anubis

            5 T spawns | 5 CT Spawns

        Inferno

            10 T spawns | 6 CT Spawns

        Mirage

            13 T spawns | 15 CT Spawns

        Nuke

            8 T spawns | 8 CT Spawns

        Overpass

            11 T spawns | 16 CT Spawns

        Vertigo

            5 T spawns | 5 CT Spawns

    Now it'll set T - Position 1 after rotating between maps.

    Print position confirmation in teamchat when respawning (Delete by default).

        Ex. Respawn: Ancient - T - Position 5

    Remove a duplicate spawn in CT Mirage.

    Fixed a bug where sometimes you could slide when spawning if the ground wasn’t flat enough.

        [Details] By default CS spawns the player (in setpos command) higher than the actual position, so I’ve subtracted 58 from the z axis to spawn close enough to the ground.

[Update v1.3]

    Now it'll unbind the keybinds first then set them.

    "SpawnMng" file now called just "Spawn", so the exec will be "exec Spawn".

    Added a new image in instructions for the cfg folder.

    Added a new image for the console.

[Update v1.2]

    Now you'll change positions while switching.

***********************************************************************************************
Instructions:

    1. Download CS2_SPAWNS.zip
    
    2. Extract the zip file.

    3. Browse local files for CS2.

    4. Then go to game > csgo > cfg .

    5. Copy all extracted files to cfg folder.

    6. Open KeybindsSpawns.cfg in a note editor if you would like to change keybinds to your liking. (Change both bind & unbind in the file).


Default Keybinds:

    Home: Rotate between maps.

    End: Set positions T or CT.

    Page Up: Set next spawn position.

    Page Down: Set previous spawn position.

    Delete: Respawn at that position.

Simply load it by typing "exec spawn" in console.

<img width="330" height="76" alt="image" src="https://github.com/user-attachments/assets/562f0ccf-4d1a-4c2a-9e14-4932f113ba47" />

& btw Cheats should be ON for it to work! 
