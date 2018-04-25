# softmax(1) file is the most updated version. can be downloaded and run block by block. prarameters can be changed for playing around.
# The naive model's accuracy is 92%-train, 85%-test now. Note: the model in softmax(1) is naive model, i.e. without dropout/SGD-momentum
# COMP5329/assign1 - my contribution is in softmax.ipynt file
# plz see softmax file, the code is based on andrew ng deep learning
#https://github.com/andersy005/deep-learning-specialization-coursera

#it should be noted that the code from andrew ng is binary classification(sigmoid) instead of softmax, so I defined softmax function, 
which is based on https://www.ics.uci.edu/~pjsadows/notes.pdf , 
https://github.com/rasbt/python-machine-learning-book/blob/master/code/bonus/softmax-regression.ipynb

#within basic modules, momentum in SGD, dropout can also be based on andrew ng's work.
only weight norm need to be defined from scratch. 

#for extra modules, we must implement minibatch, otherwise would be too slow. 
