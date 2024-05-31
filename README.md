# Nature Language Processing: Sentiment Analysis on Mental Health Problem Classification

---

This is my group project of COMP4211 Machine Learning in HKUST.

This project invloves using 6 different machine learning architectures (Naive Bayes, MLP, CNN, RNN, trnsformers)

1) Naive Bayes Classifier
2) MLP (One-hot model)
3) RNN (Index model)
4) CNN model
5) DistilBERT
6) XLNet

to do sentiment analysis on mental health problem classification.

The dataset is obtained from here: https://www.kaggle.com/datasets/reihanenamdari/mental-health-corpus

The research paper on DistilBERT: https://arxiv.org/pdf/1910.01108

The reserach paper on XLNet: https://arxiv.org/pdf/1906.08237

You should see the following things in this repository:

* COMP4211 final report.pdf: the final report for this project
* COMP4211 Presentation Slide.pdf: the presentation slide we use in the video
* COMP4211 project code.ipynb: the Jupyter Notebook
* COMP4211 project description.pdf: the description guideline of this project
* COMP4211 Project Proposal.pdf: the initial proposal of this project
* mental_health.csv: the dataset we used in this project
* DistilBERT.pdf: the reserach paper on DistilBERT
* XLNet.pdf: the research paper on XLNet

---

## Final Presentation Video:

https://youtu.be/t2dk0Re3IWc

---

## How to run?

1. Upload the Jupyter Notebook and the dataset to Google Drive
2. Open the Jupyter Notebook using Google Colab, and change the file location inside the code if necessary
3. Run all the code once

---

### Group members:

* CHAN, Chun Hin (me)
* LAW, Hui Nok

---

#### Feedback from Professor Yeung Dit Yan on project proposal:

```
Sentiment analysis as a text classification task has been extensively studied in the natural language processing (NLP) community even well before the resurgence of interest in using deep learning methods for NLP. As for chatbots, the presentation in the proposal is a bit too general. Formulation of the specific machine learning tasks involved needs more detailed elaboration. As sentiment analysis has been studed extensively, you need to put some thoughts on the novelty of the proposed application. For example, is it possible to define a variant of sentiment analysis that is much less studied by others than the usual formulation?

Grade: 95/100
```

---

#### Feedback from Professor Yeung Dit Yan on final report, presentation video, presentation slide and the Jupyter Notebook:

```
>> Report and Source Code <<

[A] 15/15

[B] 10/10

[C] 10/10

[D] 10/10

[E] 8/10

[F] 16/20
It would help to set aside a validation set to help you determine the hyperparameters for different models or achieve early stopping during model training.

[G] 12/20
In the plot on page 21, it shows that the validation accuracy is already about 0.84 at epoch 0 even though the traning accuracy is much lower. This is very abnormal. The learning curves on page 24 seem to indicate the occurrence of overfitting. You could have done something to address this issue. On page 25, the learning curve is even more abnormal. The validation accuracy is already close to 0.9 initially before learning starts! Actually it's the same for some later models without pretraining. On page 27-28, you need to explain why the learning curves fluctuate like this (also some later models). In general, the readers should be guided through the figures and visualizations with more informative text to help them gain a deeper understanding of the results. Moreover, performing error case analysis would also help to provide better insights. For clarity, it would help to give a concise summary of the performance comparison at the end, say using a table.

[H] 5/5

>> Video Presentation and Slides <<

[A] 20/20

[B] 30/30

[C] 24/30
It would help to use slide animation or a pointer to help the reader focus attention on the part you are presenting. This would be especially essential for slides with a lot of materials. It would be good to end the presentation with a short conclusion of the work and findings.

[D] 20/20

>> General <<
This task is very similar to sentiment analysis.

Grade: 88.2/100
```

