# Chat with DeepSeek-VL2-Small 🌍

A simple interface to chat with the **DeepSeek-VL2-Tiny** model using **Gradio**.

## 🚀 Configuration

```yaml
title: Chat with DeepSeek-VL2-Small
emoji: 🌍
colorFrom: blue
colorTo: red
sdk: gradio
sdk_version: 4.21.0
app_file: app.py
pinned: false
license: mit
Check out the Hugging Face Spaces configuration reference for more details.

📌 Setup & Usage
1️⃣ Run app.py
Before using the model, you must first run app.py to download the DeepSeek-VL2-Tiny model from Hugging Face.

2️⃣ Choose Your Environment
Run the application on the web using Gradio.
Alternatively, use the Jupyter Notebook: Documentation.ipynb for a notebook-based approach.
3️⃣ Adjust the Local Model Path
If running the model locally, ensure that LOCAL_MODEL_PATH in Documentation.ipynb points to your Hugging Face cache directory.

Example:

python
Copy
Edit
LOCAL_MODEL_PATH = r"C:\Users\LENOVO\.cache\huggingface\hub\models--deepseek-ai--deepseek-vl2-tiny\snapshots\66c54660eae7e90c9ba259bfdf92d07d6e3ce8aa"
4️⃣ Python Compatibility
⚠️ This project may not work on Python versions above 3.10.
✅ Recommended: Use Python 3.8 - 3.10 for best compatibility.
