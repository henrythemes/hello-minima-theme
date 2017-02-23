---
title: Welcome
layout: default
---

Hello, Minima!


Welcome to markdown madness. We hope you **really** enjoy using good old text for writing.

Just type some [markdown](http://en.wikipedia.org/wiki/Markdown)
and jekyll will automatically turn it into hypertext markup language (HTML). *Simple as that.*

> Quote goes here.

A list:

- One
- Two
- Three

Some inline code `to_html` and a preformatted code block:

```
Kramdown::Document.new( 'Hello Markdown!' ).to_html
```

with code highlighting:

``` ruby
# The Greeter class

class Greeter
  def initialize(name)
    @name = name.capitalize
  end

  def salute
    puts "Hello #{@name}!"
  end
end

# Create a new object
g = Greeter.new("world")

# Output "Hello World!"
g.salute
```

Or try

# Heading 1

## Heading 2

### Heading 3

