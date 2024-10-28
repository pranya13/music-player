🎵 Music Player
A dynamic music player application that allows users to play, pause, skip, and rewind songs seamlessly. This project utilizes both linked lists and arrays to manage and play music tracks effectively.

🚀 Features
Play/Pause Control: Users can play or pause the current track with a single button.
Skip/Previous Track: Easily navigate through the playlist by skipping to the next track or going back to the previous one.
Shuffle Playlist: Randomly shuffle the order of songs in the playlist for a fresh listening experience.
Delete Songs: Remove songs from the playlist with a simple click.
Responsive User Interface: User-friendly interface for easy interaction.
🛠️ Technologies Used
Programming Language: JavaScript
Web Technologies: HTML, CSS
Data Structures: Utilizes both arrays and linked lists for efficient song management.
📁 Structure
JavaScript:
Array Implementation: Used for the initial storage of songs, allowing easy access and manipulation of song data.
Linked List Implementation: Provides an efficient way to navigate through songs when playing, skipping, or rewinding.
📄 Usage
Play Song: Click the "Play" button to start playing the current song.
Pause Song: Click the "Pause" button to stop playback.
Next Track: Click "Next" to skip to the following track in the playlist.
Previous Track: Click "Previous" to rewind to the last track.
Shuffle: Click the "Shuffle" button to randomize the song order in the playlist.
Delete Song: Click the delete button next to any song to remove it from the playlist.
🔍 Code Overview
The application maintains a playlist using an array of song objects, each containing properties like id, title, artist, duration, and src.
User actions such as play, pause, next, and previous are handled through event listeners attached to buttons in the UI.
Songs are rendered dynamically based on the current state of the playlist.
A linked list structure can be implemented (not detailed in this code but can be added) to facilitate more complex playlist management, such as easy insertion and deletion of songs.
