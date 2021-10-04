# deploying_deep learning _ model
deploying saved melanoma model using FLASK 

Steps needed to deploy the model :
    # way to upload image
    # way to save the image
    # function to make prediction on the image
    # show the results

Tested the script on deploying melanoma Classification model(trained on SEResNext50_32x4d , dataset taken from Kaggle (https://www.kaggle.com/c/siim-isic-melanoma-classification/data))

Same scripts can be use to deploy any model(some obvious changes needed)
Also, this repo doesn't have model.bin file, so cloning the repo directly might show an error for the same.

Further Help : to deploy the models, FastAPI can also be used(might be preferably better).
                https://www.youtube.com/watch?v=1zMQBe0l1bM [Build a machine learning API from scratch with FastAPI - YouTube]
