# Clone of reddit using react/readux

Reddit clone is a React app that allows users to browse and search Reddit posts and comments.

## Features

- Browse posts from default or selected subreddits
- Search posts by keyword
- View comments for each post
- Loading and error handling

## Getting Started

The app uses Reddit's API to fetch posts and comments.

### Built with:

- **React** - Components, hooks, context, etc.
- **Redux** - Global state management
- **React-Redux** - Connects React components to Redux
- **Redux Toolkit** - Simplifies Redux code
- **React Router** - Routing and navigation

### Main Features:

- **SubredditList** - Displays a list of subreddits fetched from Reddit's API
- **PostList** - Shows a list of posts from the selected subreddit
- **SearchBar** - Enables searching the list of posts by keyword
- **Post** - Represents a single Reddit post
- **CommentList** - Shows the comments for a post, fetched lazily

React hooks are used for stateful logic throughout. Redux manages the global state of posts, comments, subreddits, etc.

## Usage

To run the app locally:

1. Clone the repository
2. Install dependencies with `npm install`
3. Start the dev server using `npm start`

The app will be available at localhost:3000

Select a subreddit from the sidebar to view posts. Use the search bar to filter posts by keyword. Click a post's comments icon to fetch and show comments.

Deployed by netlify https://reddit-clientapp.netlify.app

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch
3. Make your changes and commit them
4. Push your branch and open a pull request

Please make sure all code passes existing tests and linting. Add additional tests for new features as needed.

## License

This project is open source and available under the MIT License.

Feel free to reach out if you have any questions or need further clarification on any part of the project

