create a github pages
---
For windows
1. install ruby
   https://rubyinstaller.org/downloads/
2. install package for jekyll
   gem install jekyll
   gem install minima
   gem install bundler
   gem install jekyll-feed
   gem install tzinfo-data
3. install missing gems
   bundle install
4. preview
   bundle exec jekyll s || jekyll serve
5. use main branch
6. delete files
   Gemfile.lock 파일.
   docs폴더 및 디렉토리. (내가 다운 받은 Chirpy 테마에는 docs가 없었다.)
   .travis.tml 파일.
   _posts.docs (.md파일들이 있는데, 보고 필요한 것만 남겨 두면 된다.)
   .github 폴더에서 workflows 폴더를 남겨두고 파일 전부를 지우기.
   .github/workflows/에서 commitlint.yml과 page-deploy.yml.hook 외에 다 지우기.
   page-deploy.yml.hook파일의 .hook를 지우기.
