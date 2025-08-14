# 🤖 Fashion Vibe Classifier

This project is an AI-powered tool designed to analyze and classify the "vibe" of an outfit based on visual characteristics. It uses a combination of three distinct deep learning models to score an outfit on a spectrum from "Classy" to "Cool."

## Features

The classification is based on three key fashion attributes, with a dedicated Convolutional Neural Network (CNN) for each:

1.  **Fit Tightness Model:** Classifies the fit of the clothing as either `tight` or `baggy`.
2.  **Complexity Model:** Determines if the outfit consists of a `single layer` or is `multilayer`.
3.  **Pattern Density Model:** Analyzes the fabric pattern, categorizing it as `solid`, `checked`, or `printed`.

## The Scoring System

The predictions from these three models are fed into a scoring system. Each classification contributes to a final score that determines the overall vibe of the outfit, providing a unique and insightful analysis of fashion styles.

## Dataset

The image dataset used for training these models was **personally curated** for this project. The data was gathered, cleaned, and manually labeled to ensure quality and relevance for each of the three classification tasks.
