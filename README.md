

🚦 AI-Based Traffic Congestion Detection

An intelligent computer vision system that analyzes traffic images using YOLO (Ultralytics) to detect vehicles and estimate traffic congestion levels in real time. The system classifies traffic density and suggests adaptive traffic light timing.

⸻

📌 Overview

This project uses a deep learning object detection model to:

* Detect vehicles from uploaded traffic images
* Count different types of vehicles (car, bus, truck, etc.)
* Estimate traffic congestion level
* Suggest adaptive traffic signal timing
* Visualize results with annotated images

⸻

🧠 Technology Stack

* Python 🐍
* OpenCV (Image Processing)
* Ultralytics YOLO (Object Detection)
* NumPy
* Matplotlib
* Google Colab (Execution Environment)

⸻

🚗 Vehicle Classes Detected

The model detects COCO dataset vehicle classes:

* Bicycle 🚲
* Car 🚗
* Motorcycle 🏍️
* Bus 🚌
* Truck 🚚

⸻

⚙️ How It Works

1. Upload a traffic image
2. YOLO model processes the image
3. Vehicles are detected and classified
4. System counts total vehicles
5. Traffic density is calculated:
    * Light Traffic → Green signal longer
    * Moderate Traffic → Balanced timing
    * Heavy Traffic → Red signal priority
6. Output image is annotated and saved

⸻

AI-Traffic-Detection/
│
├── traffic_analysis.ipynb   # Main Colab Notebook
├── yolo11l.pt               # Pretrained YOLO model
├── sample_images/           # Test images (optional)
├── outputs/                 # Processed results
└── README.md                # Project documentation

🚀 Installation & Setup

1. Clone the Repository
    git clone https://github.com/your-username/AI-Traffic-Detection.git
    cd AI-Traffic-Detection

2. Install Dependencies
   pip install ultralytics opencv-python numpy matplotlib

3. Run the Notebook
   Open in **Google Colab** or **Jupyter Notebook** and execute all cells.

   ▶️ Usage

1. Run the notebook
2. Upload a traffic image when prompted
3. Wait for YOLO detection
4. View results:
    * Annotated image
    * Vehicle count
    * Traffic status report

⸻

📊 Output Example

* Detected vehicles highlighted with bounding boxes
* Traffic congestion level displayed on image
* Saved output image: traffic_analysis_result.jpg

⸻

📈 Future Improvements

* Real-time video stream processing 🎥
* Smart traffic signal integration
* Lane-wise vehicle detection
* Emergency vehicle prioritization
* Web dashboard for monitoring

⸻

🤝 Contribution

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit changes
4. Open a Pull Request

⸻

📜 License

This project is licensed under the MIT License.

⸻

👨‍💻 Author

Developed by **Ashmit Ahlawat**
