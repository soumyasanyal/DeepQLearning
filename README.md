# DeepQLearning
Implementation of Self Driving Car using Deep Q Networks - part of <a href="https://www.udemy.com/artificial-intelligence-az/learn/v4/overview">Artificial Intelligence A-Z Udemy course work</a>.

Dependencies:
1. PyTorch
2. Cython
3. Kivy

The objective of the project was to train a car (the white box along with the funky colored beads which are signals for the car) so that it can follow an randomly drawn road (in yellow) and move from airport (top left corner) to downtown (bottom right corner) and back. And, as expected, the car should not be crossing the road. To run the code, the above dependencies need to be installed and then run the 'map.py' file.

Few gifs of outputs:
1. With no road drawn:
![Car with no road](https://github.com/soumyasanyal/DeepQLearning/blob/master/img1.gif)
1. With a simple road drawn:
![Car with simple road](https://github.com/soumyasanyal/DeepQLearning/blob/master/img2.gif)
