# Greek salad-Ice cream Classifier
# Tools used
This was built with PyTorch/FastAI for the Machine Learning part and Flask as a Webserver. For containerization and easy deployment I use Docker. The dataset in use is the Food-101 Dataset but I chose to only use two of the foods contained there.

# How to use
You can easily use this as a template for your own models.

Train your own Model
<a href='https://colab.research.google.com/drive/1BMeaXUz02Dsed-PVefRBeJPsTxepBjUk?usp=sharing'>Open in Colab</a>

Go ahead and open the Notebook in Colab with a simple press of a button! Most steps will be described in detail there. Just follow along!

You can decide which two foods you want to classify by changing:

#Deciding which two foods we want to classify
labelA = 'samosa'
labelB = 'churros'
