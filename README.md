# RollDice Web Application

This is a simple Go-based web application that simulates the rolling of dice. The application serves HTTP requests and is instrumented with OpenTelemetry for enhanced observability, allowing you to monitor and trace the application's performance and behavior.

## Features

- **Dice Roll Simulation:** Simulate rolling a dice with customizable routes.
- **HTTP Server:** A basic HTTP server implemented in Go.
- **OpenTelemetry Integration:** The app is instrumented with OpenTelemetry to provide detailed telemetry data for monitoring.

## Getting Started

### Prerequisites

To build and run this application, you need:

- [Go](https://golang.org/doc/install) (version 1.16 or later)
- [OpenTelemetry Go SDK](https://pkg.go.dev/go.opentelemetry.io/otel)
- [Docker](https://docs.docker.com/get-docker/)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/mhtcode/simple-rolldiceApp-using-openTelemetry.git
   cd simple-rolldiceApp-using-openTelemetry
   ```

2. **Build the Docker image:**

   ```bash
   docker build -t rolldice-app .
   ```

3. **Running the Docker Container:**
   ```bash
   docker run -d -p 8080:8080 --name rolldice-app rolldice-app
   ```

### Usage

Once the Docker image is built and the container is running, you can access the RollDice application's functionality through the following routes:

- **Roll a Dice:** To simulate a dice roll, navigate to:
  ```plaintext
  - http://localhost:8080/rolldice/
  - http://localhost:8080/rolldice/{player}
  ```
