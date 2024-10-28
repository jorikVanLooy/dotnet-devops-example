FROM mcr.microsoft.com/dotnet/core/aspnet:2.2-stretch-slim
WORKDIR /app

# Copy the published web app
COPY /aspnet-core-dotnet-core/bin/debug/ /app

# Run command
ENTRYPOINT ["dotnet", "aspnet-core-dotnet-core.dll"]
