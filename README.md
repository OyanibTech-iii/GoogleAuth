# OAuth Login Demo

This project demonstrates a simple OAuth login flow using Google as the authentication provider in PHP.

## Features

- Modern login UI with social login options (Google, Facebook, Apple)
- Google OAuth2 authentication
- User info retrieval after login

## Setup

1. **Install dependencies**  
   Run the following command to install the Google API client:
   ```
   composer require google/apiclient
   ```

2. **Configure Google OAuth**  
   - Go to [Google Cloud Console](https://console.cloud.google.com/).
   - Create a new project and set up OAuth 2.0 credentials.
   - Replace the placeholders in [`index.php`](index.php) with your actual `Client ID`, `Client Secret`, and `Redirect URI`.

3. **Run the project**  
   - Place the files in your web server directory (e.g., `htdocs` for XAMPP).
   - Access [`index.php`](index.php) in your browser.

## Files

- [`index.php`](index.php): Main login page with UI and Google OAuth link.
- [`redirect.php`](redirect.php): Handles the OAuth callback and displays user info.
- [`ico.png`](ico.png): Favicon for the login page.
- [`composer command`](composer%20command): Composer command to install dependencies.
