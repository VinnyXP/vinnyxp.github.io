---
draft: false
date: 2024-05-02
authors:
  - vinnyxp
categories:
  - Hardware
---

# Anti-Bump Sensor
This project aims to promote safe driving and avoid car collisions through the Anti-Bump Sensor. In this workshop, we explore the old features of existing cars’ sensors and incorporate new ideas to make the anti-bump sensor prototype. Our research results in a focus on the mapping ability of the sensor and the audio + visual alerts that are the most beneficial for the driver.
<figure markdown="span">
  ![Anti-Bump Sensor](../../../images/antibumpsensor.jpg){ width="300" }
  <figcaption>Inner Working of the Anti-Bump Sensor</figcaption>
</figure>
<!-- more -->

## What it does
<figure markdown="span">
  ![Anti-Bump Sensor](../../../images/antibumpsensor-description.png){ width="800" }
  <figcaption>Project Description</figcaption>
</figure>

## Development Process
We designed an anti-bump sensor for car parking, integrating Lidar, LCD, and Speaker components to alert drivers of obstacles. The Lidar detects obstacles within specified ranges, with audible alerts increasing in frequency as obstacles near. 

Our research identified two types of Lidar sensors: topographic and bathymetric, distinguished by the color of the light beam they use. Our goal is to advance Lidar capabilities to track gestures.

The LCD provides visual display alerts, enhancing communication between driver and sensor. It empowers drivers with statistical information on obstacles and route paths. The Speaker delivers audible alerts, with improved sound quality for effective attention-grabbing. The sensor's outer structure is made of cardboard for low-budget, high-quality construction. 

It is designed to withstand environmental factors like dust and flooding, prioritizing detection of dense obstacles while minimizing interference from dust particles. Although not theft-resistant, the cardboard structure offers protection against natural disasters like flooding due to its dual-layer design with vertical air pockets.

## What I Learned
We first tackled connecting the Lidar sensor to the Arduino, using diagrams to understand pin functions. However, we faced hardware issues during testing, including a spam-like message on the LCD Display. After ruling out code errors, we focused on the wiring. By referencing connection diagrams, we optimized our wire setup. Moving each wire down one pin on the Arduino resolved the spam message.

Another challenge with the LCD Display was poor contrast, making messages hard to read against the background. Despite budget constraints, we used a potentiometer to adjust light levels, improving readability day and night.

## Improvement Room
To enhance our anti-bump sensor further, several avenues for improvement can be explored. Firstly, integrating a power switch would provide the convenience of turning the device on and off as needed, conserving energy and prolonging battery life. 

Additionally, incorporating a robust protective layer with heat-resistant properties would safeguard the internal components from damage caused by high temperatures, ensuring reliable performance even in adverse environmental conditions.

Improving the accuracy of the sensor's readings is another crucial aspect to consider. This could involve fine-tuning the algorithms used for obstacle detection or enhancing the sensitivity of the Lidar sensor to capture more precise data. By achieving greater accuracy, we can enhance the overall effectiveness of the anti-bump sensor in identifying potential hazards and alerting drivers accordingly.

Furthermore, enhancing the quality of the sounds produced by the speaker would contribute to better auditory alerts for drivers. This could entail investing in higher-quality audio components or refining the sound patterns emitted by the sensor to make them more attention-grabbing and easily distinguishable in noisy environments.
