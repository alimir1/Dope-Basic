# Dope Basic
**Dope Basic** is a simple iOS app that contains a few buttons and switches to dope things up.

## Video Walkthrough

<img src='http://i.imgur.com/zgVkFcZ.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

## Before you begin
1. Create a new iOS project
2. Call it "Animal Kingdom Basic"
3. Save the project

## Required Features
* User can tap on any of the three buttons: Dope, Hope, Nope. When the user taps on either of the buttons, a label above should display the text of the input button.
* A switch to change background to black or white
* A switch to change colors of the button to white or normal

## Hints
### Changing background colors
view.backgroundColor = .white

## Accessing @IBAction's INPUT
sender
ex: sender.isOn...

## Access UIButton's text
button.titleLabel?.text

## Change UIButton's text color
hopeButton.tintColor = .red

## 'Normal' Button Color
hopeButton.tintColor = view.tintColor
