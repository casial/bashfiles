If you're reading this, I'll bet you can guess what these files are.

# Highlights:

* 256color optimized
* auto-loads local mods (needs work)
* su'ing to root maintains history and $HOME etc.
* screen windows are automatically named the short-hostname
* Looks for existing screen sessions on login and allows you to attach to any of them
* tab-complete-able RC control aliases (start, stop, etc) with Lin/Sol/HP-UX support

# Prompt:

* prompt relies on a lot of Linux stuff, Mac OS users may have work to make it perfect
* prompt gracefully degrades on non-Linux (well it used to... untested)
* prompt Pathogen-ized (use a Pathogen-modified font)
* prompt tells you what screen window you're in if you are
* prompt tells you if you're in tmux (window info not available)
* prompt tells you if you're in a writable directory
* prompt indicates if ssh-agent is available to this shell
* prompt color inicators for root user
* git stuff in prompt only happens when you're in a "registered" git repo
![Prompt Screenshot](https://raw.github.com/riddley/bashfiles/master/screenshot.png)
