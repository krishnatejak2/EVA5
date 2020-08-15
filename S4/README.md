# Session 55

## EVA5_Session_4.ipynb
Taken from S5 - file 1 

**Basic Code + Network Structure**  
   
**Target :**  

1. 99.4% (this must be consistently shown in your last few epochs, and not a one-time achievement) **Pending**
2. Less than or equal to 15 Epochs **Done**   
3. Less than 10000 Parameters **Pending**  

**Achieved :**  ConvShape+Codestructure+Basic observations

1. Get the set-up right **Done**  
2. Set Transforms **Done**  
3. Set Data Loader **Done**  
4. Set Basic Working Code **Done**  
5. Set Basic Training  & Test Loop **Done**  
6. Experiemnt with the code **Done**  
7. Rewrite the convolutions in meaningful way **Done**  

**Results :**  

1. Epochs : **15**  
2. Parameters : **16,190**  
3. Best Train Accuracy : **96.62%**  
4. Best Test Accuracy : **98.86%**  

**Analysis :**  

1.  In the Initial Epochs, the Test acuuracy is very high compared to train accuracy - which means the model is doing quite good even at lower epochs - it might be picking up the right features early on  
2. It can be observed that the training accuracy kept on increasing through out all the epochs - which means the model is doing what it is supposed to do : learning continuously  
3. But the Test accuracy dips after some epochs - which mean that the model might be overfitting after all  
4. The Dip in the test accuracy can be observed after multiple epochs in the logs  
5. Any kind of regularization can be helpful to us in this scenario  
6. Personally, I would be happy of i do not see any kinks in the Test accuracy graph - that is no hiccups in the graph  
7. But, the number of params in the network had to be reduced first  
8. Since the Test accuracy is not trailing much behing the Train Accuracy, we might say that it is not overfitting by large  
