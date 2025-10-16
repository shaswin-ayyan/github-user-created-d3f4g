# GitHub User Account Creation Date Fetcher

This web application allows users to input a GitHub username and fetch the account's creation date in UTC (formatted as YYYY-MM-DD). It optionally supports a personal access token via URL query parameter (`?token=YOUR_TOKEN`) for authenticated requests, which can help with rate limits.

## Features
- Responsive Bootstrap 5 design for mobile and desktop.
- Graceful error handling for invalid usernames or network issues.
- Simple and clean user interface.

## Usage
1. Open the `index.html` file in your browser.
2. Enter a GitHub username into the input field.
3. (Optional) Append `?token=YOUR_TOKEN` to the URL in your browser's address bar if you want to authenticate with a personal access token.
4. Click "Fetch Info" to retrieve the account creation date.

## Notes
- Ensure your token has appropriate permissions if used.
- The creation date is displayed in UTC.

## License
This project is licensed under the MIT License.

---

**Author:** Your Name

**Date:** 2023-10-02