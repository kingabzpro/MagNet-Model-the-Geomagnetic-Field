# MagNet Model the Geomagnetic Field
[![View in Deepnote](https://deepnote.com/static/buttons/view-in-deepnote.svg)](https://deepnote.com/viewer/github/kingabzpro/MagNet-Model-the-Geomagnetic-Field/blob/main/magnet-model-the-geomagnetic-field.ipynb)
## Overview

![Magnet](https://drivendata-public-assets.s3.amazonaws.com/noaa-cover-img.png)
Help NOAA better forecast changes in Earth’s magnetic field!

The efficient transfer of energy from solar wind into the Earth’s magnetic field causes geomagnetic storms. The resulting variations in the magnetic field increase errors in magnetic navigation. The disturbance-storm-time index, or Dst, is a measure of the severity of the geomagnetic storm.

As a key specification of the magnetospheric dynamics, the Dst index is used to drive geomagnetic disturbance models such as NOAA/NCEI’s High Definition Geomagnetic Model - Real-Time (HDGM-RT). Additionally, magnetic surveyors, government agencies, academic institutions, satellite operators, and power grid operators use the Dst index to analyze the strength and duration of geomagnetic storms.

Empirical models have been proposed as early as in 1975 to forecast Dst solely from solar-wind observations at the Lagrangian (L1) position by satellites such as NOAA’s Deep Space Climate Observatory (DSCOVR) or NASA's Advanced Composition Explorer (ACE). Over the past three decades, several models were proposed for solar wind forecasting of Dst, including empirical, physics-based, and machine learning approaches. While the ML models generally perform better than models based on the other approaches, there is still room to improve, especially when predicting extreme events. More importantly, we seek solutions that work on the raw, real-time data streams and are agnostic to sensor malfunctions and noise.

## Task
In this challenge, your task is to develop models for forecasting Dst that push the boundary of predictive performance, under operationally viable constraints, using the real-time solar-wind (RTSW) data feeds from NOAA’s DSCOVR and NASA’s ACE satellites. Improved models can provide more advanced warning of geomagnetic storms and reduce errors in magnetic navigation systems.

Head on over to the [Problem Description](https://www.drivendata.org/competitions/73/noaa-magnetic-forecasting/page/279/) to get started!

## Problem description
The goal of this challenge is to develop models for forecasting Dst (Disturbance Storm-Time Index) that 1) push the boundary of predictive performance 2) under operationally viable constraints 3) using specified real-time solar-wind data feeds. More information on the dataset, performance metric, and submission specifications is provided below.

Finalists will be determined by performance on the private test set. These participants will then have the opportunity to submit their code to be audited using an out-of-sample verification set. The top 4 eligible teams that pass this final check will be awarded prizes.

**You can find more information on** [DataDriven](https://www.drivendata.org/competitions/73/noaa-magnetic-forecasting/page/279/)

## Result

I scored 40th rank in this DrivenData competition and my Jounery started with simple LSTM. You can look at all the versions. I will be relising GPU and CPU version of this notebook. [Ranking](https://www.drivendata.org/competitions/73/noaa-magnetic-forecasting/leaderboard/)

# Rules to get top 50

1) **Persistence**

![image.png](https://i.imgur.com/mVZgYui.png)

The code submission was quite different and it took me one week to get hold of it, even in a later stage when you try to use bidirectional LSTM you will get the error, you need to note down what works for cloud computing what doesn't. I have gained better scores with multiple layers of the bidirectional model but they eventually failed in the submission area.

2) **Look for a new model especially Medium Notebooks**

It took me 2 weeks just to implement these new experimental designs on these data sets, but it was worth it as I gain more knowledge on what works what doesn't. 

3) **Take a Break and reset your mindset**

If you keep on working on one thing, you will get frustrated and things will get hard. Try taking breaks.

4) **It's better to find a dedicated teammate.**

We get better when we share our idea and try to implement them together.

5) **If you are new to DataScience try to at least participate in the random competition.**

Participating in multiple competitions has helped me better understand models and real problems that can be solved with the models. I was amazed at how pre-trained models were better in performance than simple NN.
