## Predict Dog vs Cat in an image file
This webapp is created using FastAPI. It will predict whether the given image is of a dog or a cat.
# Usage
[Click Here](https://predict-dog-vs-cat.herokuapp.com//docs)
1. Click on above link & move to Post Section
2. Click on Try it out
3. Choose the Image in which you want to predict & upload it
4. Click on Execute
5. Scroll Down To Server Response 
6. In Response Body check the prediction results
7. a. If predicted Image is of a cat, you will see the results in this format -
    {
        "Cat": 1,
        "Dog": 0
    }
    b. If predicted Image is of a dog, you will see the results in this format -
    {
        "Cat": 0,
        "Dog": 1
    }
## Model Trained Using Following Website
[Google Teachable Machine](https://teachablemachine.withgoogle.com/)
## Dataset Used To Train the Image Classification Model
[Kaggle Cat & Dog Dataset](https://www.kaggle.com/tongpython/cat-and-dog)
## FastAPI Docs
[FastAPI Docmentation](https://fastapi.tiangolo.com/)