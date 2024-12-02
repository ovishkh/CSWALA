# CS Wala Course Player

A simple and interactive course video player designed for educational platforms. This project includes a main video player, a recommended video section, and a note-taking feature with persistent storage.

## Features

### 1. **Main Video Player**
- Plays the main course video using a YouTube embed iframe.
- Enforces course progression by requiring the user to complete the main video before accessing recommended videos.

### 2. **Recommended Video List**
- Displays recommended videos as thumbnails.
- Thumbnails are disabled until the main video is completed.
- Clicking on a thumbnail plays the selected video in the main video player.

### 3. **Note-Taking Section**
- Allows users to take notes while watching videos.
- Notes are automatically saved in the browser's `localStorage`.
- Previously saved notes are loaded when the page is refreshed.

### 4. **Responsive Design**
- Fully responsive layout optimized for both desktop and mobile devices.
- Dynamic adjustments for video player, sidebar, and note-taking sections.

### 5. **Modern UI**
- Clean and user-friendly interface inspired by **Programming Hero**.
- Utilizes custom color palettes for consistency.

## Technologies Used

### Frontend
- **HTML5**: For structuring the page elements.
- **CSS3**: For styling and responsive design.
- **JavaScript**: For interactive functionality.

### Local Storage
- Used for saving and loading user notes.

### YouTube Iframe API
- Embeds YouTube videos using iframes for playback.

## Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/ovishkh/CSWALA.git
   cd Play

