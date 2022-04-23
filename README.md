# AI_Security
Image classification project by vishnu
In This project,we will be using res-18 re-trained model and imagenet to recognize our image.
Note: As this is a pre-trained network, i will only recognize my face and if you want to recgnize yours then you should re train the network.
Steps:
1.download network from https://drive.google.com/file/d/1TjYVuL7HxK40bRe2aESHYqDHpRoyd5fq/view?usp=sharing.
2.Connect camera with your computer or nano.
3.Download all files in this resp and put it in same folder.
4.Using python run reimage.py in terminal using "python3 reimage.py --model=resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=labels.txt v4l2:///dev/video0" code. ("v4l2:///dev/video0" sometimes you have to change this according to you input device.)
