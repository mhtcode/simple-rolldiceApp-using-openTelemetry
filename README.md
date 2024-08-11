# RollDice Web Application

This is a simple Go-based web application that simulates the rolling of dice. The application serves HTTP requests and is instrumented with OpenTelemetry for enhanced observability, allowing you to monitor and trace the application's performance and behavior.

## Features

- **Dice Roll Simulation:** Simulate rolling a dice with customizable routes.
- **HTTP Server:** A basic HTTP server implemented in Go.
- **OpenTelemetry Integration:** The app is instrumented with OpenTelemetry to provide detailed telemetry data for monitoring.

## Getting Started

### Prerequisites

To run this application, you need:

- [Go](https://golang.org/doc/install) (version 1.16 or later)
- [OpenTelemetry Go SDK](https://pkg.go.dev/go.opentelemetry.io/otel)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/rolldice-go-app.git
   cd rolldice-go-app
   ```
