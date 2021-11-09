FROM mcr.microsoft.com/dotnet/sdk:5.0

COPY bin/Release/net5.0/publish/ App/
WORKDIR /App
# solution for binding in dotnet core
ENV ASPNETCORE_URLS=http://+:80

ENTRYPOINT ["dotnet", "code.dll"]