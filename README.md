# i3blocks-pomodoro
A pomodoro blocklet script for i3blocks. Based on https://github.com/rkashapov/i3blocks-pomodoro script (fixed bugs, added colors, ability to skip and some other features).

# Installation

To use with i3blocks, clone this repository:

```
git clone https://github.com/gitbaby/i3blocks-pomodoro.git ~/.config/i3blocks/i3blocks-pomodoro
```

Add the following lines into your ~/.config/i3blocks/config file:

```INI
[pomodoro]
command=~/.config/i3blocks/i3blocks-pomodoro/pomodoro
interval=1
```

# Usage

A left mouse button click on the pomodoro blocklet toggles pause.

A right mouse button click skips current pomodoro or break.

A middle mouse button click resets the timer.
