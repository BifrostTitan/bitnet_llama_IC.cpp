# bitnet.cpp for Internet Computer

![llama](https://user-images.githubusercontent.com/1991296/230134379-7181e485-c521-4d23-a0d6-f7b3b61ba524.png)

Inference of Bitnet 1.5b (and others) in pure C/C++

This version of bitnet-llama has been altered to run on an Internet Computer canister. The cpu threading has been forced to single threaded while removing device aware code and replacing logging with IC_API
