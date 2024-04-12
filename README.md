gorainbow

A simple Go program to add rainbow color effect to text input.

Usage:
  gorainbow <input_text>

Description:
  This program reads text from standard input and applies a rainbow color effect to it. It's intended to work with pipes, so you can use it in combination with other commands to add colorful output.

Example:
  $ fortune | gorainbow

Dependencies:
  - Go standard library

Installation:
  You can build the executable by running:
  $ go build -o gorainbow main.go

  Or you can install it to your Go bin directory:
  $ go install
