FROM microsoft/dotnet:2.1-aspnetcore-runtime-bionic
COPY . /app
WORKDIR /app
ENTRYPOINT ["dotnet", "TranslateWorker.dll"]