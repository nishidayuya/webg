# webg: A downloader to get web page with JavaScript

## Requirements

- Ruby
- Firefox
- Firefox WebDriver support

## Installation

```ruby
$ gem install webg
```

## Usage

```sh
$ webg [options] uri
```

For example: fetch 'webg' page titles by google

```sh
$ webg --text --css-selector='h3.LC20lb' 'https://www.google.com/search?q=webg'
```

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/nishidayuya/webg
