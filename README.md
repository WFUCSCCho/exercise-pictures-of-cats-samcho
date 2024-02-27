Description: This Java program takes in a command line argument that corresponds to a jpg image and converts it into a grayscale 
image. It can be readily used in the terminal using a for loop to convert every single image.

To convert every image use (Mac, bash):
% for i in CAT_00/*; do java src/Flipped_Grayscale_Cats.java $i; done > output.dat

To convert every image use (Windows Powershell): Note: Fix later
% for($x=1; $x -lt 10; $x=$x+1)   
  {   
   echo $x   
  }  
