# Day 2 – Image Analysis using Azure AI Vision SDK

This folder contains my Day 2 exploration of Azure AI Vision services as part of my AI Engineer learning path.

## 🧠 Objective
Use the Azure AI Vision SDK in Python to analyze an image and extract visual information like captions, tags, and object/person detection.

---

## 🛠️ Setup
- **Azure Service**: Computer Vision (Azure AI Vision)
- **Language**: Python
- **Library Used**: `azure-ai-vision-imageanalysis==1.0.0`
- **Environment**: Virtual Environment with `requirements.txt`
- **Credentials**: `.env` file storing `AZURE_COMPUTER_VISION_KEY` and `AZURE_COMPUTER_VISION_ENDPOINT`

---

## 📂 Files
- `image-analysis.py` – Python script performing image analysis
- `.env` – Environment file storing API key and endpoint
- `objects.jpg` – Image output with detected objects
- `people.jpg` – Image output with detected people
- `requirements.txt` – List of Python dependencies
- `README.md` – This file

---

## ⚙️ Features Implemented
- ✅ **Caption Generation**: AI-generated sentence summarizing the image
- ✅ **Dense Captions**: Multiple region-specific captions
- ✅ **Tags**: Descriptive keywords like "tree", "car", "person"
- ✅ **Object Detection**: Bounding boxes around identified items
- ✅ **People Detection**: Bounding boxes around human figures

---

## 🖼️ Sample Output
![objects](https://github.com/user-attachments/assets/0a52e445-4181-4923-a36c-114a69c4f461)

