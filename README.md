# Evilspace [![Build Status](https://secure.travis-ci.org/fs/evilspace.png)](http://travis-ci.org/fs/evilspace)

Enforce trailing spaces and tabs removing from your rails application codebase.
Show HTTP 500 page with warning about evil spaces instead application page.

![screenshot](http://i.imgur.com/4q03C.png)

## Installation

Add this line to your rails application's Gemfile:

``` rb
    gem 'evilspace',
      :git =>'git://github.com/fs/evilspace.git',
      :group => :development
```

## Usage

1. Add tabs or trailing spaces to any ruby file under app directory
2. Open any page of your application in browser
3. Look at waring page instead application page
4. Fix evil spaces
5. PROFIT!!!

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
