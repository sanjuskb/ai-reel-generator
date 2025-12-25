
---

## ⚙️ How It Works

1. User uploads images and enters text
2. Text is converted into speech using ElevenLabs
3. Images are stitched into a video using FFmpeg
4. AI-generated voice is added to the video
5. Final reel is saved and displayed in the gallery

---

## 🌍 Deployment

This app is deployed on **Railway** for demo and portfolio purposes.

🔗 **Live Demo:**  
👉 web-production-8e357.up.railway.app

⚠️ **Note:**  
Due to background processing and FFmpeg limitations on free hosting platforms, full reel generation is recommended to be run **locally**.

---

## 🔐 Environment Variables

This project uses environment variables for security.

| Variable | Description |
|--------|------------|
| `ELEVENLABS_API_KEY` | ElevenLabs API key |

API keys are **not included** in the repository.

---

## 📌 Limitations

- Background processing is handled via a worker loop (not ideal for serverless platforms)
- Free-tier hosting may limit long-running FFmpeg tasks
- Designed primarily as a **learning and portfolio project**

---

## 📈 Future Improvements

- Background music support
- Queue-based processing (Celery / Redis)
- Adjustable image duration
- Download option for generated reels
- User authentication

---

## 👤 Author

**Sanjay**  
B.Tech CSE Student  
Aspiring Backend / AI Engineer

---

## ⭐ If you like this project

Give it a ⭐ on GitHub — it really helps!

