# AutoSimulate: (Quickly) Learning Synthetic Data Generation
Official code for AutoSimulate (ECCV 2020). For more details, please refer to

**AutoSimulate: (Quickly) Learning Synthetic Data Generation**  
[Harkirat Singh Behl](https://harkiratbehl.github.io/), [Atılım Güneş Baydin](http://www.robots.ox.ac.uk/~gunes), [Ran Gal](https://www.microsoft.com/en-us/research/people/rgal/), [Philip H.S. Torr](http://www.robots.ox.ac.uk/~phst/), [Vibhav Vineet](http://vibhavvineet.info/)\
ECCV, 2020\
**[[Paper]()] [[Project Page](https://harkiratbehl.github.io/autosimulate)]**

**Note:** Code will be made available in both Tensorflow and PyTorch.

**Abstract:**
Simulation is increasingly being used for generating large labelled datasets in many machine learning problems. Recent methods have focused on adjusting simulator parameters with the goal of maximising accuracy on a validation task, usually relying on REINFORCE-like gradient estimators. However these approaches are very expensive as they treat the entire data generation, model training, and validation pipeline as a black-box and require multiple costly objective evaluations at each iteration. We propose an efficient alternative for optimal synthetic data generation, based on a novel differentiable approximation of the objective. This allows us to optimize the simulator, which may be non-differentiable, requiring only one objective evaluation at each iteration with a little overhead. We demonstrate on a state-of-the-art photorealistic renderer that the proposed method finds the optimal data distribution faster (up to 50x), with significantly reduced training data generation and better accuracy on real-world test datasets than previous methods.

## Citation
If you use this code please cite:

	@inproceedings{behl-2020-autosimulate,
  	title = {AutoSimulate: (Quickly) Learning Synthetic Data Generation},
  	author = {Behl, Harkirat Singh and Baydin, Atılım Güneş and Gal, Ran and Torr, Philip H. S. and Vineet, Vibhav},
  	booktitle = {16th European Conference on Computer Vision (ECCV)},
 	year = {2020}
	}
