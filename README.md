
# FairFareFinder

`FairFareFinder` is a tool designed to help travelers find the best destinations for weekend getaways, prioritizing locations with ideal weather conditions and cost-effective travel options. It combines weather forecasts, event schedules, and price comparisons (including travel and accommodation costs) to suggest the most suitable locations for a short trip.

## Features

- **Weather Forecast Integration**: Retrieves up-to-date weather information to suggest destinations with the best upcoming weather conditions.
- **Cost Comparison**: Compares travel and accommodation costs to find budget-friendly options.
- **Event Scheduling**: Identifies notable events happening at potential destinations.
- **Customizable Search Parameters**: Users can specify their preferences for travel time, budget, and type of activities.
- **Automatic Updates**: Regularly updates destination suggestions based on changing weather forecasts and prices.

## Getting Started

### Prerequisites

- Golang (version 1.x or later)
- Access to weather and accommodation APIs

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/FairFareFinder.git
   ```
2. Navigate to the project directory:
   ```sh
   cd FairFareFinder
   ```
3. Build the project (this will generate the `FairFareFinder` executable):
   ```sh
   go build
   ```

### Usage

Run the `FairFareFinder` executable with the desired command-line arguments. For example:

```sh
./FairFareFinder Berlin
```

Replace `Berlin` with your preferred starting location for finding getaway destinations.

## Configuration

- **API Keys**: Store your API keys in `ignore/secrets.yaml`. See `ignore/secrets.example.yaml` for the format.
- **Custom Settings**: Edit the configuration settings in `config.yaml` to adjust search parameters like maximum travel time and preferred weather conditions.

## Contributing

Contributions to `FairFareFinder` are welcome! Please read `CONTRIBUTING.md` for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Acknowledgments

- OpenWeatherMap API for weather data.
- Other API providers (if any).

---

Make sure to replace placeholder URLs and texts with actual information relevant to your project, and add or remove sections as necessary to match your project's features and setup.

install go
```
sudo apt install golang
```

```
go run main.go
```


## installing go packges
```
go get gopkg.in/yaml.v2
```
