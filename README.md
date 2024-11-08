# GitHub User Summary

This project is a simple web application that allows users to search for any GitHub user by username and view their profile information and repositories. Built with HTML, CSS, and JavaScript, this application uses the GitHub API to retrieve and display information dynamically. The project is hosted on GitHub Pages for easy access.

## Demo

Explore the live demo [here](https://arnaucarbonell.github.io/GitHubUserSummary/) (replace with the actual URL).

## Features

- Search any GitHub user by username.
- View the user’s basic profile information, including:
  - Profile picture
  - Display name and bio
  - Followers and following count
  - Total public repositories
- Display a list of the user's public repositories, including:
  - Repository name
  - Description
  - Star count
  - Link to each repository on GitHub

## Technologies Used

- **HTML** and **CSS** for the front-end structure and styling.
- **JavaScript** for handling the API requests and rendering the user data.
- **GitHub API** for fetching user and repository data.
- **GitHub Pages** for hosting the project.

## Getting Started

### Prerequisites

To run this project locally, you need a modern web browser and internet connection (to access the GitHub API).

### Installation

1. Clone this repository:
```bash
   git clone https://github.com/arnaucarbonell/GitHubUserSummary.git
   ```

2. Navigate to the project directory:
```bash
   cd github-user-search
   ```

3. Open index.html in your web browser:
```bash
   open index.html
   ```

## Usage

1. Enter a GitHub username in the search bar on the website.
2. Press "Search" to fetch and view the user's profile and repository information.
3. Click on any repository name to navigate to the GitHub page of that repository.

## Future Improvements

- **Error Handling**: Display custom error messages for cases such as user not found or API limit exceeded.
- **Search History**: Save recent searches for quick access.
- **Pagination**: For users with many repositories, add pagination to navigate through the full list.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any bug reports, feature requests, or other suggestions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
