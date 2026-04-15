\# HNG Stage 1 API



A simple REST API built with FastAPI and deployed on Ubuntu with Nginx.



\## Run Locally



```bash

pip install fastapi uvicorn

uvicorn main:app --reload

```



\## Endpoints



| Endpoint | Method | Response |

|---|---|---|

| / | GET | {"message": "API is running"} |

| /health | GET | {"message": "healthy"} |

| /me | GET | name, email, github |



\## Live URL



http://52.90.156.23

