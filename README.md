# Bird Recgnition #

In this project you can feed it a image for it to identify what type of bird is being shown.

To run the project make sure you are in the correct directory where the script is.

**The command to run the project is:** 

python3 my_recognition.py [your input].jpg [output file name].jpg

**The output**

The output image will me in the same directory that you are running the script from, and will show the type of bird with the precentage of confidence.

**What I used to train the flie:**

I used the ResNet-18 to train, this was done on a Jetson Orin

**Where the asset was found**

I collected the asset for the birds from Kaggle with the classes: 

ABBOTTS BABBLER, ABBOTTS BOOBY, ABYSSINIAN GROUND HORNBILL, AFRICAN CROWNED CRANE, AFRICAN EMERALD CUCKOO, AFRICAN FIREFINCH, AFRICAN OYSTER CATCHER, AFRICAN PIED HORNBILL, AFRICAN PYGMY GOOSE,
ALBATROSS,
ALBERTS TOWHEE,
ALEXANDRINE PARAKEET,
ALPINE CHOUGH,
ALTAMIRA YELLOWTHROAT,
AMERICAN AVOCET,
AMERICAN BITTERN,
AMERICAN COOT,
AMERICAN FLAMINGO,
AMERICAN GOLDFINCH,
AMERICAN KESTREL

There is 5 images in each class that I used to train which I trained in 35 epochs

[Video link](https://drive.google.com/file/d/1MNAWnN8_vcUJ9di2aqcrf3idBaqSxLve/view?usp=share_link)
