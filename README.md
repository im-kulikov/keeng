## KeenG

**KeenG** is a powerful service developed in Go for managing Keenetic router interfaces via a web interface. It allows you to easily enable and disable WiFi interfaces and retrieve the current status of interfaces, providing simplicity and convenience in managing your network infrastructure.

### Key Features:

- **Web Interface**: User-friendly interface for managing Keenetic WiFi interfaces.
- **Interface Management**: Ability to enable and disable selected interfaces.
- **Interface Status**: Retrieve the current status of each interface.
- **Home Assistant Integration**: Easy integration with Home Assistant for seamless home automation management.

### Installation

    ```bash
    go install github.com/im-kulikov/keeng/cmd/keeng
    ```

### Usage

After starting the service, you can access the web interface through your browser at `http://localhost:8080` (or the port you specified).

### Home Assistant Integration

For integration with Home Assistant, use the provided configuration files and follow the instructions in the [Home Assistant documentation](https://www.home-assistant.io/).

### Contributing

Contributions to the project are welcome! Please refer to [CONTRIBUTING.md](CONTRIBUTING.md) for information on how to contribute.

### License

This project is licensed under the [MIT License](LICENSE).
