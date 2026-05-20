# PlusTube

A privacy-friendly video front-end.

## Local
```
pip install -r requirements.txt
uvicorn main:app --reload
```

## Deploy on Render
Push to a Git repo, then on Render: **New → Blueprint** and point to this repo.
`render.yaml` will configure the service automatically.
