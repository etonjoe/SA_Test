# 🛡️ Safeguarding Support Agent

This is a Streamlit-based AI assistant app designed for schools in Nottingham to provide instant, policy-based guidance on safeguarding concerns.

## 🧩 Features

- Upload and process a school safeguarding policy PDF
- Ask safeguarding questions or describe real-life scenarios
- AI provides structured answers aligned with policy:
  - Summary
  - Action Steps
  - Report Requirement
  - DSL Alert
- Includes demo policy for testing
- Built with LangChain + Google Gemini Pro

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/your-username/safeguarding-support-agent.git
cd safeguarding-support-agent
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the app
```bash
streamlit run app.py
```

### 4. Set Google API Key
Add your API key to `.streamlit/secrets.toml`:
```
[general]
GOOGLE_API_KEY = "your-google-api-key"
```

## 📁 Files

- `app.py`: Streamlit UI
- `safeguarding_logic.py`: RAG + agent logic
- `requirements.txt`: Dependencies
- `demo_policy.pdf`: Sample PDF for demo/testing
- `README.md`: Project documentation

## 📬 Contact

Built by [DataSpin and Research Ltd](https://www.dataspinres.co.uk) — email: info@dataspinres.co.uk
