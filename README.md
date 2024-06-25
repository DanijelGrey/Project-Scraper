# Project Scraper

Project Scraper is a Chrome Extension which creates an offline website that can be viewed on any modern browser without requiring the browser extension or any specialized app to read the file.

## Why Grey-Box Created Project Scraper

The idea of this project arose from the need of NGOs and their communities to be able to easily add custom type of content that is not currently available for offline use. The project must not be a technically complicated solution, hence the use of browser extensions.

This Chrome extension will create an offline website that can be viewed on any modern browser without requiring the browser extension or any specialized app to read the file. It is also important to ensure that the offline site is compatible with UNI, without requiring to user to own the device.

## Table of Contents

1. [Installation](#installation)
    * [Step-By-Step Installation Guide](#step-by-step-installation-guide)
    * [Troubleshooting](#troubleshooting)
2. [Usage](#usage)
    * [Steps to Use the Extension](#steps-to-use-the-extension)
    * [Notes](#notes)
3. [External Libraries](#external-libraries)
4. [Licenses](#licenses)
    * [Project Scraper's License](#project-scrapers-license)
    * [Licenses Project Scraper Uses](#licenses-project-scraper-uses)

## Installation

### Step-by-Step Installation Guide
1. Download the Extension Source Code:
    * Clone the repository or download the ZIP file from the GitHub repository.
    * If you downloaded the ZIP file, extract it to a folder on your computer. This step is important because if you open the html while compressed the site will display incorrectly.
2. Open Chrome Extensions Page:
    * Open Google Chrome.
    * In the address bar, type chrome://extensions/ and press Enter.
    * Alternatively, you can click on the three vertical dots in the top-right corner of Chrome, go to "Extensions," and then select "Manage Extensions."
3. Enable Developer Mode:
    * In the top-right corner of the Extensions page, toggle the "Developer mode" switch to the "On" position. This will enable additional options for managing extensions.
4. Load Unpacked Extension:
    * Click on the "Load unpacked" button that appears after enabling Developer mode.
    * A file dialog will open. Navigate to the folder where you extracted or cloned the extension source code.
    * Select the folder and click "Select Folder" (or "Open" on some systems).
5. Verify Installation:
    * The extension should now appear in the list of installed extensions.
    * Ensure that the extension is enabled by checking the toggle switch next to it.
6. Pin the Extension (Optional):
    * Click on the puzzle piece icon in the top-right corner of Chrome to open the extensions menu.
    * Find the "Project Scraper" extension which looks like a box and click the pin icon next to it. This will pin the extension to the Chrome toolbar for easy access.

### Troubleshooting:
* Extension Not Loading: Ensure that you selected the correct folder containing the manifest.json file.
* Permissions Issue: Make sure you grant the necessary permissions when prompted by Chrome.
* Developer Mode Warning: Chrome may display a warning about Developer mode being enabled. This is normal and can be ignored.
* Errors: Chrome extensions may need debuging to diagnose problems or report errors to us. More information about debuging and error checking if you are a developer can be found on [Debug Extensions](https://developer.chrome.com/docs/extensions/get-started/tutorial/debug).

### Updating the Extension:
1. Pull Latest Changes:
    * If you cloned the repository, navigate to the extension folder in your terminal and run git pull to fetch the latest changes.
    * If you downloaded the ZIP file, repeat the download and extraction process with the latest version.
2. Reload the Extension:
    * Go to the chrome://extensions/ page. Alternatively, you can click on the three vertical dots in the top-right corner of Chrome, go to "Extensions," and then select "Manage Extensions."
    * Click the "Reload" button (circular arrow icon) next to the "Project Scraper" extension.

By following these steps, you should have the "Project Scraper" Chrome Extension installed and ready to use.

## Usage

### Steps to Use the Extension:
1. Install the Extension:
    * Follow the installation instructions provided in the Installation section.
2. Open the Extension:
    * Click on the extension icon in the Chrome toolbar to open the popup window.
3. Set the Starting URL:
The extension will automatically detect the URL of the current active tab. Ensure that this is the URL you want to start scraping from.
4. Configure Advanced Options:
    * Click on the "Advanced Options" button to expand the options.
    * Exclude Images: Check this box if you do not want to download images from the website. (Still in Development)
    * Focus Mode: Check this box if you want to scrape only text-based content. (Still in Development)
Restrict Domain: Check this box if you want to restrict the scraping to the current domain. (Still in Development)
    * Download Multiple URLs: Check this box if you would like to download multiple URLs. (Still in Development)
    * Depth: Set the depth for following links and downloading subpages. Enter a number to specify how many levels deep the scraper should go. (Still in Development)
5. Start the Scraping Process:
    * Click the "Click to Download" button to initiate the scraping process.
    * A progress bar will appear, showing the current progress of the scraping process. 
6. Download the Offline Website:
    * Once the scraping process is complete, the extension will generate a ZIP file containing the offline website. You will need to extract 
    * The download will start automatically, and you will be prompted to save the ZIP file.
7. View the Offline Website:
    * Extract the contents of the ZIP file to a folder on your computer.
    * Open the index.html file in any modern browser to view the offline website.

### Notes:
* Ensure that pop-ups are allowed for the website you are scraping. 
* Please wait for the current download to finish before starting a new one. 
* Don't click outside the popup window or the progress will halt. (This is an issue we are looking to fix.)

## External Libraries
* Bootstrap
* JQuery
* JSZip

## Licenses

### Project Scraper's License

Unless otherwise stated, Project Scraper is dual licensed under [GPLv3 License](GPLv3_LICENSE) or [MIT License](MIT_License). This means that you may use either the [GPLv3 License](GPLv3_LICENSE) or [MIT License](MIT_License) when using Project Scraper's source code for your project.

### Licenses Project Scraper Uses
This project uses the following open-source libraries:

#### jQuery
- **License**: MIT License
- **Source**: [jQuery License](https://jquery.org/license/)

#### Bootstrap
- **License**: MIT License
- **Source**: [Bootstrap License](https://getbootstrap.com/docs/5.0/about/license/)

#### JSZip
- **License**: Dual licensed under the MIT License or GPLv3
- **Source**: [JSZip Website](https://stuk.github.io/jszip/)
- **Source**: [JSZip Github License](https://github.com/Stuk/jszip/blob/main/LICENSE.markdown)

Please refer to the respective licenses for more details.