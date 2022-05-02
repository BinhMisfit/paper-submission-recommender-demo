# Paper Submission Recommendation Demo

There are demo codes for our proposed paper submission recommendation platform.
#  Requirements

* Python 3.7
* This code was tested with python 3.7 in https://colab.research.google.com

# Install

    pip install -r requirements.txt
    
# Run

    python app.py
    
Open your browser at <a href="http://127.0.0.1:5000/">http://127.0.0.1:5000/ </a>.

# Run with notebook

You should run this code in https://colab.research.google.com

Firstly, pushing 2 data re_data_train and re_data_test as the following:

<img src="image/image1.PNG">

Secondly,  run step by step according to my instructions in the code 

#  Dataset

This dataset has 9347 documents in the training dataset and 4665 documents in the testing dataset, which are classiﬁed into 65 diﬀerent categories (journals or conferences)

## Data Preprocessing

In this section you can read our paper to know  more
example original data and pre-processed data:
|               |  Original data     | Pre-processed data              |          
| ------------- | ------------- | -------------|
| Title         | " Fighting malicious code: an eternal struggle"  |" ﬁght malici code etern struggl"        |
| Abstract      | "Despite many years of research and signiﬁcant commercial investment, the malware problem is far from being solved (or even reasonably well contained)..."  | "espit year research signiﬁc commerci invest malwar problem far solv reason contain week mainstream press publish articl incid million credit card leak larg .."|
| Keyword       |  "PAC-Bayes bound, support vector machine, generalization capability prediction, classiﬁcation"|  "pac-bayes bound”, “support vector machine”, “generalization capability prediction”, “classiﬁcation"            | 
