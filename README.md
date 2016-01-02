# en2th
Command-line translator english to thai with log
## About
This is a simple shell script that allow you to translate an english word to thai and keep a log file on what you have looked up. For each translation, it'll tell you how many times you already have looked up the word.
## Installation
First you will need to install [translate-shell](https://github.com/soimort/translate-shell) in order to run en2th. 

Download the shell script file and place it into your path /etc/environment

```
$ wget https://raw.githubusercontent.com/mak1986/en2th/master/en2th 
$ chmod +x ./en2th
```

## Try It Out!
```
$ en2th hallo
Translate: hello
Thai: สวัสดี
You've translated 'hello': 1 time(s)
```
You can find your log file in ~/translation/log


