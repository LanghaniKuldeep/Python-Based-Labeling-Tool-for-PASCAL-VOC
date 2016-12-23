# Python-Based-Labeling-Tool-for-PASCAL-VOC

It is a python based images labelling tool with support of bounding box and it is modified version of labelMe labelling tool and customized for labelling Cars and their license plate and the output will be in Pascal VOC benchmark format.

<h2>How to Run:</h2>

cd labelImg

make all

python labelImg.py

<h1>Instruction for labeling:</h1>

1: CTRL+R: Select location where your files will be saved (annotated files).

2: Select “Open DIR”: It will pop up browsing window. In this you have to select the directory in
which you have the images.

<h2>Now Start Labeling:</h2>
For each Image:
<h3>A) For Car:</h3>
→ Select CreateRectBox.

→ Draw a bounding box around the car.

→ Select “CarBox” by double clicking from the label list.
<h3>B) For Number plate:</h3>

There are 3 cases:
<h4>1: Clear Number plate:</h4>
→ Select CreateRectBox.

→ Draw a bounding box around the plate.

→ Write Number plate Text in the box and Select ok. (Eg: AX-985)
<h4>2: Number plate not visible:</h4>
→ Select CreateRectBox.

→ Draw a bounding box any where randomly.

→ Select “-1” by double clicking from the label list.
<h4>3: Number plate visible but not readable:</h4>

→ Select CreateRectBox.

→ Draw a bounding box around the plate.

→ Select “0” by double clicking from the label list.

Press CTRL+S for saving.

Press 'N' for the next image. (You can use P if you have missed any image by chance).
