# Medio - YouTube Converter

Medio is a premier software solution designed to efficiently download videos and extract audio from YouTube. Its intuitive interface allows users to enter a YouTube video URL, adjust settings such as quality and filename, and initiate the download process. Medio supports a wide range of video formats, including **MP4, MKV, AVI, FLV, WMV and MOV**, as well as audio formats like **MP3, OGG, WAV, M4A, AAC and WMA**.

With a user-centric design, the software is accessible to users of all technical levels. Unlike many other YouTube Converters, it is optimized for high-speed downloads, enabling users to obtain videos and audio quickly.

Two license types are available for purchase, offering new features such as additional formats or the Playlist Downloader. Developed with Visual Studio 2022, Medio is compatible with both `Windows` and `Linux` systems, requiring the **.NET Framework 6.0** or higher to ensure efficient performance across platforms.

## Table of Contents

1. [System Requirements](#system-requirements)
2. [License Options and Advantages](#license-options-and-advantages)
    - [Encore License Benefits](#encore-license-benefits)
    - [Premium License Benefits](#premium-license-benefits)
3. [Free Trial License Key](#free-trial-license-key)
4. [Getting Started Guide](#getting-started-guide)
    - [Step 1: Configure Settings](#step-1-configure-settings)
    - [Step 2: Download Content](#step-2-download-content)
5. [Updating Software](#updating-software)
6. [Third-Party Libraries](#third-party-libraries)
7. [Retrieving Data from Database](#retrieving-data-from-database)
8. [Copyright](#copyright)
9. [Screenshots](#screenshots)

## System Requirements

- **Operating System:** Windows 10 or higher, Ubuntu 20.04 LTS or higher
- **Processor:** Intel Core i3 or AMD Ryzen 3 or equivalent
- **RAM:** Minimum 4 GB
- **Storage:** Minimum 300 MB of free disk space for the application
- **Software:**
  - **Windows:** .NET Framework 6.0 or higher
    - [Download .NET Framework 6.0](https://dotnet.microsoft.com/download/dotnet/6.0)
  - **Linux:** .NET 6.0 SDK or runtime
    - [Download .NET 6.0 SDK](https://dotnet.microsoft.com/download/dotnet/6.0)
    - [Download .NET 6.0 Runtime](https://dotnet.microsoft.com/download/dotnet/6.0/runtime)

## License Options and Advantages

To initiate the purchase process, follow these steps:

1. Navigate to the `Premium` tab in the application's navigation menu.
2. Select the desired license option.
3. Click the button that leads to the Stripe payment page.
4. Complete the purchase using one of the available payment methods on Stripe.

Upon successful payment, the license will be sent within **5-10 minutes** to the email address associated with the Stripe account.

### Encore License Benefits

- **Full Access to Settings:** Unlocks all video and audio formats, as well as various buffer sizes.
- **Secure License Key Storage:** Links the license key to the account in Medio’s database.
- **Increased Download Bandwidth:** Provides enhanced bandwidth limits for faster download speeds. Users can further increase their download speed by adjusting the buffer size in the settings. Increasing the buffer size, which ranges from 1024 to 9216, can help optimize download speed by allowing more data to be preloaded during the download process. This is especially useful for high-speed internet connections and large files.
- **Expanded History:** Extends the history to 10 pages for more detailed tracking of download activities.

### Premium License Benefits

Includes all benefits of the Encore License, plus:

- **Further Expanded History:** Extends the history to 25 pages for more detailed tracking of download activities.
- **Unlimited Download Bandwidth:** Removes restrictions on download bandwidth, allowing for maximum speed based on your internet connection and system performance.
- **Playlist Downloader Feature:** Enables downloading entire playlists from YouTube.

## Free Trial License Key

Purchasing a lifetime license key grants unrestricted use of Medio at any location and time. Once activated, the features associated with the selected license become permanent for the Medio software. This permanence is maintained unless the software is reinstalled in a different directory path or installed on a new device. In such cases, the license key must be redeemed again to load the latest information from the database. 

For those wishing to evaluate Medio's functionality and features before purchasing, a license key can be redeemed below. Upon redemption, the next **10** downloads will be unrestricted and include access to the Playlist Downloader feature. Each device can redeem the key only once. After another redeem, the key can still be entered but won't enable temporary premium features.

**Access Medio's Complete Feature Set with this Key:**
<pre>
Free Trial License:     PT4O-5TYD-WKTV-0ZZ7
</pre>

In the unlikely event of complications during the purchase process, direct all license-related queries or refund requests to the developer.

## Getting Started Guide

Optimize your settings before starting any downloads to match your preferences. Follow these steps for a streamlined process:

### Step 1: Configure Settings

- Navigate to the **Settings** page.
- Select the desired format and adjust preferences such as buffer size to match your requirements.

### Step 2: Download Content

1. **Open the Converter:**
   - Access the `Converter` tab from the sidebar on the left.

2. **Select Download Type:**
   - Choose `Download Video` for videos or `Download Audio` for audio tracks.

3. **Input URL:**
   - Paste the YouTube URL into the designated field at the top of the Converter tab.

4. **Adjust Additional Settings:**
   - **Save Location:** Click the three dots next to the `Choose a Folder Path` field to specify the save directory. All downloaded files will be stored in this location, so it is recommended to use a separate folder for playlists to keep files organized.
   - **File Naming:** Enter a custom name for your file in the `Title your Video` field. For single videos or audios, a custom name can be selected, while for playlists, the original title will be used.
   - **Quality Selection:** Choose your preferred resolution from the provided list. This selection will be applied during the downloading process and can help to reduce the file size.

5. **Initiate Download:**
   - Click the `Start Download` button to begin. The application will display the download status in the upper right corner, showing progress and completion indicators. The `Loading Tools` status indicates that it is starting all necessary processes for downloading and converting while reading the size of the video. The time required for this step depends on the size of the video from YouTube and the internet connection but usually takes only a few seconds.

> **Note:** Medio processes valid links only. An "invalid link" status will be shown for unrecognized URLs.

For further assistance or information, please [open an issue](https://github.com/BerndHagen/Medio-YouTube-Converter/issues) on the GitHub repository or consult the FAQ section in the 'Settings' tab.

## Updating Software

To maintain optimal performance and stability when downloading audio or video content from YouTube, it is crucial to use the latest version of Medio. Updates bring enhanced features and fix bugs that could compromise the software's performance. Using an outdated version may lead to incomplete downloads or failures during content conversion. The Build Number version can be found in the bottom left corner of the application, which can be used to check if there is a newer version of Medio available on this GitHub Repository.

To update your Medio software, follow these steps:

1. Download the latest version from the repository and save it to your device.
2. Open the downloaded **ZIP** folder and start the Medio setup to initiate the installation process.
3. Follow the on-screen instructions to complete the installation, replacing any old files with the new updates.
4. Once the installation is complete, launch the application.

For optimal performance, make sure the installation path is set to `C:\Users\...\AppData\Local\Arctisoft-Studio\Medio - YouTube Converter` during setup. This prevents potential issues and ensures that features are not blocked due to a lack of administrative rights.

## Third-Party Libraries

Medio leverages several third-party libraries to enhance its functionality. One key library used in the application is **FFmpeg**, which plays a crucial role in media processing tasks.

- **FFmpeg:** FFmpeg is a powerful multimedia framework used for handling video, audio, and other multimedia files and streams. It is used by Medio for video and audio format conversion, as well as for encoding and decoding media files.

  - **Website:** [FFmpeg Official Website](https://ffmpeg.org)
  - **License:** FFmpeg is licensed under the LGPL or GPL, depending on the configuration and features enabled.

For more details about FFmpeg, including its capabilities and licensing, please refer to the [FFmpeg documentation](https://ffmpeg.org/documentation.html).

If you have any questions or issues regarding the use of FFmpeg with Medio, feel free to [open an issue](https://github.com/BerndHagen/Medio-YouTube-Converter/issues) on GitHub.

## Retrieving Data from Database

By purchasing a license key and redeeming it again in the `Settings` tab under `Key Activation`, **Medio** allows the retrieval of personal data from the database. This process includes downloading:

- **Personal Settings**
- **Avatar**
- **Experience Points**
- **Level**
- **Total Megabytes Downloaded**
- **Amount of Audios and Videos Downloaded**
- **Latest Download**

**Important:** While this process restores most of your personal data, some information such as the **Download History** is stored locally on the device and cannot be recovered from the database. Consequently, any locally stored Download History will be lost if Medio is set up on a new device!

## Copyright

This software program, **Medio**, is an intellectual creation of Bernd Hagen, the author and copyright holder, and is protected by copyright law. This comprehensive copyright notice outlines the terms and conditions governing the use, distribution, and modification of Medio:

- **License:** Medio is made available for free download and use without requiring a separate license. You are granted a limited, non-exclusive, and non-transferable right to use the software in accordance with the terms set forth herein.
- **Prohibited Modifications:** You are expressly prohibited from modifying, decompiling, disassembling, reverse engineering, or otherwise manipulating Medio in any manner. Any attempts to do so will be deemed a clear violation of this copyright.
- **Warranty Disclaimer:** Medio is provided "as is," without any warranty of any kind, whether express or implied. This includes, but is not limited to, warranties of merchantability, fitness for a particular purpose, and noninfringement. The author and copyright holder make no guarantees regarding the accuracy, reliability, or performance of the software.
- **Limitation of Liability:** In no event shall the author or copyright holder be held liable for any claims, damages, or other liabilities, whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the software or the use thereof. You expressly understand and agree that you assume all risks associated with the use of Medio.

By downloading, installing, or using Medio, it is acknowledged that the copyright notice has been read and understood, and agreement to abide by its terms and conditions is given. Failure to comply with these terms may result in legal action and the revocation of rights to use Medio.

For full details on licensing terms and conditions, refer to the [LICENSE](https://github.com/BerndHagen/Medio-YouTube-Converter/blob/main/LICENSE) file.

## Screenshots

For those interested in previewing the appearance of Medio Software before downloading the setup folder, the screenshots provided below offer a comprehensive overview. Each screenshot highlights various tabs and features of the application. Please note that future updates may introduce additional functionalities.

| Dashboard Page | Converter Page | History Page |
|------------------------------|-----------------------------|-----------------------------|
| <img src="https://github.com/BerndHagen/Medio-YouTube-Converter/raw/main/img/img_v1.5.0-medio_dashboard.png" width="300px"> | <img src="https://github.com/BerndHagen/Medio-YouTube-Converter/raw/main/img/img_v1.5.0-medio_converter.png" width="300px"> | <img src="https://github.com/BerndHagen/Medio-YouTube-Converter/raw/main/img/img_v1.5.0-medio_history.png" width="300px"> |

| Premium Page               | Activation Page             | Settings Page             |
|-----------------------------|-----------------------------|----------------------------|
| <img src="https://github.com/BerndHagen/Medio-YouTube-Converter/raw/main/img/img_v1.5.0-medio_premium.png" width="300px"> | <img src="https://github.com/BerndHagen/Medio-YouTube-Converter/raw/main/img/img_v1.5.0-medio_redeem.png" width="300px"> | <img src="https://github.com/BerndHagen/Medio-YouTube-Converter/raw/main/img/img_v1.5.0-medio_settings.png" width="300px"> |
