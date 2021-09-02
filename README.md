# Deploying a Sentiment Analysis Model
In this project, our goal will be to have a simple web page that a user can use to enter a movie review. The web page will then send the review off to our deployed model (Recurrent Neural Network), which will predict the sentiment of the entered review. All that mainly with Amazon Web Services (AWS) and Pytorch.

## Project Outline
Recall the general outline for SageMaker projects using a notebook instance, which is comprised of the following:
1. Download or otherwise retrieve the data.
2. Process / Prepare the data.
3. Upload the processed data to S3.
4. Train a chosen model.
5. Test the trained model (typically using a batch transform job).
6. Deploy the trained model.
7. Use the deployed model.

For this project, you will be following the steps in the general outline with some modifications.

## Instructions
This project requires **Python 3.x** version. And in order to complete this project, you need to install the following libraries:

- [sklearn](https://scikit-learn.org/stable/)
- [nltk](https://www.nltk.org/)
- [bs4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [numpy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org)
- [Amazon SageMaker](https://sagemaker.readthedocs.io/en/stable/)
- [torch](https://pytorch.org/docs/stable/index.html)
- [boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html).

I recommend installing [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

Also, we will be using the [IMDb dataset](http://ai.stanford.edu/~amaas/data/sentiment/).

### Code

Template code is provided in the `SageMaker Project.ipynb` file.

### Run

In a terminal or command window, navigate to the top-level project directory `Deploying-a-Sentiment-Analysis-Model/` (that contains this README) and run one of the following commands:

```bash
ipython notebook "SageMaker Project.ipynb"
```  
or
```bash
jupyter notebook "SageMaker Project.ipynb"
```

This will open the iPython Notebook software in your browser.