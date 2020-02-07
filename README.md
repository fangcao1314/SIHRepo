# SIHRepo

The Goal of this Challenge is The Early Detection of Sepsis using Physiological Data. The Early Prediction of Sepsis is Potentially Life-Saving. So we will develop a Digital Solution that uses Machine Learning Techniques to predict Sepsis Atleast 6 Hours Before the Occurence of Disease in Patients. Internationally, an Estimated 30 Million People Develop Sepsis and 6 Million People Die from Sepsis Each Year. Early Detection Helps in Improving Sepsis Outcomes, where Each Hour of Delayed Treatment has been Associated with Roughly a 4-8% Increase in Mortality .
<br />
<br />

## PowerPoint Presentation for our problem statement
> https://github.com/sourabhyadav999/SIHRepo/blob/master/sepsis_ppt.pptx
> https://github.com/sourabhyadav999/SIHRepo/blob/master/sep.pptx

## QnA For Evaluation
## The QnA for our project has been updated and can be found at the same link
> https://github.com/sourabhyadav999/SIHRepo/blob/master/Product.docx


It is such a Difficult Problem to predict that till now Highest Accuracy which has been achieved is 67.3% by [Shamim Nemati](https://www.ncbi.nlm.nih.gov/pubmed/?term=Nemati%20S%5BAuthor%5D&cauthor=true&cauthor_uid=29286945 ), PhD, [Andre Holder](https://www.ncbi.nlm.nih.gov/pubmed/?term=Holder%20A%5BAuthor%5D&cauthor=true&cauthor_uid=29286945 ), MD, MSc, [Fereshteh Razmi](https://www.ncbi.nlm.nih.gov/pubmed/?term=Razmi%20F%5BAuthor%5D&cauthor=true&cauthor_uid=29286945 ), [Matthew D. Stanley](https://www.ncbi.nlm.nih.gov/pubmed/?term=Stanley%20MD%5BAuthor%5D&cauthor=true&cauthor_uid=29286945 ), MD, [Gari D. Clifford](https://www.ncbi.nlm.nih.gov/pubmed/?term=Clifford%20GD%5BAuthor%5D&cauthor=true&cauthor_uid=29286945 ), PhD, and [Timothy G. Buchman](https://www.ncbi.nlm.nih.gov/pubmed/?term=Buchman%20TG%5BAuthor%5D&cauthor=true&cauthor_uid=29286945 ), PhD, MD

The results of their research can be found here
> https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5851825/#!po=78.8889

<br>

This is also a challenge proposed by PhysioNet which gives deep insight into the problem
> https://physionet.org/content/challenge-2019/1.0.0/

<br>

## The website is deployed and you can check it out here
> https://sachinverma53121.github.io/SIHRepo/index.html

<br>
To make this model available for wider audience, we have implemented another feature to our project,An Android App.

### This App Apk bundle internally contains our model for prediction of sepsis, Which makes this app to work in offline situation where there is scarcity of internet
> https://github.com/suveb/SepsisPredictionApp

<br>

The code for creating REST Api service created that is implemented in our website is found here
> https://github.com/suveb/SepsisApiDeployment

<br>



<br>

Video Tutorial For Website
> https://drive.google.com/file/d/1SvQd4iZc8QOSQWxpq69SEZcvUM_qXkg3/view?usp=sharing

<br>

Video Tutorial For App
> https://drive.google.com/file/d/1Y4C6IqwIC35ozFvhetfi9inGEPG8ip_f/view?usp=drivesdk

<br>

## The Machine Learning Model for predicting the disease is present in this as jupyter notebook.
The Machine Learning Model uses Keras classifier for the classification of sepsis label. Currently we have a accuracy of 73% overall and 88.94% in positive cases. We used a layer of autoencoders for dimensionality reduction which will also increase its efficiency and decreasing the complexity. 
> [sepsisupdatedmodel.ipynb](https://github.com/sourabhyadav999/SIHRepo/blob/master/sisupdatedmodel.ipynb)


## System Requirements
Our website and App doesn't require any specific application.
The website can run on any Web browser.
Our App run offline on any Mobile device having sdk version greater than 21(Android Lollipop and Above)

