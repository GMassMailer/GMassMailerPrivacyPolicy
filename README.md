# GMassMailer - Email Campaign Manager

GMassMailer is a powerful Chrome extension that automates Gmail email campaigns. Easily upload contacts, personalize messages, schedule delivery, and track campaign progress—all within your browser.

## Features
- **Bulk Email Sending:** Upload CSV files with contacts (First name, Last name, Email, Subject, Body) and send personalized emails in bulk.
- **Personalization:** Automatically fill in recipient names and custom fields for each email.
- **Scheduling & Rate Limiting:** Set custom intervals (1–1440 minutes) and daily sending limits (up to 1,000 emails/day).
- **Automatic Authentication:** Securely connects to your Gmail account and refreshes authentication as needed.
- **Progress Tracking:** Real-time updates on sent emails, remaining contacts, and campaign status.
- **Error Handling & Recovery:** Smart retry logic for failed sends, with detailed error reporting and recovery options.
- **CSV Export:** Automatically export campaign results, including sent dates, for easy reporting and analysis.
- **User-Friendly Interface:** Simple popup UI for campaign management, status monitoring, and CSV downloads.

## Installation
1. Download or clone this repository.
2. Open [chrome://extensions](chrome://extensions) in your browser.
3. Enable **Developer mode** (top right).
4. Click **Load unpacked** and select the extension folder.

## Usage
1. Click the GMassMailer icon in your Chrome toolbar.
2. Upload a CSV file with your contacts and message details.
3. Set your desired sending interval and daily limit.
4. Start the campaign and monitor progress in real time.
5. Download results as a CSV file when the campaign completes.

## Permissions
GMassMailer requests the following Chrome permissions:
- `identity` – For secure authentication with your Gmail account.
- `storage` – To save campaign settings and progress.
- `scripting`, `alarms`, `downloads` – For campaign automation and CSV export.

## Privacy & Security
Your data stays private—GMassMailer only accesses your Gmail account with your permission and never shares your information.

## Support
For help or feedback, visit [https://gmassmailer.com](https://gmassmailer.com) or email us at [support@gmassmailer.com](mailto:support@gmassmailer.com).

---

© 2025 GMassMailer. All rights reserved. 
