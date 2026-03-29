# 🎵 Spotify Playlist Automator

A Python script that automatically creates Spotify playlists by scanning your entire liked songs library and filtering tracks by specified artists.

## 🔧 What it does
- Authenticates with Spotify using OAuth 2.0
- Scans your complete liked songs library
- Filters tracks based on one or multiple artist names
- Automatically creates a new public playlist with the matched songs
- Handles large libraries by processing songs in batches

## 🛠️ Tech Stack
- Python
- Spotipy (Spotify Web API wrapper)
- OAuth 2.0 Authentication
- python-dotenv (secure credential management)

## ⚙️ Setup
1. Clone the repo
2. Install dependencies:
```
   pip install spotipy python-dotenv
```
3. Create a `.env` file:
```
   SPOTIFY_CLIENT_ID=your_client_id
   SPOTIFY_CLIENT_SECRET=your_client_secret
```
4. Update `FILTER_ARTISTS` and `PLAYLIST_NAME` in the script
5. Run the notebook

## 📌 Example
```python
PLAYLIST_NAME = "Seedhe MauJ"
FILTER_ARTISTS = ["Seedhe Maut", "Calm", "Encore ABJ", "OG Lucifer"]
```
