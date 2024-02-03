# I setup the tensor flow in Jupyter noteboooks using a virtual environment.. 

A virtual environment is a tool that helps to keep dependencies required by different projects separate by creating isolated Python virtual environments for them. 
This is one of the most important tools that most Python developers use.

Tensorflow was clashing with already installed libraries. So i set up a a virtual environment (venv).

(base) camgoodhue@Camerons-MBP ~ % python -m venv tensorflow
(base) camgoodhue@Camerons-MBP ~ % source tensorflow/bin/activate

I then install tensorflow on my venv
(tensorflow) (base) camgoodhue@Camerons-MBP ~ % pip install tensorflow

I was required to update my virtual environment pip as well to be able to install tensorflow 
(tensorflow) (base) camgoodhue@Camerons-MBP ~ % pip install --upgrade pip

Install the tensorflow environment settings on to tehe Jupyter Notebook kernel as an option.
(tensorflow) (base) camgoodhue@Camerons-MBP cat-dog-classification % python -m ipykernel install --user --name=tensorflow

A good youtube video for setting up TensorFlow correctly with Jupyter notebook can be found here! https://www.youtube.com/watch?v=rbsWdaZYahE 




