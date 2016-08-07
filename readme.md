#PackDinos

Using this source is really simple:

1. Copy the files from the PackDinos directory to your a folder in your modding directory 

2. Restart your Ark Modding Kit

3. You should now see a Character Blueprint and a Buff 

4. It is possible that you need to properly link the Character Blueprint
  
  a) Open the Character Blueprint 
  
  b) Find Edit -> Reparent 
  
  c) Reparent to Dino_Character_BP

5. Copy (do NOT subclass) the Character Blueprint of the Dino you would like to enable Packs for 

6. Reparent your copied Dino to the Character Blueprint from this repository

7. In the reparented Dino Blueprint's main tab find the category "Pack" to modify all relevant settings 

8. It might be necessary to link the Buff correctly (I am not sure if the link is kept after copying)
 
  a. Open the Character Blueprint you copied from this repository 

  b. In the main tab find the "Pack" category and look for "Pack Leader Buff Class"

  c. Set the buff class you copied from this repository

9. Done!