<h1 align="center">Hi there 👋, I'm Nguyen Hong Nhat Linh</h1>
<h3 align="center">AI Engineer · Computer Vision · Edge AI · LLM</h3>

<p align="center">
  <a href="mailto:nlinh.nh7@gmail.com"><img src="https://img.shields.io/badge/Email-nlinh.nh7%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/LinhNhat07"><img src="https://img.shields.io/badge/GitHub-LinhNhat07-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  <img src="https://img.shields.io/badge/Location-Vietnam-2E8B57?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=LinhNhat07&color=blue&style=flat-square" alt="Profile views"/>
</p>

---

## 🧑‍💻 About Me

- 🎓 **B.Sc. in Data Science – Information Technology**, Ho Chi Minh City University of Technology, 2021 – 2025
- 🏭 **AI Engineer** at **Hondaplus Vietnam Co., Ltd.**, building AI-powered quality inspection systems for production lines
- 🔭 Focus areas: **Computer Vision** (object detection, segmentation, anomaly detection), **VLM**, **OCR**, **Edge AI**, **LLM & RAG**
- 📄 Co-author of **VR-TSD**, published at the international conference **CSA 2025** (Springer)
- 🌐 Languages: Vietnamese (native), English (basic), Chinese (basic)
- 📫 Reach me at **nlinh.nh7@gmail.com**

---

## 🛠️ Skills

**Programming Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**AI / Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)
![GStreamer](https://img.shields.io/badge/GStreamer-FF3131?style=flat-square&logo=gstreamer&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat-square)

**Models & Architectures:** YOLO (v5/v8/v11, YOLOX, YOLO-NAS), RT-DETR, RTMDet, EfficientDet, Detectron2 (Faster R-CNN), SSD-MobileNet, PatchCore, DeepLabV3, ResNet, EfficientNet, ViT, CLIP, Transformer, PhoBERT

**LLM & Chatbots:** RAG, local / on-premise chatbots, open-source LLMs (Gemma 4, gpt-oss, DeepSeek, Qwen)

**Backend & Applications**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![PyQt5](https://img.shields.io/badge/PyQt5-41CD52?style=flat-square&logo=qt&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Edge AI, Hardware & IoT**

![NVIDIA Jetson](https://img.shields.io/badge/NVIDIA%20Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)

- Edge devices: NVIDIA Jetson (AGX, Orin, Nano), Raspberry Pi; FP16/INT8 model quantization
- Industrial cameras: Keyence, Basler, Cognex, Dino-Lite
- Industrial integration: PLC, RS485, ESP32, Telegram API
- Networking & IT: LAN/Wi-Fi, TCP/IP, router/switch configuration, PC maintenance, user support

---

## 💼 Work Experience

### 🏢 AI Engineer — Hondaplus Vietnam Co., Ltd.
*Feb 2025 – Present*

**🔍 [Industrial AI Visual Inspection System](https://github.com/LinhNhat07/Industrial-AI-Visual-Inspection-System)**
- Two inspection problems on bottle production lines: **appearance inspection** (defects, foreign objects, plastic threads) and **label inspection** (skewed, inverted, misplaced labels)
- Researched, benchmarked and deployed YOLO (v8, v11, YOLOX, YOLO-NAS), RTMDet, RT-DETR, EfficientDet, Detectron2 (Faster R-CNN) and SSD-MobileNet; two-stage **RT-DETRv2** (crop → detect) for tiny defects; **PatchCore** anomaly detection when defect data is scarce; **DeepLabV3** for semantic segmentation (ResNet/ViT backbones). Achieved **mAP@50 of 0.89 – 0.99**
- Label inspection with cascaded detectors and a configurable rule engine (split lines → OK / NG), object tracking to count each bottle once, and per-product profiles
- Acquired live data from industrial cameras (Keyence, Basler, Cognex, Dino-Lite) using OpenCV and hardware-accelerated GStreamer
- Collected raw production-line data, filtered noise and manually labeled images to build a high-quality ground-truth dataset
- Deployed on Jetson Orin / Orin Nano / Nano and an RTX 5060 workstation; optimized with TensorRT and ONNX (FP16/INT8): **~290 ms** per 10 MP image for appearance inspection and **~150 ms** per image for label inspection, within the line cycle time
- PLC-triggered capture and real-time NG signals to **Keyence PLCs** to trigger air blowers or robotic arms that remove defective products from the line
- Built a desktop app (PyQt5) and web apps (FastAPI/Flask) with real-time monitoring dashboards, logging and defect statistics on PostgreSQL
- Instant alerts via Telegram API; buzzers and warning lights controlled over Modbus RTU / RS485 / ESP32
- System in production at the company and at its **parent company in Japan**
- 🎬 [Project demo](https://drive.google.com/drive/folders/1SxIDtwbnsQlO3FvqJkyTdKspGBzYx1n4)

**🤖 Internal AI Chatbot**
- Chatbot combining **RAG** with open-source LLMs (Gemma, gpt-oss, Qwen)
- Python web app for employees to use on the company intranet
- Runs fully **on-premise** on a PC with an RTX 5060 Ti GPU; data never leaves the company

**🖧 IT System Administration**
- Installed and maintained computers and network equipment (LAN/Wi-Fi, routers, switches); troubleshot hardware, software and network issues for staff

### 🏢 AI Engineer Intern — Hondaplus Vietnam Co., Ltd.
*Aug 2024 – Feb 2025*

- Insect detection and monitoring system with **YOLOv8**, classifying and tracking multiple species in real time
- Defect detection on product trays with **YOLOX**, detecting foreign objects as small as **0.03 mm**
- Integrated a multi-camera Basler setup with Jetson Orin for real-time quality control on the production line
- Built a departmental task management system in **C#**

---

## 🚀 Featured Projects

| Project | Domain | Highlights |
|---|---|---|
| 🏭 [Industrial AI Visual Inspection System](https://github.com/LinhNhat07/Industrial-AI-Visual-Inspection-System) | Computer Vision · Edge AI | Appearance defects (RT-DETR + PatchCore) and label skew/inversion (YOLO / RTMDet / RT-DETR) on Jetson, 150–290 ms per image, PLC/Modbus |
| 🚦 [VR-TSD: Vietnamese Traffic Sign Recognition](https://github.com/LinhNhat07/VR-TSD-Vietnamese-Traffic-Sign-Recognition) | Computer Vision · Research | CSA 2025 paper (co-author), mAP@50 0.94, 168 FPS + Vietnamese voice alerts |
| 💬 [Vietnamese News Comment Sentiment Classification](https://github.com/LinhNhat07/Vietnamese-Comment-Sentiment-PhoBERT) | NLP | PhoBERT on 9.2k labeled VnExpress reader comments, 78% accuracy |
| 🏠 [HCMC House Price Prediction](https://github.com/LinhNhat07/HCMC-House-Price-Prediction) | Machine Learning | XGBoost on 9.5k crawled listings, R² 0.80 |

### 🚦 [VR-TSD: Vietnamese Traffic Sign Recognition](https://github.com/LinhNhat07/VR-TSD-Vietnamese-Traffic-Sign-Recognition)
> *A Real-World Dataset and a Lightweight YOLOv8n Model for Traffic Sign Recognition in Vietnam*

- 📄 **Co-author** of the paper published at **CSA 2025 – The 17th International Conference on Computer Science and its Applications** · [Read on Springer](https://link.springer.com/chapter/10.1007/978-981-95-7896-2_10)
- **My role:** worked across the research pipeline: data collection and labeling, preprocessing, training and benchmarking, and evaluation
- **VR-TSD dataset:** 58 classes, 8,078 images, 13,016 manually labeled boxes from dash cams and phones (night, backlight, rain, occlusion)
- Benchmarked 6 lightweight models (YOLOv5nu/su, YOLOv8n/s, YOLO11n/s); chose **YOLOv8n** for its balance of accuracy, speed and size
- Results: **mAP@0.5 = 0.9434**, **168.86 FPS** on an NVIDIA A100, **77.52 FPS** on iPhone 11 Pro Max (NCNN), 6 MB
- **Extension beyond the paper:** real-time pipeline with **Vietnamese voice alerts** (temporal filtering, per-sign cooldown, gTTS)
- Tech: `Python` `PyTorch` `Ultralytics` `Roboflow` `NCNN` `OpenCV` `gTTS`
- 🎬 [Voice alert demo](https://drive.google.com/file/d/1JtekjwLvfJC0tHHrWJdlvd40RyeMrAkl/view)

### 💬 [Vietnamese News Comment Sentiment Classification with PhoBERT](https://github.com/LinhNhat07/Vietnamese-Comment-Sentiment-PhoBERT)
- Crawled **18,913 reader comments** from VnExpress (Selenium + BeautifulSoup) and labeled **9,153** of them (Negative / Neutral / Positive)
- Engagement analysis of the most-discussed articles and most-liked / most-replied comments
- Fine-tuned **PhoBERT** in PyTorch with class balancing (Neutral is only 9% of the data)
- Results: **Accuracy = 78.25%**, F1-weighted = 0.78, F1-macro = 0.69
- Tech: `Python` `PyTorch` `Hugging Face` `PhoBERT` `Selenium` `BeautifulSoup`

### 🏠 [Ho Chi Minh City House Price Prediction with XGBoost](https://github.com/LinhNhat07/HCMC-House-Price-Prediction)
- Crawled **9,482 real-estate listings** from Rever.vn; parsed free-text prices, removed missing values and IQR price outliers (7,494 rows for training)
- XGBoost Regressor on location (street, ward, district) and size features, compared with a Linear Regression baseline (R² = 0.50)
- Results: **R² = 0.80** (5-fold CV 0.80 ± 0.007), MAE = 1.01, RMSE = 1.45 billion VND, MAPE = 17%
- Tech: `Python` `Pandas` `NumPy` `Scikit-learn` `XGBoost`

---

## 🏆 Achievements

| Date | Achievement |
|---|---|
| Nov 12, 2025 | 📄 **VR-TSD** paper published at **CSA 2025** – The 17th International Conference on Computer Science and its Applications ([Springer](https://link.springer.com/chapter/10.1007/978-981-95-7896-2_10)) |

---

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=LinhNhat07&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=LinhNhat07&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=LinhNhat07&theme=tokyonight&hide_border=true" alt="GitHub streak"/>
</p>

---

<p align="center"><i>⭐ Thanks for stopping by! Always happy to connect and collaborate.</i></p>
