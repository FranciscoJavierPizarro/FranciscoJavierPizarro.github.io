comandos para lanzar esto


sudo apt update
sudo apt install ruby-full build-essential zlib1g-dev git


echo '# Install Ruby Gems to ~/gems' >> ~/.zshrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.zshrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc

gem install jekyll bundler

bundle install
bundle exec jekyll s