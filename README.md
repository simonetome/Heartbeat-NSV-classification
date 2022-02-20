<h2>Heartbeat classification using Machine and Deep learning
techniques</h2>

<h4>Project for <em>Applied AI in Biomedicine</em> @ <strong>PoliMi</strong> (prof. Valentina Corino)</h4>

<h3>Abstract</h3>
In this project, some Machine Learning models have been applied for classifying three different
types of beats in an ECG: normal sinus rhythm beats, ventricular beats like premature ventricular
complex beats (PVCs), and supraventricular beats like premature atrial complex beats (PACs).
The methodology used was carried out applying as input of the models the preprocessed signals
divided into patches centered on the peak to be classified. The models inspected are classical
Machine Learning models such as Support Vector Classifier, K-Nearest Neighbors and Random
Forest Classifier, and also complex Neural Networks like ResNet or CNN with LSTM. Those
methods are trained not only with the preprocessed input but also with a reconstructed input
obtained by an Autoencoder that constructs easily identified patches of beats.


<h3>Authors</h3>

- Francesco Masciulli: MSc Computer Engineering;
- Francesca Pietrobon: MSc Mathematical Engineering;
- Simone Tomè: MSc Computer Engineering;


<h3>Repository structure</h3>

```
├─── models                     // saved models
├─── Papers                     // bibliography
├─── report                     // final report
├─── report                     // results one the final dataset
├─── AE_models.ipynb            // ML models with Autoencoder
├─── final_model.ipynb          // final model for the test set 
├─── LSTM_CNN.ipynb             // model one vs all CNN + LSTM
├─── Resnet.ipynb               // ResNet model 
├─── test_production.ipynb      // notebook for predictions on test set 
└─── training_set.zip           // Dataset
```

<h4>Main Dependencies</h4>

```
- Pyhton 3.x
- TensorFlow
- Keras
- Pandas
- Numpy 
- tqdm
- Matplotlib 
```
