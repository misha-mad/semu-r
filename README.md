# semu-r

## Svelte ❤️‍🔥 Rust = Sega Genesis Emulator

[![License](https://img.shields.io/badge/License-GPL--3.0-blue)](https://github.com/misha-mad/semu-r/blob/master/LICENSE)

**semu-r** is a web-based Sega Genesis (Mega Drive) emulator written in Rust and Svelte. This project aims to bring
classic Sega Genesis games to the web with high performance and compatibility.

## Features

- **Web-Based**: Play Sega Genesis games directly in your browser.
- **Written in Rust**: Utilizes Rust for high-performance emulation.
- **Built with Svelte**: Provides a modern and responsive user interface.

## Getting Started

To run the project locally, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your-username/semu-r.git
    cd semu-r
    ```

2. **Install dependencies**:

   Navigate to the `frontend` directory (assuming the Svelte code is there) and install npm packages:

    ```bash
    cd frontend
    npm install
    ```

3. **Build and run the project**:

   For the Rust part, you may need to build it using Cargo. Ensure Rust is installed and build the project:

    ```bash
    cargo build
    ```

   For the Svelte frontend, start the development server:

    ```bash
    npm run dev
    ```

4. **Open your browser**:

   Navigate to `http://localhost:5000` (or the port specified in your Svelte configuration) to start playing.

## Usage

- Place your Sega Genesis ROM files in the `public/roms` directory.
- Load a ROM through the web interface and start playing.

## Contributing

Contributions are welcome! Please fork the repository, make changes, and submit a pull request. Ensure that your code
adheres to the project's coding standards.

## License

This project is licensed under the GNU General Public License v3.0 (GPL-3.0). See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please reach out to [zakharovma.spb@gmail.com](mailto:zakharovma.spb@gmail.com).
