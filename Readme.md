## DL Tips


## Pretrained model 
https://github.com/GalacticExchange/pretrained

## Image or Media Dataset 
- Use K.set_image_dim_ordering("th") 
	- for th (Theano) image ordering you should provide data in a format:
		- [batches, channels, image_width, image_weight]

	- for tf (TensorFlow) image ordering is:
		- [ batches, width, height, channels]
