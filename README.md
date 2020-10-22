# audioStyleTransfer



## Start Container
Depending on OS and preference run one of the following startup scripts.
* This will pull the correct version of tensorflow from docker hub.
* Build the image if it is not yet pulled 
* Create a container 
* Map the container to the root of where ever the repository was cloned 


# Run compose
`docker-compose up`



## Change url in output to localhost

`http://(1c21f51fc83f or 127.0.0.1):8888/?token=a55206c3a1c38ca33035959600b4131883c96b11aea3b543 `

to
`http://localhost:8888/?token=a55206c3a1c38ca33035959600b4131883c96b11aea3b543`

paste in browser and open `neural-style-audio-tf.ipynb`


### References
- Original paper on style transfer:
[A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576)
- [Neural style TensorFlow implementation](https://github.com/anishathalye/neural-style)
- Publications on texture generation with random convolutions:
 - [Extreme Style Machines](https://nucl.ai/blog/extreme-style-machines/)
 - [Texture Synthesis Using Shallow Convolutional Networks with Random Filters](https://arxiv.org/abs/1606.00021)
 - [A Powerful Generative Model Using Random Weights for the Deep Image Representation](https://arxiv.org/pdf/1606.04801)





