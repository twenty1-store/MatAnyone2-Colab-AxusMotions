# 🎬 MatAnyone 2 - One-Click Google Colab UI

Welcome! This repository provides an automated, one-click setup to run **MatAnyone 2** (a state-of-the-art AI video matting and background removal tool) completely free using Google Colab. 

No coding, terminal commands, or complicated folder setups required. Just click, launch, and use the interactive Web UI.

### 🚀 Quick Start

Click the button below to launch the notebook directly in your browser:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/twenty1-store/MatAnyone2-Colab-AxusMotions/blob/main/MatAnyone2_by_AxusMotions.ipynb)

---

### 📖 How to Use This Tool

1. **Launch the Notebook:** Click the "Open in Colab" badge above.
2. **Save a Copy:** Before running anything, go to `File > Save a copy in Drive` so you have your own private version.
3. **Turn on the GPU:** Go to `Runtime > Change runtime type`, select **T4 GPU**, and click Save. (This is required for the AI to process video quickly).
4. **Run the Code:** Click the "Play" button next to the code block.
5. **Open the Web UI:** Wait 2–3 minutes for the system to download the AI models and install the required tools. Once finished, a public URL (e.g., `https://xxxx.gradio.live`) will appear at the bottom of the text. Click it!
6. **Process Your Video:** Upload your video in the web interface, click on the subject you want to isolate, and let the AI do the heavy lifting.

---

### ⚠️ Important Notes & Troubleshooting

* **Temporary Links:** The Gradio Web UI link (`.gradio.live`) is temporary. It will expire if your Colab tab is closed, left idle for too long, or after 72 hours. 
* **Restarting:** If your link expires or you close the window, simply open your saved Colab notebook and hit the "Play" button again to generate a fresh link.
* **First Run:** The very first time you process a video in the UI, it may take a little longer because it has to download the MatAnyone 2 weights. Subsequent videos in the same session will be much faster.

---
*Maintained by AxusMotions.*
