<p align="center">
  <a href="https://play.google.com/store/apps/dev?id=7086930298279250852" target="_blank">
    <img alt="" src="https://github-production-user-asset-6210df.s3.amazonaws.com/125717930/246971879-8ce757c3-90dc-438d-807f-3f3d29ddc064.png" width=500/>
  </a>  
</p>

# FaceRecognition-JavaScript

### Our facial recognition algorithm is ranked among the top globally by NIST in the FRVT 1:1 leaderboard. <span><img src="https://github.com/kby-ai/.github/assets/125717930/bcf351c5-8b7a-496e-a8f9-c236eb8ad59e" alt="badge" width="36" height="20"></span>  
🔗 [Latest NIST FRVT Evaluation Report (2024-12-20)](https://pages.nist.gov/frvt/html/frvt11.html)  

![FRVT Leaderboard Sheet](https://github.com/user-attachments/assets/16b4cee2-3a91-453f-94e0-9e81262393d7)

## 🔗 Quick Links

- 🆔 **ID Document Liveness Detection (Linux):** [Try Here](https://web.kby-ai.com)   <span><img src="https://github.com/kby-ai/.github/assets/125717930/bcf351c5-8b7a-496e-a8f9-c236eb8ad59e" alt="badge" width="36" height="20"></span>
- 🤗 **Hugging Face:** [Visit Here](https://huggingface.co/kby-ai)  
- 📚 **Products & Resources:** [Browse Here](https://github.com/kby-ai/Product)  
- 🛟 **Help Center:** [Read Here](https://docs.kby-ai.com)  
- 💼 **KYC Verification Demo (Android):** [Check It Out](https://github.com/kby-ai/KYC-Verification-Demo-Android)  
- 🙋‍♀️ **Docker Hub:** [Explore Here](https://hub.docker.com/u/kbyai)  

## 🧠 Overview

This repository demonstrates advanced **face recognition** technology by **KBY-AI** using JavaScript.

> The models run on web browsers through the `ONNX Runtime` framework, enabling real-time inference on the client side.

## 📱 Try the App

### Available on Google Play:

<a href="https://play.google.com/store/apps/details?id=com.kbyai.facerecognition" target="_blank">
  <img alt="Download on Google Play" src="https://user-images.githubusercontent.com/125717930/230804673-17c99e7d-6a21-4a64-8b9e-a465142da148.png" height="80"/>
</a>

## 🎥 Performance Demo

Watch a live performance demo of our app on YouTube:  
You can visit our YouTube video [here](https://www.youtube.com/watch?v=HpDggnWsG1c) to see how well our demo app works.</br></br>
[![Face Recognition Android](https://img.youtube.com/vi/HpDggnWsG1c/0.jpg)](https://www.youtube.com/watch?v=HpDggnWsG1c)

## 🧰 How to Run

1. Verify installation:
   ```bash
   npm --version
   node --version
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Build the project:
   ```bash
   npm run build
   ```

4. Run tests:
   ```bash
   npm run test
   ```


## 🧪 API Reference

```javascript
loadDetectionModel()
detectFace(session, canvas_id)

loadLandmarkModel()
predictLandmark(session, canvas_id, bbox)

loadLivenessModel()
predictLiveness(session, canvas_id, bbox)

loadExpressionModel()
predictExpression(session, canvas_id, bbox)

loadPoseModel()
predictPose(session, canvas_id, bbox, question)

loadEyeModel()
predictEye(session, canvas_id, landmark)

loadGenderModel()
predictGender(session, canvas_id, landmark)

loadAgeModel()
predictAge(session, canvas_id, landmark)

loadFeatureModel()
extractFeature(session, canvas_id, landmarks)
```

## 📞 Support

- 🧙 **Email:** contact@kby-ai.com  
- 🧙 **Telegram:** [@kbyaisupport](https://t.me/kbyaisupport)
- 🧙 **WhatsApp:** [+1 909-280-2609](https://wa.me/+19092802609)  
- 🧙 **Discord:** [KBY-AI Community](https://discord.gg/vBUMRJJe)  
- 🧙 **Microsoft Teams:** [Join Here](https://teams.live.com/l/invite/FBAYGB1-IlXkuQM3AY)
