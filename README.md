# Calculator-Golang-Multistage-Docker

This repository showcases the utilization of a multistage Dockerfile for building and packaging a Go application. Multistage builds are employed to enhance the final Docker image size and bolster security.

## Prerequisites

To use Docker, you must have it installed on your computer. Simply visit the [Docker's official website](https://www.docker.com/get-started) to download and install it.

## Getting Started

1. Clone this repository:

   ```sh
   git clone https://github.com/robinthakur00/calculator-golang-multistage-docker.git
   cd calculator-golang-multistage-docker
   ```

2. Build the Docker image:
   ```sh
   docker build -t calculator-multistage .  
   ```

## Usage

Run the Docker container:

   ```sh
   docker run -it --rm calculator-multistage 
   ```

## Contributing

Contributions are welcome! If you find any issues or want to improve this project, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).