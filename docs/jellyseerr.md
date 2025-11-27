# Jellyseerr

Jellyseerr is a free and open-source software application for managing requests for your media library. It's a fork of Overseerr built specifically for Jellyfin and Emby media servers.

## 🔐 Access Instructions

### Web Access
- **URL**: `http://[SERVER-IP]:5055`
- **Default Port**: 5055
- **Authentication**: Jellyfin/Emby or local account

### Initial Setup
1. Navigate to Jellyseerr web interface
2. Complete the setup wizard:
   - Select Jellyfin or Emby as your media server
   - Enter your media server URL and credentials
   - Configure notification settings
   - Set up request permissions
3. Import existing libraries from your media server
4. Configure user permissions and quotas

### User Access
- Users can sign in with Jellyfin/Emby credentials
- Or create local accounts (if enabled by admin)
- Access from any web browser
- Mobile-responsive design works on all devices

## ✨ Key Features

### Request Management
- **Easy Requesting**: Simple interface to request movies and TV shows
- **Search Integration**: Search across multiple metadata providers (TMDB, TVDB)
- **Automatic Approval**: Configure auto-approval for trusted users
- **Request Limits**: Set quotas per user (daily, weekly, monthly)
- **Batch Requests**: Request entire TV seasons with one click

### Media Discovery
- **Trending Content**: See what's popular on TMDB
- **Upcoming Releases**: Browse upcoming movies and TV shows
- **Recommendations**: Get personalized recommendations
- **Popular Requests**: See what others are requesting
- **Rich Metadata**: Detailed information with trailers, cast, and ratings

### Integration Features
- **Jellyfin/Emby Sync**: Automatic library synchronization
- **Sonarr Integration**: Automatic TV show downloading
- **Radarr Integration**: Automatic movie downloading
- **Multiple Instances**: Support for multiple Sonarr/Radarr servers
- **Quality Profiles**: Different quality settings for different content

### Notification System
- **Email Notifications**: Updates on request status
- **Discord Integration**: Notify Discord channels
- **Telegram Support**: Push notifications via Telegram
- **Slack Integration**: Team notifications
- **Webhook Support**: Custom integrations
- **Pushover/Pushbullet**: Mobile push notifications

### User Management
- **Role-Based Access**: Admin, user, and custom roles
- **Permission Control**: Granular control over features
- **Request Quotas**: Limit requests per user
- **User Import**: Automatically import Jellyfin/Emby users
- **Watch List Sync**: Import Plex/Jellyfin watchlists

## 📝 Basic Usage Guide

### Requesting Content

#### Movies
1. Use the search bar to find a movie
2. Click on the movie for details
3. Select quality profile (if multiple available)
4. Click "Request" button
5. Track request status on Requests page

#### TV Shows
1. Search for TV show
2. View available seasons
3. Select seasons/episodes to request
4. Choose quality profile
5. Submit request
6. New episodes auto-requested when available (optional)

### Request Status
- **Pending**: Awaiting admin approval
- **Approved**: Approved, being processed
- **Processing**: Downloading via Sonarr/Radarr
- **Available**: Ready to watch on your media server
- **Declined**: Request was denied (with optional reason)

### Managing Your Requests
1. Navigate to "Requests" page
2. Filter by status (pending, approved, available)
3. View request details and progress
4. Cancel pending requests
5. Report issues with available content

### Discovering Content
- **Discover Tab**: Browse trending movies and shows
- **Filters**: Genre, year, rating filters
- **Collections**: Browse movie collections
- **Keywords**: Search by genre or themes
- **Watchlists**: Import from other services

### Issues & Reporting
1. Navigate to content that has issues
2. Click "Report Issue" button
3. Select issue type:
   - Video quality problems
   - Audio issues
   - Subtitles not working
   - Wrong content
   - Other issues
4. Add description
5. Submit for admin review

## 💡 Tips & Best Practices

### For Users
- Check if content is already available before requesting
- Use the "Available" filter to see what you can watch now
- Set up notifications to know when requests are ready
- Request entire seasons rather than individual episodes
- Report issues promptly to help improve library quality

### For Administrators
- Set reasonable request quotas to prevent abuse
- Configure auto-approval for trusted users
- Set up multiple quality profiles for different content types
- Enable notifications for all request status changes
- Regular sync with media server to keep availability accurate
- Use request limits during high-traffic periods

### Content Discovery
- Browse "Trending" section for popular current content
- Check "Upcoming" for releases you can request in advance
- Use genre filters to find specific types of content
- Follow cast/crew to discover related content
- Check similar content suggestions

### Request Optimization
- Request older content during off-peak hours
- Use lower quality profiles for content you'll watch once
- Request complete series when available
- Group similar requests together
- Check existing requests before duplicating

## 🔧 Troubleshooting

### Login Issues
- Verify Jellyfin/Emby credentials are correct
- Check media server is accessible
- Clear browser cache and cookies
- Ensure user has permission to access Jellyseerr
- Verify user exists in Jellyfin/Emby

### Request Not Processing
- Check Sonarr/Radarr integration is configured
- Verify API keys are correct
- Ensure download client is working
- Check quality profiles are set up
- Review Sonarr/Radarr logs for errors

### Content Not Showing as Available
- Trigger manual library sync in settings
- Verify content exists in Jellyfin/Emby
- Check library paths are correct
- Wait for automatic sync (occurs periodically)
- Ensure library is enabled in Jellyseerr

### Notification Not Received
- Check notification settings are configured
- Verify email/Discord/Telegram credentials
- Check spam/junk folders for emails
- Test notification from settings page
- Review notification logs

### Search Not Working
- Verify internet connection
- Check TMDB API is accessible
- Try different search terms
- Clear browser cache
- Check API rate limits haven't been exceeded

## 🔔 Setting Up Notifications

### Email Configuration
1. Go to Settings → Notifications → Email
2. Enter SMTP server details
3. Configure sender address
4. Test email delivery
5. Enable desired notification types

### Discord Setup
1. Create a webhook in Discord server settings
2. Go to Settings → Notifications → Discord
3. Paste webhook URL
4. Customize notification message template
5. Test and enable

### Telegram Setup
1. Create a bot via @BotFather
2. Get bot token
3. Start conversation with bot and get chat ID
4. Enter details in Jellyseerr settings
5. Test notification

## 🎯 Advanced Features

### 4K Requests
- Configure separate Radarr/Sonarr instances for 4K
- Set up 4K quality profiles
- Enable 4K toggle in request interface
- Different approval workflow for 4K content

### Collection Requests
- Request entire movie collections with one click
- Automatic quality profile application
- Batch approval option
- Series tracking

### Watchlist Integration
- Import from Plex Watchlist
- Sync Jellyfin Favorites
- Auto-request watchlist items
- Regular watchlist sync

### Regional Content
- Configure regional availability filters
- Set preferred languages
- Region-specific metadata
- Localized content discovery

## 📚 Additional Resources

- [Jellyseerr Documentation](https://docs.jellyseerr.dev/)
- [GitHub Repository](https://github.com/Fallenbagel/jellyseerr)
- [Discord Community](https://discord.gg/jellyseerr)
- [Installation Guide](https://docs.jellyseerr.dev/getting-started/installation)

---

[← Back to Main Wiki](../README.md)
