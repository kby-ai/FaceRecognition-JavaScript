<p align="center">
  <a href="https://play.google.com/store/apps/dev?id=7086930298279250852" target="_blank">
    <img alt="" src="https://github-production-user-asset-6210df.s3.amazonaws.com/125717930/246971879-8ce757c3-90dc-438d-807f-3f3d29ddc064.png" width=500/>
  </a>  
</p>

# FaceRecognition-JavaScript

### Our facial recognition algorithm is globally top-ranked by NIST in the FRVT 1:1 leaderboards. <span><img src="https://github.com/kby-ai/.github/assets/125717930/bcf351c5-8b7a-496e-a8f9-c236eb8ad59e" alt="badge" width="36" height="20"></span>  
[🔗Latest NIST FRVT evaluation report 2024-12-20](https://pages.nist.gov/frvt/html/frvt11.html)  

![FRVT Sheet](https://github.com/user-attachments/assets/16b4cee2-3a91-453f-94e0-9e81262393d7)

## 🔗 Quick Links

- 🆔 **ID Document Liveness Detection (Linux):** [Try Here](https://web.kby-ai.com)   <span><img src="https://github.com/kby-ai/.github/assets/125717930/bcf351c5-8b7a-496e-a8f9-c236eb8ad59e" alt="badge" width="36" height="20"></span>
- 🤗 **Hugging Face:** [Visit Here](https://huggingface.co/kby-ai)  
- 📚 **Products & Resources:** [Browse Here](https://github.com/kby-ai/Product)  
- 🛟 **Help Center:** [Read Here](https://docs.kby-ai.com)  
- 💼 **KYC Verification Demo (Android):** [Check It Out](https://github.com/kby-ai/KYC-Verification-Demo-Android)  
- 🙋‍♀️ **Docker Hub:** [Explore Here](https://hub.docker.com/u/kbyai)  

## Overview

This repository demonstrates both `face recognition` technology developed by `KBY-AI` in JavaScript languages.

> In this repository, we implemented our face recognition model through `ONNX Runtime` framework to run it on web browser.</br>

## 📱 Try the App

### Available on Google Play:

<a href="https://play.google.com/store/apps/details?id=com.kbyai.facerecognition" target="_blank">
  <img alt="Download on Google Play" src="https://user-images.githubusercontent.com/125717930/230804673-17c99e7d-6a21-4a64-8b9e-a465142da148.png" height="80"/>
</a>

## 🎥 Performance Demo

Watch a live performance demo of our app on YouTube:  
You can visit our YouTube video [here](https://www.youtube.com/watch?v=HpDggnWsG1c) to see how well our demo app works.</br></br>
[![Face Recognition Android](https://img.youtube.com/vi/HpDggnWsG1c/0.jpg)](https://www.youtube.com/watch?v=HpDggnWsG1c)

## 🧰 How To Run
- Install `npm` and `node` package and then check the version with the following commands.
```bash
npm --version
node --version
```
- Install dependencies
```bash
npm install
```
- Build project
```bash
npm run build
```
- Run project
```bash
npm run test
```
## APIs
#### Load face detection model
```javascript
loadDetectionModel()
```
#### Detect face against the image
```javascript
detectFace(session, canvas_id)
```
#### Load face landmark extraction model
```javascript
loadLandmarkModel()
```
#### Extract face landmark in the image using detection result
```javascript
predictLandmark(session, canvas_id, bbox)
```
#### Load face liveness detection model
```javascript
loadLivenessModel()
```
#### Detect face liveness in the image using detection result. (Anti-spoofing)
```javascript
predictLiveness(session, canvas_id, bbox)
```
#### Load face expression model
```javascript
loadExpressionModel()
```
#### Detect face expression
```javascript
predictExpression(session, canvas_id, bbox)
```
#### Load face pose estimation model
```javascript
loadPoseModel()
```
#### Predict facial pose
```javascript
predictPose(session, canvas_id, bbox, question)
```
#### Load eye closeness model
```javascript
loadEyeModel()
```
#### Predict eye closeness
```javascript
predictEye(session, canvas_id, landmark)
```
#### Load gender detection model
```javascript
loadGenderModel()
```
#### Predict gender using face image
```javascript
predictGender(session, canvas_id, landmark)
```
#### Load age detection model
```javascript
loadAgeModel()
```
#### Predict age using face image
```javascript
predictAge(session, canvas_id, landmark)
```
#### Load face recognition model
```javascript
loadFeatureModel()
```
#### Extract face feature vector in 512 dimension
```javascript
extractFeature(session, canvas_id, landmarks)
```

## 📞 Support

- 🧙 **Email:** contact@kby-ai.com  
- 🧙 **Telegram:** [@kbyai](https://t.me/kbyai)  
- 🧙 **WhatsApp:** [+1 909-280-2609](https://wa.me/+19092802609)  
- 🧙 **Discord:** [KBY-AI Community](https://discord.gg/CgHtWQ3k9T)  
- 🧙 **Microsoft Teams:** [Join Here](https://teams.live.com/l/invite/FBAYGB1-IlXkuQM3AY)

