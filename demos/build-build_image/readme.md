Instructions:

- Run: docker image build -t pd:latest .
- Run: docker run -d -p 5000:5000 pd
- Run: curl http://localhost:5000/
- Run: docker rm -f ID