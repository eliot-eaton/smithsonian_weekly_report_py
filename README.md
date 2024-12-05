# TSX Supersite Web Scraper

This repository contains a Python script to scrape data from the TSX Supersite, filter it based on specific parameters, and download the relevant files.

## Table of Contents

- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/tsx-supersite-webscraper.git
    cd tsx-supersite-webscraper
    ```


## Configuration

1. Create a `config.json` file in the root directory of the project with the following structure:
    ```json
    {
        "dir": "path/to/download/directory",
        "url": "https://download.geoservice.dlr.de/supersites/files/",
        "supersite": "specific_supersite",
        "orbit": "orbit_number",
        "beam_id": "beam_id",
        "start": "YYYYMMDD",
        "end": "YYYYMMDD",
        "user": "your_username",
        "password": "your_password"
    }
    ```

2. Update the `supersite_config.json` file with your specific parameters.

## Usage

1. Run the script:
    ```sh
    python supersite_tsx_tar_download.py
    ```

2. Follow the prompts to download the files.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

