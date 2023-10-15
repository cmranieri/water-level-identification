# Water level identification with laser sensors, inertial units, and machine learning

## Citation request

Ranieri, C.M., Foletto, A.V., Garcia, R.D., Matos, S.N., Medina, M.M., Marcolino, L.S. and Ueyama, J., 2024. Water level identification with laser sensors, inertial units, and machine learning. _Engineering Applications of Artificial Intelligence_, 127, p.107235.

You can check the original paper [here](https://authors.elsevier.com/a/1hvOs3OWJ94sCr).


## Descritpion

When it comes to managing flood risks, it's crucial to know exactly how high the water is in places like rivers and streams in cities. Imagine trying to gauge the height of a river without actually touching it. We considered two types of sensors for this aim: ultrasonic sensors and LiDAR sensors. The ultrasonic ones send sound waves to measure depth, while LiDAR uses laser light. The advantage? LiDAR isn't bothered by typical flood conditions like fog or heavy rainfall. However, not many people have really checked if LiDAR is good for this job.

In our recent study, we wanted to see if LiDAR can achieve reliable performance under not ideal conditions. So, we set up a controlled experiment using both types of sensors and an inertial measurement unit (IMU) to see how things like water cloudiness and angle of measurement might affect accuracy. We threw in some machine-learning magic to see if we could improve our predictions.

By combining data from these devices with machine learning, our predictions became way more accurate! The ultrasonic sensor was particularly better when the water was clear and the angle was higher. But overall, there wasn't a massive difference between the two.

This repo contains the data, the experiments and the analysis made in this work and published in the research paper.
