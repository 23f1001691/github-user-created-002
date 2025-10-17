# GitHub User Info

A simple web application to fetch and display GitHub user account creation date.

## Features

*   Fetches GitHub user data using the GitHub API.
*   Displays the account creation date in YYYY-MM-DD UTC format.
*   Uses Bootstrap for styling and responsiveness.
*   Handles API errors gracefully.
*   Supports optional GitHub token via query parameter.

## Live Demo

[https://your-github-username.github.io/github-user-info/](https://your-github-username.github.io/github-user-info/)

## Setup Instructions

1.  Create a new repository on GitHub named `github-user-info`.
2.  Clone the repository to your local machine:
    ```bash
    git clone https://github.com/your-github-username/github-user-info.git
    ```
3.  Copy the `index.html` file into the repository.
4.  Commit and push the changes to the repository:
    ```bash
    git add index.html README.md
    git commit -m "Initial commit"
    git push origin main
    ```
5.  Enable GitHub Pages for the repository:
    *   Go to the repository settings on GitHub.
    *   Navigate to the "Pages" section.
    *   Select the `main` branch as the source.
    *   Click "Save".

## Usage

1.  Open the deployed GitHub Pages site in your browser.
2.  Enter a GitHub username in the input field.
3.  Click the "Get Info" button.
4.  The account creation date will be displayed below the form.
5. You can optionally use the `token` query parameter. Example: `https://your-github-username.github.io/github-user-info/?token=YOUR_GITHUB_TOKEN`

## Technical Stack

*   HTML5
*   CSS3 (Bootstrap)
*   JavaScript (ES6+)

## Browser Compatibility

*   Chrome
*   Firefox
*   Safari
*   Edge