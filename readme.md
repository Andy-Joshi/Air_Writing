✍️ Real-Time Air Writing (Browser-Based Hand Tracking)

A real-time air writing web app that lets users draw in the air using their index finger through their webcam.

Runs entirely in the browser. No backend. No installation.


🔥 Features

Real-time webcam hand tracking

Tracks index fingertip (Landmark 8)

Draws smooth lines on HTML canvas

Runs fully client-side

Lightweight and fast

🧠 How It Works

The browser accesses the webcam using Web APIs.

Hand landmarks are detected using MediaPipe.

Landmark 8 (index fingertip) is extracted every frame.

Normalized coordinates are mapped to pixel positions.

Lines are drawn between consecutive points on a <canvas> element.

The result: real-time air drawing using just a webcam.

🛠 Tech Stack

HTML

MediaPipe


📦 How to Run

Clone the repository:

git clone https://github.com/yourusername/repo-name.git

Open app.html in your browser.

Allow webcam access.

That’s it.

🎯 What This Project Demonstrates

Real-time computer vision in the browser

Frame-by-frame processing

State management between frames

Coordinate transformation