# xswitchto

## What
``xswitchto firefox`` switches to firefox. 
* Raise and focus firefox if you already had it opened, or  open a new firefox window if you had not.
* If you have many firefox windows open, cycle through them.
 
Replace firefox with any application you like.

## Dependencies
This program works with any [EWMH compliant window manager](https://en.wikipedia.org/wiki/Extended_Window_Manager_Hints#List_of_window_managers_that_support_Extended_Window_Manager_Hints).

* xdotool
* wmctrl

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
