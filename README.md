# Lucid-Neural-Style-Transfer

Based off the lucid tensorflow 2d Neural style transfer example found here: https://github.com/tensorflow/lucid
The original example provided there no longer works, but I found a solution so I am reuploading it. .

To get started, you can run the project through browser via following google colab link: https://colab.research.google.com/github/400lbhacker/Lucid-Neural-Style-Transfer/blob/main/Final_Style.ipynb

This uses lucid googlenet library /w CPPN. produces more mystical results with higher entropy
![Image of Yaktocat](https://github.com/400lbhacker/beast-pytorch-tensorflow-neural-style-transfer/blob/master/rr.png)

note: 
------------------------------------
images may require slight modification before they are uploaded, which are listed below, 
Using mspaint the modifications needed take less than 20 seconds total. (for both images)

1) - your initial image must be named the following before you upload: content.jpg

2) - your style image must be named the following before you upload: style.jpg 

3) - initial image and style image must both be the same size! if your content photo is 400x800 in size, 
than you must also resize your desired style image to also be 400x800 in size before they are both uploaded

4) - both images must not have any extra layers, (ie transparency) so this is why I have jpg enforced now, 
png are supported however.
------------------------------------

changes/improvements/features:
-----------------------------------------------
1)- runs online, no installation or even a python enviroment required.

2)- no programming experience or code modification needed

3)- automatic upload photo button and UI. no typing needed. all done with just a couple clicks.

4)- instant preview of your modifications, (get the hang quickly of what each thing does)

5)- no image size limitation/truncation, HD images supported. 

6)- insanely fast results, especially for large images, doesnt require 500+ iterations like others

7)- ability to modify/add/subtract layers to customize style parameters.

8)- added support for 26 other neural-nets/imagenets, and all their layers. (100+ new) this has never been done by any other projects.

9)- fixxed all errors, automatically acquires & sets correct dependencies

10)- enhanced backward compatability, runtime is now also python-3 compatable  

11)- added helpful tips in code to show when to go to next step (etc)

-----------------------------------------------


