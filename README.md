🖼️ Ubuntu Image Fetcher

Ubuntu Image Fetcher is a simple, user-friendly Python tool for downloading images from the web and saving them locally. It prompts the user for an image URL, fetches the image, and stores it in a dedicated Fetched_Images directory.

📦 Features

🛠️ Automatically creates a folder Fetched_Images if it doesn’t exist

🌐 Downloads an image from any valid URL

💾 Saves the image using its original filename (or a default if unavailable)

🧠 Mindful, minimal output and community-inspired language

🐍 Requirements

Python 3.x

requests module (can be installed via pip)

🔧 Installation

Clone or download this repository:

git clone https://github.com/your-username/ubuntu-image-fetcher.git
cd ubuntu-image-fetcher


Install dependencies:

pip install requests

🚀 Usage

Run the script directly from the terminal:

python3 image_fetcher.py


You'll be prompted to enter an image URL. The image will be downloaded and saved to the Fetched_Images folder in the current directory.

🧪 Example
Welcome to the Ubuntu Image Fetcher
A tool for mindfully collecting images from the web

Please enter the image URL: https://example.com/path/to/image.jpg
Successfully fetched: image.jpg
Image saved to Fetched_Images/image.jpg

Community enriched.

🛑 Error Handling

Handles invalid URLs or HTTP errors gracefully

Informs the user if the download fails due to connection or server issues

📁 Output

All images are stored in the Fetched_Images/ directory with their original filename when available.

📜 License

This project is open source and available under the MIT License
.

✨ Author

Built with care for mindful tech communities.
Feel free to adapt, expand, or contribute.
