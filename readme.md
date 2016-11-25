#PackDinos

Using this source is really simple:

1. Download the repository files 

2. In your "Mods" directory create this folder structure: "Soyo/Dinos/Special/Pack/" 

3. Copy the files from the PackDinos in the repository directory to the new folder in your mods directory.

4. Restart your Ark Modding Kit

5. You should now see a Character Blueprint and a Buff 

6. It is possible that you need to properly link the Character Blueprint
  
  a) Open the Character Blueprint 
  
  b) Find Edit -> Reparent 
  
  c) Reparent to Dino_Character_BP

7. Copy (do NOT subclass) the Character Blueprint of the Dino you would like to enable Packs for 

8. Reparent your copied Dino to the Character Blueprint from this repository

9. In the reparented Dino Blueprint's main tab find the category "Pack" to modify all relevant settings 

10. It might be necessary to link the Buff correctly (I am not sure if the link is kept after copying)
 
  a. Open the Character Blueprint you copied from this repository 

  b. In the main tab find the "Pack" category and look for "Pack Leader Buff Class"

  c. Set the buff class you copied from this repository

11. Done!