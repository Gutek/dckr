Instructions:

- Run: docker run --rm -it $(docker build -q -f CmdDockerfile .)
- Run: docker run --rm -it $(docker build -q -f CmdDockerfile .) hostname
- Run: docker run --rm -it $(docker build -q -f EntrypointDockerfile .)
- Run: docker run --rm -it --entrypoint hostname $(docker build -q -f EntrypointDockerfile .)