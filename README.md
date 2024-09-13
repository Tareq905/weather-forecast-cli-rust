Weather Station 🌦️

Weather Station is a simple and efficient command-line interface (CLI) app built with Rust that fetches current weather information for any location. The app provides accurate weather data using online weather APIs.
Features

    Fetch current weather by city name.
    Display temperature, humidity, and weather conditions.
    Fast and lightweight CLI.
    Built using Rust for high performance.

Prerequisites

Make sure you have Rust installed. You can install it using rustup:

bash

curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

Installation

To clone and run the Weather Station app, follow these steps:

    Clone the repository:

    bash

git clone https://github.com/your-username/weather-station.git

Navigate to the project directory:

bash

cd weather-station

Build the project:

bash

cargo build --release

Run the app:

bash

cargo run -- <city_name>

Replace <city_name> with the name of the city for which you want to fetch the weather data. Example:

bash

    cargo run -- London

Usage

Once you have built the app, you can run it directly with:

bash

./target/release/weather-station <city_name>

Example:

bash

./target/release/weather-station New York

Contributing

Feel free to fork this repository, create a new branch, and submit a pull request with your improvements or bug fixes!
