# ProPresenter Remote Control Client

A web-based remote control interface for ProPresenter, allowing you to monitor and control presentations from any device with a web browser.

https://davidallardyce.github.io/ProPresenterRemoteControlClient/

## Features

- 🖥️ View the current active slide with preview of the next slide
- 🎮 Navigate between slides (previous/next)
- 📝 View slide notes content
- 🖼️ Browse complete slide thumbnails in a responsive grid
- 📂 Select and navigate between presentations within playlists
- 👆 Click-to-trigger functionality for direct slide access
- ⚙️ Configuration options for server connection and quality settings

## Setup

### Requirements

- ProPresenter 7 or newer with API enabled
- Web server to host the app files (or run locally)
- Modern web browser

### Installation

1. Copy the files from the [docs](/docs) folder 

2. Deploy the files to any web server or open them directly in your browser.

3. Configure the connection to your ProPresenter instance:
   - Click the gear icon in the top-left corner
   - Enter your ProPresenter machine's IP address and port
   - Click "Save"

## Usage

### Main Control Interface

The main page (`index.html`) provides:
- Current slide view with notes
- Next slide preview
- Navigation buttons
- Playlist selection

### Slide List View

The thumbnail view (`list.html`) provides:
- Complete grid of all slides in the presentation
- Click any slide to trigger it (when enabled)
- Visual indicator of the current active slide
- Quality settings for thumbnails

## Configuration Options

- **Connection Settings**: Configure the host and port of your ProPresenter instance
- **Thumbnail Quality**: Adjust quality to balance between image clarity and loading speed
- **Click-to-Trigger**: Enable/disable slide triggering when clicking thumbnails

## Technical Details

ProPresenter Remote Control Client is built with:
- Pure JavaScript (no framework dependencies)
- Bootstrap 5 for responsive UI
- Communicates with the ProPresenter API

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- The ProPresenter team for providing API access to their software
