tmux_away
==========

irssi script to set away/unaway based on tmux status

This is most useful when combined with something like the AwayMail
plugin:

https://github.com/alanhamlett/AwayMail-Irssi-Plugin

### Installation
```
git clone https://github.com/jcvernaleo/tmux_away
cp tmux_away/tmux_away.pl ~/.irssi/scripts/
ln -s ~/.irssi/scripts/tmux_away.pl ~/.irssi/scripts/tmux_away.pl
```

### Usage

Make sure irssi is running inside a tmux session.

```
/load tmux_away.pl
```

There are a few config options, but the defaults should be fine for
most uses.

```
/set tmux_away_active ON/OFF/TOGGLE
/set tmux_away_repeat <integer>
/set tmux_away_message <string>
/set tmux_away_window <string>
/set tmux_away_nick <string>
```

### Maintainer
John C. Vernaleo <john@netpurgatory.com>

### License
Released under the GPL v2 (as the original tmux_away was).

