# GitHub Dashboard

A dashboard for visualizing and managing GitHub repositories, issues, pull requests, and activity metrics.

## Features

- **Repository Overview** - View all repositories with key metrics
- **Issue Tracking** - Monitor open/closed issues across projects
- **Pull Request Management** - Track PR status and reviews
- **Activity Feed** - Real-time updates on repository activity
- **Analytics** - Visualize contribution trends and statistics

## Installation

```bash
git clone https://github.com/yourusername/github-dashboard.git
cd github-dashboard
npm install
```

## Configuration

Create a `.env` file:

```
GITHUB_TOKEN=your_personal_access_token
GITHUB_USERNAME=your_username
```

## Usage

```bash
npm start
```

Navigate to `http://localhost:3000`

## API Integration

Uses GitHub REST API v3 and GraphQL API for data fetching.

## Tech Stack

- Frontend: React/Vue/Angular
- Backend: Node.js/Python
- API: GitHub REST/GraphQL
- Styling: CSS/Tailwind

## License

MIT
