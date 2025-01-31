## Reinforcement Learning Visualized

## Environment

The environment is a simple 1D line where the agent has a starting position at zero and the goal is located at 100. The agent can either accelerate or deaccelarate to reach the goal state from the starting position. 

![Screen-Recording-2022-05-18-at-1 36 22](https://user-images.githubusercontent.com/50364479/168923762-e985f555-eebb-4727-8686-fc28beda565b.gif)

### 2x2 teacher

Here we have visualized the cell divisions and actions during the training for teacher which has a 2x2 policy. The figure below shows the evolution of the actions during the training. Yellow color represents acceleration while purple denotes deacceleration. In all of the visualizations, the trajectory of the car is shown as a black line. 

<img src="https://user-images.githubusercontent.com/50364479/171622561-cfa84caa-2e6b-46b1-ac3f-7291b7ab9dd9.gif" width="600">

The figure below shows the cell divisions of the agent during the training.

<img src="https://user-images.githubusercontent.com/50364479/171622575-b7ccef67-0981-43e4-b5e4-541222a3f699.gif" width="600">

The figure below visualizes the cell divisions of the last layer of the agent.

<img src="https://user-images.githubusercontent.com/50364479/171622838-d517b639-bcc0-45eb-a8f5-db98ab470bc6.gif" width="600">



### 2x2x2x2 student

Next, we train a 2x2x2x2 student using the the teacher that was given as an example in the previous section. The actions during the training are visualized below. The first two layers are copied from the teacher and not optimized during the training.

<img src="https://user-images.githubusercontent.com/50364479/171622802-8d872a30-1d40-4a44-936d-c40017d0f68f.gif" width="600">

The figure below shows the cell divisions of the agent during the training.

<img src="https://user-images.githubusercontent.com/50364479/171622816-f781f7de-9507-4ac5-9531-ceb8d2c33e0a.gif" width="600">

The figure below visualizes the cell divisions of the last two layers of the agent.

<img src="https://user-images.githubusercontent.com/50364479/171622597-197b9e1b-338e-4252-9312-ff51f3483dc5.gif" width="600">

The final report can be found behind this link [report](https://github.com/ylajaaski/state_space_page/files/8842312/State_Space_Final_Paper__Copy_.pdf).


