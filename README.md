# xswitchto
* This only works for systems that are using the **X window system**.

## What
``xswitchto firefox`` switches to firefox. 
* Focus and raise firefox if you already had it opened, or  open a new firefox window if you had not.

Replace firefox with any application you like.

## How
... does it find windows?
* It uses the class of a window.
* It uses [xlabel](https://github.com/billtsek/xlabel/) if it's installed (with higher priority than the class).

  Needed if you want to find terminal applications like vim.

## Usage
To get help for the ``xswitchto`` command, type ``xswitchto -h`` in your terminal.

## Installation
* ``xswitchto`` is just a shell script, so just download it, make it executable and run it.

## Why
I needed a way to quickly switch between windows of the same application.
