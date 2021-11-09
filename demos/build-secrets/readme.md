Instructions:

- Show Dockerfile
- Run: echo TAJNE_HASLO_JAN_DOCKER > tajne.txt
- Run: docker build -t secret --progress=plain --secret id=pd,src=tajne.txt .
- Take a look at log
- Run: docker image history secret
- Run: docker run --rm secret ls /run/secrets