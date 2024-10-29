# **Medio - YouTube Converter**

**Medio** is a user-friendly software solution designed for efficiently downloading YouTube content. Whether you need to download videos, extract audio or save entire playlists, Medio offers a comprehensive solution. Its intuitive interface allows to effortlessly input a YouTube link, select the preferred quality and filename, and start downloading with just a few clicks.

### **Key Features**

- **Video Downloads:** Download your favorite YouTube videos in various formats and qualities, ensuring you have the content available offline whenever you need it.
- **Audio Extraction:** If you only need the audio, Medio allows you to extract and download the audio track from any YouTube video. This is perfect for creating your own music library, podcasts or other audio content.
- **Playlist Downloads:** Medio enables you to download entire playlists, saving you time and effort. This feature is especially useful for those who want to bulk download content for offline access.

### **Supported Formats**

Medio supports a wide range of video and audio formats:

- **Video Formats:** `MP4`, `MKV`, `AVI`, `FLV`, `WMV`, `MOV`
- **Audio Formats:** `MP3`, `OGG`, `WAV`, `M4A`, `AAC`, `WMA`

### **Quality Control**

Medio gives you the flexibility to choose from a wide range of video and audio qualities:

- **Video Quality Options:** `4320p`, `2160p`, `1440p`, `1080p`, `720p`, `480p`, `360p`, `240p`, `144p`
- **Audio Quality Options:** `160k`, `128k`, `96k`, `64k`, `48k`, `32k`
  
Medio uses the ffmpeg library to recode the audio, ensuring that the final media file matches the user's selected audio quality, even down to `32 kbps` if needed. If the selected audio or video quality isn’t available on YouTube, Medio **automatically** selects the **highest available** quality for the one that isn’t supported, ensuring the best possible result. While Medio could support even higher audio qualities, YouTube currently limits audio quality to `160 kbps`. Re-encoding a media file to a higher bitrate beyond YouTube’s cap would only increase the file size without any improvement.

## **Table of Contents**

1. [System Requirements](#system-requirements)
2. [License Options and Benefits](#license-options-and-benefits)
   - [Encore License](#license-options-and-benefits)
   - [Premium License](#license-options-and-benefits)
3. [Free Trial License Key](#free-trial-license-key)
4. [Getting Started Guide](#getting-started-guide)
   - [Step 1: Configure Your Settings](#step-1-configure-your-settings)
   - [Step 2: Download Your Content](#step-2-download-your-content)
5. [Updating Software](#updating-software)
6. [Third-Party Libraries](#third-party-libraries)
   - [FFmpeg](#ffmpeg)
   - [yt-dlp](#yt-dlp)
7. [Data Collection and Account Management](#data-collection-and-account-management)
   - [Key Activation and Data Sync](#key-activation-and-data-sync)
8. [Copyright](#copyright)
9. [Screenshots](#screenshots)

## **System Requirements**

### **Minimum Requirements**
- **Operating System:** Windows 7 or higher
- **Processor:** Dual-core processor (e.g., Intel Core 2 Duo or AMD Athlon X2)
- **RAM:** 2 GB
- **Storage:** 200 MB of free disk space
- **Software:** .NET 6.0 Runtime
  - [Download .NET 6.0 Runtime](https://dotnet.microsoft.com/download/dotnet/6.0/runtime)
- **Internet:** Internet connection for downloading content and verifying licenses

### **Recommended Requirements**
- **Operating System:** Windows 7 or higher
- **Processor:** Quad-core processor (e.g., Intel Core i5 or AMD Ryzen 5)
- **RAM:** 4 GB or higher
- **Storage:** 200 MB of free disk space
- **Software:** .NET 6.0 Runtime
  - [Download .NET 6.0 Runtime](https://dotnet.microsoft.com/download/dotnet/6.0/runtime)
- **Internet:** A stable internet connection for optimal performance

## **License Options and Benefits**

Medio is available for **free**, allowing users to download unlimited audio files in `MP3` format and videos in `MP4` format. By purchasing a license key, users can unlock a range of additional features for a lifetime, providing unrestricted access at any time and from any location. Once activated, these features remain permanent unless the software is reinstalled in a new directory or on a different device. In such cases, the license key must be redeemed again to restore data from the database. Two types of licenses are available for purchase, each offering unique benefits, such as support for additional formats or the Playlist Downloader feature. The license key will be automatically sent via email within **5-10 minutes** after payment is successfully processed.

### **★--[ Encore License ]--★**

| **Feature**                     | **Description**                                                        |
|---------------------------------|------------------------------------------------------------------------|
| **Full Settings Access**        | Unlock all video and audio formats with customizable buffer sizes      |
| **Secure Storage**              | Securely retrieve account data from the database via license key       |
| **Increased Bandwidth**         | Faster media downloads with increased bandwidth capacity               |

### **★--[ Premium License ]--★**

| **Feature**                     | **Description**                                                        |
|---------------------------------|------------------------------------------------------------------------|
| **Full Settings Access**        | Unlock all video and audio formats with customizable buffer sizes      |
| **Secure Storage**              | Securely retrieve account data from the database via license key       |
| **Unlimited Bandwidth**         | Download media files at ultra-fast speeds without bandwidth limits     |
| **Extended History**            | Access to a larger download history, increasing from 2 to 25 pages     |
| **Additional Resolutions**      | Select higher video resolutions, including 2160p (4K) and 4320p (8K)   |
| **Playlist Downloader**         | Download and convert multiple media files with the Playlist Downloader |

## **Free Trial License Key**

Experience Medio's premium features with the free trial license key provided below. This key grants a one-time access to premium features, including all settings, playlist downloads, expanded history, higher video resolutions and unlimited bandwidth, available for up to **10** downloads. 

**Unlock Medio's Premium Converter Features:**
```yaml
License Key:     PT4O-5TYD-WKTV-0ZZ7
```

Once the license key has been redeemed, it becomes invalid and can't be used again. After the download limit is reached, the premium features will no longer be accessible.

## **Getting Started Guide**

Follow these steps to begin downloading from YouTube:

### **Step 1: Configure Your Settings**

1. **Open the Settings Menu**
   - Launch **Medio** and navigate to the `Settings` tab.

2. **Set Your Preferences**
   - **Format:** Choose the desired video or audio format for your downloads.
   - **Additional Settings:** Adjust settings like buffer size to suit your needs.

### **Step 2: Download Your Content**

1. **Access the Converter**
   - Go to the **Converter** tab in the sidebar.

2. **Select Download Type**
   - Choose whether to download the **video** or extract only the **audio** from a YouTube link.

3. **Enter the YouTube URL**
   - Paste the YouTube link into the input field at the top of the **Converter** page.

4. **Configure Download Options**

   - **Save Location:**
     - Click the `...` button next to the directory path field to select your save location.
     - For playlists, it’s recommended to create a dedicated folder to keep files organized.
     
   - **File Name:**
     - Enter a custom name in the `Title your Video` field.
     - For playlists, original video titles are used automatically.
     
   - **Select Quality:**
     - Choose your preferred resolution from the available options. If quality isn't your top priority, opting for a lower quality can help reduce the file size.

5. **Initiate the Download**
   - Click the `Start Download` button to begin the process.
   - **Monitor Progress:** Check the progress in the upper-right corner of the app. The `Loading Tools` status means **Medio** is preparing your download, which usually takes a few seconds.

**Medio** exclusively processes valid YouTube links. If an unrecognized URL is entered, the software will display an `Invalid Link` status. Also, if a media file with the same name and format already exists in the specified path, it will be **automatically skipped** during the download process. If the status changes to `Network Error`, it indicates that the download could not continue due to a lost Internet connection. To ensure successful downloads, especially for complete playlists, please make sure you have a stable Internet connection.

For further assistance or detailed information, do not hesitate to open an [issue](https://github.com/BerndHagen/Medio-YouTube-Converter/issues). For any questions or to start a discussion, feel free to initiate a [discussion](https://github.com/BerndHagen/Medio-YouTube-Converter/discussions) on the GitHub repository.

## **Updating Software**

To keep Medio working at its best, it’s important to use the latest version. Updates include new features and fix bugs that might cause issues. Using an outdated version can lead to incomplete downloads or errors during conversion due to outdated files. You can find the Build Number version in the bottom left corner of the application, which helps you check if there’s a newer version available on the GitHub repository.

To update Medio follow these steps:

1. Download the latest version from the repository and save it to your device.
2. Open the downloaded **ZIP** file and start the setup to begin the installation.
3. Follow the instructions to replace old files with the new updates.
4. Once the installation is complete, launch the application.

For best performance, make sure the installation path is set to `C:\Users\...\AppData\Local\Arctisoft-Studio\Medio - YouTube Converter`. This prevents any issues and ensures that features aren’t blocked due to lack of administrative rights.

## Third-Party Libraries

Medio leverages several third-party libraries to efficiently process media files and deliver a seamless user experience. The two primary libraries are **FFmpeg** and **yt-dlp**.

### FFmpeg

**FFmpeg** is a robust multimedia framework essential to Medio’s functionality. It handles video, audio and other multimedia files and streams, enabling tasks such as format conversion and media encoding/decoding.

- **Website:** [FFmpeg Official Website](https://ffmpeg.org)
- **License:** FFmpeg is licensed under the LGPL or GPL, depending on the configuration and features used.

### yt-dlp

**yt-dlp** is an open-source command-line tool that enables the downloading of videos from YouTube. Medio integrates yt-dlp to efficiently manage content extraction and downloads, ensuring users can easily access a wide range of sources. This library is regularly updated to stay compatible with the latest website changes and formats.

- **Website:** [yt-dlp GitHub Repository](https://github.com/yt-dlp/yt-dlp)
- **License:** yt-dlp is licensed under the Unlicense, a public domain equivalent license, allowing free use, distribution, and modification.

### Additional Information

For more details about FFmpeg and yt-dlp, including their capabilities and licensing, refer to their official documentation:

- **FFmpeg Documentation:** [FFmpeg Documentation](https://ffmpeg.org/documentation.html)
- **yt-dlp Documentation:** [yt-dlp Documentation](https://github.com/yt-dlp/yt-dlp#readme)

If you have any questions or issues related to these libraries, please [open an issue](https://github.com/BerndHagen/Medio-YouTube-Converter/issues) on GitHub.

## Data Collection and Account Management

Medio collects account data to enhance and personalize your experience. Upon installation and the first launch of the application, an **account is automatically created** in the database, allowing you to begin using Medio right away. The collected data includes:

- Personal settings
- Selected avatar
- Account creation date
- Accumulated experience points and current level
- Total megabytes downloaded
- Total number of audio and video files downloaded
- Number of remaining downloads when using a trial license key
- Version of Medio being used (e.g., Classic, Encore, or Premium)

### Key Activation and Data Sync

Once a key has been purchased and redeemed in the `Settings` tab under **Key Activation**, it can always be used to retrieve the latest account data from Medio's database. This ensures that your preferences and progress are preserved across sessions.

While most account data is backed up and can be restored from the database, some data, such as your **Download History**, is stored locally on your device. **Locally stored data cannot be recovered** if Medio is reinstalled on a different system or directory, which will result in the loss of your Download History.

- Accounts **without a license key** will be automatically deleted from the database if they remain inactive for **180 days**.
- Users with an **Encore** or **Premium** license connected to their account are **exempt from this time limit** and can maintain their account indefinitely.

**Note:** Once an account has been deleted from the system, it **can't be restored**. All associated data is permanently removed and can't be recovered.

## **Copyright**

This software is the intellectual property of the Author and is protected by international copyright laws. This copyright notice outlines the key terms governing the use, distribution, and modification of the software:

1. **License**: You are granted a revocable, non-exclusive, non-transferable license to download, install, and use the software for personal, non-commercial purposes.

2. **Modifications Prohibited**: Any modification, decompiling, reverse-engineering, or derivative work based on the software is strictly prohibited without the Author's prior written consent.

3. **Attribution**: When redistributing Medio - YouTube Converter, appropriate credit to the Author is required, including a link to the original source when applicable.

4. **Third-Party Libraries**: Medio leverages third-party libraries like FFmpeg (LGPL) and yt-dlp (Unlicense) for multimedia processing. Please review and comply with their respective licenses.

5. **Warranty Disclaimer**: Medio is provided *"as is,"* without warranties of any kind, express or implied. The Author assumes no liability for damages resulting from the use of the software.

6. **Limitation of Liability**: The Author is not responsible for any indirect, special, incidental, or consequential damages arising out of the use or inability to use the software.

7. **Termination**: The license to use this software may be terminated if the terms of this notice are violated. Upon termination, all use must cease and copies must be deleted.

By using Medio - YouTube Converter, you agree to these terms and conditions. Failure to comply may result in legal action and revocation of your rights to use the software. For full details on licensing terms and further information, please refer to the [LICENSE](https://github.com/BerndHagen/Medio-YouTube-Converter/blob/main/LICENSE) file.

## **Screenshots**

If you'd like a preview of Medio before downloading, the screenshots below offer a clear overview of the application's features. Please note that future updates may introduce additional functionalities.

| Medio - Dashboard Page       | Medio - Converter Page      | Medio - History Page        |
|------------------------------|-----------------------------|-----------------------------|
| <img src="https://github.com/BerndHagen/Medio-YouTube-Converter/raw/main/img/img_v1.5.0-medio_dashboard.png" width="300px"> | <img src="https://github.com/BerndHagen/Medio-YouTube-Converter/raw/main/img/img_v1.5.0-medio_converter.png" width="300px"> | <img src="https://github.com/BerndHagen/Medio-YouTube-Converter/raw/main/img/img_v1.5.0-medio_history.png" width="300px"> |

| Medio - Premium Page        | Medio - Activation Page     | Medio - Settings Page      |
|-----------------------------|-----------------------------|----------------------------|
| <img src="https://github.com/BerndHagen/Medio-YouTube-Converter/raw/main/img/img_v1.5.0-medio_premium.png" width="300px"> | <img src="https://github.com/BerndHagen/Medio-YouTube-Converter/raw/main/img/img_v1.5.0-medio_redeem.png" width="300px"> | <img src="https://github.com/BerndHagen/Medio-YouTube-Converter/raw/main/img/img_v1.5.0-medio_settings.png" width="300px"> |
