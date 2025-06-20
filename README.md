# Psykos: Your Aesthetic Image Bot 🌌

![Psykos Logo](https://img.shields.io/badge/Psykos-Bot-orange?style=for-the-badge&logo=python)

Welcome to the **Psykos** repository! This bot fetches random images from Tumblr, analyzes their aesthetics, and posts them on Bluesky. It’s designed to enhance your social media feed with beautiful visuals, all while utilizing advanced AI tools.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [How It Works](#how-it-works)
5. [Technologies Used](#technologies-used)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)
9. [Releases](#releases)

## Features

- Fetches random images from Tumblr.
- Analyzes image aesthetics using AI models.
- Posts curated images on Bluesky.
- Open-source and community-driven.
- Supports automation for seamless operation.

## Installation

To get started with Psykos, you need to clone the repository and install the required packages. Follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/light133777/psykos.git
   cd psykos
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the bot, you will need to set up your Tumblr and Bluesky API keys. Once you have those, you can configure the bot.

1. Create a `.env` file in the root directory of the project.
2. Add your API keys:
   ```
   TUMBLR_API_KEY=your_tumblr_api_key
   BLUESKY_API_KEY=your_bluesky_api_key
   ```

3. Run the bot:
   ```bash
   python main.py
   ```

The bot will start fetching images and posting them on Bluesky.

## How It Works

Psykos operates in a few key steps:

1. **Image Fetching**: The bot uses the Tumblr API to retrieve random images based on specific tags or categories.
2. **Aesthetic Analysis**: The bot employs a CLIP model to analyze the aesthetics of each image. This ensures that only visually appealing images are selected.
3. **Posting**: After analysis, the bot posts the images on Bluesky, ensuring that your feed stays fresh and engaging.

![Image Processing Flow](https://via.placeholder.com/800x400.png?text=Image+Processing+Flow)

## Technologies Used

Psykos utilizes several powerful technologies to function effectively:

- **Python**: The primary programming language for the bot.
- **BeautifulSoup**: For web scraping and data extraction.
- **Pillow**: For image processing.
- **PyTesseract**: For text recognition in images.
- **PyTumblr**: To interact with the Tumblr API.
- **Torch and Transformers**: For AI model implementation and aesthetic analysis.
- **ATProto**: For Bluesky integration.

## Contributing

We welcome contributions from the community. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request.

Please ensure that your code adheres to the existing style and includes relevant tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For questions or suggestions, feel free to reach out:

- **Author**: [Your Name](https://github.com/yourusername)
- **Email**: your.email@example.com

## Releases

To download the latest version of Psykos, visit the [Releases section](https://github.com/light133777/psykos/releases). You will find the necessary files to download and execute.

Feel free to check the Releases section for updates and new features.

---

Psykos aims to bring a unique aesthetic experience to your social media. By combining advanced image processing and AI, we hope to make your feeds more visually appealing. Thank you for your interest in Psykos!