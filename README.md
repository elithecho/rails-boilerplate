# Rails Application template

Open source base template for rails, get your new rails project up and running quickly. This is the bare minimum which I feel is enough to kickstart your rails project running postgres and rspec.

`rails new -T -d=postgresql`

## Setting Up

Delete the gems you do not need and uncomment the ones you need.

### Front-end dependecies
- [Title](https://github.com/calebthompson/title)
- [bootstrap-sass](https://github.com/twbs/bootstrap-sass)
- [FFaker](https://github.com/ffaker/ffaker)

Run `rake tmp:clear` to clear your cache before auto prefixer will take effect


### Using SCSS dependencies

```
# Remember to rename your application.css to application.scss
# app/assets/stylesheets/application.scss

# Bootrap sass
@import "bootstrap-sprockets";
@import "bootstrap";

# Bourbon/Neat
@import "bourbon";
// Overriding default neat grid
// @import "grid-settings";
@import "neat";

# Foundation
rails g foundation:install

@import "foundation_and_overrides";

# Normalization if your framework doesn't provide
@import "normalize-rails"
```

### Javascript

```
//= require jquery
//= require jquery_ujs
//= require turbolinks
//= require_tree .

# Bootstrap
//= require bootstrap-sprockets

```

### Development Dependenies

- Using [Bullet](https://github.com/flyerhzm/bullet) is optional

#### Registrations
- Devise
- OmniAuth
```
$ rails generate devise:install
$ rails generate devise MODEL eg. MODEL => User
```


### Test Depencies

```
$ rails generate rspec:install

# If you install webmock and rspec
# spec/spec_helper
require 'webmock/rspec'
```

## Contributing

1. Clone the repo
2. Create a branch `fork/<some_br>`
3. Add stuff and create a pull request
4. ...
5. PROFIT!
