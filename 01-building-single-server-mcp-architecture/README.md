Advanced Model Context Protocol: Single Server MCP Architecture
This project implements a Model Context Protocol (MCP) using a Python client-server architecture. The server provides weather and AI model data via APIs, and the client fetches this data. The project demonstrates secure environment variable management and modular Python application structure, with support for OpenWeatherMap and Google Gemini APIs
🚀 Quick Start
1. Clone the Repository
git clone https://github.com/pritamnikam/advanced-model-context-protocol.git
cd 01-building-single-server-mcp-architecture
2. Create a Python Virtual Environment
python -m venv venv
3. Activate the Virtual Environment
On Windows (Command Prompt):
venv\Scripts\activate
On Windows (PowerShell):
.\venv\Scripts\Activate.ps1
On macOS/Linux:
source venv/bin/activate
Note:
If you get a script execution error in PowerShell, run:
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser

4. Install Dependencies
pip install -r requirements.txt
5. Configure Environment Variables
Copy .env-example to .env and update the values:

cp .env-example .env
Edit .env and set your API keys and configuration:

OPENWEATHERMAP_API_KEY=your_openweather_api_key
OPENWEATHERMAP_API_URL=openweather_api_url

GOOGLE_GEMINI_API_KEY=your_google_gemini_api_key
MODEL_ID=name_of_model
TEMPRATURE=temprature_between_0_to_1
