```markdown
# 🩺 Gemini Pro Medical Report Analyzer 📋

## Description
This project leverages the power of Google's Gemini Pro large language model to analyze medical reports, providing concise summaries, personalized dietary recommendations, and potential disease insights based on identified risk factors. The intuitive Streamlit frontend makes it easy for users to interact with the model and gain valuable health insights.

## Key Features
- **Medical Report Analysis**: Upload your medical reports (e.g., X-rays, blood tests) for Gemini Pro to analyze and present a clear summary.
- **Personalized Diet Recommendations**: Receive tailored dietary suggestions based on your medical report findings and potential health risks.
- **Disease Risk Assessment**: Gain insights into possible diseases associated with identified risk factors, empowering you to make informed lifestyle decisions.
- **Streamlit Frontend**: Enjoy a user-friendly interface for uploading reports, viewing summaries, and managing recommendations.

## Prerequisites
- Python 3.6 or later
- Streamlit
- PyTorch (for Gemini Pro inference)
- Transformers (for Gemini Pro tokenization)

## Installation
### Clone this repository:
```bash
git clone https://github.com/MayurPimpude/Doctor-Gemini
```

### Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate
```

### Install required dependencies:
```bash
pip install -r requirements.txt
```

## Usage
1. Start the Streamlit app:
```bash
streamlit run doctor.py
```

2. Access the app in your web browser (usually at http://localhost:8501).
3. Upload your medical report in a supported format (e.g., PDF, PNG, JPG).
4. Click "Submit" to process the report using Gemini Pro.
5. Review the generated report summary, dietary recommendations, and disease risk assessment.

## Output
![image](https://github.com/MayurPimpude/Doctor-Gemini/assets/100997225/c1e3fb5b-a3c9-4500-8bb5-98fc8328f808)

![image](https://github.com/MayurPimpude/Doctor-Gemini/assets/100997225/2f864bda-adc7-49c7-bcf5-192c0e03c8f6)

![image](https://github.com/MayurPimpude/Doctor-Gemini/assets/100997225/3e511726-4260-4d90-8162-19fa3e7d76cd)
