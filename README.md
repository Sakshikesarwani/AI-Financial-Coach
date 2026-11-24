💰 AI Financial Coach

An AI-powered personal finance assistant that analyzes income, expenses, savings goals, and debts to provide personalized financial insights and actionable recommendations.

<p align="center">
  <a href="https://ai-financial-coach-cgnu2tvbd9zbjoswep7enn.streamlit.app/">
    <strong>🚀 Live Demo</strong>
  </a>
</p>

## Features

### 🤖 Multi-Agent Financial Analysis

- **Budget Analysis Agent:** Analyzes spending patterns and recommends budget optimizations.
- **Savings Strategy Agent:** Creates personalized savings plans and emergency fund strategies.
- **Debt Reduction Agent:** Suggests optimized debt repayment strategies using Avalanche and Snowball methods.

### 📊 Expense Analysis

- Upload expenses through CSV files.
- Track transactions by date, category, and amount.
- Visualize spending patterns through interactive charts.
- Analyze expenses and identify spending trends.

### 💰 Savings Recommendations

- Emergency fund planning.
- Personalized savings strategies.
- Goal-based savings recommendations.
- Practical suggestions for consistent saving.

### 💳 Debt Management

- Analyze multiple debts and interest rates.
- Compare Avalanche and Snowball repayment methods.
- Generate debt repayment strategies.
- Visualize debt reduction progress.

### 📈 Interactive Visualizations

- Expense breakdown charts.
- Income vs. expenses analysis.
- Debt comparison graphs.
- Financial insights and metrics.

## Tech Stack

- Python
- Google ADK
- Google Gemini API
- Streamlit
- Pandas
- Plotly

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Sakshikesarwani/AI-Financial-Coach.git
cd AI-Financial-Coach
```

### 2. Create a Virtual Environment

```bash
py -3.12 -m venv venv
.\venv\Scripts\Activate.ps1
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure API Key

Get your Gemini API key from [Google AI Studio](https://aistudio.google.com/apikey).

Create a `.env` file in the project root:

```env
GOOGLE_API_KEY=your_api_key_here
```

### 5. Run the Application

```bash
streamlit run ai_financial_coach_agent.py
```

Open `http://localhost:8501` in your browser.

## CSV File Format

The application accepts CSV files containing these columns:

| Column | Description |
|---|---|
| Date | Transaction date (YYYY-MM-DD) |
| Category | Expense category |
| Amount | Transaction amount |

Example:

```csv
Date,Category,Amount
2024-01-01,Housing,1200.00
2024-01-02,Food,150.50
2024-01-03,Transportation,45.00
```

A sample CSV template is available in the application sidebar.

## Disclaimer

This application provides informational financial insights and recommendations. It is not a substitute for professional financial advice.

