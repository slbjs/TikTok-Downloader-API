# 🎵 TikTok Downloader API

A free and simple TikTok video downloader API — no watermark, fast response, and full video metadata.

---

## 🌐 API Endpoint

**Base URL:**
https://tdownv4.sl-bjs.workers.dev/

**Example Request:**
https://tdownv4.sl-bjs.workers.dev/?down=https://vt.tiktok.com/ZSr7brpo4/

---

## 🧾 Example JSON Response
```json
{
  "title": "Jordan barret⚡Ill do it #looksmaxing #mewing #mogged #mogger #mogging #GlowUp #nevergiveup #pslgod #jawline #model #SuperModel #fyp #fashionweek #looksmax #jordanbarrett #barrett",
  "content_type": "video",
  "video_id": "7496184960873680150",
  "author": {
    "username": "mk.looksmaxxing",
    "nickname": "mk.looksmaxxing",
    "avatar": "https://p19-common-sign-useastred.tiktokcdn-eu.com/tos-useast2a-avt-0068-euttp/104122251944b813f14ef56d3e383bb4~tplv-tiktokx-cropcenter:300:300.jpeg",
    "duration": 60,
    "view_count": 311065,
    "like_count": 24933,
    "audio_url": "https://v16-ies-music.tiktokcdn.com/.../audio.mp3"
  },
  "download_url": "https://v16m-default.tiktokcdn.com/.../video.mp4"
}´´´

⚙️ Features

🎬 Download TikTok videos without watermark

🔊 Extract and download audio tracks

🧾 View metadata (title, likes, views, author info)

⚡ Fast and public API (Cloudflare Workers)



---

🧠 Usage

Just replace the TikTok video URL after ?down=:

https://tdownv4.sl-bjs.workers.dev/?down=YOUR_TIKTOK_URL


---

📚 Notes

No API key required

Works with both short and long TikTok links

Free to use (for educational and personal use)
