# Neutral-Style-Transfer-implementation
This is based on the research paper "A neural algorithm based on Artistic Style" by Leon A. Gatys,Alexander S. Ecker, Matthias Bethge

**wHAT IS THIS NST ALGORITHM ABOUT?**

So this algorithm takes an input image and another image whose artistic style we want to copy onto our input image.
Suppose here we use this as our input image, 
![city](https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/635a45b6-fa72-4485-8d68-034c2749bbd6)

and we want to copy the artistic style of Van Gouh's famous painting 'the starry night' onto our particular image.

![starry_night](https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/2389ea97-5112-4206-be91-77d6f26ef44a) 

What is the result we get? 

We get this beautiful style of the starry night implemented onto the city image.

<img width="500" alt="Screenshot 2024-05-23 141134" src="https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/d9b032e4-cdcb-438a-9ca4-f9c720ec801b">

This algorithm uses CNN nets (usually VGG-16/19) and gives a composite, stylized image out which keeps the content from the content image but takes the style from the style image.

More examples of this->



<img width="500" alt="lion3" src="https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/8e695931-6e9b-48a9-8b6b-33e2b13420ee">
<img width="500" alt="Screenshot 2024-05-23 141449" src="https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/0d84902f-9e37-44e8-bae4-b4eee7e3d007">
<img width="500" alt="lion5" src="https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/fd807094-c7d3-46e9-969f-24b0cf877e00">
<img width="500" alt="lion4" src="https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/8307dadf-4519-4293-a05b-4692e9515a3e">

