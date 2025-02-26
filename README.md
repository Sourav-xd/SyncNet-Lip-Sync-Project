# SyncNet-Lip-Sync-Project
This repository contains the implementation of SyncNet for Lip-Syncing a given video with an input audio file. It extracts frames from a video, processes them using SyncNet, and generates a lip-synced output video. 
'''
📌 Features:
✅ Frame Extraction – Extracts frames from the input video.
✅ Audio Preprocessing – Converts audio to 16kHz mono for SyncNet.
✅ Lip-Sync Processing – Uses syncnet_v2.model to sync video with audio.
✅ Final Video Generation – Merges processed frames with audio using FFmpeg.

📁 SyncNet-LipSync-Project/
 ├── data/                  # Contains model files (syncnet_v2.model)
 ├── output/                # Stores generated lip-synced video
 ├── syncnet_python/        # Main SyncNet scripts
 ├── input_video.mp4        # Input video file
 ├── input_audio.wav        # Input audio file
 ├── run_syncnet.py         # Main script to run SyncNet
 ├── README.md              # Project description
 ├── requirements.txt       # Dependencies (if needed)
 '''
 
