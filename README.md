# OpenCV--Article


OpenCV is the huge open-source library for the computer vision, machine learning, and image processing and now it plays a major role in real-time operation which is very important in today's systems. By using it, one can process images and videos to identify objects, faces, or even handwriting of a human.

1)OpenCV is an image processing library created by Intel and later supported by Willow Garage and now maintained by Itseez.
2)Opencv is available on Mac, Windows, Linux. Works in C, C++, and Python.
3)It is Open Source and free.
4)Opencv is easy to use and install.
5)Digital Images are stored in the form of matrix

Computers see Images
   1)GrayScale (1 Channel)
   2)RGB (3 Channel)

![Screenshot from 2023-02-23 15-13-01](https://user-images.githubusercontent.com/64459769/220871658-889d4bf9-3e5c-43f9-a74e-061740e1ee5c.png)

<h2> 1) How to Read ,Write and Show Images using openCV </h2>

OpenCV read images in the format of  BGR
matplotlib read images in the format of RGB

To read image we should use cv2.imread 
To write image we should use cv2.imwrite

imread has three types of flag
  * cv2.IMREAD_COLOR reads the image with RGB colors = 1
  * cv2.IMREAD_GRAYSCALE reads the image as grey image = 0
  * cv2.IMREAD_UNCHANGED reads the image as is from the source = -1

To show the image by using imshow(name, img)

![Screenshot from 2023-02-23 14-57-27](https://user-images.githubusercontent.com/64459769/220868246-21dc85f5-27c6-463b-8093-966af2fddf17.png)

To reshape the image size by using resize in cv2
![Screenshot from 2023-02-23 15-21-23](https://user-images.githubusercontent.com/64459769/220873556-d0713e69-edbb-4122-8087-7c547201368c.png)



<h2>basic operations with video and webcams</h2>

Inbuild Camera = 0
External Camera = 1


