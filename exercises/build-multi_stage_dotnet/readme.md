Instructions

To build execute in code folder:

dotnet publish -c Release
docker build -t webapp .
docker run --rm -it -p 5000:80 webapp

you can see Dockerfile, its not perfect one.
you can also see BisDockerfile that does build dotnet app in container

Try to improve this using multistage build.

Tip: use mcr.microsoft.com/dotnet/aspnet:5.0 for final image
Tip: remember about COPY --from=FROM_ALIAS


