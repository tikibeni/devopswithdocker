Changes made to fix the button:

backend/Dockerfile:
Commented out the following

```Dockerfile
ENV REQUEST_ORIGIN=http://localhost:5000
```

frontend/Dockerfile:
Commented out the following

```Dockerfile
ENV REACT_APP_BACKEND_URL=http://localhost:8080
```

This way nginx can handle the routing.