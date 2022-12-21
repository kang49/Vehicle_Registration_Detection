<h1>AI for Vehicle Detection in the Road</h1>

<p>This project uses machine learning to detect vehicles in the road from video input.</p>

![Views](https://visitor-badge.glitch.me/badge?page_id=kang49.Vehicle_Registration_Detection)

<h2>Prerequisites</h2>

<ul>
  <li>Python 3.x</li>
  <li>OpenCV</li>
  <li>NumPy</li>
</ul>

<h2>Installation</h2>

<ol>
  <li>Clone the repository:
<pre><code>git clone https://github.com/&lt;your_username&gt;/vehicle-detection.git
cd vehicle-detection
</code></pre>
  </li>
  <li>Install the required libraries:
<pre><code>pip install opencv-python numpy
</code></pre>
  </li>
</ol>

<h2>Usage</h2>

<p>To run the vehicle detection script, use the following command:</p>

<pre><code>python detect.py
</code></pre>

<p>By default, the script will use the video file <code>data_test/3e6fb758869a42c6a173e8a5af229ad1.mp4</code> as input. To use a different video file or a webcam as input, modify the <code>cap</code> variable in the script.</p>

<h2>Testing</h2>

<p>To ensure that the vehicle detection is working correctly, you can visually inspect the output of the script. The detected vehicles should be highlighted with green bounding boxes.</p>

<h2>Documentation</h2>

<p>The script uses the YOLOv4 object detection model to identify vehicles in the video frame. The model is configured with the file <code>v4/yolov4.cfg</code> and weights are loaded from <code>v4/yolov4.weights</code>. The list of class names that the model can detect is stored in <code>v4/coco.names</code>.</p>

<h2>Contribution</h2>

<p>To contribute to this project, please create a pull request with your changes. Make sure to follow the existing code style and to include tests for any new features.</p>

<h2>License</h2>

<p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>
