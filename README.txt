This is demo for a prototype of an Avatar style open world game.

You may download from Github, Sourceforge, or Google Docs

Github: clone the repository

Google Docs: just downlaod it

Sourceforge: download and
The component files of the game are too big for uploading, so 2 were taken out.  
Unzip the project and then copy and paste the 2 pak files in the avatarFirebert2/Content/Paks directory.
There may be issues with anti virus programs.

The data_pack folder has to be in the same directory as the executable.  You can change the images in the data_pack, but they must use the same names to be picked up by the game.




Uploading your own images:
In the data_pack directory there are 2 tables: image_table.csv and animatic_image_table.csv.  They are copies of what is loaded into the game.  You can not change the table in the game, but you can change the images that the tables point to.  Substitute your image files for the ones in the data_pack directory and give them the names of the original files.  When the game loads the image file at runtime, then your image will appear.
