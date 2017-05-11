# Action Conditioned GAN Demo
Demo GIF of samples from action conditioned GAN. All predictions here are made by recursively sample 6 times from the generator network, which is equivalent of 12 frames into the future.

**Samples with regular actions**:

Generated Frames:

![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid16/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid63/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid34/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid43/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid11/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid13/generated.gif)

Ground Truth:

![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid16/gt.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid63/gt.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid34/gt.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid43/gt.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid11/gt.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid13/gt.gif)

**Samples with reverse actions**:

The generator generate different motion on reversed action even though it was never trained on such action. 
This demosntrates that the neural network has some level of understanding of the dynamics.

Reverse Action Frames:

![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/rev_example/vid14/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/rev_example/vid23/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/rev_example/vid29/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/rev_example/vid35/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/rev_example/vid42/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/rev_example/vid59/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/rev_example/vid61/generated.gif)

Regular action Generated Frames:

![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid14/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid23/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid29/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid35/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid42/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid59/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid61/generated.gif)

Ground Truth:

![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/rev_example/vid14/gt.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/rev_example/vid23/gt.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/rev_example/vid29/gt.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/rev_example/vid35/gt.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/rev_example/vid42/gt.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/rev_example/vid59/gt.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/rev_example/vid61/gt.gif)

**Samples with 2x actions**:

As you can see, the effect of applying twice amount of action is not linear to the visual effect. As the results, the acceleartion/changes are less pronounced.

Twice action Frames:

![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/2x_sample/vid29/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/2x_sample/vid35/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/2x_sample/vid53/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/2x_sample/vid58/generated.gif)

Regular action Generated Frames:

![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid29/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid35/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid53/generated.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid58/generated.gif)

Ground Truth:

![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid29/gt.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid35/gt.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid53/gt.gif)
![Animation](https://github.com/yidingjiang/Action_Conditioned_GAN_demo/blob/master/regular_sample/vid58/gt.gif)
