# Renify

<img align="left" alt="demo1" width="800px" src="https://github.com/GeorgeDavila/Renify/blob/main/results/Renify_demo1.png?raw=true" /> 

<br />


<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

For StyleGAN2_Pinkney_Toonify_yourself.ipynb change runtime to GPU then pretty much just click play/run all the cells in order. Your input image should include a face, otherwise will produce error. Preferrably just 1 face (sometimes error with multiple, sometimes not). To upload from local device just right click files and upload it to content/stylegan2/raw and change name to user_photo.jpg (or change the name in code). If you do that just be sure to skip the following 2 cells:

user_photo_link = input("LINK_TO_YOUR_PHOTO_HERE, SHOULD END EITH .JPG OR .PNG, just the 'copy image address' link ") 

import os
os.system("wget " + user_photo_link + "  -O raw/user_photo.jpg")


Alternatively you can leave the nme the same and look for it manually in content/stylegan2/generated/ 
