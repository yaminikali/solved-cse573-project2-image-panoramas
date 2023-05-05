Download Link: https://assignmentchef.com/product/solved-cse573-project2-image-panoramas
<br>
<h3></h3>

The goal of this task is to experiment with image stitching methods. Given a set of photos, your program should be able to stitch them into a panoramic photo (as shown in Figure 1). There are no restrictions regarding the method you use to stitch photos into a panoramic photo. For this project, you can assume the following:

<ul>

 <li>Your code will need to be able to stitch together anywhere from 2-5 image and you will not know that in advance.</li>

 <li>You can assume that IF an image is to be part of the panorama, it will overlap at least one other image and by at least 20%.</li>

 <li>Images that do not overlap with any other image can be ignored.</li>

 <li>Images will overlap with at most one other image.</li>

 <li>You are only expected to produce one panorama. For example, if images 1 and 2 overlap, and 3 and 4 overlap, but there is not overlap between 1,2 and 3,4 producing either composite/panorama is fine.</li>

</ul>

Please keep in mind:

<ul>

 <li>You will have to determine the spatial arrangement of the images automatically, they can be presented to your code in any order.</li>

 <li>Although the Figure below shows horizontal panoramas, you five images can be stitched together in any way.</li>

 <li>While some of the most modern techniques may use a spherical projection for better panoramas, you are free to assume that basic 2D Planer transformations are sufficient for this project.</li>

</ul>

1

<h4>Bonus – UB 360<sup>◦ </sup>Panoramas</h4>

To get the 15 bonus points, you can take up to 9 photos that can be stitched together to form a 360<sup>◦ </sup>horizontal panorama such as the one in Figure 2. The images you take should demonstrate something of value to you about UB life. This could be at an event, something on campus, a road trip, etc, but have something UB related in the scene. You must then take your program and stitch them into a panoramic photo. The overlapped region between any 2 of the photos you take should not exceed 50%. See below for an example of the 360 degree panoramas stitching.

Finally, we will print/submit the best ones for display in the department and/or website.