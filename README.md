# fyi
this is my v3 website. it works. i intend to make a few improvements that make the code more generative so it's easier for u to use your own directory structure
#### overview
- static, single-page [app shell](https://developers.google.com/web/fundamentals/architecture/app-shell)
- built with [middleman](https://middlemanapp.com)
- [surge](https://surge.sh) recommended for hosting
#### stack
- [middleman](https://middlemanapp.com) as our generator
- [slim](http://slim-lang.com) as our templating language
- [sass](http://sass-lang.com) for styling
- [sprockets es6](https://github.com/TannerRogalsky/sprockets-es6) to convert ecmascript with a `.js.es6` extension to vanilla javascript with [babel](https://babeljs.io)
## development
#### setup
1. 'cd' to project
2. `bundle install`
#### preview
1. `cd` to project
2. `bundle exec middleman` or `middleman`
3. open [localhost:4567](http://localhost:4567)
#### build
1. `cd` to project
2. `bundle exec middleman build` or `middleman build`
