# Export Kindle vocabulary to CSV

A cute little script to export your Kindle vocab on any platform.
All you need is to plug in your Kindle Paperwhite 3, open up a terminal and...

## Requirements
- Node.js 14 or newer

## Installation and Usage

```shell
$ npm install -g kindle-export
$ kindle-export
```
Optionally provide the path to your db as parameter
```shell
$ kindle-export --db ~/Desktop/vocab.db
```
Optionally provide the export path
```shell
$ kindle-export --output ~/Desktop/vocab.csv
```

## Development

```shell
$ git clone https://github.com/martinchristov/kindle-export.git
$ cd kindle-export
$ npm install
$ node index.js
```

