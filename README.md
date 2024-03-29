# WATCHYOU-AI Documentation

## Introduction

WATCHYOU-AI is a web application that utilizes machine learning and deep learning algorithms for real-time object detection using the COCO-SSD model from TensorFlow.js. The application allows users to interact with their webcam, capture snapshots, record videos, and toggle various settings. This documentation provides an overview of the project, installation instructions, usage guidelines, and configuration details.

## Overview

This project aims to provide users with a convenient tool for real-time object detection using their webcam. Leveraging the COCO-SSD model from TensorFlow.js, WATCHYOU-AI can detect various objects in the webcam feed. Additionally, it offers features such as auto-recording when a person is detected, user interaction buttons for flipping the video and capturing snapshots, settings for volume control and dark mode, and an intuitive user interface for easy interaction.

## Prerequisites

Before installing and using WATCHYOU-AI, ensure you have Node.js installed on your system. You can download and install Node.js from [here](https://nodejs.org/).

## Installation

To install WATCHYOU-AI, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/Saunakghosh10/watchyou.git
   ```

2. Navigate to the project directory:
   ```
   cd watchyou
   ```

3. Install dependencies:
   ```
   npm install
   ```

## Usage

Follow these steps to use WATCHYOU-AI:

1. Start the development server:
   ```
   npm run dev
   ```

2. Open your web browser and visit `http://localhost:3000`.

## Configuration

WATCHYOU-AI allows for customization through configuration adjustments. Follow these guidelines to configure the application:

- Adjust settings in the `src/components/theme-toggle` and other relevant files to customize the application behavior according to your preferences.

## Dependencies

WATCHYOU relies on the following dependencies:

- React
- ShadCN
- TensorFlow.js
- COCO-SSD
- Lucide-react
- React-loader-spinner
- Sonner
- React-webcam

## Acknowledgments

The creators of TensorFlow.js and COCO-SSD deserve special thanks for providing powerful tools that enable real-time object detection in web applications.
