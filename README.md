# Privacy Policy for DEAL$AI

**Last Updated:** [11/22/2025]

## Introduction

DEAL$AI ("we," "our," or "the Extension") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, store, and protect information when you use our Chrome extension.

## Information We Collect

### 1. Product Information
When you use the Extension to compare prices or search for products, we access and process:
- Product titles, prices, and descriptions from web pages you visit
- Product URLs and links from retailer websites
- Search queries you enter into the Extension

**Purpose:** This information is necessary for the Extension's core functionality of finding and comparing prices across multiple retailers.

### 2. Local Storage Data
The Extension stores the following data locally on your device using Chrome's local storage API:
- Learned CSS selectors for different retailer websites (to improve extraction accuracy)
- Optimal batch sizes for parallel searching (learned from past searches to prevent browser crashes)
- Site performance patterns (to prioritize successful retailers in future searches)

**Purpose:** This data improves the Extension's performance and accuracy over time. All data is stored locally on your device and is never transmitted to external servers.

### 3. Usage Activity
The Extension tracks limited activity data during active search sessions:
- When you initiate a price comparison or product search
- Search progress and status updates
- Number of sites searched and results found

**Purpose:** This data is used to manage search state and provide real-time feedback. It is not stored permanently and is only used during active search sessions.

### 4. No Personally Identifiable Information
We do **NOT** collect:
- Your name, email address, or contact information
- Your location or IP address
- Your browsing history outside of active Extension sessions
- Payment information or financial data
- Authentication credentials
- Personal communications
- Any other personally identifiable information

## How We Use Your Information

### Core Functionality
- **Product Price Comparison:** We use product information you provide to search for the same or similar products across multiple retailer websites
- **Deal Discovery:** We use your search queries to find deals, promotions, and discounts across various sources
- **Product Search:** We use your search terms to find products across multiple retailers

### Performance Optimization
- **Local Learning:** We use locally stored patterns to improve search speed and accuracy
- **Adaptive Batch Sizing:** We learn optimal settings for your device to prevent browser crashes
- **Site Prioritization:** We remember which retailers work best for different product categories

### AI Processing
Product queries (not personal information) are sent to our backend AI service to:
- Generate optimized search plans
- Extract product information from web pages
- Verify product matches using semantic similarity
- Validate prices and product details

## Third-Party Services

### Backend AI Service
The Extension uses a backend service hosted on Google Cloud Run to access AI services:
- **Service Provider:** Google Cloud Platform
- **Purpose:** AI processing for product extraction, verification, and search planning
- **Data Transmitted:** Only product queries and search terms (no personal information)
- **Data Storage:** The backend does not store your queries or search history
- **Location:** United States (Google Cloud Run, us-central1 region)

### AI Providers
Our backend service may use the following AI providers:
- **Google Gemini API:** For product extraction and verification
- **Groq API:** For fast AI processing
- **Hugging Face API:** As a fallback provider

**Data Sharing:** Product queries are shared with these AI providers solely for processing. No personal information is included.

## Data Storage and Retention

### Local Storage
- All learned patterns and optimization data are stored locally on your device
- This data remains on your device and is never transmitted to external servers
- You can clear this data at any time by uninstalling the Extension or clearing Chrome's extension storage

### Backend Storage
- The backend service does not store your search queries or product information
- API requests are processed in real-time and not logged or stored
- No persistent storage of user data occurs on backend servers

### Data Retention
- Local storage data persists until you uninstall the Extension or clear Chrome's extension storage
- No data is retained on backend servers after processing completes

## Data Security

We implement the following security measures:
- **Local Storage:** All local data is stored using Chrome's secure storage API
- **API Communication:** All API calls use HTTPS encryption
- **No Personal Data:** We do not collect or store personally identifiable information
- **Backend Security:** Backend services use Google Cloud Platform security features

## Your Rights and Choices

### Access and Control
- **View Local Data:** You can view locally stored data using Chrome's developer tools
- **Clear Data:** Uninstall the Extension to clear all locally stored data
- **Disable Features:** You can stop using the Extension at any time

### Data Deletion
- **Local Data:** Uninstall the Extension to delete all locally stored data
- **Backend Data:** No data is stored on backend servers, so no deletion is necessary

### Opt-Out
- You can stop using the Extension at any time by uninstalling it
- No data collection occurs when the Extension is not in use

## Children's Privacy

The Extension is not intended for children under the age of 13. We do not knowingly collect information from children. If you believe we have inadvertently collected information from a child, please contact us immediately.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by:
- Updating the "Last Updated" date at the top of this policy
- Posting the new Privacy Policy in the Extension's GitHub repository

Your continued use of the Extension after any changes constitutes acceptance of the updated Privacy Policy.

## International Users

The Extension is operated from the United States. If you are using the Extension from outside the United States, please be aware that:
- Your information may be transferred to, stored, and processed in the United States
- Data protection laws in your country may differ from those in the United States
- By using the Extension, you consent to the transfer of your information to the United States

## Data Sharing and Disclosure

We do **NOT**:
- Sell your data to third parties
- Share your data with advertisers
- Use your data for purposes unrelated to the Extension's functionality
- Transfer your data to determine creditworthiness or for lending purposes

We **ONLY** share product queries (not personal information) with:
- Our backend AI service for processing (as described above)
- AI providers (Google, Groq, Hugging Face) for AI processing

## Cookies and Tracking

The Extension does not use cookies or tracking technologies. We do not track your browsing behavior outside of active Extension sessions.

## Contact Us

If you have any questions about this Privacy Policy or our data practices, please contact us:

- **GitHub Repository:** [Your GitHub Repository URL]
- **Issues:** Open an issue on the GitHub repository
- **Email:** [Your Contact Email - Optional]

## Compliance

This Privacy Policy is designed to comply with:
- Chrome Web Store Developer Program Policies
- General Data Protection Regulation (GDPR) principles
- California Consumer Privacy Act (CCPA) principles

## Summary

**What We Collect:**
- Product information from web pages (when you use the Extension)
- Local optimization data (stored on your device only)

**What We Don't Collect:**
- Personal information (name, email, location, etc.)
- Browsing history
- Payment information
- Authentication credentials

**How We Use It:**
- To find and compare prices across retailers
- To improve Extension performance (locally)
- To process search queries through AI services

**Where It's Stored:**
- Locally on your device (Chrome extension storage)
- Not stored on backend servers

**Your Rights:**
- Uninstall the Extension to delete all local data
- No personal data is collected, so no personal data to delete

---

**By using DEAL$AI, you agree to this Privacy Policy. If you do not agree, please do not use the Extension.**

