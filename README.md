# Paul Desmond

MS in Artificial Intelligence (Maryville University, 2025). I spent ten years teaching across China, Guatemala, and Kenya, and I now build data and machine learning projects. I am looking for Data Analyst, Data Engineer, or AI/ML Engineer work, remote or in the NYC area, with a preference for EdTech.

The teaching background is the part most data candidates do not have. A decade in classrooms means I have worked for years with the academic, behavioral, and attendance data that education products run on, and I can explain a model to people who do not build them.

## Featured projects

### IEEE-CIS Fraud Detection
github.com/SamOryeJack/IEEE-Fraud-Detection
LightGBM classifier on 590,000 transactions across 432 features. Reached 0.93 private AUC on the Kaggle leaderboard after roughly 25 iterations using Hyperopt tuning and SHAP feature analysis. Maryville capstone, team project.

### High School Analytics Application
github.com/SamOryeJack/Education-Data
DuckDB star schema with 17 tables and 318,532 rows covering 636 students across four academic years. Streamlit and Plotly dashboard built on the ESSA five-indicator framework, with FERPA small-cell suppression on any group under 10.

### Twitter Sentiment Analysis (Four-Model Comparison)
github.com/SamOryeJack/Twitter-Sentiment-RNN
Four models on the 1.6M-tweet Sentiment140 set under one shared cleaning step and one stratified split: GRU and LSTM both reached 0.8252 test accuracy, TF-IDF plus logistic regression 0.8059, Word2Vec plus logistic regression 0.7738. The ranking flipped with scale. On a 160k sample the classical TF-IDF baseline won and the RNNs were data-starved, but at the full 1.6M the RNNs overtook it, a clean demonstration that deep models need data to earn their complexity. Live Gradio demo runs the GRU.

### Indoor Scene Classifier
github.com/SamOryeJack/indoor-scene-cnn
EfficientNetB0 transfer-learning model that sorts photos into 67 indoor-scene categories, with Grad-CAM heatmaps showing where the network looks. 79.92% top-1 and 96.51% top-5 on a random 80/20 split of the 15,620-image MIT Indoor Scenes dataset (a random split, not the official Indoor-67 benchmark split). Live Gradio demo on Hugging Face Spaces.

### GPU Infrastructure Monitoring Stack
github.com/SamOryeJack/docker-monitoring-stack
Fourteen-container Docker Compose stack on GCP tracking 1,145 metrics through Prometheus, Grafana, cAdvisor, and the NVIDIA DCGM exporter. Query times under 40ms at roughly $5 total cloud cost.

## Tech stack

Languages and querying: Python, SQL, Bash
Machine learning and data: LightGBM, scikit-learn, TensorFlow, Keras, pandas, NumPy
Data engineering and analytics: DuckDB, Streamlit, Plotly, ETL pipelines
Cloud and containers: Docker, Docker Compose, GCP, AWS, Terraform, Prometheus, Grafana

## Contact

LinkedIn: linkedin.com/in/paul-desmond-155495219
Email: paul.desmond@outlook.com
Location: NYC area, open to remote
