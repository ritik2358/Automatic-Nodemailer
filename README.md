# Automatic-Nodemailer

Automatic-Nodemailer is a Node.js based application that allows you to automatically respond to emails sent to your Gmail mailbox while you're away on a vacation or unavailable. This application checks for new emails in a specified Gmail ID, sends replies to emails that have no prior responses, and adds a label to the email before moving it to the labeled folder. The entire process is repeated automatically at random intervals between 45 to 120 seconds.

## Features

- **Email Checking**: The application continuously monitors the specified Gmail ID for new emails.
- **Automated Replies**: Emails that have not received any previous responses are automatically replied to by the application.
- **Labeling and Moving**: The application adds a label to the email and moves it to the labeled folder, organizing your emails effectively.
- **Random Intervals**: The entire process of checking for new emails, sending replies, and labeling/moving emails is repeated at random intervals between 45 to 120 seconds, ensuring a natural response pattern.

## Prerequisites

Before running the Automatic-Nodemailer application, make sure you have the following prerequisites installed on your system:

- Node.js: Version 12 or higher
- NPM: Version 6 or higher

## Getting Started

Follow the steps below to get started with Automatic-Nodemailer:

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/ritik2358/Automatic-Nodemailer.git
   ```

2. Navigate to the project directory:

   ```
   cd Automatic-Nodemailer
   ```

3. Install the required dependencies:

   ```
   npm install
   ```

4. Add your credentials in a `credentials.json` file:

   - Visit [Google Cloud Console](https://console.cloud.google.com/) and create a new Google Console Project.
   - Go to the "APIs & Services" screen.
   - Select "OAuth consent screen" and configure it.
   - Go to the "Credentials" tab and create an OAuth client ID.
   - Download the JSON file and paste the contents in the `credentials.json` file.

5. Start the application:

   ```
   npm start
   ```

   or

   ```
   npm run dev
   ```

6. Sit back and let Automatic-Nodemailer handle your incoming emails while you enjoy your vacation!

## Contributing

Contributions to Automatic-Nodemailer are welcome! If you find a bug or want to suggest an enhancement, please create an issue or submit a pull request.

## Support

If you have any questions, feel free to reach out to me by creating an issue. I'll be happy to assist you.
