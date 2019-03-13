# Pwn Check

Implemented in javascript, can be used to safely verify a password against the [Have I Been Pwned](https://haveibeenpwned.com/Passwords) API.

## How it Works

This is basically the same implementation as [Michael Pound](https://github.com/mikepound) did and showcased on [YouTube](https://www.youtube.com/watch?v=hhUb5iknVJs) but done in JS instead of Python so it can run directly in a web browser.

The code is kept minimal and simple to allow reviewing and auditing. The only web request that is made is for the password API using the 5 first characters of the hash generated from the given password.

## Usage

* Input a password
* Click the check button
* Amount of matches is displayed

If no match is found, good for you, your password is still safe. Otherwise it is strongly recommended to change it asap.

## Links

* [Web App on GitHub](https://sdescarries.github.io/pwn-check/)
* [Have I Been Pwned API](https://haveibeenpwned.com/API/v2)
