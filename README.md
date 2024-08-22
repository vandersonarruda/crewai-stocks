# CrewAI Stocks

This is a simple project that uses the CrewAI framework to analyze stock prices and news articles about a specific company. The goal is to create a newsletter that highlights the company's performance and future prospects.

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.10 or higher
- pip

## Installation

1. Clone the repository:

```bash
git clone https://github.com/crewai/crewai-stocks.git
```

2. Navigate to the project directory:

```bash
cd crewai-stocks
```

3. Create a virtual environment:

```bash
python3 -m venv venv
```

4. Install the required dependencies:

```bash
pip3 install -r requirements.txt
```

5. Create a `.env` file in the project directory and add your OpenAI API key:

```bash
echo "OPEN_API_KEY=your_openai_api_key" > .env
```

6. Run the project:

```bash
streamlit run crewai-stocks.py
```

## Usage

To run the project, follow these steps:

1. Open the project in your web browser.
2. Enter the company's ticker symbol in the text input field.
3. Click the "Run Research" button.
4. Review the generated newsletter.

## License

This project is licensed under the MIT License.