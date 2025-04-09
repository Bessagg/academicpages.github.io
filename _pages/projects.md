---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /projects
---

# Table of Contents

- [Surgical Instruments Detection with Custom Trainning](#surgical-detection)
- [Patient's Clinical Outcome Prediction](#patient-outcome-prediction)
- [Model aggregation to forecast reservoir production](#forecast-oil-production)
- [Car suspension design](#apuama)

---

## Surgical Instruments Detection with Custom Trainning (2024 --)

- Automated inventory checks via a phone camera, reducing task time by 99%, from ~20minutes to seconds.
- The model identified missing components.
- Captured and manually annotated images to build a custom labeled dataset for model training.
- Fine-tuned YOLO using transfer learning to detect missing components.
- Identified screws by box position using a custom clustering algorithm.
- Handled low-contrast aluminum parts by testing lighting, angles, and OpenCV preprocessing.

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/detection_0.jpeg?raw=true"
           alt="detection_0" height="300"/>
      <div><b>(a)</b> Playing with opencv and distortion correction.</div> <!-- Placeholder for description -->
    </td>
    <td align="center">
      <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/detection_1.jpeg?raw=true"
           alt="detection_1" height="300"/>
      <div><b>(b)</b> - Initial setup to control: opencv + led lights.</div> <!-- Placeholder for description -->
    </td>
    <td align="center">
      <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/detection_01.jpeg?raw=true"
           alt="detection_01" height="300"/>
      <div><b>(c)</b> - Opencv transforms for blob detection.</div> <!-- Placeholder for description -->
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/detection_4.jpeg?raw=true"
           alt="detection_4" height="300"/>
      <div><b>(e)</b> - AI: natural light condition.</div> <!-- Placeholder for description -->
    </td>
    <td align="center">
      <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/detection_5.jpeg?raw=true"
           alt="detection_5" height="300"/>
      <div><b>(f)</b> - Detections with a segmentation model.</div> <!-- Placeholder for description -->
    </td>
    <td align="center">
    <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/gridded_image.png?raw=true"
          alt="detection_3" height="300"/>
    <div><b>(d)</b> - AI + clustering algorithm: color and labels by same row/column.</div> <!-- Placeholder for description -->
    </td>
  </tr>
</table>

<!-- Separate table for videos -->
<table>
  <tr>
    <td align="center">
      <video height="300" controls>
        <source src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/detection_video.mp4?raw=true"
                type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div><b>(g)</b> - App with solution</div>
    </td>
    <td align="center">
      <video height="300" controls>
        <source src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/detection_congress.mp4?raw=true"
                type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div><b>(h)</b> - Presented by Jhonson & Jhonson's CEO in SOBRACIL 2024, videosurgery congress.</div>
    </td>
  </tr>
</table>

---

## Patient's Clinical Outcome Prediction (2023 --)

- Objective: Accelerate treatment for high-risk patients by leveraging real-time data.
- Developed, evaluated and monitored models for patient's clinical outcome prediction. Deployed APIs for integration with the app.
- EHR (Electronic Health Record) data is continuously updated before the patient’s next scheduled consultation, potentially indicating risks in real-time. The model operates 24/7, delivering instant alerts to physicians and performing risk stratification, enabling faster interventions and improving patient outcomes.

<p align="center">
  <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/invisual_dash.jpeg?raw=true" alt="tiredata" width="800"/>
</p>

---

## Model aggregation to forecast medium-term reservoir production (2020 - 2021)

- Scientific initiation project, with a published paper in on of the biggest energy congress of the world, Rio Oil and Gas.
- I worked at Fortaleza's research group, STORMS. We used realizations of a benchmark resevouir model "OLYMPUS" as models to forecast production.
- We associated weights to each model and tested different optimization alogirthms to minimize a developed loss function.
- Particle Swarm optimization and others Bio-Inspired optimization algorithms.
- This strategy was validated with an average prediction error below 5%;

<p align="center">
  <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/model_agreg2.png?raw=true" alt="tiredata" width="800"/>
</p>

## Car suspension design - Apuama Racing - FSAE (2018 - 2019)

- Used mathematical models to create vehicle simulations (point-mass-model, biclycle-model).
- Used Tire Models to interpolate new data points from the tire's data.
- Developed a Suspension distribution forces program in Matlab. We would use the maximum forces obtained in braking and cornering simulations to dimension and reduce mass of the suspension.
- Project to reduce steering torque for better handling of the vehicle.
- Method to measure the car's center of gravity and validate design.

<table>
  <tr>
    <td>
      <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/hosier_tire_data.jpg?raw=true" alt="tiredata" height="200"/>
    </td>
    <td>
      <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/suspa_1.jpeg?raw=true" alt="suspa" height="200"/>
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/suspa_3.jpeg?raw=true" alt="suspa_3" height="200"/>
    </td>
    <td>
      <img src="https://github.com/Bessagg/academicpages.github.io/blob/master/_projects/suspa_4.jpeg?raw=true" alt="suspa_4" height="200"/>
    </td>
  </tr>
</table>

---
