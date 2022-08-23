
# QR code detection & comparison with OpenCV and WeChat implementation


## Description
Original OpenCV QR Code Scanner is not accurate enough, especially in far or dark environment. So we developed our own detecting method based on QR Code characteristics and C++ knowledge and compared the accuracy between OpenCV, our method and WeChat(the most precise implementation we know).



## Result Walk-through

* Our Method can successfully detect curled and rotated QR Code.
<img src="Curled.png" width = "500">

* In far QR Code situation:
<img src="far.png" width = "500">

* In dark QR Code situation:
<img src="dark.png" width = "500">

* In occluded QR Code situation:
<img src="occluded.png" width = "500">
 
* Comparison conclusion between My Method, OpenCV and WeChat:
<img src="conclusion.png" width = "500">

## Demo Check

https://www.youtube.com/watch?v=dDti9EbQsfI&t=441sv
