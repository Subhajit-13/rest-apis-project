# CONTRIBUTING

## How to run docker locally

```
 docker run -dp 5000:5000 -w /app -v "$(pwd):/app" IMAGE_NAME sh -c "flask run --host0.0.0.0"

 ```