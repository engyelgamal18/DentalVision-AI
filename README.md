# DentalVision AI

DentalVision AI is a hands-on AI project that explores how object detection can be used with panoramic dental X-rays.

The goal of the project is to understand how AI can help dentists during image review by highlighting possible findings, while keeping the final clinical decision with the dentist.

## Project Overview

In this project, I worked on:

- Preparing panoramic dental X-ray images
- Image annotation
- Training an object detection model
- Reviewing AI predictions
- Evaluating the model results

I used YOLOv11 as the object detection model.

## Who This Project Is For

This project is mainly for:

- Dental professionals interested in AI
- Students learning about AI in healthcare
- People interested in object detection and medical imaging

DentalVision AI is not designed to replace a dentist or make an independent diagnosis.

## Project Workflow

The project follows four main stages:

1. **Prepare Data**  
   I prepared and reviewed panoramic dental X-ray images for the project.

2. **Annotation**  
   I added and reviewed annotations for different dental classes.

3. **Model Training**  
   I trained and tested a YOLOv11 object detection model using the prepared images.

4. **Prediction & Evaluation**  
   I reviewed the model predictions and evaluation results to understand its performance.


## Architecture

```text
Panoramic Dental X-rays
          ↓
   Image Preparation
          ↓
      Annotation
          ↓
   YOLOv11 Training
          ↓
     AI Prediction
          ↓
  Model Evaluation
          ↓
 DentalVision AI Demo
```

## Website Demo

The project website gives an interactive walkthrough of the DentalVision AI workflow.

Users can:

- Explore the project workflow
- View original panoramic X-rays
- View annotated dental images
- Review AI predictions
- View model evaluation results
  
 ## Running the Website Locally

1. Download or clone this repository.

 ```bash  
git clone https://github.com/engyelgamal18/DentalVision-AI.git
 ```
2. Open the project folder.

3. Open `index.html` in a browser.

You can also use the Live Server extension in Visual Studio Code.

No additional dependencies are required for the website.

## Usage Example

Open the DentalVision AI website and select:

**Project Gallery → Start Analysis**

The interactive imaging console allows users to move through the project workflow using the Previous and Next controls.

The viewer includes examples of:

- Original panoramic X-rays
- Dental image annotations
- Manual annotation examples
- AI model analysis
- AI prediction examples
- Final evaluation results
  
## V2 Evaluation Results

The final model evaluation included the following metrics:

- Precision: 71.1%
- Recall: 75.3%
- mAP@50: 76.7%
- F1 Score: 73.1%
  
 ## Limitations

The project has some important limitations:

- The model was trained on a limited dataset.
- Results may change depending on image quality and patient cases.
- The detections still need to be reviewed by a qualified dental professional.
- The model does not provide an independent clinical diagnosis.
- More data and external testing would be needed before any real clinical use.

 ## What I Would Improve Next

If I continue developing DentalVision AI, I would like to:

- Use a larger and more diverse dataset.
- Add more dental finding classes.
- Test the model on completely unseen images.
- Improve the evaluation process.
- Improve the interactive prediction viewer.
- Make detection results easier to inspect at full size.

## AI Transparency

I used AI tools during this project to help with coding, troubleshooting, documentation, and understanding parts of the workflow.

I reviewed and tested the outputs myself, including the website, model results, project content, and final presentation.

AI was used as a learning and development assistant, not as a replacement for clinical judgment.

## Disclaimer

DentalVision AI is an educational and experimental project.

It is not a medical device and should not be used for diagnosis or treatment decisions. Clinical interpretation should always be performed by a qualified dental professional.
