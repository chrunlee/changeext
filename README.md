Changes the extension of some filename to a new one。
=========================================

## Installation

Install it as a command line tool via `npm -g`.

```sh
npm install changeext -g
```

## Execution

```sh
$ changeext --help     // print help information
$ changeext txt js     // change 'txt' to 'js' 
$ changeext -i js -t txt // change 'js' to 'txt'
// or with directory
$ changeext -d /home/test/ -i js -t txt
// or loop for directory
$ changeext -d /home/test/ -i js -t txt -l
$ changeext txt js -r // change file extension with random name
```

## License
The MIT license.