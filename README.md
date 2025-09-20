# 🚀 Recruitment ATS - Advanced Candidate Management System

[![Version](https://img.shields.io/badge/version-1.63.1-blue.svg)](https://github.com/sravannotshravan/recruitmentats)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![PWA](https://img.shields.io/badge/PWA-enabled-purple.svg)](https://web.dev/progressive-web-apps/)

A powerful, modern recruitment application tracking system (ATS) built as a Progressive Web App. Streamline your hiring process with advanced analytics, bulk operations, smart tagging, and real-time candidate management.

## ✨ Key Features

### 📋 **Core Functionality**
- **📄 Drag & Drop File Upload** - Support for Excel (.xlsx) and CSV files
- **⚡ Real-time Processing** - Instant data parsing and candidate display
- **💾 Persistent Storage** - All data saved locally in your browser
- **🔍 Smart Field Detection** - Automatically recognizes Name, Email, Phone, Registration Number

### 🎯 **Candidate Management**
- **Three-Status System** - Approve ✅, Reject ❌, or Pending ⏳
- **Individual Tag Removal** - Click X to remove specific tags
- **Live Tag Preview** - See tags as you type with color coding
- **Bulk Operations** - Select and process multiple candidates at once

### 📊 **Analytics Dashboard**
- **Real-time Metrics** - Total applications, approval rates, review progress
- **Recent Activity** - Track latest decisions with candidate names
- **Synchronized Counters** - All numbers stay perfectly in sync
- **Visual Status Breakdown** - Clear overview of candidate pipeline

### ⌨️ **Keyboard Shortcuts**
- **1** - Approve current candidate
- **2** - Reject current candidate  
- **3** - Set to pending
- **Arrow Keys** - Navigate between candidates
- **Tab** - Auto-format tags

## 🚀 Quick Start

### Option 1: Use Online (Recommended)
Visit the live application: **[recruitment-ats.vercel.app](https://recruitment-ats.vercel.app)** *(Replace with your actual deployment URL)*

### Option 2: Run Locally
1. **Clone the repository**
   ```bash
   git clone https://github.com/sravannotshravan/recruitmentats.git
   cd recruitmentats
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your web browser
   start index.html  # Windows
   open index.html   # macOS
   xdg-open index.html  # Linux
   ```

3. **Or use a local server** (recommended)
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Then visit http://localhost:8000
   ```

## 📖 How to Use

### 1. **Upload Your Data**
- Drag and drop your Excel/CSV file onto the upload area
- Supported formats: `.xlsx`, `.csv`
- Required columns: `Name`, `RegistrationNumber` (other fields auto-detected)

### 2. **Review Candidates**
- Navigate through candidates using Next/Previous buttons or arrow keys
- Review all candidate information in organized cards
- Use keyboard shortcuts (1, 2, 3) for quick decisions

### 3. **Manage Tags**
- Click on any tag field to add/edit tags
- Use the color picker to customize tag colors
- Remove individual tags by clicking the X button
- Press Tab to auto-format comma-separated tags

### 4. **Bulk Operations**
- Select multiple candidates using checkboxes
- Apply bulk approve, reject, or pending actions
- Export approved candidates to Excel or VCard format

### 5. **Monitor Progress**
- Check the analytics dashboard for real-time metrics
- Track recent activity and approval rates
- Monitor review progress across your candidate pipeline

## 🏷️ Tag Management System

### Features
- **🎨 20 Color Options** - Choose from a diverse color palette
- **📚 Popular Tags** - Quick access to frequently used tags
- **✨ Individual Removal** - Remove specific tags without editing the whole list
- **👀 Live Preview** - See exactly how tags will look before saving
- **⌨️ Smart Formatting** - Auto-format with proper spacing

### Usage
1. Click on any "🏷️ Tags" field
2. Type tags separated by commas
3. Choose colors for new tags using the color picker
4. Press Tab to auto-format or Enter to save
5. Click X on any tag to remove it individually

## 📊 Analytics Dashboard

### Metrics Tracked
- **Total Applications** - Complete candidate count
- **Approval Rate** - Percentage of approved candidates
- **Review Progress** - How many candidates have been reviewed
- **Status Breakdown** - Approved, rejected, and pending counts
- **Recent Activity** - Latest 10 decisions with candidate details

### Real-time Updates
All metrics update instantly as you make decisions, ensuring you always have current information about your recruitment pipeline.

## 📱 Progressive Web App (PWA)

### Installation
1. Visit the app in Chrome, Edge, or Safari
2. Look for the "Install" button in the address bar
3. Click to install as a standalone app
4. Access from your device's app menu

### Offline Capability
- Works completely offline after first load
- All data processing happens on your device
- No internet required for core functionality

## 🛠️ Technical Specifications

### Built With
- **HTML5/CSS3/JavaScript** - Core web technologies
- **Bootstrap 5.3.3** - Responsive framework
- **XLSX.js** - Excel file processing
- **Service Worker** - PWA offline functionality
- **LocalStorage** - Client-side data persistence

### Browser Support
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Performance
- **Fast Loading** - Optimized assets and minimal dependencies
- **Efficient Processing** - Handles large datasets smoothly
- **Low Memory Usage** - Client-side processing with smart caching

## 📁 File Structure

```
recruitmentats/
├── index.html              # Main application file
├── manifest.json           # PWA manifest
├── sw.js                   # Service worker for offline support
├── logo.png               # Application logo
├── android-chrome-*.png   # PWA icons
├── PWA_SETUP.md          # PWA setup instructions
└── README.md             # This file
```

## 🔐 Privacy & Security

### Data Handling
- **100% Client-Side** - All processing happens in your browser
- **No Server Required** - Your data never leaves your device
- **No Analytics Tracking** - Complete privacy protection
- **Local Storage Only** - Data saved in your browser's local storage

### Security Features
- No external API calls for core functionality
- No user authentication required
- No personal data transmitted over network
- Secure local data storage

## 🆕 Version History

### v1.63.1 *(Latest - September 20, 2025)*
- 🔧 **Recent Activity Fix**: Proper candidate name and registration number display
- 📝 **Enhanced Field Detection**: Uses exact field names from source documents

### v1.63 
- 🏷️ **Enhanced Tag Management**: Individual tag removal with X buttons
- 👀 **Live Tag Preview**: Real-time visual feedback while typing
- ⌨️ **Smart Tag Formatting**: Tab key for auto-formatting

### v1.62 
- ⌨️ **Keyboard Shortcuts**: Quick actions with 1, 2, 3 keys
- 🧭 **Enhanced Navigation**: Arrow key navigation between candidates

### v1.61 
- 🔄 **Counter Synchronization**: Fixed pending counter consistency
- 📊 **Analytics Improvements**: Better metric accuracy

[View complete changelog](https://github.com/sravannotshravan/recruitmentats/commits/main)

## 🤝 Contributing

We welcome contributions! Please feel free to submit issues and enhancement requests.

### Development Setup
1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Make your changes and test thoroughly
4. Commit with descriptive messages
5. Push to your fork and submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with modern web standards for maximum compatibility
- Inspired by the need for efficient, privacy-focused recruitment tools
- Designed for both technical and non-technical users

## 📞 Support

Having issues? Need help?

- 📧 **Email**: [Personal](sravan.kowshik@outlook.com) , [College Email](sravan.kowsik2023@vitstudent.ac.in) *(Replace with your actual email)*
- 🐛 **Bug Reports**: [GitHub Issues](https://github.com/sravannotshravan/recruitmentats/issues)
- 💡 **Feature Requests**: [GitHub Discussions](https://github.com/sravannotshravan/recruitmentats/discussions)

---

<div align="center">

**⭐ Star this repository if it helped you manage your recruitment process more efficiently!**

Made with ❤️ for efficient recruitment management

</div>
