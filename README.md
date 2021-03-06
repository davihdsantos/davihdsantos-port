# Davi Henrique's portfolio

Hello, my name is Davi Henrique. I have a Ph.D. in robotics. Currently (2021) I'm a post-doc researcher working with time series prediction using deep learning. You can check my academic production [here](https://scholar.google.com.br/citations?user=_vNl6lAAAAAJ&hl=en).

Next, I present some of the projects I've developed so far.


# [Project 1: Construction of the autonomous sailboat plaform Nboat](https://nboat-documentation.readthedocs.io/en/master/index.html)

This is a project that I've been working on since 2013 when I was an undergrad. The Nboat is a fully autonomous sailboat robot capable of performing long-term offshore missions without human intervention. I participated in the design and implementation of the electronic system and most of the software for the intelligence of the sailboat (both autonomous navigation and control). This project gave me hands-on experience with all aspects of an autonomous vehicle, from its actuators control, sensors, and data processing, to its intelligence, path planning, and following. It also increased my interest in autonomous systems.

<p align="center">
  <img src="https://nboat-documentation.readthedocs.io/en/nboat2/_images/nboat.png" width="250" alt="Nboat2"/>
</p>

Heres a [video](https://youtu.be/S_Lfw_ExR9Y) of the Nboat during field experiments. And heres a [video](https://youtu.be/S5Qi1rFyclI) of the Fboat, a twin of the Nboat that we constructed in late 2021.

# [Project 2: A framework for rapid viral infection forecast](http://ncovid.natalnet.br/)

The Ncovid framework is proposed as an environment for rapid forecast and understanding of the dynamics of viral pandemics, using state-of-the-art data-driven methods. The Ncovid framework offers several tools for end-to-end generation and evaluation of predictions, from traditional epidemiological models such as SIR and SEIRD, to the more modern ones based on Machine Learning and Deep Learning, offering confidence in the forecasts presented by our website. The main goal is that the Ncovid presents itself as an initial tool for rapid understanding of the epidemiological dynamics of future viral pandemics.

- Daily and weekly forecasts
- Automated data aquisition and processing
- Evaluation of models in production
- Automated training and deployment of forecast models
- Agile Scrum methodology
- Continous integration and deployment
- Containerized microservices

**Website under construction**

# [Project 3: Implementation of sailboat navigation system](https://github.com/Natalnet/ardupilot/tree/nboat_develop)

- Developed multiple controller strategies for the sail
- Developed new strategies to sail upwind
- Added metrics for performance evaluation
- Implemented these features in the Ardupilot framework
- Tested the system with SITL

# [Project 4: Simulator for Water Surface Vehicles in ROS-Gazebo](https://github.com/disaster-robotics-proalertas/usv_sim_lsa)

- A simulator with multiple USV platforms
- Realistic disturbances (dynamic waves, wind and water currents)
- Hydro and Aerodynamics modeling of all platforms
- Autopilot for all platforms (heading and speed control)

![boats](https://raw.githubusercontent.com/disaster-robotics-proalertas/usv_sim_lsa/master/images/barcos4.png)

# [Project 5: Forecast of COVID-19 time series using STACKED-LSTM](https://github.com/Natalnet/ncovid-air-paper)

- Predict the infected and deaths time series of COVID-19
- Use of deep learning techniques
- Implemented the data pre-processing and model training and evaluation
- Hyperparameter optimization of the network architecture
- Evaluation of multiple forecast models (generated with STACKED-LSTM)

![covid_forecast](https://github.com/Natalnet/ncovid-air-paper/blob/main/forecasted_curve.png?raw=true)
