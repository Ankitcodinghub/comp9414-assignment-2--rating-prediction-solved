# comp9414-assignment-2--rating-prediction-solved
**TO GET THIS SOLUTION VISIT:** [COMP9414 Assignment 2- Rating Prediction Solved](https://www.ankitcodinghub.com/product/comp9414-artificial-intelligence-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120158&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP9414 Assignment 2- Rating Prediction Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
This assignment is inspired by a typical real-life scenario. Imagine you have been hired as a Data Scientist by a major e-commerce retailer. Your job is to analyse customer reviews to determine whether you can predict the ratings of new products so they can be promoted on your website.

For this assignment, you will be given a collection of Amazon customer reviews. Each review consists of short text (a few sentences), and one of five ratings: a number from 1 to 5. You are required to evaluate various supervised machine learning methods using a variety of features and settings to determine what methods work best for rating prediction in this domain (these features could then be used to recommend items to users based on their interests).

The assignment has two components: programming to produce a collection of models for rating prediction, and a report to evaluate the effectiveness of the models. The programming part involves development of Python code for data preprocessing of reviews and experimentation of methods using NLP and machine learning toolkits. The report involves evaluating and comparing the models using various metrics.

You will use the NLTK toolkit for basic language preprocessing, and scikit-learn for feature construction and evaluating the machine learning models. You will be given an example of how to use NLTK and scikit-learn to define the machine learning methods (example.py), and an example of how to plot metrics in a graph (plot.py).

Data and Methods

A training dataset is a .tsv (tab separated values) file containing a number of reviews, with one review per line, and linebreaks within reviews removed. Each line of the .tsv file has three fields: instance number, text and rating (a number from 1 to 5). A test dataset is a .tsv file in the same format as a training dataset except that your code should ignore the rating field. Training and test datasets can be drawn from supplied file reviews.tsv (see below). For evaluation of the models, we will use one 80–20 split of this file.

Use the supervised learning methods discussed in the lectures: Decision Trees (DT), Bernoulli Naive Bayes (BNB) and Multinomial Naive Bayes (MNB). Do not code these methods: instead use the implementations from scikit-learn. Read the scikit-learn documentation on Decision Trees and Naive Bayes, and the linked pages describing the parameters of the methods.

Look at example.py to see how to use CountVectorizer and train and test the machine learning algorithms, including how to generate metrics for the models developed, and plot.py to see how to plot these metrics on a graph for inclusion in your report.

The programming part of the assignment is to produce DT, BNB and MNB models and your own model for rating prediction in Python programs that can be called from the command line to train and classify reviews read from correctly formatted .tsv files. The report part of the assignment is to analyse these models using a variety of parameters, preprocessing tools and scenarios.

Programming

You will submit four Python programs: (i) DT classifier.py, (ii) BNBclassifier.py, (iii) MNBclassifier.py and (iv) my classifier.py. The first three of these are standard models as defined below. The last is a model that you develop following experimentation with the data. Use the given dataset reviews.tsv containing 2500 labelled reviews to develop and test the models, as described below.

These programs, when called from the command line, will read from standard input (not a hardcoded file reviews.tsv), and should print to standard output (not a hard-coded file output.txt), the instance number and rating produced by the classifier of each review in the test set when trained on the training set (one per line with a space between the instance number and rating – a number from 1 to 5), where the training set is the first 80% of the file, and the test set is the remaining 20% (the file length will always be divisible by 5). For example: python3 DT classifier.py &lt; reviews.tsv &gt; output.txt

should write to the file output.txt the instance number and rating of each review in the test set (the last 20% of the file), as determined by the Decision Tree classifier trained on the training set (the first 80% of the file).

When reading in the dataset, make sure your code reads all the instances (some Python readers use “excel” format, which uses double quotes as separators).

Standard Models

You will develop three standard models. For all models, make sure that scikit-learn does not convert the text to lower case. For Decision Trees, use scikit-learn’s Decision Tree method with criterion set to ’entropy’ and with random state=0. Scikit-learn’s Decision Tree method does not implement pruning, rather you should ensure that Decision Tree construction stops when a node covers fewer than 1% of the training set. Decision Trees are prone to fragmentation, so to avoid overfitting and reduce computation time, for the Decision Tree models use as features only the 1000 most frequent words from the vocabulary, after preprocessing to remove “junk” characters as described above. Write code to train and test a Decision Tree model in DT classifier.py.

For both BNB and MNB, use scikit-learn’s implementations, but use all of the words in the vocabulary as features. Write two Pythons programs for training and testing Naive Bayes models, one a BNB model and one an MNB model, in BNBclassifier.py and MNBclassifier.py.

Your Model

Develop your best model for rating prediction by either varying the number and type of input features for the learners, the parameters of the learners, and the training/test set split, or by using another method from scikit-learn. Submit one program, my classifier.py, that trains and tests a model in the same way as for the standard models. Conduct new experiments to analyse your model and present results that justify your choice of this model in the report.

Report

In the report, you will first evaluate the standard models, then present your own model. For questions 1–4 below, consider two scenarios, where there are 5 classes in scenario 1 corresponding to the ratings, but 3 classes in scenario 2, where the ratings are combined into a “sentiment”:

(1) the classes are the rating values from 1 to 5 (1, 2, 3, 4 and 5), and

(2) the classes are a “sentiment”, where 1, 2 or 3 is negative, 4 is neutral and 5 is positive. For evaluating all models, report the results of training on the first 2000 instances in the dataset (the “training set”) and testing on the remaining 500 instances (the “test set”).

Use the metrics (micro- and macro-accuracy, precision, recall and F1) and classification reports from scikit-learn. Show the results in Python plots (do not take screenshots of sklearn classification reports), and write a short response to each question below. The answer to each question should be self contained. Your report should be at most 10 pages. Do not include appendices.

(i) Show all metrics on the test set for scenario 1 comparing the two models (a) and (b), and explain any similarities and differences.

(ii) Show all metrics on the test set for scenario 2 comparing the two models (a) and (b), and explain any similarities and differences.

(iii) Explain any differences in the results between scenarios 1 and 2.

(i) Show all metrics on the test set for scenario 1 comparing the corresponding models (a) and (b), and explain any similarities and differences.

(ii) Show all metrics on the test set for scenario 2 comparing the corresponding models (a) and (b), and explain any similarities and differences.

(iii) Explain any differences in the results between scenarios 1 and 2.

(i) Show all metrics on the test set for scenario 1 comparing the corresponding models (a) and (b), and explain any similarities and differences.

(ii) Show all metrics on the test set for scenario 2 comparing the corresponding models (a) and (b), and explain any similarities and differences.

(iii) Explain any differences in the results between scenarios 1 and 2.

(i) Show all metrics on the test set for scenario 1 comparing the corresponding models (a) and (b), and explain any similarities and differences.

(ii) Show all metrics on the test set for scenario 2 comparing the corresponding models (a) and (b), and explain any similarities and differences.

(iii) Explain any differences in the results between scenarios 1 and 2.

Submission

• Make sure your name and zid appears on each page of the report

• Submit all your files using a command such as (this includes Python code and report):

give cs9414 ass2 DT*.py BNB*.py MNB*.py myclassifier.py report.pdf

• Your submission should include:

– Your .py files for the specified models and your model, plus any .py “helper” files

– A .pdf file containing your report

• When your files are submitted, a test will be done to ensure that one of your Python files runs on the CSE machine (take note of any error messages printed out)

• When running your code on CSE machines:

– Do not download NLTK in your code: CSE machines have NLTK installed

• Check that your submission has been received using the command:

9414 classrun -check ass2

Assessment

Assessment Criteria

• Correctness: Assessed on standard input tests, using calls such as:

python3 DT classifier.py &lt; reviews.tsv &gt; output.txt

• Report: Assessed on correctness and thoroughness of experimental analysis, clarity and succinctness of explanations, and presentation quality.
