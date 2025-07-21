# WildFireSim

WildFireSim is a small Blazor Server application that demonstrates how a wildfire might spread across a grid based landscape.  
The simulator lets you adjust parameters such as wind direction, wind speed, ember ignition probability and more, then visualizes the fire as it burns through forest and residential areas.

## Running the project

This project targets **.NET 8**. After installing the .NET SDK simply build and run the application:

```bash
# restore dependencies and build
dotnet build WildFireSim.sln

# run the web app
dotnet run --project WildFireSim/WildFireSim.csproj
```

Once running, open `http://localhost:5000` in your browser to try the interactive simulator.

## Features

- Adjustable probabilities for how quickly fire spreads through forest or residential areas
- Ember generation with configurable chance to ignite new fires
- Wind direction and speed which influence both fire spread and embers
- Real‑time visualization of the grid as the simulation progresses

WildFireSim is meant as a demonstration project highlighting the use of Blazor for building interactive web apps with .NET.
