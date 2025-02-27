# AstraSync
# AI-Powered Interview Assessment System

This project implements a state-of-the-art AI-powered interview assessment system that evaluates a candidate's speech, language proficiency, body language, and behavioral cues using deep learning models. The system is optimized for real-time performance on an RTX 4060 GPU.

## Features
- **Speech-to-Text (STT) with Filler Word Detection & Pronunciation Analysis**
- **Lexical Richness & Sentence Complexity Analysis**
- **AI Vision-Based Interview Behavior Analysis**
- **Speech & Vision Fusion for AI-Based Scoring**
- **Interactive Web-Based AI Evaluation Dashboard**
- **JSON-Based Interview Reports**

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ai_interview_assessment.git
    cd ai_interview_assessment
    ```

2. Build the Docker image:
    ```bash
    docker build -t ai_interview_assessment .
    ```

3. Run the Docker container:
    ```bash
    docker run -p 8000:8000 ai_interview_assessment
    ```

4. Open your browser and navigate to `http://localhost:8000`.

## Usage
- The web-based dashboard provides an interactive interface for conducting and evaluating interviews.
- API endpoints are available for integrating with other systems.

## Directory Structure
```plaintext
ai_interview_assessment/
├── Dockerfile
├── README.md
├── app/
│   ├── __init__.py
│   ├── main.py
│   ├── models/
│   │   ├── __init__.py
│   │   ├── whisper_large_v3.py
│   │   ├── deepgram_filler_detection.py
│   │   ├── speechbrain_pronunciation_analysis.py
│   │   ├── extract_mfcc.py
│   │   ├── deepgaze_eye_tracking.py
│   │   ├── attire_classification.py
│   │   ├── movement_tracking.py
│   │   ├── emotion_detection.py
│   ├── utils/
│   │   ├── __init__.py
│   │   ├── real_time_inference.py
│   │   ├── report_generation.py
│   ├── static/
│   │   ├── styles.css
│   ├── templates/
│   │   ├── index.html
│   ├── config.py
├── requirements.txt
```

## License
[MIT License](LICENSE)
