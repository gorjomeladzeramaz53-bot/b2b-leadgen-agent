Enterprise B2B Lead-Gen & Competitor Intelligence Agent
A powerful asynchronous B2B lead generation and competitor intelligence backend service built with FastAPI, SQLAlchemy, and Groq AI.

🚀 Features
Automated Scraping & Extraction: Gathers business leads and web intelligence data.

AI-Powered Analysis: Leverages Groq AI to intelligently parse and structure company details, contacts, and insights.

Asynchronous Architecture: Built with FastAPI, SQLite (aiosqlite), and Uvicorn for high performance.

Interactive API Documentation: Ready-to-use Swagger UI (/docs).

🛠️ Tech Stack
Backend: Python 3.x, FastAPI, Uvicorn

Database: SQLite with SQLAlchemy (AsyncSession)

AI Integration: Groq API

Containerization: Docker & Docker Compose support

⚙️ Installation & Local Setup
Clone the repository:
git clone https://github.com/gogoineladz/b2b-leadgen-agent.git
cd b2b-leadgen-agent

Create and activate a virtual environment:
python -m venv venv

On Windows:
venv\Scripts\activate

Install dependencies:
pip install -r requirements.txt
pip install aiosqlite

Configure environment variables:
Create a .env file in the root directory and add your API key:
GROQ_API_KEY=your_groq_api_key_here
DATABASE_URL=sqlite+aiosqlite:///./leadgen.db

Run the application:
python -m uvicorn app.main:app --reload

Access Swagger UI:
Open your browser and navigate to: http://127.0.0.1:8000/docs
