
# SimpleBlog - A Ruby on Rails Blog App

SimpleBlog is a basic blog application built using the Ruby on Rails framework. It allows users to create, edit, and delete blog posts.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Create new blog posts with titles and content.
- Edit and update existing blog posts.
- Delete blog posts.
- Basic styling using the Bootstrap framework.

## Getting Started

### Prerequisites

- Ruby (version 3.2.2 recommended)
- Ruby on Rails
- SQLite

### Installation

1. Clone the repository:

   ```
   git clone https://github.com/gtchakama/SimpleBlog.git
   ```

2. Navigate to the project directory:

   ```
   cd SimpleBlog
   ```

3. Install dependencies:

   ```
   bundle install
   ```

4. Set up the database:

   ```
   rails db:create
   rails db:migrate
   ```

### Usage

1. Start the Rails server:

   ```
   rails server
   ```

2. Open your web browser and navigate to: <http://localhost:3000>

3. Create, edit, and delete blog posts using the web interface.

### Contributing

Contributions are welcome! If you find any issues or want to enhance the project, please open an issue or submit a pull request.

1. Fork the repository.

2. Create a new branch:

   ```
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and commit them:

   ```
   git commit -m "Add your commit message here"
   ```

4. Push to your forked repository:

   ```
   git push origin feature/your-feature-name
   ```

5. Open a pull request on GitHub.

### License

This project is licensed under the [MIT License](LICENSE).
