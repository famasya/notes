- Videos: https://www.youtube.com/watch?v=euwN5DHfLEo
- Notebook: https://colab.research.google.com/drive/1vrZVUFzuPypWOMOS12og6cJMRom4XlbW?usp=sharing
-
- Notes:
	- Understand norm: https://machinelearningmastery.com/vector-norms-machine-learning
		- L1 norm = manhattan distance
		- L2 norm = euclidean distance => commonly used
		- Max norm = getting max norm in an array
		  ```python
		  # max norm of a vector
		  from numpy import inf
		  from numpy import array
		  from numpy.linalg import norm
		  a = array([1, 2, 3])
		  print(a)
		  maxnorm = norm(a, inf)
		  print(maxnorm) # result = 3
		  ```
	- Understand reguralization:
	  >  Regularizations are techniques used to reduce the error by fitting a function appropriately on the given training set and avoid overfitting.
	  
	  source: https://towardsdatascience.com/regularization-an-important-concept-in-machine-learning-5891628907ea
	- Understand logits:
		-
		  > The raw predictions which come out of the last layer of the neural network.
		  > 1. This is the very tensor on which you apply the argmax function to get the predicted class.
		  > 2. This is the very tensor which you feed into the softmax function to get the probabilities for the predicted classes.
		  source: https://stackoverflow.com/questions/41455101/what-is-the-meaning-of-the-word-logits-in-tensorflow
		-
-
- Additional resource:
	- https://arxiv.org/pdf/1508.02297.pdf (Understanding "norm" better)