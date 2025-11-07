# Plex Media Server

Plex is a powerful media server that organizes your personal video, music, and photo collections and streams them to all of your devices.

## 🔐 Access Instructions

### Web Access
- **URL**: `http://[SERVER-IP]:32400/web`
- **Default Port**: 32400
- **Authentication**: Plex account required

### Initial Setup
1. Navigate to the Plex web interface
2. Sign in with your Plex account (or create one at plex.tv)
3. The server should be automatically discovered on your local network
4. If not found, manually add server using the IP address

### Mobile & TV Apps
- Download the official Plex app from your device's app store
- Sign in with the same Plex account
- The server will be automatically detected on the same network

## ✨ Key Features

### Media Organization
- **Automatic Metadata**: Fetches posters, descriptions, and information for movies and TV shows
- **Library Management**: Organize content into separate libraries (Movies, TV Shows, Music, Photos)
- **Smart Collections**: Create custom collections based on genres, actors, or other criteria

### Streaming & Playback
- **Transcoding**: Automatically converts media to compatible formats for any device
- **Remote Access**: Stream your media from anywhere (requires Plex Pass for mobile)
- **Offline Sync**: Download content for offline viewing (Plex Pass feature)
- **Watch Together**: Synchronized playback with friends and family

### User Management
- **Managed Users**: Create profiles for family members with content restrictions
- **Sharing**: Share your libraries with friends while maintaining control
- **Parental Controls**: Set content ratings and restrictions per user

### Advanced Features
- **Live TV & DVR**: Watch and record over-the-air TV (with compatible tuner)
- **News & Podcasts**: Access free streaming content and podcasts
- **Music Features**: Lyrics, artist bios, and music videos
- **Tautulli Integration**: Advanced statistics and monitoring (separate app)

## 📝 Basic Usage Guide

### Adding Media
1. Place media files in the appropriate folders on the server
2. Ensure files follow naming conventions:
   - Movies: `Movie Name (Year).ext`
   - TV Shows: `Show Name/Season XX/Show Name - S01E01.ext`
3. Plex will automatically scan and add new content

### Library Scanning
- **Automatic**: Libraries scan periodically for new content
- **Manual**: Click "Scan Library Files" or "Refresh Metadata" in library settings
- **Forced Refresh**: Hold Shift and click refresh to force metadata reload

### Optimizing Your Media
- Navigate to a library and click the "..." menu
- Select "Optimize" to create optimized versions for specific devices
- Useful for mobile devices or slow connections

### Managing Playback
- **Quality Settings**: Adjust streaming quality in Settings > Quality
- **Subtitles**: Toggle subtitles with the CC button during playback
- **Audio Tracks**: Switch between audio tracks if multiple are available

## 💡 Tips & Best Practices

### Server Optimization
- Enable hardware transcoding for better performance (Plex Pass required)
- Store media on fast drives for better streaming performance
- Use SSD for metadata and database files

### Content Organization
- Keep consistent naming conventions for best metadata matching
- Use Plex's "Fix Match" feature if content is misidentified
- Split large libraries (e.g., separate libraries for 4K content)

### Network Configuration
- For remote access, enable Remote Access in Settings
- Configure port forwarding on your router (port 32400)
- Use Plex Relay only as a fallback (enable direct connections when possible)

### Quality Settings
- **Original**: No transcoding, best quality but requires bandwidth
- **Maximum**: High quality with transcoding if needed
- **Automatic**: Plex chooses based on connection speed

## 🔧 Troubleshooting

### Server Not Found
- Verify server is running and accessible on the network
- Check firewall settings (allow port 32400)
- Manually specify server address: `http://[SERVER-IP]:32400`

### Buffering Issues
- Lower streaming quality in playback settings
- Check network bandwidth and server CPU usage
- Enable transcoding optimization

### Metadata Issues
- Use "Fix Match" to manually match content
- Ensure file naming follows Plex conventions
- Check Plex's metadata agents are enabled and up to date

## 📚 Additional Resources

- [Plex Support](https://support.plex.tv/)
- [Plex Forums](https://forums.plex.tv/)
- [Naming Conventions Guide](https://support.plex.tv/articles/naming-and-organizing-your-media-files/)

---

[← Back to Main Wiki](../README.md)
