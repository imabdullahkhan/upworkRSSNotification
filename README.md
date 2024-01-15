# Upwork Job Notifier

This Node.js script checks an Upwork RSS feed for new job postings and sends an email notification when a new job is detected.

## Prerequisites

- Node.js installed on your machine
- npm (Node Package Manager) to install the required packages

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/upwork-job-notifier.git
Change into the project directory:

bash
Copy code
cd upwork-job-notifier
Install dependencies:

bash
Copy code
npm install
Configuration
Open the upwork-job-notifier.js file

Update the following variables with your information:

emailSender: Your Gmail email address.
emailPassword: Your Gmail email password or app-specific password.
emailReceiver: The email address where you want to receive notifications.
upworkRssUrl: Upwork RSS feed URL with your security token.
