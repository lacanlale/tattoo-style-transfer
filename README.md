# Style transfer test
NOTE: All code was used and modified from [TensorFlows original tutorial](https://www.tensorflow.org/tutorials/generative/style_transfer)

## About
This project was mostly a _get_things_done_quick_ to play around with pre-trained style transfer models.
The primary additions are just made to:
1. Use images from the Google drive (input and target images)
2. Save results to the Google drive (see /images/outputs/ folder)
3. Create a gif of the process

In this repo, there's a single input image with 7 potential style-target images. I mostly used this to see how tattoo styles would look on different images but the results didn't come out as I had hoped.
I might revisit this in the future to fix certain results like traditional tattoo styles, but for the time being, this was mostly a learning experience.
GIFs of the transfer process aren't found here (as they can be large) but running the code locally (or in Google Colab) should produce the same results.
