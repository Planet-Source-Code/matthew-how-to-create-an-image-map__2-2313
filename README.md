<div align="center">

## How to create an Image Map


</div>

### Description

Shows how to create an Image Map.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Matthew](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/matthew.md)
**Level**          |Beginner
**User Rating**    |3.7 (11 globes from 3 users)
**Compatibility**  |Java \(JDK 1\.1\), Java \(JDK 1\.2\)
**Category**       |[Graphics](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/graphics__2-75.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/matthew-how-to-create-an-image-map__2-2313/archive/master.zip)





### Source Code

This article actully is HTML, not javascript.<br><br><font face="arial"><size ="2">
In this tutorial, I will show you how to create an Image Map, but first let me explain a little about Image Maps. Image Maps are just one big image, with different sections of it defined for links. It is very easy and all you use is HTML. If you would like to see how to create a rollover in an image map, see my tutorial on that. <br><br>
Right so lets get started. For an image map all you need is one big image. Then after you have that, you need to find the coordinates of where you want the link to be. To do this, open the image in Paint, Adobe PhotoShop, or some other image-editing program. The easiest way to do this I think is with Paint. So I will explain how to do it there. Take your mouse and click the crop button on the tool bar. Then take the crosshairs, and put the center on the upper left corner where you want the link to start, in the bottom right, there should be some numbers in the form of 0, 0, right them down or remember them. Then take your crosshair and do the same thing to the bottom right corner. Right those down as well. Now you have your coordinates. We can now start the actual coding. Every time I start coding and end coding I will put a dotted line, like this: --------------------<br>
Ok so here we go!<br>
------------------------<br><br>
&#60HTML&#62 &#60HEAD&#62 &#60TITLE&#62 Your title here! &#60/TITLE&#62 &#60/HEAD&#62 &#60BODY&#62 <br><br>
&#60Map Name="Name"&#62<br>
&#60Area Shape="rect" Coords="0, 0, 0, 0" Href="yourpage.html"&#62<br>
&#60/MAP&#62
&#60IMG SRC="Map.gif" UseMap="#Name"&#60<br>
&#60/BODY&#62 &#60/HTML&#62<br>
--------------------------<br><br>
There its as simple as that, know let me explain it. You start your document with the HTML and HEAD tags, then you put the title, end the title and head, and start the body. Then inside the body, I defined the map. I then put the Area shape (you can choose from rect for a rectangle, circle for a circle, and poly for an irregular shape), the coordinates (put the ones we got earlier in the tutorial) and the link. Put that line for each of the links on your image (of course with different coordinates, etc.!) Then I ended the image map, and put the code for the image that will be the map. Inside that I put UseMap="#Name" that says that theta image is the Image Map (Make sure you make your own name for the map). Then I ended the Body and Html. It is as simple as that!!!

