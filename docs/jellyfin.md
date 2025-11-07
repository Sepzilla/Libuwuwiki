# Jellyfin Media Server

Jellyfin is a free, open-source media server solution that puts you in control of your media with no strings attached, no premium licenses, and no tracking.

## 🔐 Access Instructions

### Web Access
- **URL**: `http://[SERVER-IP]:8096`
- **Default Port**: 8096
- **Authentication**: Local user accounts (no external account required)

### Initial Setup
1. Navigate to the Jellyfin web interface
2. Complete the initial setup wizard on first launch:
   - Set preferred language
   - Create admin account
   - Add media libraries
   - Configure remote access (optional)
3. Sign in with your created credentials

### Mobile & TV Apps
- Download official Jellyfin apps from app stores
- Open app and enter server address: `http://[SERVER-IP]:8096`
- Sign in with your local username and password
- Save connection for easy access

## ✨ Key Features

### Media Management
- **Multiple Libraries**: Organize Movies, TV Shows, Music, Books, and Photos
- **Metadata Providers**: Automatic fetching from TMDB, TVDB, MusicBrainz, and more
- **Custom Artwork**: Upload custom posters, backdrops, and logos
- **Collections**: Group related content together

### Streaming & Playback
- **Direct Play**: Stream content in original quality when compatible
- **Transcoding**: Automatic conversion for incompatible formats
- **Hardware Acceleration**: Support for Intel QSV, NVIDIA NVENC, AMD, and more
- **Multiple Audio/Subtitle Tracks**: Full support for multi-language content
- **SyncPlay**: Watch content together in real-time with others

### User Management
- **Unlimited Users**: No restrictions on number of users
- **Permissions**: Granular control over user access to libraries
- **Profiles**: Individual watch history and preferences per user
- **Parental Controls**: Content rating restrictions and user locks

### Advanced Features
- **Live TV & DVR**: Record and watch live TV with compatible tuners
- **DLNA Support**: Stream to DLNA-compatible devices on your network
- **Plugins**: Extend functionality with community plugins
- **No Phone Home**: Completely private, no telemetry or tracking
- **API Access**: Full REST API for custom integrations

## 📝 Basic Usage Guide

### Adding Media Libraries
1. Go to Dashboard → Libraries
2. Click "Add Media Library"
3. Select library type (Movies, Shows, Music, etc.)
4. Add folder paths where media is stored
5. Configure metadata settings and preferred providers
6. Save and let Jellyfin scan the content

### File Naming Conventions
- **Movies**: `Movie Name (Year)/Movie Name (Year).ext`
- **TV Shows**: `Show Name/Season 01/Show Name - S01E01.ext`
- **Music**: `Artist/Album/## - Track Name.ext`

### Managing Playback
1. **Quality Settings**: 
   - Dashboard → Playback → Transcoding
   - Set maximum bitrate for different connection types
2. **Client Settings**: Each app has its own quality preferences
3. **Audio & Subtitles**: Select preferred languages in user settings

### Scheduled Tasks
- Navigate to Dashboard → Scheduled Tasks
- Configure automatic library scans
- Set up metadata refresh intervals
- Schedule chapter image extraction

## 💡 Tips & Best Practices

### Server Configuration
- Enable hardware acceleration if you have compatible hardware
- Configure reverse proxy (Nginx/Apache) for HTTPS access
- Set up automatic library scans for convenient updates
- Use external metadata storage to keep media folders clean

### Performance Optimization
- Store metadata and cache on SSD for faster loading
- Limit simultaneous transcodes based on server capacity
- Use Direct Play when possible to reduce server load
- Enable image extraction for better thumbnails

### Content Organization
- Keep consistent folder and file naming
- Use the "Identify" feature to manually match content
- Create collections for movie series or themed content
- Tag content for easier discovery

### User Experience
- Set custom display preferences per library
- Configure intro detection to skip TV show intros
- Enable HTTPS for secure remote access
- Use custom CSS for personalized theming

## 🔧 Troubleshooting

### Playback Issues
- Check transcoding logs in Dashboard → Logs
- Verify hardware acceleration is working properly
- Ensure client device supports the codec or enable transcoding
- Check network bandwidth if experiencing buffering

### Library Not Updating
- Manually trigger library scan from Dashboard
- Check folder permissions (Jellyfin needs read access)
- Verify network paths are accessible
- Review scanning logs for errors

### Login Problems
- Reset password using "Forgot Password" on login screen
- Check user permissions haven't been disabled
- Verify server is accessible on the network
- Clear browser cache or app data

### Remote Access Issues
- Configure port forwarding on router (port 8096)
- Set up Dynamic DNS if IP changes frequently
- Consider using reverse proxy for HTTPS
- Check firewall rules allow incoming connections

## 🔌 Useful Plugins

Access plugins from Dashboard → Plugins → Catalog:
- **OpenSubtitles**: Automatic subtitle downloading
- **Trakt**: Sync watch history with Trakt.tv
- **Anime**: Enhanced metadata for anime content
- **Playback Reporting**: Track viewing statistics
- **LDAP Authentication**: Integrate with LDAP/Active Directory

## 📚 Additional Resources

- [Jellyfin Documentation](https://jellyfin.org/docs/)
- [Jellyfin Forums](https://forum.jellyfin.org/)
- [GitHub Repository](https://github.com/jellyfin/jellyfin)
- [Installation Guides](https://jellyfin.org/docs/general/installation/)

---

[← Back to Main Wiki](../README.md)
