# Calibre Downloader

Calibre Downloader is an automated system for downloading, organizing, and importing e-books into your Calibre library. This combines tools like Readarr, LazyLibrarian, or custom scripts to automate your e-book acquisition.

## 🔐 Access Instructions

### Readarr (E-book Download Manager)
- **URL**: `http://[SERVER-IP]:8787`
- **Default Port**: 8787
- **Authentication**: Set during initial setup

### LazyLibrarian (Alternative)
- **URL**: `http://[SERVER-IP]:5299`
- **Default Port**: 5299
- **Authentication**: Configured in settings

### Initial Setup
1. Navigate to your e-book downloader interface
2. Complete initial configuration:
   - Set root folder for e-book storage
   - Configure download clients (Transmission, qBittorrent, etc.)
   - Add indexers for searching
   - Set up Calibre integration
3. Configure quality profiles and naming conventions
4. Test connection to Calibre server

## ✨ Key Features

### Automated Discovery
- **Author Monitoring**: Track favorite authors for new releases
- **Wishlist Management**: Queue books for automatic download
- **Series Tracking**: Automatically download new books in series
- **Metadata Search**: Find books across multiple sources
- **Release Calendar**: See upcoming book releases

### Download Management
- **Multiple Sources**: Support for various download providers
- **Quality Profiles**: Prefer specific formats (EPUB, MOBI, PDF)
- **Format Conversion**: Auto-convert to preferred formats
- **Duplicate Detection**: Avoid downloading duplicates
- **Retry Logic**: Automatically retry failed downloads

### Calibre Integration
- **Auto-Import**: Automatically add downloads to Calibre
- **Metadata Enhancement**: Fetch and update book metadata
- **Library Organization**: Maintain consistent file structure
- **Cover Art**: Download high-quality cover images
- **Tag Management**: Auto-apply tags based on genre, author, etc.

### Search & Indexing
- **Multiple Indexers**: Configure multiple book sources
- **Manual Search**: Search for specific books
- **Automated Search**: Periodic searches for monitored content
- **Priority Ordering**: Configure search order for best results
- **RSS Support**: Monitor RSS feeds for new releases

### Notification System
- **Download Complete**: Notify when books are ready
- **Import Success**: Confirm successful Calibre import
- **Failed Downloads**: Alert on download failures
- **New Releases**: Notify about new books from monitored authors
- **Multiple Channels**: Email, Discord, Telegram, etc.

## 📝 Basic Usage Guide

### Adding Authors to Monitor
1. Search for author by name
2. Click on author profile
3. Select "Monitor" to track new releases
4. Choose monitoring options:
   - All books
   - Future books only
   - Specific series
   - None (manual only)
5. Select quality profile
6. Save and trigger search if desired

### Adding Individual Books
1. Use search bar to find specific book
2. Click "Add Book" or "+" icon
3. Select quality preferences
4. Choose download location
5. Add to library
6. Manually trigger search or wait for automated search

### Managing Quality Profiles
1. Navigate to Settings → Profiles
2. Create or edit quality profiles:
   - Preferred format order (EPUB > MOBI > PDF)
   - Minimum/Maximum file size
   - Language preferences
   - Release group preferences
3. Assign profiles to authors or books
4. Set default profile for new additions

### Monitoring Downloads
1. Navigate to Activity or Queue section
2. View active downloads with progress
3. Check completed imports
4. Review failed downloads
5. Manually retry or remove failed items

### Library Management
1. View all monitored authors and books
2. Filter by status (monitored, available, missing)
3. Mass editor for bulk changes
4. Remove unwanted items
5. Update metadata for existing books

## 💡 Tips & Best Practices

### Configuration Tips
- Set up multiple indexers for better availability
- Configure preferred formats in quality profiles
- Use automatic searching for monitored content
- Set appropriate search intervals (daily/weekly)
- Enable notifications for important events

### Download Strategy
- Prefer EPUB format for maximum compatibility
- Set reasonable file size limits
- Use delayed profiles for patient downloading
- Enable series completion preference
- Configure automatic retries for failed downloads

### Calibre Integration
- Point to existing Calibre library folder
- Enable automatic metadata refresh
- Configure file naming conventions
- Set up custom columns for tracking
- Use tags to mark auto-downloaded content

### Performance Optimization
- Limit concurrent downloads based on bandwidth
- Schedule searches during off-peak hours
- Use download client rate limiting
- Enable only necessary indexers
- Regular cleanup of completed downloads

### Organization
- Use consistent naming schemes
- Group by author and series
- Maintain separate profiles for different content types
- Regular library maintenance and cleanup
- Archive or remove unavailable content

## 🔧 Troubleshooting

### Books Not Being Found
- Check indexers are configured correctly
- Verify indexer API keys are valid
- Try manual search to test availability
- Check search terms and alternate titles
- Review indexer capabilities and limits

### Download Failures
- Verify download client is running
- Check download client connection settings
- Ensure sufficient disk space
- Review download client logs
- Check indexer availability

### Import Issues to Calibre
- Verify Calibre library path is correct
- Check file permissions on library folder
- Ensure Calibre server is running
- Review import logs for errors
- Manually test import with sample file

### Quality Profile Problems
- Review profile configuration
- Check preferred format availability
- Adjust size constraints if too restrictive
- Verify format conversion settings
- Test with manual search first

### Metadata Not Updating
- Check metadata provider settings
- Verify internet connectivity
- Try alternative metadata sources
- Manually refresh metadata
- Check API rate limits

## 🔌 Readarr Specific Features

### Calibre Content Server Integration
- Direct integration with Calibre server
- Automatic book status checking
- Library scanning for existing books
- Metadata synchronization
- Format management

### Book Search
- **Automatic**: Periodic searches for monitored books
- **Manual**: On-demand searching
- **Interactive**: Choose from multiple results
- **RSS Sync**: Real-time monitoring of indexers

### Import Lists
- **Goodreads Integration**: Import from Goodreads shelves
- **Calibre Import**: Import existing library
- **Custom Lists**: CSV or JSON import
- **Author Import**: Bulk author addition

## 🔌 LazyLibrarian Specific Features

### Magazine Support
- Download and organize magazines
- Automated magazine subscriptions
- Cover management
- Issue tracking

### Audio Book Support
- Download audiobooks
- Integration with Audiobookshelf
- Format preferences
- Chapter management

### Custom Providers
- Support for various download sources
- Direct download support
- Newsgroup integration
- Torrent support

## 🔔 Notification Setup

### Discord Notifications
1. Create webhook in Discord
2. Navigate to Settings → Connect → Discord
3. Enter webhook URL
4. Select event types to notify
5. Customize message template
6. Test notification

### Email Notifications
1. Configure SMTP settings
2. Enter recipient email addresses
3. Select notification triggers:
   - Download complete
   - Import success
   - Grab failed
   - Health warnings
4. Customize email templates
5. Send test email

## 📊 Monitoring & Statistics

### Activity Dashboard
- Recent downloads
- Import history
- Search queue
- Active connections
- System health

### Library Statistics
- Total books
- Authors monitored
- Missing books
- File format distribution
- Storage usage

### Health Checks
- Indexer connectivity
- Download client status
- Calibre connection
- Disk space warnings
- Configuration issues

## 📚 Additional Resources

### Readarr
- [Readarr Wiki](https://wiki.servarr.com/readarr)
- [GitHub Repository](https://github.com/Readarr/Readarr)
- [Discord Community](https://discord.gg/readarr)

### LazyLibrarian
- [LazyLibrarian GitLab](https://gitlab.com/LazyLibrarian/LazyLibrarian)
- [Documentation](https://lazylibrarian.gitlab.io/)
- [Support Forum](https://www.reddit.com/r/LazyLibrarian/)

### General Resources
- [Calibre Integration Guide](https://manual.calibre-ebook.com/)
- [E-book Format Guide](https://wiki.mobileread.com/wiki/E-book_formats)
- [Indexer Setup Guide](https://trash-guides.info/)

---

[← Back to Main Wiki](../README.md)
