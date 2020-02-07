sudo apt install ruby
sudo gem install bundler
sudo apt install ruby-dev
sudo gem install jekyll



gem install bundler -v '1.17.3'
sudo apt-get install libxslt-dev libxml2-dev

unzip jekyll-theme-massively-master.zip
mv jekyll-theme-massively-master sdhlab.com

mkdir .bundle
bundle update

bundle exec jekyll serve
