# github-bot
# Commit Graph Modifier

This project modifies a user's Git commit graph by adding commits on random dates. The main goal is to generate a visually appealing commit history for GitHub profiles.

## Features

- Adds commits on random dates within a specified range.
- Customizable number of commits and date range.
- Uses simple and widely-used Node.js packages.

## Packages Used

- [`simple-git`](https://www.npmjs.com/package/simple-git): A simple interface for running Git commands in any Node.js application.
- [`random`](https://www.npmjs.com/package/random): Random number generation utilities.
- [`moment`](https://www.npmjs.com/package/moment): A library for parsing, validating, manipulating, and formatting dates.
- [`jsonfile`](https://www.npmjs.com/package/jsonfile): Easily read/write JSON files.

## Getting Started

### Prerequisites

- Node.js installed on your machine.
- Git installed on your machine.

### Installation

1. Clone this repository:
    ```sh
    git clone https://github.com/your-username/commit-graph-modifier.git
    cd commit-graph-modifier
    ```

2. Install the required packages:
    ```sh
    npm install simple-git random moment jsonfile
    ```
