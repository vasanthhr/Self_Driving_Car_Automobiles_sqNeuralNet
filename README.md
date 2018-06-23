## Self_Driving_Car_Automobiles_sqNeuralNet

### Getting Started


<img src="https://github.com/vasanthhr/Self_Driving_Car_Automobiles_sqNeuralNet/blob/master/Autonomous_vehicles.JPG" width="500" height="400" />

<br/>


#### Module Overview
```
I have placed my code/package(main core part) in github repository. 
And please find the below points to understand more on it.

1. The code shows the neural networks, which involves Convolutional Neural Networks(CNN) and 
   Last layer of Recurrent Neural Network(RNN). 

2. Here, the Convolutional Neural Networks process the input frames/images and send back to 
   Recurrent Neural Network. 
   
@Courtesy : NVIDIA  (The Model structure)

I gave code here and it’s a foundation to achieve self-driving car/automobiles or autonomous car/automobiles.

But I haven’t posted my another modules here that has more hidden layers 
and multi LSTMs (complete Deep Learning and Self/Auto learning). 


I can support/guide you if you want work on this Deep Learning and Self/Auto learning process.

```
<br/>


#### Predict input videos (here: Frames/Images)
```
Predict the Driving angle by passing live frames/images.

Realtime inputs: Input Frames/Images would come from Dynamic Camera/Video processor
                 (Usually it would be attached in cars/automobiles coverage area.).

Use more samples and epochs to increase the acccuracy and to redcue the loss.

Here, by seeing overall results I could say that model achieved with good precision 
(precision: To measure model's performance).

```
##### Output for this live(Below Image Input: Frame/Image):
```

array([[103.16771]], dtype=float32)

Car needs to be turned right by Degree : 103.16771
```
<img src="https://github.com/vasanthhr/Self_Driving_Car_Automobiles_sqNeuralNet/blob/master/Car_turning_slight_right.JPG" width="600" height="380" />
