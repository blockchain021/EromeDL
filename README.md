# EromeDL

EromeDL is a Tampermonkey script that allows you to download videos from Erome, bypassing download restrictions. It is inspired by the famous YouTube-DL but specifically adapted for Erome.

## Features

- Download videos from Erome that are not available for direct download.
- Open video in a new tab with proper formatting for viewing.
- Fully compatible with Tampermonkey.

## Installation Instructions

Follow these steps to install the script:

1. **Install Tampermonkey**:
   - If you don't have Tampermonkey installed, add it to your browser from the official [Tampermonkey website](https://www.tampermonkey.net/).

2. **Install the Script**:
   - Click the link below to go directly to the GreasyFork page where you can install the script:
   
   [Install EromeDL Script on GreasyFork](https://greasyfork.org/pt-BR/scripts/522155-eromedl)

   - Once you're on the GreasyFork page, click the **Install this script** button.
   - Tampermonkey will prompt you to install the script. Click **Install**.

3. **Using the Script**:
   - Go to the [Erome website](https://www.erome.com/) and open the video you want to download.
   - The script will automatically add a download button below the video.
   - Click the download button to open the video in a new tab, ready to be downloaded.

   <div style="display: flex; justify-content: space-between;">
      <img src="https://github.com/user-attachments/assets/5218e246-6cd5-41c5-be92-0216b47c5d2b" width="45%" />
      <img src="https://github.com/user-attachments/assets/5de302ff-4d12-4cb9-8990-a5706766bf76" width ="45%" />
   </div>
   
   <div style="display: flex; justify-content: space-between;">
      <img src="https://github.com/user-attachments/assets/da15e4fd-b056-4084-b467-565e9b82e22f" width="45%" />
      <img src="https://github.com/user-attachments/assets/b65577ea-8cab-4ab8-9764-839fbbc546ca" width="45%" />
   </div>


## License

**This script is licensed under the MIT License. You are free to use, modify, and redistribute this code, provided that you retain credit to the original author and include the full license text in any copies or substantial portions of the software.**

## Legal Disclaimer

- The use of this script **must comply** with the content policies of Erome and local copyright laws.
- The author of this script **is not responsible** for any misuse of the code.
- This script is provided **"as is"**, without any warranties, express or implied. Use at your own risk.

## Contributions

Feel free to submit pull requests if you want to contribute or improve the code.

## Changelog

### Version 1.7
- Added custom icon for Tampermonkey script.
  - The EromeDL script now displays a personalized heart-shaped icon in the Tampermonkey extension.
  - The icon is visible next to the script name in the Tampermonkey menu for better recognition.

### Version 1.6
- Fixed video download issue.
- Improved button functionality for seamless video download.
- Enhanced user experience with the new download tab.

### Version 1.5
- Added support for dynamically generated videos.
- Improved error handling for missing video URLs.
- Added advanced fallback to retrieve video URLs from `data-setup` attribute.
