# CatSimulator

## Short Description
- CatSimulator is cat-raising game which can raise a cat virtually.

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
- A virtual environment was developed to interact cat in game with human (gamer) using Unity3D, where a number of known objects here that are known to be liked by cats, which a laser pointer controlled by a human (gamer) (cat likes following laser pointer), climb up stacked boxes, cat scratchers, etc.


### 2) Action Classfication
#### How to collect the training data which describes the action which can do with a cat ?
- Data was collected manually using Kinect3D which can capture human action in 3D using a stereo camera. 

- CatSimulator can classify human's action using sequenctial 3D data for cetain action, which is clapping, stroking, or hugging with 
- This project was made for graudation project to get a bachelor's degree. We made behavior classifier using sequential 3D data (x, y, z axis for certain action)
- Related language and tools: C#, Unity
