# AWS DeepRacer Student League

A reinforcement learning (RL) reward function I built for the AWS DeepRacer Student League. Ranked first in Sweden and top 50 in the EU twice. Received an Udacity AI & ML Nanodegree ($9000) scholarship.


I found that the car could constantly maintain the student league's maximum speed of 1.0 m/s throughout the track, so I gave speed the largest weight in the reward function.

- **Speed:** reward increases up to the maximum speed.
- **Heading:** reward alignment with the track direction, calculated from nearby waypoints.
- **Position:** reward staying near the centerline, decreasing with distance from it.
