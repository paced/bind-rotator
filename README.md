# Source Bind Rotator

Clientside web app for silly Source game bind rotations.

## Screenshots

![Courtesy of r/copypasta](http://i.imgur.com/7MJri4E.png "navyseal")
![Ingame Team Fortress 2 Chat](http://i.imgur.com/0aGrpFx.png "demoman?")

## Introduction

View the app [here](https://paced.github.io/source-bind-rotator/).

Why do you need this app? Well, you don't. But it can be a bit of fun. You can use it to turn lengthy, mostly
unformatted copypasta or even movie scripts, novels, what have you into a bind rotation. This means you can press a
button of choice and it will output a string to chat. Continue pressing it to continue until you get to the end. Then
it loops.

## Usage

- Open the [link](https://paced.github.io/bindRotator/) in your browser or clone the repository to your drive.
- Paste in your long string/text and choose a key.
- *You must apply two alias names in the input boxes. This will allow you to create multiple bind rotations provided
  you bind different keys. The aliases should not contain any special characters or whitespace.*
- Click "Generate".
- Copy paste the output to either your autoexec.cfg, or create a new file, e.g.: binds.cfg, and put "exec binds.cfg"
  in your autoexec.
- In game you can press that button to use the rotation.

## Notes

There is a known issue with quotation mark characters. It should work for most cases, but escaping doesn't work so well
with Source "say" commands.
