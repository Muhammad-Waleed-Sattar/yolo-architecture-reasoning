# YOLO Architecture Reasoning: From v1 to Modern Variants

## Motivation
Object detection systems are often evaluated primarily through benchmarks such as mAP and inference speed. While these metrics are important, they do not explain *why* a particular architecture performs well or *why* certain design decisions persist across generations of models.

YOLO (You Only Look Once) represents a major shift in object detection by framing detection as a single regression problem rather than a multi-stage pipeline. Understanding the architectural reasoning behind YOLO—especially its early design choices—provides insight into how constraints such as real-time inference, computational efficiency, and end-to-end optimization shape modern deep learning systems.

This project focuses on reasoning about YOLO’s architectural structure rather than reproducing results, with the goal of developing deeper intuition about model design tradeoffs that generalize beyond a single algorithm.


## Problem Statement
What question this project tries to answer.

## Background: YOLO v1
High-level overview of YOLO v1 and its design philosophy.

## Key Architectural Decisions in YOLO
Why YOLO uses grid-based prediction, convolutional layers, and unified detection.

## Evolution Beyond YOLO v1
How and why later YOLO versions modified the original design.

## Tradeoffs and Design Reasoning
Accuracy vs speed, localization vs classification, simplicity vs flexibility.

## What I Would Explore With More Compute
Concrete next steps if given larger compute resources.

## Reflections
What I learned and how my understanding evolved.
