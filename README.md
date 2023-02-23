# OpenCV--Article


OpenCV is the huge open-source library for the computer vision, machine learning, and image processing and now it plays a major role in real-time operation which is very important in today's systems. By using it, one can process images and videos to identify objects, faces, or even handwriting of a human.

command to install opencv library - pip install opencv-python
opencv- BGR
matplotlib - RGB

To read image we should use cv2.imread 
To write image we should use cv2.imwrite

imread has three types of flag
  * cv2.IMREAD_COLOR reads the image with RGB colors = 1
  * cv2.IMREAD_GRAYSCALE reads the image as grey image = 0
  * cv2.IMREAD_UNCHANGED reads the image as is from the source = -1

To show the image by using imshow(name, img)

![Screenshot from 2023-02-23 14-57-27](https://user-images.githubusercontent.com/64459769/220868246-21dc85f5-27c6-463b-8093-966af2fddf17.png)

