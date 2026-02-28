
<h1>🌾 AgroPredict AI</h1>

<p>
<strong>AgroPredict AI</strong> is a machine learning-powered system that predicts crop yields using
environmental and agricultural factors such as rainfall, temperature, pesticide usage,
crop type, and cultivated area. It helps farmers and agronomists make data-driven decisions
to improve agricultural productivity.
</p>

<div class="section">
    <span class="badge">Python</span>
    <span class="badge">Machine Learning</span>
    <span class="badge">Streamlit</span>
    <span class="badge">Regression</span>
</div>

<hr>

<div class="section">
<h2>🚀 Features</h2>
<ul>
    <li>Predicts crop yield using multiple regression models</li>
    <li>Interactive Streamlit-based web interface</li>
    <li>Handles numerical and categorical features with preprocessing pipelines</li>
    <li>Model comparison using MAE and R² score</li>
    <li>Reusable ML pipeline with model persistence</li>
</ul>
</div>

<hr>

<div class="section">
<h2>🧠 Workflow</h2>

<pre>
Agricultural Dataset
        │
        ▼
Data Preprocessing
(Scaling & Encoding)
        │
        ▼
Train Regression Models
        │
        ▼
Best Model Selection
        │
        ▼
Streamlit Web App Prediction
</pre>

</div>

<hr>

<div class="section">
<h2>📁 Project Structure</h2>

<pre>
agropredict-ai/
│
├── data/
├── app.py               # Streamlit app
├── model.pkl            # Trained ML model
├── pipeline.pkl         # Preprocessing pipeline
├── train_model.py
├── requirements.txt
└── README.html
</pre>

</div>

<hr>

<div class="section">
<h2>⚙️ Installation</h2>

<h3>1️⃣ Clone Repository</h3>
<pre>
git clone https://github.com/your-username/agropredict-ai.git
cd agropredict-ai
</pre>

<h3>2️⃣ Install Dependencies</h3>
<pre>
pip install -r requirements.txt
</pre>

</div>

<hr>

<div class="section">
<h2>▶️ Usage</h2>

<pre>
streamlit run app.py
</pre>

<p>
The web app allows users to input:</p>
<ul>
    <li>Year</li>
    <li>Rainfall</li>
    <li>Temperature</li>
    <li>Pesticide Usage</li>
    <li>Area</li>
    <li>Crop Type</li>
</ul>

<p>and generates a predicted crop yield.</p>

</div>

<hr>

<div class="section">
<h2>🛠 Technology Stack</h2>
<ul>
    <li>Python</li>
    <li>Pandas</li>
    <li>NumPy</li>
    <li>Scikit-learn</li>
    <li>Streamlit</li>
    <li>Pickle</li>
</ul>
</div>



<div class="section">
<h2>📜 License</h2>
<p>
This project is licensed under the MIT License.
</p>
</div>

<hr>

<div class="section">
<h2>🌱 Future Enhancements</h2>
<ul>
    <li>Add deep learning models for yield prediction</li>
    <li>Integrate live weather APIs</li>
    <li>Support more crop types</li>
    <li>Deploy using Docker</li>
    <li>Add historical trend visualizations</li>
</ul>
</div>

</body>
</html>
