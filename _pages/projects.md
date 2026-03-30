---
layout: single
title: "Selected Projects"
permalink: /projects/
author_profile: false
---

<div class="project-showcase">
    <p class="project-showcase__lead">
        A selection of representative projects in robotics system design, perception, planning, and autonomous exploration.
    </p>

    <article class="project-card">
        <div class="project-card__media">
            <img src="{{ '/images/projects/titan.jpg' | relative_url }}" alt="Titan humanoid combat robot">
        </div>
        <div class="project-card__body">
            <h3 class="project-card__title">Design and Development of Titan: A Humanoid Combat Robot</h3>
            <p class="project-card__period">July 2021 - July 2022</p>
            <ul class="project-card__points">
                <li>Designed the full mechanical structure and developed control circuit boards with a custom remote-control pipeline.</li>
                <li>Built control and communication APIs and delivered a PC-based motion editing and visualization interface.</li>
                <li>Received National-level Outstanding Achievement in Innovation and Entrepreneurship and was selected for the 16th National College Students' Innovation and Entrepreneurship Annual Conference.</li>
            </ul>
        </div>
    </article>

    <article class="project-card">
        <div class="project-card__media">
            <img src="{{ '/images/projects/teleoperation.gif' | relative_url }}" alt="Teleoperation system visualization">
        </div>
        <div class="project-card__body">
            <h3 class="project-card__title">Multi-sensor Fusion Teleoperation for Robotic Manipulators</h3>
            <p class="project-card__period">September 2022 - May 2023</p>
            <ul class="project-card__points">
                <li>Combined eye tracker, RealSense, and Kinect to estimate grasp target position and human-arm posture for grip solution derivation.</li>
                <li>Integrated A* path planning and polynomial interpolation, then established a secure trajectory channel for force-feedback teleoperation.</li>
                <li>Validated in real-world experiments with a 36% accuracy improvement over traditional teleoperation methods.</li>
            </ul>
        </div>
    </article>

    <article class="project-card">
        <div class="project-card__media project-card__media--split">
            <img src="{{ '/images/projects/formation.gif' | relative_url }}" alt="UAV swarm formation flight">
            <img src="{{ '/images/projects/transformation.gif' | relative_url }}" alt="UAV swarm formation transformation">
        </div>
        <div class="project-card__body">
            <h3 class="project-card__title">UAV Swarm Formation Transformation</h3>
            <p class="project-card__period">August 2023 - November 2023</p>
            <ul class="project-card__points">
                <li>Improved swarm localization accuracy via UWB, IMU, and vision fusion.</li>
                <li>Applied the Hungarian algorithm to optimize formation-transformation task allocation and reduce energy cost.</li>
                <li>Completed real-world validation with stable formation-switching behavior.</li>
            </ul>
        </div>
    </article>

    <article class="project-card">
        <div class="project-card__media">
            <img src="{{ '/images/projects/cave_exploration.gif' | relative_url }}" alt="Autonomous cave exploration visualization">
        </div>
        <div class="project-card__body">
            <h3 class="project-card__title">Autonomous UAV Exploration of Unknown Mine Environments</h3>
            <p class="project-card__period">March 2024 - August 2024</p>
            <ul class="project-card__points">
                <li>Developed an autonomous UAV system for large-scale underground mine exploration in communication-denied environments.</li>
                <li>Integrated frontier-based exploration with K-TSP viewpoint planning for efficient and lightweight search.</li>
                <li>Used kinodynamic A* and B-spline smoothing to generate safe and smooth trajectories in complex spaces over 1 million m<sup>3</sup>.</li>
            </ul>
        </div>
    </article>
</div>