# Empty ember-cli/rails project

Get the code with command:

```bash
git clone git@github.com:hiptest/empty-embercli-rails5-project.git
cd empty-embercli-rails5-project
```

You need to install:
- Ruby 2.5
- Rails 5.0.6
- Node.js 8.9.4
- npm 25.6.0

Install ember-cli:

```bash
npm install -g ember-cli
```

Build the project:

```bash
bundle install
bin/rake ember:install
```

Run the server:

```bash
bin/rails server
```

Go to the empty page: http://localhost:3000/
