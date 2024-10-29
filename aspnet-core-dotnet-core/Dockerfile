FROM mcr.microsoft.com/dotnet/core/aspnet:2.2-stretch-slim
WORKDIR /app

# Copy the published web app
COPY /aspnet-core-dotnet-core/bin/Debug/netcoreapp2.2/publish/ /app

RUN ls -la

# Run command
ENTRYPOINT ["dotnet", "aspnet-core-dotnet-core.dll"]
