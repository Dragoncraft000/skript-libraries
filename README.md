# skript-libraries
Libraries and Helper functions I made for my skript Projects


## Currently Included

### Client Displays
Includes a variety of different functions for Clientside Packet Based Display Entities using PoaSK and 
Skbe. (Quaternion Rotations)
Each update functions supports optionally specifying a list of players to send the update to but most of the time that's not needed as the update packets will be ignored by the client if the entity does not exist.

### Projectiles
Custom Projectile Library allowing for custom speed, drag and gravity per projectile.
Includes a function that uses the Client Display Library to align a Display Entity to the location of that projectile.

### Debugging
Simple Debugging functions, currently contains just a way to temporarily highlight block position by rendering custom Debug Markers with a specific color, transparency and optionally also a text label.

