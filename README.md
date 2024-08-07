
![image](https://github.com/user-attachments/assets/98a32b29-908f-4888-99b3-6084de33b413)



# Camera Gallery Web Application

## Overview

The **Camera Gallery Web Application** is a comprehensive browser-based tool for capturing, recording, and managing media. It leverages modern web technologies, including HTML5, CSS, JavaScript, and IndexedDB, to offer a seamless user experience for video and image processing.

## Features

- **Real-Time Video Recording:** Users can record videos directly from their webcam and store them locally.
- **Image Capturing:** Snapshots can be taken from the live video feed and saved.
- **Media Storage:** Videos and images are stored in the browser using IndexedDB, ensuring persistent local storage.
- **Gallery View:** A dedicated gallery page displays recorded videos and captured images, with options for viewing, downloading, and deleting media.
- **Filter Application:** Apply various filters to images and videos in real-time.
- **Timer Functionality:** A visual timer shows the recording duration while capturing video.

## Technologies Used

- **HTML5:** Structure and content.
- **CSS3:** Styling and layout.
- **JavaScript:** Functionality, including media capture, IndexedDB operations, and DOM manipulation.
- **IndexedDB:** Local storage for video and image data.
- **MediaRecorder API:** Handling media recording and capturing.

## How It Works

1. **Media Capture:** Utilizes the `getUserMedia` API to access webcam and microphone, enabling video recording and image capturing.
2. **Media Storage:** Records and saves media as blobs in IndexedDB, organized into `video` and `image` object stores.
3. **Gallery Management:** Retrieves stored media for display in a gallery, with options to delete or download items.
4. **User Interface:** Features intuitive buttons for recording, capturing, applying filters, and navigating to the gallery.

## Setup

To run this project locally:

1. Clone the repository.
2. Open `index.html` in a web browser.
3. Ensure you have a modern browser that supports IndexedDB and MediaRecorder APIs.

## Contribution

Feel free to contribute by submitting issues, pull requests, or suggestions.

