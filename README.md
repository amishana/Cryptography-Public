# Cryptography-Public<br />
### Description:<br />
This program allows the user to input a message and encode/decode it through an image. When the program is run you will be asked what you want to do: encode a message, decode a message, print a message, show an image, or quit the program. Enter the indicated key (E, D, P, S, Q respectively) and the program will execute that task. If you choose to encode a message, the computer will prompt you for an input image file name (your original image), a message (what you want to encode), and an output image file name (the name of the file that will hold your encoded image). It will then ask you what type of encoding you would like to do, either Steganography or Steganography & Caesar Cypher, and encode your image based on the inputted information. If you choose to decode a message, the computer will prompt you for the image file name that you want to decode (this should be your output image file name from the encoding process). Then, it will ask what type of decoding you would like to do, either Steganography or Steganography & Caesar Cypher (note that the program will error out if you did not encode a message or encoded in Steganography but chose to decode in Steganography & Caesar Cypher). If you choose to print a message, your message will be printed, only if a message has been inputted at an earlier step through encoding. If you choose to show an image, you will be asked for the image file name and that will be shown. If you choose to quit, the program will end. 

### How to Gain Access to the Full Repository:<br />
I submitted this project as a part of a class at UC Santa Cruz, and am not allowed to post it publicly. If you would like to see this project, please message me on LinkedIn (at www.linkedin.com/in/amishanambiar) and I will grant you access. Thank you for your understanding.

### How to Run This Project:<br />
First, install a Python IDE. I used PyCharm for this project, but others such as IDLE or Visual Studio should work as well. Then, download all the files in the repository and open them in your IDE. Run cryptography.py. You may use flower.jpg as your original image file, but any image file (.jpg or .png) that is in the same location as the code will work as well. The output image file name may be named anything but must always be a .png file because it allows for lossless compression.

### Authors:<br />
#### Amisha Nambiar and Professor Larissa Munishkina from the University of California Santa Cruz
Amisha Nambiar authored cryptography.py, steganography.py and codec.py.<br />
Amisha Nambiar and Professor Larissa Munishkina authored the pseudocode for cryptography.py, steganography.py and codec.py.<br />
NationalToday.com took the photo in flower.jpg<br />

### Files in This Repository:<br />
1. cryptography.py contains the main code and is the file that should be run.<br />
2. steganography.py contains the encode, decode, print, and show processes.<br />
3. codec.py contains the actual encoding and decoding of the image.<br />
