# macmetrep.github.io

static hosting

* index: coaching upsell
* guides: where our various recommendations are hosted

## Setup Guide

### Prerequisites
- Ruby (version 2.5.0 or higher)
- RubyGems
- Git

### macOS Setup for Prerequisites (Sonoma/macOS 15)
1. Install Homebrew if not already installed:
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

2. Install Ruby using rbenv:
   ```bash
   brew install rbenv ruby-build
   echo 'eval "$(rbenv init - zsh)"' >> ~/.zshrc
   source ~/.zshrc
   rbenv install 3.2.2
   rbenv global 3.2.2
   ```

3. Install Jekyll and Bundler:
   ```bash
   gem install jekyll bundler
   ```

4. Verify installations:
   ```bash
   ruby -v    # Should show Ruby 3.2.2 or higher
   jekyll -v  # Should show Jekyll 4.x.x
   ```

Note: If you encounter permissions errors during gem installation, never use sudo with gems. Instead, add this to your ~/.zshrc:
```bash
export GEM_HOME=$HOME/.gem
export PATH=$GEM_HOME/bin:$PATH
```

### Local Development Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/macmetrep/macmetrep.github.io.git
   cd macmetrep.github.io
   ```

2. Install Jekyll and dependencies:
   ```bash
   gem install bundler jekyll
   bundle install
   ```

3. Run the site locally:
   ```bash
   bundle exec jekyll serve
   ```
   The site will be available at `http://localhost:4000`

### GitHub Pages Integration
This site is automatically deployed through GitHub Pages:
1. Push changes to the `main` branch
2. GitHub Actions will automatically build and deploy the site
3. Changes will be live at `https://macmetrep.github.io`

### Adding New Content
- Create new guides in the `guides` directory using Markdown files
- Add new pages using the Jekyll page format with YAML front matter
- Images and other assets go in the `assets` directory
