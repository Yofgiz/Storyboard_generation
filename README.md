# Semantic Image and Text Alignment: Automated Storyboard Synthesis for Digital Advertising

## Overview

This project is aimed at automating the generation of advertisement sequences using a combination of images and text. The tool takes input from a JSON file that outlines a series of creative concepts. Each concept includes details such as the creative idea's name, a frame-by-frame breakdown, an overarching description of the advertisement's concept, and recommended assets for each frame. The tool then composes these concepts into frames and generates a sequence to convey the intended message to the audience. It's designed to streamline the process of creating ads for various platforms.

## Input JSON Format

The input JSON file outlines a series of concepts, with each object containing the following details:
* Concept: The creative idea's name.
* Implementation: A detailed, frame-by-frame breakdown, providing visual representations and explanations for each segment.
* Explanation: An overarching description of the advertisement's concept and the intended user flow.
* Asset Suggestions: For each frame, a curated list of three recommended assets is provided, detailing the category and a brief description of each suggested element.

## Features

## Image Generation

Utilizing various methods to geneate visually reach images from textual descriptions, ensuring a diverse and engaging visuual output.

## Text Generation

Implementation of strategies to transform text into visually appealing imagse, with a focus on size and other critical visual attributes.

## Image Composition

An algorithm for dynamically positioning and sizing of assets within a frame, providing flexibility and adaptability acrsoo diverse content types.

## Storyboard

An algorithm for arranging frames in a cohesive sequence, effectively conveying the progression of the ad campaign.

## Installation

- Clone this repository to your local machine using the following command:
```
    git clone https://github.com/Yofgiz/Storyboard_generation.git
    cd Storyboard_generation
```

- Install the required dependencies using pip and the provided requirements.txt file:
    `pip install -r requirements.txt`
