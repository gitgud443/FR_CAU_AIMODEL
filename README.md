# AIsystem-2502

# Face Recognition API - Final Project

**Student Name:** Arthus ROBIN
**Student ID:** 50251582
**Course:** AI System  
**Date:** November 16, 2025

## Project Overview

A Docker-based face recognition API that compares facial similarity between two images using InsightFace and FastAPI.

Featuring face detection based on insightface.

## Technical Stack

- **Python**: 3.9
- **FastAPI**: 0.104.1
- **InsightFace**: 0.7.3 (for face detection, keypoints, and embeddings)
- **ONNXRuntime**: 1.15.1 (model inference)
- **OpenCV**: 4.8.1.78 (image processing)
- **Docker**: Containerization

### API Endpoints

- **GET `/health`** - Health check
- **GET `/torch-version`** - PyTorch version info
- **POST `/face-similarity`** - Main endpoint for face comparison
