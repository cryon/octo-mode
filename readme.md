# Octo mode for Emacs

Major mode for Octo; a high level assembly language for the
[Chip8](http://mattmik.com/files/chip8/mastering/chip8.html) virtual machine.

More information about the language can be found
[here](https://github.com/JohnEarnest/Octo).

## Installation

[![MELPA](https://melpa.org/packages/octo-mode-badge.svg)](https://melpa.org/#/octo-mode)

The easiest way to install octo-mode is from melpa.  Assuming MELPA is added to
your archive list you can list the available packages by typing <code>M-x
list-packages</code>, look for <code>octo-mode</code>, mark it for installation
by typing <code>i</code> and then execute (install) by typing <code>x</code>. Or
install it directly with <code>M-x package-install RET octo-mode</code>.

If you want to install it manually, just drop this file anywhere in your
<code>load-path</code>. By default octo-mode associates itself with the
<code>*.8o</code> file ending. You can enable the mode manually by <code>M-x
octo-mode RET</code>.

## Contribute

Please report any issues you find with the mode and feel free to send me
pull-requests with improvements!

If you send a merge-request please make sure that your commits contains exactly
what you indent them to. Refrain from doing more than one logical change in each
commit and rebase your branch on this repository's master branch to avoid
interleaved commits from different branches.

Study [this blog post](http://chris.beams.io/posts/git-commit/) by Chris Beams
on how to write good commit messages.

> * Separate subject from body with a blank line
> * Limit the subject line to 50 characters
> * Capitalize the subject line
> * Do not end the subject line with a period
> * Use the imperative mood in the subject line
> * Wrap the body at 72 characters
> * Use the body to explain what and why vs. how
