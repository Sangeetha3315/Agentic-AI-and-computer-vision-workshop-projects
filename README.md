# Agentic-AI-and-computer-vision-workshop-projects

This repository contains the AI projects I worked on during a series of hands-on workshops.

The workshops gave me a chance to experiment with different areas of AI instead of just learning the concepts theoretically. The projects cover **Computer Vision, RAG, and AI Agents**, and most of the work was done using Google Colab.

## Projects

### 🖐️ Hand Gesture Classifier

A computer vision project that classifies different hand gestures from images.

I worked with OpenCV and explored transfer learning using **MobileNetV2** with TensorFlow/Keras. The project also includes webcam-based image capture and prediction.

**Tech:** Python, OpenCV, TensorFlow, Keras, MobileNetV2

---

### 👤 Smart Attendance System

A real-time face recognition project that uses a webcam to identify enrolled people and record their attendance.

The project combines **YOLO for face detection** and **DeepFace for face recognition**, along with OpenCV for the live camera feed. Attendance is recorded with timestamps and can be exported as a CSV file.

**Tech:** Python, OpenCV, YOLOv8, DeepFace, NumPy, Pandas

---

### 📚 RAG Research Assistant

A project exploring how **Retrieval-Augmented Generation (RAG)** can be used to work with research papers.

Research papers are downloaded from arXiv, their text is extracted and divided into smaller chunks, and the chunks are converted into embeddings using Sentence Transformers. **FAISS** is then used to find relevant information, which is passed to a Groq LLM to generate the final response.

**Tech:** Python, PyPDF, Sentence Transformers, FAISS, Groq

---

### 🤖 AI Research Agent

A simple AI research workflow that combines an LLM with web search.

The agent can search the web, retrieve information from webpages, and use the retrieved content to generate a research-oriented response.

**Tech:** Python, Groq, DuckDuckGo Search, Requests, BeautifulSoup

---

## What I Learned

Working through these projects gave me practical exposure to things I had mostly encountered as concepts before, including:

* Working with pretrained AI models
* Image classification and computer vision
* Face detection and recognition
* Transfer learning
* Processing live webcam input
* Embeddings and vector search
* Building a basic RAG pipeline
* Working with LLM APIs
* Using web search with AI
* Connecting different components together to build an AI workflow

## About This Repository

These are **workshop projects**, not projects I developed completely from scratch. I'm keeping them here as a record of what I learned and experimented with during the workshops.

As I continue learning, I plan to build my own projects using some of these concepts and take them further.

## Running the Projects

The projects are provided as Jupyter/Google Colab notebooks.

You can open a notebook in Google Colab and run the cells in order. Some projects may require a GPU, external APIs, or additional packages.

Check the individual notebook for its specific requirements.

