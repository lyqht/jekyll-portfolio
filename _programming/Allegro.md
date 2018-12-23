---
title: Allegro
excerpt: Kivy & Python Project to make a basic GUI that syncs real-time data from temperature, humidity and ambient light sensors from Firebase and displays it to the user.
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/programming/Allegro/databg.jpg
classes:
  - wide

---
<figure class="half">
    <a href="/assets/programming/Allegro/welcome_screen.png"><img src="/assets/programming/Allegro/welcome_screen.png"></a>
    <a href="/assets/programming/Allegro/data.jpg"><img src="/assets/programming/Allegro/data.jpg"></a>
</figure>

## Purpose
Allegro is a IOT project that involves the use of Kivy & Python Code to make a basic GUI that syncs real-time data from temperature, humidity and ambient light sensors to Firebase and displays it to the user. These sensors are connected together via a breadboard to a Raspberry Pi.

An overall relative score from the data is calculated as the Brisk Score in which the higher the Brisk Score is, the less likely the user should be drying their clothes on that day. A feedback on state of laundry room and also whether the user should do laundry today.

#### Group Members:
- Lee Gui An (piroton)
- Tey Siew Wen (lyqht)
- Tan Tiang Teck
- Merrick Tay Yu Jie
- Stephanie Lim Ann Tian Yuan

## About the project
<figure class="half">
  <a href="/assets/programming/poster.jpg"><img src="/assets/programming/Allegro/poster.jpg" width="50%"></a>
  <figcaption> Poster made by Merrick </figcaption>
</figure>

## Background of the Problem
Laundry room hazards are issues that have been easily overlooked. For example, there could be leakage from the washing machine hose, or that there could be accumulation of lint in the hose which could result in a fire. Detergents could also be forgotten to be sealed, resulting in contamination of air, which could pose a risk to the users' health, and it also affect the fabric condition of the laundry. Hence we propose a Kivy App that has a simple interface for users to access remotely and monitor the condition of their laundry room.


## Benefits of the proposed solutions
- IOT-enabled device allows for remote collection of laundry room condition data and monitoring
- Based on the trend of the brisk score against the elapsed time since the app starts monitoring the state of the laundry room, the app prompts investigation on the user's end if there could be a firehazard due to machine hose blockage or biohazard risk due to exposed detergents.

## Rooms for Improvement
Due to lack of time, and thus lack of training data, we were unable to implement machine learning facilties such as TensorFlow /sklearn module this time for predictive qualitative assessments of the Brisk score. However, having a machine learning algorithm would better allow users to pre-empt periods of bad laundry conditions and also allows for a larger range of more specific feedback for the user. For example, with enough data, the model may be able to suggest the exact timing that the laundry will take to dry if they choose to dry it in the current weather and laundry room condition.
