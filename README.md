# Machine-Learning-Project__Prediction-of-Train-Fare-wrt-Distance-

#Language:
This project is written in Python language

#IDE used:
Jupyter

#Project Summary:
In this project, I tried to calculate FARE of multiple trains with respect to DISTANCE, with good accuracy.




#Working Step:
1. This project takes input(Train Name) from user
2. Then it checks weather input is in dictionary(which have train name as key and train classes as value)
3. Then it asks for input(Train classes).
4. As the Train Name and Train class is saved in variable, it imports data of that train from device(filename=train_type+class_type
data=pd.read_csv(filename + '.csv'))
5. Then it splits data into x and y
6. Then the prog. starts testing and training of x and y data. I used most data to improve accuracy.
7. Then it asks for the DISTANCE from user
8.  After testing and training, prog. predicts the FARE of the Train, and as per the Distance.


#Tests:
1.
 Which train you are looking for: 
 Rajdhani 
 Satabdi 
 Jan Satabdi 
 Mail 
 Garibrath 
 Ordinary 
 
*Case Sensetive
Your Input:Mail

 Which Class: {'2S', 'SL', 'FC'}

 Your Input:2S

 My model accuracy is.. 99.73601630288793

 Distance:5486

 
 Fare of Mail for 5486.0 KM, of 2S is ₹ [1450.63726154] *Taxes not included
 
 2.
 Which train you are looking for: 
 Rajdhani 
 Satabdi 
 Jan Satabdi 
 Mail 
 Garibrath 
 Ordinary 
 
 *Case Sensetive
 Your Input:Rajdhani

 Which Class: {'3A', '2A', '1A'}

 Your Input:2A

 My model accuracy is.. 77.0047957246876

 Distance:568

 
 Fare of Rajdhani for 568.0 KM, of 2A is ₹ [1190.7500065] *Taxes not included


3.
 Which train you are looking for: 
 Rajdhani 
 Satabdi 
 Jan Satabdi 
 Mail 
 Garibrath 
 Ordinary 
 
 *Case Sensetive
 Your Input:Satabdi

 Which Class: {'EC', 'CC'}

 Your Input:EC

 My model accuracy is.. 99.52239543153355

 Distance:864

 
 Fare of Satabdi for 864.0 KM, of EC is ₹ [2298.56928488] *Taxes not included

4. 
 Which train you are looking for: 
 Rajdhani 
 Satabdi 
 Jan Satabdi 
 Mail 
 Garibrath 
 Ordinary 
 
 *Case Sensetive
 Your Input:Ordinary

 Which Class: {'FC', '2S', 'SL'}

 Your Input:FC

 My model accuracy is.. 99.61315314945921

 Distance:5688

 
 Fare of Ordinary for 5688.0 KM, of FC is ₹ [6624.00684287] *Taxes not included

5. WRONG INPUT 
 Which train you are looking for: 
 Rajdhani 
 Satabdi 
 Jan Satabdi 
 Mail 
 Garibrath 
 Ordinary 
 
 *Case Sensetive
 Your Input:ordinary

 Which Class: None
