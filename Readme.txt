There are three folders: DQN, DDQN and output_video

--download all requirements from requirements.txt
--------------------------------inside DQN folder 
--Wimblepong is environment provided for simple AI agent (we use it as it is) 
--AAR_utils: it is our utility file 
--DQN agent : agent.py 
--run command : 

To train: 
python train_basic.py --train True

To test: 
python train_basic.py  #best model is saved and fetched

--imgs: plot of training reward
--weights: weights saved after each 500 epochs

-----------------------------------inside DDQN folder
--Wimblepong is environment provided for simple AI agent (we use it as it is) 
--AAR_utils: it is our utility file 
--DDQN agent: agent.py

--run command : 

To train: 
python train_basic.py --train True

To test: 
python train_basic.py  #best model is saved and fetched

--imgs: plot of training reward
--weights: weights saved after each 500 epochs

--------------------------------inside output video
--DQN_video : video for pong test using DQN
--DDQN_video : video for pong test using DDQN

--------------------------------------------------------------------------------------------------------------------

