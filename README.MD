# AI-Bot-Agent

Automated voice testing system that places phone calls to a clinic receptionist AI, simulates patient conversations, saves transcripts, and generates bug reports using OpenAI.

## Tech Stack
- FastAPI — webhook server
- Twilio — telephony and speech processing
- OpenAI — transcript analysis and bug detection
- Railway — cloud deployment

## Setup

1. Install dependencies: `pip install -r requirements.txt`
2. Create a `.env` file with:
```
TWILIO_ACCOUNT_SID=
TWILIO_AUTH_TOKEN=
TWILIO_FROM_NUMBER=
TARGET_NUMBER=
PUBLIC_BASE_URL=
OPENAI_API_KEY=
```
3. Start the server: `uvicorn app:app --host 0.0.0.0 --port 5000`
4. Run a test call: `python twilio_test_call.py`
5. Run 10 calls: `python test_10calls.py`
6. Generate bug report: `python bug_analyzer.py`
