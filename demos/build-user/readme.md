Instructions:

- Run: docker run --rm alpine:latest id
- Show Dockerfile
- Run: docker build -t user .
- Uncomment user creation, and re-run build
- Run: docker run --rm $(docker build -q .) id



