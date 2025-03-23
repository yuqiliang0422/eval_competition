# eval_competition


We use segmentation - mask2former swin-large to do the segmentation task (resolution 1024*1024)

We use eva-clip02 and DWT feature enhancements to do the regression and segmentation tasks based on the competition's baseline (model_res.py and resnet.py).

We finally fuse the segmentation results.
