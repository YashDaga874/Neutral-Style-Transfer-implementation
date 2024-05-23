# Neutral-Style-Transfer-implementation
This is based on reproducing the original research paper titled "A neural algorithm based on Artistic Style" by Leon A. Gatys,Alexander S. Ecker, Matthias Bethge

### WHAT IS THIS NST ALGORITHM ABOUT?

So this algorithm takes an input image and another image whose artistic style we want to copy onto our input image.
Suppose here we use this as our input image, 


<img width="500" alt="lion3" src="https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/635a45b6-fa72-4485-8d68-034c2749bbd6">

and we want to copy the artistic style of Van Gouh's famous painting 'the starry night' onto our particular image.
<img width="500" alt="lion3" src="https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/2389ea97-5112-4206-be91-77d6f26ef44a">

What is the result we get? 

We get this beautiful style of the starry night implemented onto the city image.

<img width="500" alt="Screenshot 2024-05-23 141134" src="https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/d9b032e4-cdcb-438a-9ca4-f9c720ec801b">

This algorithm uses CNN nets (usually VGG-16/19) and gives a composite, stylized image out which keeps the content from the content image but takes the style from the style image.

More examples of this with the styles->


<p align="center">
<img width="300" alt="lion3" src="https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/8e695931-6e9b-48a9-8b6b-33e2b13420ee">
<img width="300" alt="Screenshot 2024-05-23 141449" src="https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/0d84902f-9e37-44e8-bae4-b4eee7e3d007">
<img width="300" alt="lion4" src="https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/8307dadf-4519-4293-a05b-4692e9515a3e">

<img width="240"  src="https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/533da69b-313d-4d82-b7b8-f37273bd6157">
<img width="155"  src="https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/e1817050-cf8d-4f43-88cb-f9deb1b304c4">
<img width="240"  src="https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/39930685-b737-41fc-ad95-79eb4344c0cf">
</p>


# The updated NST algorithm by  Johnson et al.

The updated neural style transfer algorithm, specifically referencing the ECCV16 paper "Perceptual Losses for Real-Time Style Transfer and Super-Resolution" by Johnson et al., involves using perceptual loss functions to train a feed-forward neural network for real-time style transfer.It found that swapping the batch normmalization for instance normalization led to further better results as well.

Here are a few results from that -> 

<p align="center">

<img width="324" alt="lion9" src="https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/a24a548a-ea51-4cf2-9618-f79f38d37b48">
<img width="308" alt="lion8" src="https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/c4e00269-884b-48a3-8446-bd5c863403ed">
<img width="308" alt="lion9" src="https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/2137e3db-e62c-468d-ab05-8cc466b7f0fb">
</p>

The first image is the style(starry nights), the second image is the implementation of the original NST algorithm and the second one is the updated ECCV16 style NST algorithm by Johnson et al.                                               

# Implementing the same on a .mp4 video

Here's a short dj.mp4 video of just 1 second, on which I implemented the same algorithm, and here is the original clip-> 


https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/31c28682-db8b-42b0-abdc-07019185828d


And we implemented the same starry nights style onto this short clip and here's the result->

https://github.com/YashDaga874/Neutral-Style-Transfer-implementation/assets/118438239/d3865383-a3c0-4b24-a0a5-66952366b8c9



## Setup
1. Open the .ipynb file in Google colab.
2. Upload the .zip file and the .jpg and the .mp4 file as well.
3. Run the code, you are good to go.Cheers :)

### You can connect with me on my linkedin ->
www.linkedin.com/in/yash-daga-0b2041257



