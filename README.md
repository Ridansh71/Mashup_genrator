# Music Mashup Generator

![Uploading Screenshot 2024-03-07 144838.png…]()


The Music Mashup Generator is a tool that allows users to generate custom music mashups by combining multiple audio tracks extracted from YouTube music videos.

## Features

- **Search YouTube Videos**: Search for music videos of your favorite artists on YouTube.
- **Download Videos**: Download the selected music videos from YouTube.
- **Convert to Audio**: Extract audio from downloaded videos and convert them to MP3 format.
- **Trim Audio Clips**: Trim audio clips to a specified duration.
- **Create Mashup**: Combine trimmed audio clips into a single mashup audio file.
- **Send via Email**: Send the generated mashup via email as a compressed ZIP file.

## Usage

1. **Fill in Details**: Enter the name of the artist, number of videos to download, duration of each video, and your email address in the input fields.
2. **Generate**: Click on the "Generate" button to start the mashup generation process.
3. **Wait for Completion**: Wait for the progress bar to reach 100% indicating that the mashup generation is complete.
4. **Check Email**: Check your email inbox for the download link to the mashup ZIP file.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/music-mashup-generator.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit app:

    ```bash
    streamlit run mashup_generator.py
    ```

## Dependencies

- `streamlit`: Web framework for creating interactive web applications.
- `googlesearch-python`: Library for performing Google searches programmatically.
- `pytube`: Library for downloading YouTube videos.
- `moviepy`: Library for editing video files.
- `send_mail`: Custom function for sending emails.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
