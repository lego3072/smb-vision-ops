# SMB Vision Ops

Agent-ready visual ops API for job-site summaries, issue flags, and next-action recommendations across small service teams.

## Run locally
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload --port 8000
```

## Endpoints
- `/`
- `/docs-page`
- `/health`
- `/v1/public/config`
- `/llms.txt`
