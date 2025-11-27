# Heimdall Application Dashboard

Heimdall is an elegant solution to organize all your web applications. It's a dashboard for all your web applications, designed to make access to your homelab services simple and beautiful.

## 🔐 Access Instructions

### Web Access
- **URL**: `http://[SERVER-IP]:80` or `http://[SERVER-IP]:443` (HTTPS)
- **Default HTTP Port**: 80
- **Default HTTPS Port**: 443
- **Authentication**: Optional (configured in settings)

### Initial Setup
1. Navigate to Heimdall interface
2. On first launch, click the settings icon (gear/cog)
3. Configure basic settings:
   - Background image or color
   - Search provider preferences
   - Authentication (if desired)
4. Begin adding applications
5. Organize applications into groups/sections

### User Setup
- If authentication is enabled, create user accounts
- Each user can have personalized dashboard
- Set permissions for application visibility
- Configure user-specific settings

## ✨ Key Features

### Application Management
- **Easy Adding**: Simple interface to add applications
- **Link Organization**: Group applications by category or function
- **Custom Icons**: Use built-in icons or upload custom ones
- **Color Themes**: Customize application tile colors
- **App Statistics**: Display stats from supported applications (downloads, disk space, etc.)
- **Pinned Items**: Pin frequently used apps to the top

### Enhanced Applications
Heimdall supports "Enhanced Apps" that show real-time information:
- **Sonarr/Radarr**: Shows wanted items and queue
- **NZBGet/SABnzbd**: Download queue and speed
- **Plex**: Recently added content
- **pfSense**: System stats and alerts
- **Nextcloud**: Storage usage
- Many more supported applications

### Customization
- **Backgrounds**: Solid colors, gradients, or custom images
- **Themes**: Light and dark modes
- **Layout Options**: Grid or list view
- **Item Sizing**: Adjust tile sizes
- **Custom CSS**: Advanced styling options
- **Search Bar**: Integrated web search with multiple engines

### User Features
- **Multi-User Support**: Individual dashboards per user
- **Public/Private Apps**: Control app visibility
- **Bookmarks**: Quick access within each app
- **Notes**: Add notes to application tiles
- **Tags**: Categorize and filter applications

### Search Integration
- **Multiple Search Engines**: Google, DuckDuckGo, Bing, etc.
- **Quick Search**: Search directly from dashboard
- **Search Shortcuts**: Type to search without clicking
- **Custom Search Providers**: Add your own search engines

## 📝 Basic Usage Guide

### Adding Applications

#### Basic Application
1. Click the "+" or "Add" button
2. Fill in application details:
   - **Title**: Display name (e.g., "Plex")
   - **URL**: Full URL to application
   - **Description**: Optional description
   - **Color**: Choose tile background color
3. Select an icon (search or upload)
4. Save application

#### Enhanced Application
1. Add application as above
2. Enable "Enhanced" toggle
3. Select application type from dropdown
4. Enter additional details:
   - **API Key**: From the application
   - **API URL**: Usually same as application URL
   - **Statistics**: Choose what to display
5. Test connection
6. Save application

### Organizing Applications
1. **Drag and Drop**: Click and drag tiles to reorder
2. **Create Tags**: Add tags to group similar apps
3. **Filter by Tag**: Click tags to show only tagged apps
4. **Create Sections**: Use tags as section headers
5. **Pin Important Apps**: Star icon to pin to top

### Customizing Appearance

#### Background
1. Click Settings (gear icon)
2. Go to "Interface" tab
3. Choose background option:
   - Solid color (pick from palette)
   - Background image (upload or URL)
   - Bing/Unsplash daily image
4. Adjust opacity if needed
5. Save changes

#### Theme & Layout
1. Navigate to Settings
2. Select theme (Light/Dark)
3. Choose item size (small, medium, large)
4. Adjust items per row
5. Enable/disable search bar
6. Save preferences

### Using Enhanced Apps
- **Real-Time Stats**: Enhanced apps show live data
- **Quick Actions**: Some apps support quick actions from tile
- **Status Indicators**: Color-coded status information
- **Refresh Data**: Click app to refresh statistics
- **Configuration**: Click edit to adjust what's displayed

### Search Functionality
1. Click search bar or start typing
2. Enter search query
3. Select search engine (if multiple configured)
4. Press Enter to search
5. Results open in new tab

## 💡 Tips & Best Practices

### Organization Strategies
- Group by function (Media, Management, Monitoring, etc.)
- Use consistent color scheme for related services
- Pin your most-used applications
- Use tags for different categories
- Keep dashboard uncluttered - only add what you use

### Enhanced App Setup
- Configure API access for each supported app
- Use read-only API keys when possible
- Test connectivity after configuration
- Enable only useful statistics to reduce clutter
- Refresh intervals should match your needs

### Visual Design
- Use high-quality custom icons for consistency
- Choose background that doesn't clash with tiles
- Light background for dark mode, dark for light mode
- Adjust tile transparency for better background visibility
- Use color coding: Green for available, red for down, etc.

### Performance
- Limit number of enhanced applications (API calls)
- Use caching where available
- Optimize background image size
- Disable unused features
- Regular cleanup of unused applications

### Security
- Enable authentication for remote access
- Use HTTPS when exposed to internet
- Set up reverse proxy for additional security
- Use strong passwords for user accounts
- Regularly review user access

## 🔧 Troubleshooting

### Applications Not Loading
- Check URL is correct and accessible
- Verify network connectivity to service
- Ensure service is running
- Check for typos in URL
- Try accessing URL directly in browser

### Enhanced Apps Not Working
- Verify API key is correct
- Check API URL matches application URL
- Ensure application API is enabled
- Test API access manually
- Review application logs for errors

### Statistics Not Updating
- Check API connection status
- Verify API rate limits not exceeded
- Refresh page or clear browser cache
- Check application is responding
- Review enhanced app configuration

### Background Image Issues
- Verify image URL is accessible
- Check image file size (optimize if needed)
- Clear browser cache
- Try different image format
- Check image hosting service is available

### Authentication Problems
- Clear browser cookies and cache
- Reset password if forgotten
- Check user permissions
- Verify authentication is enabled
- Review Heimdall logs

### Can't Add Applications
- Check if duplicate already exists
- Verify all required fields are filled
- Test URL accessibility
- Check browser console for errors
- Update Heimdall to latest version

## 🎨 Customization Ideas

### Common Setups

#### Media-Focused Dashboard
- Plex/Jellyfin prominently displayed
- Sonarr/Radarr with queue info
- Jellyseerr for requests
- Download client stats
- Media organization tools

#### System Administration
- Portainer for container management
- Grafana for monitoring
- Proxmox or ESXi access
- Router/firewall interface
- Backup solution access
- Log aggregation tools

#### Content Management
- Calibre for e-books
- Audiobookshelf for audiobooks
- Photo management (Photoprism/Immich)
- Document management
- Note-taking applications

### Tag Organization Examples
- `#media-servers`
- `#automation`
- `#downloads`
- `#monitoring`
- `#productivity`
- `#admin-tools`

## 🔌 Advanced Features

### API Integration
- Heimdall has its own API for external integrations
- Create custom applications with API
- Automate application management
- Export/import configurations

### Backup & Restore
- Export settings and applications
- Backup database regularly
- Version control configurations
- Easy migration to new instance

### Multi-Instance Setup
- Run multiple Heimdall instances
- Different dashboards for different purposes
- User-specific instances
- Public vs. private dashboards

### Custom CSS
- Add custom styling in settings
- Override default themes
- Create completely custom looks
- Share CSS with community

## 📱 Mobile Access

### Responsive Design
- Fully responsive layout
- Touch-friendly interface
- Mobile-optimized search
- Swipe gestures support

### Mobile Tips
- Add to home screen for app-like experience
- Use mobile browsers for best compatibility
- Configure larger tile sizes for touch accuracy
- Enable simplified view for mobile

## 🌐 Reverse Proxy Setup

### Benefits
- Single domain access (dashboard.yourdomain.com)
- HTTPS encryption
- Authentication layer
- DDoS protection

### Common Reverse Proxies
- **Nginx Proxy Manager**: User-friendly interface
- **Traefik**: Container-native
- **Caddy**: Automatic HTTPS
- **Nginx**: Traditional and powerful

## 📚 Additional Resources

- [Heimdall Documentation](https://heimdall.site/)
- [GitHub Repository](https://github.com/linuxserver/Heimdall)
- [LinuxServer.io Docs](https://docs.linuxserver.io/images/docker-heimdall)
- [Community Forums](https://discord.gg/linuxserver)
- [Application List](https://github.com/linuxserver/Heimdall/wiki/Enhanced-apps)

---

[← Back to Main Wiki](../README.md)
