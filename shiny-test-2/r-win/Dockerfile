# Build based on Windows 

#FROM mcr.microsoft.com/windows/servercore:ltsc2019-amd64
FROM mcr.microsoft.com/windows/servercore:ltsc2019

RUN mkdir /shiny-app

COPY r-scripts/*.R /shiny-app

WORKDIR /shiny-app

CMD ["cmd", "cd"]

CMD ["cmd", "dir"]
