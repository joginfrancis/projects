# Tiny ATC

I've been using PCB milling machines for a while now, and one of the most challenging aspects of the milling process is the need for regular tool changes. This difficulty could be solved by using an Automatic Tool Changer. However, there are no compact, cost-effective ATCs available anywhere.

When I first started this project one of my main goals was to make it easy to recreate. I quickly realise it's not as simple as it seems. The machines available to the general public, such as 3d printers and desktop CNC mills, are not precise enough to meet the precisions required for making an accurate spindle, However, if I could create a 3D printed ATC that can mill PCBs with 1/64 and 1/32 mills milling bits, it may help pave the way for many others.

### references

Carvera - [https://www.kickstarter.com/projects/makera-inc/carvera](https://www.kickstarter.com/projects/makera-inc/carvera)

**Roland -** [https://www.rolanddg.com/en/news/2002/021108-roland-introduces-automatic-tool-changer-for-unattended-milling](https://www.rolanddg.com/en/news/2002/021108-roland-introduces-automatic-tool-changer-for-unattended-milling)

Diy - [https://shane.engineer/blog/power-drawbar-x2-mini-mill](https://shane.engineer/blog/power-drawbar-x2-mini-mill)

      - [https://www.youtube.com/watch?v=CFCo1EBo3cU](https://www.youtube.com/watch?v=CFCo1EBo3cU)

      - [https://www.youtube.com/watch?v=NhHAEFwQcCA](https://www.youtube.com/watch?v=NhHAEFwQcCA)

[https://shane.engineer/blog/power-drawbar-x2-mini-mill](https://shane.engineer/blog/power-drawbar-x2-mini-mill)

[https://hackaday.com/2020/01/11/stacks-of-spring-washers-power-the-drawbar-on-this-cnc-mill-conversion/](https://hackaday.com/2020/01/11/stacks-of-spring-washers-power-the-drawbar-on-this-cnc-mill-conversion/)



### Magnetic Tool Attachment

My initial approach was to use a couple of magnets to attach the collet to the holder . Since we are using small diameter bits for PCB milling the axial cutting force should be minimal and hence a neodymium magnet could be able to handle the load. the rotation of the tool is arrested with a projection on the holder similar to BT40 holders

<iframe src="https://myhub.autodesk360.com/ue2faaf1a/g/shares/SH9285eQTcf875d3c53935a80c2c4fc662bf?mode=embed" width="100%" height="450" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

![magnetic.jpg](../images/Tiny%20ATC/magnetic.jpg#center#zoom){ width=55%}

I also had few iterations of the same concept

![magnet2.jpg](../images/Tiny%20ATC/magnet2.jpg#cover2#zoom)
![magnet1.jpg](../images/Tiny%20ATC/magnet1.jpg#cover2#zoom)

<iframe src="https://myhub.autodesk360.com/ue2faaf1a/g/shares/SH9285eQTcf875d3c539c3fac9a7e0d4f533?mode=embed" width="100%" height="450" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

![Untitled](../images/Tiny%20ATC/Untitled.png#cover2#zoom)
![explode.png](../images/Tiny%20ATC/explode.png#cover2#zoom)


### Collet Designs

<iframe src="https://myhub.autodesk360.com/ue2faaf1a/g/shares/SH9285eQTcf875d3c539c36024de718a2cf1?mode=embed" width="100%" height="450" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

The teethes on the holder and spindle will transfer the rotational motion from the spindle to the holder .

![Untitled](../images/Tiny%20ATC/Untitled%201.png#cover2#zoom)
![Untitled](../images/Tiny%20ATC/Untitled%202.png#cover2#zoom)

At the top of the collet holder a neodymium magnet is embedded it will get attracted towards another magnet in the spindle.  the magnets will keep the holder attached to the spindle.

![Screenshot (145).png](../images/Tiny%20ATC/Screenshot_(145).png#center#zoom){width=70%}

![IMG_20211120_120821.jpg](../images/Tiny%20ATC/IMG_20211120_120821.jpg#cover_banner#zoom)

### Spring Collet

I tried a different approaches to avoid the need of an extra holder . 

![clicklock.jpg](../images/Tiny%20ATC/clicklock.jpg#center#zoom){ width=55%}

The bit could be directly attached to the mechanism with a split collet and spring .

![clicklock2.jpg](../images/Tiny%20ATC/clicklock2.jpg#center#zoom){ width=55%}

### Spring Collet Version

![IMG_20211109_111817.jpg](../images/Tiny%20ATC/IMG_20211109_111817.jpg#cover5#zoom)
![IMG_20211109_111953.jpg](../images/Tiny%20ATC/IMG_20211109_111953.jpg#cover5#zoom)
![IMG_20211109_112042.jpg](../images/Tiny%20ATC/IMG_20211109_112042.jpg#cover5#zoom)
![IMG_20211109_112036_1.jpg](../images/Tiny%20ATC/IMG_20211109_112036_1.jpg#cover5#zoom)
![IMG_20211109_112033.jpg](../images/Tiny%20ATC/IMG_20211109_112033.jpg#cover5#zoom)

![test1.jpg](../images/Tiny%20ATC/test1.jpg#zoom)

![IMG_20211109_111700.jpg](../images/Tiny%20ATC/IMG_20211109_111700.jpg#cover4#zoom)
![IMG_20211109_111652.jpg](../images/Tiny%20ATC/IMG_20211109_111652.jpg#cover4#zoom)
![IMG_20211112_160806_1.jpg](../images/Tiny%20ATC/IMG_20211112_160806_1.jpg#cover4#zoom)
![IMG_20211117_161115_1.jpg](../images/Tiny%20ATC/IMG_20211117_161115_1.jpg#cover4#zoom)

![IMG_20211117_151430.jpg](../images/Tiny%20ATC/IMG_20211117_151430.jpg#zoom)

![IMG_20211117_151335.jpg](../images/Tiny%20ATC/IMG_20211117_151335.jpg#cover2#zoom)
![IMG_20211117_154155.jpg](../images/Tiny%20ATC/IMG_20211117_154155.jpg#cover2#zoom)

![IMG_20211117_160717_1 (2).jpg](../images/Tiny%20ATC/IMG_20211117_160717_1_(2).jpg#center#zoom){ width=70%}

<iframe width="100%" height="450" src="https://www.youtube.com/embed/oYFQRWzRnRY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe src="https://myhub.autodesk360.com/ue2faaf1a/g/shares/SH9285eQTcf875d3c539555fadf711371279?mode=embed" width="100%" height="450" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# V2 -  Actuated opening and closing of collet

![Screenshot (30).png](../images/Tiny%20ATC/Screenshot_(30).png#cover2#zoom)
![Screenshot (29).png](../images/Tiny%20ATC/Screenshot_(29).png#cover2#zoom)

![photo_2022-02-03_17-01-20.jpg](../images/Tiny%20ATC/photo_2022-02-03_17-01-20.jpg#cover4#zoom)
![photo_2022-02-03_17-01-24.jpg](../images/Tiny%20ATC/photo_2022-02-03_17-01-24.jpg#cover4#zoom)
![photo_2022-02-03_17-01-16.jpg](../images/Tiny%20ATC/photo_2022-02-03_17-01-16.jpg#cover4#zoom)
![photo_2022-02-03_17-01-08.jpg](../images/Tiny%20ATC/photo_2022-02-03_17-01-08.jpg#cover4#zoom)

![photo_2022-02-03_17-01-03.jpg](../images/Tiny%20ATC/photo_2022-02-03_17-01-03.jpg#cover4#zoom)
![photo_2022-02-03_17-01-11.jpg](../images/Tiny%20ATC/photo_2022-02-03_17-01-11.jpg#cover4#zoom)
![photo_2022-02-03_17-00-59.jpg](../images/Tiny%20ATC/photo_2022-02-03_17-00-59.jpg#cover4#zoom)
![photo_2022-02-03_17-00-45.jpg](../images/Tiny%20ATC/photo_2022-02-03_17-00-45.jpg#cover4#zoom)

![photo_2022-02-03_17-00-27.jpg](../images/Tiny%20ATC/photo_2022-02-03_17-00-27.jpg#cover2#zoom)
![photo_2022-02-03_17-00-34.jpg](../images/Tiny%20ATC/photo_2022-02-03_17-00-34.jpg#cover2#zoom)

![photo_2022-02-03_16-59-47.jpg](../images/Tiny%20ATC/photo_2022-02-03_16-59-47.jpg#zoom)


<iframe width="100%" height="450" src="https://www.youtube.com/embed/yuMtzLfyT6w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe src="https://myhub.autodesk360.com/ue2faaf1a/g/shares/SH9285eQTcf875d3c539f7070660caf92e96?mode=embed" width="100%" height="450" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>
