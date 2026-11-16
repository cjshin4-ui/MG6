# MG6
Question1. I think the entire for loop would happen before the Update method finishes. So if each for loop has to fully complete, then a for loop that would take a really long time to finish would make the game lag.

Question2. One issue is that the player can double jump and glitch down when inside of the platform. This is because when the player starts moving up, the collider disables, letting the plyaer move through, but when the player starts moving down, the collider turns on again which causes the player to collide with the platform, allowing them to jump again or making the player glitch down. 
