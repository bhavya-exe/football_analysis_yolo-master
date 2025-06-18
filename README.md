Football Analysis App ⚽

A computer vision-based system to analyze football match videos using YOLO object detection and OpenCV.

💡 Features

Detect players, ball, and movement using YOLOv5

Track players using centroid tracking

Generate player heatmaps

Summarize match stats (shots, passes, fouls)

Streamlit UI for user interaction

⚡ Tech Stack

Python

YOLOv5 (via Ultralytics)

OpenCV

Streamlit

NumPy, Matplotlib

🔧 Setup

pip install -r requirements.txt
streamlit run app.py

🎨 Outputs

Annotated match video

Heatmap of player positions

JSON stats (ball possession, shots, fouls)

🌐 Demo

Upload a match video and view the analysis live via Streamlit dashboard.

✨ Future Improvements

DeepSORT/ByteTrack integration

Export CSV reports

Real-time match analytics
