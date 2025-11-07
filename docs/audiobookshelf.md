# Audiobookshelf

Audiobookshelf is a self-hosted audiobook and podcast server designed for organizing and streaming your audiobook collection with a beautiful, user-friendly interface.

## 🔐 Access Instructions

### Web Access
- **URL**: `http://[SERVER-IP]:13378`
- **Default Port**: 13378
- **Authentication**: Local user accounts

### Initial Setup
1. Navigate to Audiobookshelf web interface
2. On first launch, create the root/admin account
3. Set up your first library (audiobooks or podcasts)
4. Point to the directory where your audiobooks are stored
5. Let the initial scan complete

### Mobile Apps
- **iOS**: Available on the App Store
- **Android**: Available on Google Play Store
- Enter server URL: `http://[SERVER-IP]:13378`
- Sign in with your credentials
- Enable offline downloads for listening on the go

## ✨ Key Features

### Audiobook Management
- **Smart Organization**: Automatically organizes by author, series, and narrator
- **Metadata Management**: Fetch from multiple sources (Audible, iTunes, Google Books)
- **Cover Art**: Automatic cover art downloading with manual upload option
- **Series Tracking**: Track series progress across all books
- **Collections**: Create custom collections for organization

### Listening Experience
- **Playback Controls**: Variable playback speed (0.5x - 3x)
- **Sleep Timer**: Auto-stop after specified time or chapter end
- **Bookmarks**: Save specific positions with notes
- **Chapter Support**: Navigate by chapters with chapter preview
- **Position Sync**: Continue where you left off across all devices

### Podcast Features
- **Auto-Downloads**: Automatically download new episodes
- **Episode Management**: Mark as played/unplayed, queue management
- **Custom Schedules**: Set download schedules for each podcast
- **Search**: Browse and add podcasts from iTunes directory

### User Management
- **Multiple Users**: Unlimited user accounts
- **Individual Progress**: Each user maintains their own listening history
- **Permissions**: Control library access per user
- **Statistics**: Track listening time and book completion

### Mobile Features
- **Offline Downloads**: Download books for offline listening
- **Background Playback**: Continue listening while using other apps
- **CarPlay Support**: Native CarPlay integration (iOS)
- **Android Auto**: Native Android Auto support
- **Smart Downloads**: Automatically download next in series

## 📝 Basic Usage Guide

### Adding Audiobooks
1. Place audiobook files in the library folder
2. Organize files in this structure:
   ```
   Author Name/
     Book Title/
       Book Title - Part 01.mp3
       Book Title - Part 02.mp3
       cover.jpg (optional)
   ```
3. Trigger library scan from Library → Scan
4. Audiobookshelf will automatically organize and fetch metadata

### Supported Formats
- **Audio**: MP3, M4A, M4B, OGG, FLAC, OPUS, WAV, AAC, WMA
- **E-books**: EPUB, PDF, CBZ, CBR, MOBI
- **Metadata**: JSON, XML

### Managing Your Library
- **Match Books**: Click "Match" to search for correct metadata
- **Edit Metadata**: Click edit icon to manually adjust details
- **Update Covers**: Upload custom cover art or search online
- **Merge Books**: Combine multiple versions of the same book

### Using Bookmarks
1. During playback, click the bookmark icon
2. Add a title and notes (optional)
3. Access all bookmarks from the book details page
4. Jump directly to bookmarked positions

### Playlists & Collections
- **Collections**: Group books by theme, genre, or any criteria
- **Playlists**: Create ordered listening queues
- **Series**: Automatically tracks reading order for book series

## 💡 Tips & Best Practices

### File Organization
- Use consistent folder structure (Author/Book Title)
- Include metadata files (desc.txt, reader.txt) for better organization
- Keep audiobook files together in book folders
- Use clear, descriptive file names

### Metadata Best Practices
- Let Audiobookshelf auto-fetch metadata first
- Verify narrator information is correct
- Add series information for better browsing
- Include genre tags for filtering

### Mobile Usage
- Download books before trips for offline listening
- Enable mobile data streaming in settings (optional)
- Use sleep timer for bedtime listening
- Configure auto-delete for finished books to save space

### Server Configuration
- Enable HTTPS for secure remote access
- Set up regular backups of the database
- Configure authentication timeout for security
- Use reverse proxy for subdomain access

### Library Management
- Separate libraries for audiobooks and podcasts
- Regular metadata refreshes for updated information
- Use the search function to find specific books quickly
- Set up watched folders for automatic imports

## 🔧 Troubleshooting

### Books Not Appearing
- Check folder permissions (server needs read access)
- Verify files are in supported formats
- Manually trigger library scan
- Check scan logs in settings for errors

### Playback Issues
- Verify audio files aren't corrupted
- Check device codec support
- Try reducing playback speed
- Clear app cache on mobile

### Metadata Not Loading
- Check internet connection for online fetches
- Try alternative metadata providers
- Manually enter metadata if auto-fetch fails
- Verify book title and author format

### Sync Issues
- Ensure both devices are connected to server
- Check authentication hasn't expired
- Force sync from mobile app settings
- Verify server time is correct

### Mobile App Problems
- Update to latest app version
- Re-login to refresh connection
- Clear app cache and data
- Verify server URL is accessible from mobile network

## 🎧 Advanced Features

### Server Settings
- **Backup Schedule**: Automatic database backups
- **Scanner Settings**: File type preferences and exclusions
- **Notifications**: Email notifications for new episodes
- **Custom Metadata Providers**: Add custom providers via API

### User Statistics
- Total listening time
- Books completed
- Current streak
- Favorite authors and narrators

### Integration Options
- **RSS Feeds**: Generate private RSS feeds for any playlist
- **OPML Import**: Import podcast subscriptions from other apps
- **API Access**: Full REST API for custom integrations
- **Webhooks**: Trigger actions on events (new book, playback start, etc.)

## 📚 Additional Resources

- [Audiobookshelf Documentation](https://www.audiobookshelf.org/docs)
- [GitHub Repository](https://github.com/advplyr/audiobookshelf)
- [Discord Community](https://discord.gg/audiobookshelf)
- [Installation Guide](https://www.audiobookshelf.org/install)

---

[← Back to Main Wiki](../README.md)
