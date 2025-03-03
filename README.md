# Metatrader Terminals

Tools and Scripts for packaging metatrader into a docker image.

## Installation

To install the necessary dependencies, run:
```bash
docker build -t metatrader5-terminal ./MetaTrader5
```

## Usage

To start the Metatrader terminal, use:
```bash
docker run -d --name metatrader5-terminal metatrader5-terminal
```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.
