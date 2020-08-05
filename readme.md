Command line arguments
The script requires four input arguments.
input image
YOLO config file
pre-trained YOLO weights
text file containing class names
All of these files are available on the github repository I have put together. (link to download pre-trained weights is available in readme.)
You can also download the pre-trained weights in Terminal by typing
wget https://pjreddie.com/media/files/yolov3.weights
This particular model is trained on COCO dataset (common objects in context) from Microsoft. It is capable of detecting 80 common objects. See the full list here.
Input image can be of your choice. Sample input is available in the repo.
Run the script by typing
$ python yolo_opencv.py --image dog.jpg --config yolov3.cfg --weights yolov3.weights --classes yolov3.txt
