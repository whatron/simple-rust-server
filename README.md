# simple-rust-server

A simple HTTP/1.1 server written completely in Rust.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)

## Features

- HTTP/1.1 server implementation in Rust.
- Utilizes only standard Rust libraries.
- Reads and parses essential components of incoming requests
- Returns HTML content in response.

## Getting Started

### Prerequisites

- [Rust](https://www.rust-lang.org/tools/install)
- [Cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-http-server.git

2. Navigate to the project directory:

   ```bash
   cd server

3. Build and run the project:
   ```bash
   cargo build
   cargo run

By default, the server will listen on http://127.0.0.1:8080. You can customize the configuration by modifying the appropriate settings in the code or using command-line arguments.

Visit http://127.0.0.1:8080 in your browser or use a tool like curl to interact with the server.
