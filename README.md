# CatSimulator

## Short Description
- CatSimulator is cat-raising game which can raise a cat virtually.
- Demo Video: https://youtu.be/iwCqoYJd53U

## Member
- Eunbin Choi (Leader), Hyerin Joo, Younghyeon Joe

## Period
- 2017.04.10 ~ 2017.10.20

## Environment Setting & Tools & Language & Skills
- Environment Setting: Microsoft Kinect
- Tools: Unity3D, Jupyter Notebook
- Language: C#, Python
- Skills: LSTM

## Game Simulation
- A Gamer can play with a cat in the game virtual environment. The game can be controlled by human actions (i.e., the human hand is the computer's mouse) and a laser pointer can be used to guide the cat to the desired position of the gamer. Without the gamer's control, the cat moves randomly. If you are hungry, eat, and if you are bored, play with the scratcher or box in the game environment.
- Then, if the gamer's behavior is recognized by the Kinect3d camera, then the cat can understand the gamer's behavior and respond accordingly. For example, petting a cat will makes her expression better, and clapping a cat loudly will makes her expression worse. Also, when you cheer on a cat, the cat dances and sings to the cheer.

## Details
### 1) Game Environment
- A virtual environment had been developed to interact with cat abd human (gamer) in game using Unity3D. Here are many known objects that cat is known to love such as laser pointers (this is controlled by the gamer), stacked boxes, cat scratcher, and more.


### 2) Action Classfication
#### How to collect the training data which describes the action which can do with a cat ?
- Training data was collected manually using Kinect3D which can capture human action in 3D using a stereo camera, which define 3D sequence data.
- Using LSTM network, human's action was trained by training data, and predicted type of input action when test data is input in real time with the smallest root mean square deviation.

