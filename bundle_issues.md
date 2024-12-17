# First, remove any existing Gemfile.lock
rm Gemfile.lock

# Install bundler locally
gem install --user-install bundler

# Create a local directory for gems
mkdir -p vendor/bundle

# Configure bundler to use local directory
bundle config set --local path 'vendor/bundle'

# Install gems
bundle install
