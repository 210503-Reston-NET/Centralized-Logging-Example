# Demo for setting up centralized logging


## Install [ELK stack](https://www.elastic.co/guide/en/kibana/current/docker.html) with docker
install:
 - Elasisearch
 - Kibana


## Nuget Packages:
```
dotnet add package Serilog
dotnet add package Serilog.AspNetCore
dotnet add package Serilog.Enrichers.Environment
dotnet add package Serilog.Settings.Configuration
dotnet add package Serilog.Sinks.Debug
dotnet add package serilog.sinks.elasticsearch
```


Read [this](https://www.humankode.com/asp-net-core/logging-with-elasticsearch-kibana-asp-net-core-and-docker)
for configuration instructions.
