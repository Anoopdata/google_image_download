# google_image_download

# 🚀 Introduction

Welcome to the Bing image scraping tool.


## 📋 Requirements

To use this software, ensure you have Python 3.8 or later and all the necessary dependencies installed. Dependencies can be installed by running the following command in your terminal:

```bash
$ pip install -r requirements.txt
```
## ⚙️ Installation

To set up the image scraper on your machine, clone this repository and install the dependencies as shown below:

```bash
$ git clone https://github.com/ultralytics/google-images-download
$ cd google-images-download
$ pip install -r requirements.txt
```

## 🖥️ How to Run

Run the image scraper following these steps:

1. Ensure Google Chrome is installed on your machine. If not, download and install from [here](https://www.google.com/chrome/).

2. Download and update chromedriver corresponding to your version of Chrome [here](https://developer.chrome.com/docs/chromedriver/).

3. Execute the script. Use the `--url` parameter to download images from a specific Bing URL or the `--search` parameter for Bing search terms. By default, the images will be saved in the `./images` directory. Note that any images that cause errors will be skipped during the download process.

Example usage to download images using a URL:

```bash
$ python3 bing_scraper.py --url 'https://www.bing.com/images/search?q=flowers' --limit 10 --download --chromedriver /path/to/your/chromedriver
```

Example usage to download images using search terms:

```bash
$ python3 bing_scraper.py --search 'honeybees on flowers' --limit 10 --download --chromedriver /path/to/your/chromedriver




## 📬 Contact

If you encounter any issues or have features you'd like to request, please visit our [GitHub Issues](https://github.com/ultralytics/google-images-download/issues) page. For general discussions, questions, or to connect with the community, join our vibrant [Discord](https://discord.com/invite/ultralytics) community.

<br>
<div align="center">
  <!-- Social media and contact icons -->
  <a href="https://github.com/ultralytics"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-github.png" width="3%" alt="Ultralytics GitHub"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="space">
  <a href="https://www.linkedin.com/company/ultralytics/"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-linkedin.png" width="3%" alt="Ultralytics LinkedIn"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="space">
  <a href="https://twitter.com/ultralytics"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-twitter.png" width="3%" alt="Ultralytics Twitter"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="space">
  <a href="https://youtube.com/ultralytics"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-youtube.png" width="3%" alt="Ultralytics YouTube"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="space">
  <a href="https://www.tiktok.com/@ultralytics"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-tiktok.png" width="3%" alt="Ultralytics TikTok"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="space">
  <a href="https://ultralytics.com/bilibili"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-bilibili.png" width="3%" alt="Ultralytics BiliBili"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="space">
  <a href="https://discord.com/invite/ultralytics"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-discord.png" width="3%" alt="Ultralytics Discord"></a>
</div>
```
