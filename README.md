# driuft.com

[![Website Status](https://img.shields.io/website?url=https%3A%2F%2Fdriuft.com)](https://driuft.com)
[![GitHub last commit](https://img.shields.io/github/last-commit/driuft/driuft.com)](https://github.com/driuft/driuft.com/commits/main)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## Overview

Source code for my personal website [driuft.com](https://driuft.com), built with MkDocs. This repository is open-sourced to share my site's configuration and implementation.

## Tech Stack

- **Framework**: [MkDocs](https://www.mkdocs.org/) - A fast, simple static site generator
- **Theme**: Customized Material theme
- **Deployment**: GitHub Pages
- **Additional Features**:
  - Custom CSS styling
  - Web fonts integration
  - Responsive design optimizations

## Site Structure

```
driuft.com/
├── docs/                   # Main documentation content
│   ├── assets/             # Shared assets like images and fonts
│   │   ├── fonts/          # Custom fonts
│   │   └── images/         # General image files
│   ├── blog/               # Blog section
│   │   ├── posts/          # Individual blog posts
│   │   │   └── images/     # Images specific to blog posts
│   │   └── index.md        # Blog index page
│   ├── speaking/           # Speaking engagements and talks
│   │   └── index.md        # Speaking overview page
│   ├── stylesheets/        # Custom CSS files
│   │   └── extra.css       # Additional CSS configurations
│   └── index.md            # Homepage content
├── mkdocs.yml              # MkDocs configuration file
└── README.md               # Project overview and instructions

```

## Local Setup

If you want to run this site locally:

### Prerequisites

- Python 3.x
- pip (Python package installer)

### Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/driuft/driuft.com.git
   cd driuft.com
   ```

2. Install MkDocs and dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the development server:
   ```bash
   mkdocs serve
   ```

4. View the site locally at `http://127.0.0.1:8000/`

## Key Configuration Details

### MkDocs Configuration

The site is configured in `mkdocs.yml`, which includes:

- Theme settings
- Navigation structure
- Plugin configurations
- Custom styling options

## Deployment

The site is deployed to GitHub Pages through GitHub Actions. The workflow automatically builds and deploys the site when changes are pushed to the main branch.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. Feel free to use this configuration as inspiration for your own MkDocs projects.
