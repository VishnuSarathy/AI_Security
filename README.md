# AI_Security
Image classification project by vishnu<br>
In This project,we will be using resnet-18 re-trained model and imagenet to recognize our image.<br>
Note: As this is a pre-trained network, it will only recognize my face and if you want to recgnize yours then you should re train the network.<br>
Watch This for <a href="">more</a> information.<br>
<h4>Steps:<br></h4>
1.Download network from <a href="https://drive.google.com/file/d/1TjYVuL7HxK40bRe2aESHYqDHpRoyd5fq/view?usp=sharing">here</a>.<br>
2.Connect camera with your computer or nano.<br>
3.Download all files in this repository and put it in same folder.<br>
4.Using python run reimage.py in terminal using <code>python3 reimage.py --model=resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=labels.txt v4l2:///dev/video0</code>. ("v4l2:///dev/video0" sometimes you have to change this according to you input device.)
