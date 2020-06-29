# HOW TO BUILD YOUR OWN FIRMWARE

### NEEDED PROGRAMS

     (1) IAR 1.0.7 (link soon)
     (2) BinEncode (link soon)
     
### BUILDING
 (1) Download and unzip the repo
 
 (2) Open the repo folder and go to EWARM inside this map there is a file you can open with IAR called mkstft35.eww.
 
 (3) Inside IAR go to Project and push on Rebuild All this can take a while when its done you can modify the code. 
 
 (4) IF you modified the code you need to push again on Rebuild All.
 
 (5) When its done go to BinEncode, push on scan and go to EWARM > mkstft35 > Exe here you can see the mkstft35.bin open it and push on Encode
 
 (6) Now the encoded file is inside the folder Windows > BinEncode The file called Robin_nano35.bin rename it to mkstft35 and its ready to flash!
