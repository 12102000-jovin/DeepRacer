# DeepRacer

## Recommendations

### Recommendation 1: Choose your action space wisely.

Choosing the action space is crucial because it determines the available speed and steering angle for the agent. Once the model is trained, the action space cannot be changed even if you clone it. There are two types of action spaces: discrete and continuous.

In a discrete action space, you can select a set of choices for speed and steering. You can decide how many actions you want, and for each angle, you can adjust the speed. For example, you can set the speed of the agent to 1m/s if the steering angle is 15 degrees. On the other hand, in a continuous action space, the agent learns to select the best speed and steering values from the ranges you set. Instead of limited choices, the agent can pick any value within specified ranges. For instance, it could choose a steering angle between -30 and +30 degrees and an acceleration value between 1.2m/s and 2.4m/s.

I am using the continuous action space because it allows the agent to make small adjustments and achieve smoother driving on the track. However, it faces challenges in finding the right balance between speed and control. To get better results, I recommend training it for more than an hour. Since there are no fixed choices, the agent needs to explore and experiment with various values within the specified ranges.

![image](https://github.com/12102000-jovin/DeepRacer/assets/84697754/cb37ce24-18c4-4d74-9eb0-8c7cf85bba13)

