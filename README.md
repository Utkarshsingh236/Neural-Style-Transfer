# Neural Style Transfer
### 🎨🖌 Creating Art with the help of Artificial Intelligence !
Neural Style Transfer (NST) refers to a class of software algorithms that manipulate digital images, or videos, in order to adopt the appearance or visual style of another image. NST algorithms are characterized by their use of deep neural networks for the sake of image transformation. Popular use cases for NST are the creation of artificial artwork from photographs, for example by transferring the appearance of famous paintings to user-supplied photographs.


</div>


## 🎯 Objective 
The main goal of this project is to explore Neural-style-transfer through implementation. We'll Implement a NST model using Tensorflow and keras, and at the end of the project we'll deploy it as a web app so that anyone can create stunning digital art which they could even sell as NFT's.

## 📝 Summary of Neural Style Transfer

Style transfer is a computer vision technique that takes two images — a "content image" and "style image" — and blends them together so that the resulting output image retains the core elements of the content image, but appears to be “painted” in the style of the style reference image. Training a style transfer model requires two networks,which follow a encoder-decoder architecture : 
- A pre-trained feature extractor 
- A transfer network

<div align="center">
<img src="/nst architecture.jpg" width="80%"/>
</div>

<br> <!-- line break -->



The ‘encoding nature’ of CNN’s is the key in Neural Style Transfer. Firstly, we initialize a noisy image, which is going to be our output image(G). We then calculate how similar is this image to the content and style image at a particular layer in the network(VGG network). Since we want that our output image(G) should have the content of the content image(C) and style of style image(S) we calculate the loss of generated image(G) w.r.t to the respective content(C) and style(S) image.



<div align="center">
<img src="/final_oss.png" width="50%" />
</div>

<br> <!-- line break -->


In simple words,we optimize our NST models to reduce the 'content loss' and the 'style loss'. The content loss function ensures that the activations of the higher layers are similar between the content image and the generated image. The style loss function makes sure that the correlation of activations in all the layers are similar between the style image and the generated image.
## 🖼🖌 Some of the art we created in this project

<div align="center">
  <img src="/imgs/pic 1.jpg" width="35%"/>
<img src="/imgs/style 1.jpg" width="35%"/>
<img src="/imgs/product 1.jpg" width="35%"/>
</div>

<div align="center">
<img src="/imgs/pic2.jpg" width="35%"/>
<img src="/imgs/style2.jpg" width="35%"/>
<img src="/imgs/product 2.jpg" width="35%"/>
</div>

<div align="center">
<img src="/imgs/pic4.jpg" width="35%"/>
<img src="/imgs/style4.jpg" width="35%"/>
<img src="/imgs/product4.jpg" width="35%"/>
</div>

<div align="center">
<img src="/imgs/pic5.jpg" width="35%"/>
<img src="/imgs/style5.jpg" width="35%"/>
<img src="/imgs/product5.jpg" width="35%"/>
</div>


<div align="center">
<img src="/imgs/pic3.jpg" width="35%"/>
<img src="/imgs/style3.jpg" width="35%"/>
<img src="/imgs/product3.jpg" width="35%"/>
<img src="/imgs/product3.3.jpg" width="35%"/>
</div>





