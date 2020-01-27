# SIHRepo

The Goal of this Challenge is The Early Detection of Sepsis using Physiological Data. The Early Prediction of Sepsis is Potentially Life-Saving. So we will develop a Digital Solution that uses Machine Learning Techniques to predict Sepsis Atleast 6 Hours Before the Occurence of Disease in Patients. Internationally, an Estimated 30 Million People Develop Sepsis and 6 Million People Die from Sepsis Each Year. Early Detection Helps in Improving Sepsis Outcomes, where Each Hour of Delayed Treatment has been Associated with Roughly a 4-8% Increase in Mortality .
<br />
<br />

It is such a Difficult Problem to predict that till now Highest Accuracy which has been achieved is 67.3% by [Shamim Nemati](https://www.ncbi.nlm.nih.gov/pubmed/?term=Nemati%20S%5BAuthor%5D&cauthor=true&cauthor_uid=29286945 ), PhD, [Andre Holder](https://www.ncbi.nlm.nih.gov/pubmed/?term=Holder%20A%5BAuthor%5D&cauthor=true&cauthor_uid=29286945 ), MD, MSc, [Fereshteh Razmi](https://www.ncbi.nlm.nih.gov/pubmed/?term=Razmi%20F%5BAuthor%5D&cauthor=true&cauthor_uid=29286945 ), [Matthew D. Stanley](https://www.ncbi.nlm.nih.gov/pubmed/?term=Stanley%20MD%5BAuthor%5D&cauthor=true&cauthor_uid=29286945 ), MD, [Gari D. Clifford](https://www.ncbi.nlm.nih.gov/pubmed/?term=Clifford%20GD%5BAuthor%5D&cauthor=true&cauthor_uid=29286945 ), PhD, and [Timothy G. Buchman](https://www.ncbi.nlm.nih.gov/pubmed/?term=Buchman%20TG%5BAuthor%5D&cauthor=true&cauthor_uid=29286945 ), PhD, MD

The results of their research can be found here
> https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5851825/#!po=78.8889

<br>

This is also a challenge proposed by PhysioNet which gives deep insight into the problem
> https://physionet.org/content/challenge-2019/1.0.0/

<br>

The website is deployed and you can check it out here
> https://sachinverma53121.github.io/SIHRepo/index.html

<br>

The code for creating REST Api service created that is implemented in our website is found here
> https://github.com/suveb/SepsisApiDeployment

<br>

The Machine Learning Model for predicting the disease is present in this as jupyter notebook.
The Machine Learning Model uses Keras classifier for the classification of sepsis label. Currently we have a accuracy of 25%, and we are continously improving our model to increase the accuracy. We intend to use a layer of auto encoders for dimensionality reduction which will also increase its efficiency. 
> [sihmodel.ipynb](https://github.com/sourabhyadav999/SIHRepo/blob/master/sihmodel.ipynb )
