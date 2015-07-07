## Using Catpix gem to print an image in the terminal

quite simple to do:

```ruby
require 'catpix'
Catpix::print_image "caveman1.png",
  :limit_x => 1.0,
  :limit_y => 0,
  :center_x => true,
  :center_y => true,
  :bg => "white",
  :bg_fill => true
```

Gem:

```
gem install catpix
```
Gem details:

https://github.com/pazdera/catpix


```
ruby captix.rb
```

<img src="cavemanprint.png" >
