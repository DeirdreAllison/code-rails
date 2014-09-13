# Installing Ruby and Rails

- Ensure your laptop setup meets the following requirements:
  - Ruby 2.11 at the latest patch level.
    - Ruby should be installed in userspace, not at the system level. If you are using `sudo` to install gems, then "you're doing it wrong".
    - If you're on a Mac, you should use the Homebrew package manager: http://brew.sh. On linux your system will already have a package manager.
  - Rails, latest version 4.1
  - #assignment Paste the output of `which ruby` ,  `gem env`, and `which rails` here in this assignment to submit this assignment online.
- Ubuntu 13.04 (or latest Ubuntu)
  - Choose RVM or Rbenv
    - rbenv
      - follow instructions in our slide deck
      - http://www.stehem.net/2012/05/08/how-to-install-ruby-with-rbenv-on-ubuntu-12-04.html
  - Capybara with poltergeist gem and PhantomJS
    - For PhantomJS / Poltergeist set up on Ubuntu see: http://faculty.washington.edu/ivanoats/blog/2014/01/08/setting-up-phantomjs-on-ubuntu/
    - fedora: set qmake to the right version of qt
- Mac OS X
  - Install XCode command line tools
    - Install Homebrew including latest git and qt
      - rbenv
        - brew install rbenv ruby-build rbenv-gem-rehash
        - rbenv install 2.1.1 (or current patch level)
        - rbenv global 2.1.1
  - Rbenv
    - Follow our slide instructions
      - Optional reference: http://createdbypete.com/articles/ruby-on-rails-development-with-mac-os-x-mountain-lion/ (don't' bother installing mysql)