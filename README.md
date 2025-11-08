# SaaS-on-Wheels

A comprehensive self-hosted server platform that provides a suite of services for your family or organization. SaaS-on-Wheels brings enterprise-grade applications to your personal server, giving you full control over your data and services.

## Authentication

Users can sign in to the SaaS-on-Wheels Server using:

- **Pangolin**: A modern authentication provider for seamless access management
- **Authentik**: An open-source Identity Provider for enterprise-grade authentication

All users are pre-authorized, ensuring secure access to the services they need.

## Dashboard Access

Access all your applications through the **Pangolin Dashboard**, which provides:
- Centralized access to all SaaS-on-Wheels services
- Single sign-on (SSO) across all applications
- Easy navigation between different services
- User-friendly interface for managing your applications

## Available Services

### Calibre Library Server

The Calibre Library Server provides family-wide access to your ebook collection. All family members can access, download, and read books from the shared library.

#### Getting Your Ebooks

**For Audible Books:**
1. Log in to your Audible account at [audible.com](https://www.audible.com)
2. Go to your Library
3. Click on your profile name in the top right and select "My Library"
4. For each book you want to download:
   - Click the three dots (...) next to the book title
   - Select "Download" to get the AAX or AA file
5. Convert AAX/AA files to more compatible formats using tools like:
   - OpenAudible
   - AAXtoMP3
   - inAudible
6. Upload the converted files to the family Calibre server

**For Kindle Books:**
1. Log in to Amazon at [amazon.com/myk](https://www.amazon.com/myk)
2. Navigate to "Content and Devices" or "Manage Your Content and Devices"
3. Go to the "Your Content" tab
4. For each book:
   - Click the "..." button next to the book title
   - Select "Download & transfer via USB"
   - Choose the device format (preferably MOBI or AZW3)
   - Click "Download"
5. Upload the downloaded files to the family Calibre server

**Note:** Some Kindle books have DRM protection. You may need to:
- Use DeDRM tools (check local laws regarding DRM removal for personal use)
- Ensure you're downloading books you've legitimately purchased
- Keep backups of your original files

#### Uploading Books to Calibre

1. Access the Calibre web interface through the Pangolin dashboard
2. Click "Add books" or drag and drop files into the interface
3. Calibre will automatically:
   - Import the book metadata
   - Organize books in the library
   - Make them available to all family members
4. Alternatively, use the Calibre desktop application to connect to the server and upload books

#### Syncing Your Kindle with Calibre

There are several methods to sync your Kindle device with the Calibre library:

**Method 1: USB Connection (Recommended)**
1. Connect your Kindle device to your computer via USB cable
2. Open the Calibre desktop application
3. Calibre will automatically detect your Kindle device
4. Select the books you want to transfer from your Calibre library
5. Click "Send to device" button in Calibre
6. Wait for the transfer to complete
7. Safely eject your Kindle device

**Method 2: Email Delivery**
1. Set up your Kindle email address in Calibre:
   - Go to Preferences → Sharing books by email
   - Add your Kindle's email address (found in Amazon account settings under "Manage Your Content and Devices" → "Preferences" → "Personal Document Settings")
2. In Amazon settings, add the Calibre server's email to your approved email list
3. Select books in Calibre and use "Connect/share" → "Email to" to send books directly to your Kindle
4. Books will appear on your Kindle within minutes (requires WiFi connection)

**Method 3: Calibre Content Server**
1. Enable the Calibre Content Server in your SaaS-on-Wheels setup
2. Access the content server from your Kindle's web browser
3. Browse and download books directly to your Kindle
4. Books will appear in your Kindle library

**Tips for Kindle Syncing:**
- Calibre automatically converts books to Kindle-compatible formats (MOBI, AZW3)
- Metadata and covers are preserved during transfer
- Collections can be managed in Calibre and synced to your device
- Use "Send to device" options in Calibre to customize format preferences

## Roadmap

SaaS-on-Wheels is continuously evolving. Upcoming features include:

### Planned Services

- **Filesharing Service**: Self-hosted file sharing and synchronization (NextCloud/Syncthing-style)
- **Zotero Server**: Research and reference management for academic and professional work
- **AI Models**: Self-hosted AI services including:
  - Large Language Models (LLMs) for text generation
  - Image generation and manipulation
  - Code assistance and analysis
  - Document processing and summarization

## Getting Started

1. Ensure you have received your pre-authorization credentials
2. Visit the Pangolin dashboard URL provided by your administrator
3. Sign in using Pangolin or Authentik
4. Browse available services and start using SaaS-on-Wheels

## Support

For support and questions, contact your SaaS-on-Wheels administrator.