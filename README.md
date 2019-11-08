# Installation instructions

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
`yarn install --check-files` (if you don't have Yarn installed vitis https://yarnpkg.com/lang/en/docs/install/#mac-stable)

#### Install forman
`gem install foreman`

#### Start the server
`rails server`

#### Run Foreman in another terminal (but from the same root)
`foreman start -f Procfile.dev`

#### Visist the site on you machine
Visit `localhost:3000`
