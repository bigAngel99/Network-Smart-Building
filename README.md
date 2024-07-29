# Security Camera System

This repository implements a python security system that uses OpenCV and a basic person detection model to record and save video. It also mentions some security analysis for the camera. It features the following:
- Person detection
- Store video records on Google Cloud
- Text notifications using Twilio
- Arming & disarming the system
- Camera activity logging
- Access control via IP using Advanced IP Scanner
- Using API to interact

## Installation

Before starting make sure you have the following installed:

- Python 3.9+
- Node.js
- ffmpeg

Install the python dependencies by running: `pip install -r requirements.txt` from the root directory.

Next, `cd frontend && npm install`

## Usage
+ Running The Backend: run the `main.py` file with `cd backend && python main.py`.
+ Running The Frontend: run `npm start` from `/frontend`.

