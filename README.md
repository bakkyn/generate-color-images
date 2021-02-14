# Image Manipulation and Computational Photography

Sergei Mikhailovich Prokudin-Gorskii developed a method for generate color images before color photography. He took three photo of various subjects. These photos took with Blue, Green and Red filter. These three photographs are combined into one onto plate glass. His goal was to project each image on top of each other using Blue, Green and Red filter to combine them into a color photograph [1].
The purpose in this homework is to make the given black and white photographs using Sergei
Mikhailovich Prokudin-Gorskii's technique that use RGB image channel.

<b>Process</b>
My approach is formed from four part those are; Get_image, Split_image, Align image finally getting colored image.
Approach start with dividing the photograph into three parts that Red, Green, Blue channel like Prokudin-Gorskii’s plates. Before the dividing part, i crop the total image for use only the internal pixels. To find height value of each photograph divide total height to three so we get three photograph divided equal height. After the preparation stage that Get_image, Split_image next part is Align that also the most important part. 

# Results
![alt text](https://github.com/bakkyn/generate-color-images/blob/main/results/1.png)
![alt text](https://github.com/bakkyn/generate-color-images/blob/main/results/2.png)
![alt text](https://github.com/bakkyn/generate-color-images/blob/main/results/3.png)
![alt text](https://github.com/bakkyn/generate-color-images/blob/main/results/4.png)
![alt text](https://github.com/bakkyn/generate-color-images/blob/main/results/5.png)

<b>Failed Part of the Algorithm</b>
As can be seen in the eighth picture under the title of result, despite all my attempts, the result
is not satisfactory. As I explained in the title of development, even the small differences in the
border cut divert the pictures from the results of the large scale. This painting is in the same
tones and consists of thin twigs, which requires a lot of detail in advertising. Therefore, the
desired result cannot be achieved in this picture.

Sergey Prokudin-Gorsky. (2020, September 28). Retrieved November 28, 2020, from
https://en.wikipedia.org/wiki/Sergey_Prokudin-Gorsky [1]
Also you can check the web address for more explanation for all process that is included in about section.
