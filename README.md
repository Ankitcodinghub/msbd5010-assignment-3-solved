# msbd5010-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [MSBD5010 Assignment 3 Solved](https://www.ankitcodinghub.com/product/msbd5010-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91311&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MSBD5010 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

Overview

This assignment consists of two sections: programming section and written section. Both programming and written parts should be submitted via the CANVAS system. If you would like to finish the written assignment with hand writing, you may scan and upload it.

In the programming section, you need to finish an incomplete function which is a part of JPEG lossy-compression using discrete cosine transform (DCT). A set of M- files can be obtained from CANVAS and the code skeleton has been implemented. You need to complete the missing implementations in the programming section.

In the written section, you need to answer one question about image compression.

Programming assignment specifics

You need to complete the implementation in the compression_jpeg.m file, which is a part of JPEG lossy encoder/decoder using DCT. The steps of this compressor can be summarized as follows:

(1) Subtract the image intensity by 128.

(2) Partition the input image into 8×8 blocks. For example, if the input image has a resolution of 128×128, there are 16*16=256 blocks after partitioning.

(3) Apply DCT to each of the 8×8 block (use command “DCT2” in Matlab)

(4) Perform quantization with Quantization Table and convert all the quantized coefficients into integer.

(5) Following zig-zag order, convert all 8×8 blocks into vectors with 64 elements.

</div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
The procedure for the decompression of the image is the simple inverse of the above steps:

(1) Convert the vectors back to 8×8 blocks.

(2) Multiply the blocks with quantization table. (3) Apply Inverse DCT to each block.

(4) Group all 8×8 blocks back to form an image. (5) Add 128 to each pixel of the image.

You need to implement step (3) &amp; (4) in compression and step (2) &amp; (3) in decompression.

Sample runs of the programming assignment

sample_run.fig is the sample output. You are supposed to obtain similar output on the screen when you run the following command in the MATLAB environment:

&gt;&gt; compression_jpeg

Written assignment specifics

Lossless compression (Huffman coding).

Given a 1-D image profile as follows (intensity values range from 0 to 15):

Index 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 Intensity 1 3 7 12 2 3 9 12 9 7 9 12 1 1 12 12

Perform Huffman coding for the image and calculate the compression ratios. Note that you don’t have to consider the intensity with zero frequency.

Show all your steps clearly.

For Huffman coding, show your steps in terms of the tables as shown in the Huffman Encoding part of the lecture notes (Image Compression). You should assign label ‘1’ to the intensity with higher frequency in the Huffman code assignment table.

In the calculations of compression ratios, ignore the storage overhead due to the lookup tables.

</div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
