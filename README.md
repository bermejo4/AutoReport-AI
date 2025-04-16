# AutoReport-AI
Interactive AI-powered report generator with visualizations and export to PDF/PPTX/HTML. Built with Streamlit and OpenAI.

-----

**AutoReport-AI** is an interactive Streamlit application that automatically generates insightful reports from CSV or Excel datasets using artificial intelligence. Key features include:

- 📊 **Data summarization** using GPT-4 (OpenAI) to describe the dataset's structure, columns, statistics, and more.  
- 📈 **Automatic visualizations** for all numeric variables with histograms and boxplots.  
- 🖼️ **AI-generated image** based on the data description using DALL·E.  
- 🧠 **Python code generation** with GPT-4 to build custom visualizations.  
- 📤 **Export options**: create reports in PDF, PowerPoint, and HTML formats.  

Ideal for data analysts, data scientists, and non-technical users who need to quickly turn data into beautiful, shareable reports — without writing code manually.

-----

# 🧠 AutoReport-AI

**AutoReport-AI** is an interactive Streamlit application that automates the generation of data reports using artificial intelligence. It analyzes datasets, creates visualizations, and exports complete reports in PDF, PowerPoint, and HTML formats — all without writing code.

-----

## 🚀 Features

### 🔄 Data Handling
- Upload `.csv` or `.xlsx` datasets.
- Preview the dataset in a friendly Streamlit interface.

### 📝 AI-Powered Data Summary
- Uses **GPT-4 (OpenAI)** to generate a descriptive summary:
  - Describes each column.
  - Explains ranges, measures, and distributions.
  - Available in **English** or **Spanish**.

### 📊 Automatic Visualizations
- Creates:
  - **Histograms** and **boxplots** for all numeric columns (via Plotly).
  - Additional matplotlib plots generated dynamically by **GPT-4**.
- All plots are rendered live and saved as `.png`.

### 🎨 DALL·E Integration
- Generates a unique image that visually represents the dataset based on its description using **DALL·E**.

### 📁 Export Options
- Export the full report in:
  - **PDF**
  - **PowerPoint (.pptx)**
  - **HTML**
- Each export includes:
  - Summary, visualizations, code-generated charts, and DALL·E image.

### 🧩 Other Features
- Allows uploading of additional `.txt` files (`description.txt`, `summary.txt`) to manually provide summaries.
- **All files (uploaded data, generated images, reports, plots) are saved in the same folder where the app is executed**, making them easily accessible after the session ends.
- Supports multiple report generation workflows in the same run.

-----

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/AutoReport-AI.git
cd AutoReport-AI
```

2. Create a virtual environment and activate it (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the dependencies:
```bash
pip install -r requirements.txt
```

4. Set your OpenAI API key:
```python
# Inside the code (temporarily, or replace with environment variable):
openai.api_key = "your-openai-api-key"
```

-----

## ▶️ Running the App

```bash
streamlit run main.py
```

Then open the app in your browser (usually `http://localhost:8501`).

-----

## 📦 Requirements

Make sure you have the following Python libraries:

- `streamlit`
- `pandas`
- `plotly`
- `fpdf`
- `matplotlib`
- `openai`
- `Pillow`
- `python-pptx`
- `requests`

You can install them all via:

```bash
pip install -r requirements.txt
```

-----

## 📸 Screenshots

_Coming soon..._

-----

## 📄 License

MIT License ©bermejo4

-----

## 🤖 Powered by

- [OpenAI GPT-4](https://platform.openai.com/)
- [Streamlit](https://streamlit.io/)
- [Plotly](https://plotly.com/python/)
- [DALL·E](https://openai.com/dall-e)

-----