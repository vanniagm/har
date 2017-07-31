## Human Activities Recognition

This data project is an exploration and prediction of different human activities using the dataset recorded by Ugulino, W. et al. (See publication:  [Wearable Computing: Accelerometers' Data Classification of Body Postures and Movements](http://groupware.les.inf.puc-rio.br/har)).
The authors documented the activities of six young health participants. The participants were asked to perform one set of 10 repetitions of the Unilateral Dumbbell Biceps Curl in five different fashions: exactly according to the specification (Class A), throwing the elbows to the front (Class B), lifting the dumbbell only halfway (Class C), lowering the dumbbell only halfway (Class D) and throwing the hips to the front (Class E).

Read more: [Article](http://groupware.les.inf.puc-rio.br/har#ixzz4nIbNef8f)

#### HAR database description

This database documents the following phenomena:
The devices record an event at 45 Hx, that means 1 read every .02 s. However the authors used for feature extraction a sliding window approach with different lengths from 0.5 second to 2.5 seconds, with 0.5 second overlap. In each step of the sliding window approach they calculated features on the Euler angles (roll, pitch and yaw), as well as the raw accelerometer, gyroscope and magnetometer readings. The 'classe' variable records the different positions the participants performed. I 

In this work I will first do a feature processing and selection, in order to illustrate the dependance of the activities classes variable I wish to predict and all the other variables. Next, a prediction model is built for the outcome "classe" taking into account any insight concluded from the exploratory analysis.

### The results are saved in the 'results.csv' file
