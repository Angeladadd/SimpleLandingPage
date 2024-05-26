powered by jekyllrb.com

## Setup

follow the steps on https://jekyllrb.com/docs/installation/macos/ to install all prerequisites

## Development


## Run locally

```sh
bundle exec jekyll serve
# browse to localhost:4000
```

## Issues

### Update ruby version

```
brew install ruby
brew link --overwrite ruby --force
echo 'export PATH="/opt/homebrew/opt/ruby/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc
```
