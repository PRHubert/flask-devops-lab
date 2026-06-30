#Flask DevOps lab (Version A)
##Usage
Activate the virtual environment, install requirements, and run the app:

```bash
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

## API Routes

- `/api/health` — returns a JSON status check confirming the app is running
- `/api/config` — returns the app configuration from config.json
- `/api/report` — returns hostname, Python version, and app uptime in seconds
