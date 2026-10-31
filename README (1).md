# AI Accessibility Communication Agent

An AI-powered accessibility project designed to help people with
different communication needs interact more easily with the world around
them.

The **AI Accessibility Communication Agent** aims to bring together sign
language understanding, speech and text processing, computer vision, and
an intelligent communication agent in one system. Its goal is to reduce
communication barriers and support more inclusive everyday interactions.

> **Project status:** This repository is under development. Features
> described as planned or in progress are goals of the project and
> should not be considered completed unless their implementation is
> available in the repository.

## Project Overview

People with disabilities may face communication barriers when
interacting with people, services, or environments that do not support
their preferred way of communicating. This project explores how AI can
make those interactions more accessible.

The system is designed around multiple input and output methods,
including sign language, text, speech, and images. An AI agent is
intended to understand the user's request, identify the required action,
and provide an accessible response.

## Main Modules

### 1. Sign Language Recognition and Translation

-   Analyze sign language input from video.
-   Extract body and hand movement features using computer vision.
-   Recognize sign sequences and translate them into readable text.
-   Explore continuous sign language translation, where a sequence of
    signs is converted into a meaningful sentence.

### 2. Text and Speech Interaction

-   Accept text or speech as communication input.
-   Convert text into speech where audio output is needed.
-   Support the planned conversion of text or speech into sign-language
    output through an animated avatar.

### 3. Image and Document Understanding

-   Process images such as documents, menus, labels, and everyday
    objects.
-   Use OCR to extract readable text from supported images.
-   Make extracted information available through accessible text or
    speech output.

### 4. AI Communication Agent

-   Interpret the user's request and infer the intended task.
-   Support interaction flows such as asking for information, requesting
    assistance, or communicating a need.
-   Provide clear responses and confirmations before actions where
    appropriate.

### 5. Accessibility-Focused Interaction

The project is intended to support different communication needs,
including speaking, hearing, reading, seeing, writing, and
learning-related accessibility scenarios. The exact supported workflows
will depend on the final implementation.

## Current Development Focus

One major development track is the **Sign Language Recognition &
Translation** module.

Work and experiments in this area include:

-   Skeleton-based sign recognition using the ArabSign dataset.
-   An LSTM-based model using extracted skeletal features.
-   Experiments with continuous sign language translation using the
    How2Sign dataset.
-   2D human keypoint extraction with OpenPose.
-   Development of a Transformer-based model to process sequences of
    keypoints and generate text tokens.

These are research and development activities; model performance and
supported capabilities should be reported with the corresponding
experiment details rather than assumed to represent the complete system.

## Technologies

The project uses or explores the following technologies:

-   **Programming:** Python
-   **Deep Learning:** PyTorch, LSTM, Transformers
-   **Computer Vision:** OpenPose, human keypoint extraction
-   **Datasets:** ArabSign, How2Sign
-   **Language Processing:** Natural Language Processing (NLP)
-   **Image Text Extraction:** OCR

The final technology stack may change as the system develops.

## High-Level Workflow

1.  The user provides an input through a supported modality, such as
    video, text, speech, or an image.
2.  The relevant module processes the input.
3.  AI models extract useful information, recognize signs, or interpret
    the request.
4.  The communication agent determines an appropriate response or next
    step.
5.  The system presents the result in an accessible format, such as
    text, speech, or a planned sign-language avatar.

## Project Goals

-   Reduce communication barriers between people with disabilities and
    the wider community.
-   Explore reliable sign language recognition and continuous
    translation.
-   Support multiple input and output modalities.
-   Make everyday information more accessible through OCR and speech.
-   Build an extensible AI-based accessibility assistant.

## Team

Developed as a graduation project by a team of five students at the
Faculty of Engineering, Artificial Intelligence Department, Ismailia
National University.

## Project Status

**In progress.** Individual modules are being researched, developed, and
tested. Integration into one complete communication assistant is part of
the project roadmap.

## Disclaimer

This project is an academic development effort. It is not a certified
medical device, emergency response service, or guaranteed replacement
for professional sign language interpreters or accessibility support.

## License

No license has been specified yet. Add a license file before allowing
others to reuse, modify, or distribute this project.
