HELP! I'm trying to install this Bootstrap theme https://coderthemes.com/hyper/saas/index.html in my Rails 6 app.

It's not working through the 'official' Webpacker way! (unfortunately is working in the ugly way, see next sentence)

# Current challenge
> Load the JS files through webpacker, instead of the hacky `<script src="/js/vendor.js"></script>` stuff in `application.html.erb`

### Installation instructions

#### Make sure you have ruby version 2.6.5
`rbenv install 2.6.5` # you might need to install rbenv first: https://github.com/rbenv/rbenv

`rbenv local 2.6.5`

#### Make sure Rails 6.0.0 is installed
`gem install rails -v 6.0.0`

#### Clone this repo into your current folder
`git clone git@github.com:henkjanwils/bootstrappy-with-theme.git .`

#### Install the app
`bundle install`

#### Install all node packaches
`yarn install --check-files` (if you don't have Yarn installed visit https://yarnpkg.com/lang/en/docs/install/#mac-stable)

#### Install forman
`gem install foreman`

#### Start the server
`rails server`

#### Run Foreman in another terminal (but from the same root)
`foreman start -f Procfile.dev`

#### Visist the site on you machine
Visit `localhost:3000` and confirm that the theme should work

# If you find the solution?
Please push a Pull Request
