# snippets from .bashrc files

**Colorized and formatted prompt for client machines:**
```bash
if [ "$color_prompt" = yes ]; then
    PS1='${debian_chroot:+($debian_chroot)}\[\033[01;38;5;2m\]\u\[\033[01;38;5;2m\]@\[\033[01;38;5;2m\]\h\[\033[00m\]   \[\033[01;38;5;26m\]\w\[\033[01;38;5;137m\]\n\[\033[01;38;5;15m\]> \[\033[00m\] '
else
    PS1='${debian_chroot:+($debian_chroot)}\[\033[01;38;5;2m\]\u\[\033[01;38;5;2m\]@\[\033[01;38;5;2m\]\h\[\033[00m\]   \[\033[01;38;5;26m\]\w\[\033[01;38;5;137m\]\n\[\033[01;38;5;15m\]> \[\033[00m\] '
fi
```

**Colorized and formatted prompt for ansible:**
```bash
if [ "$color_prompt" = yes ]; then
    PS1='${debian_chroot:+($debian_chroot)}\[\033[01;38;5;11m\]\u\[\033[01;38;5;11m\]@\[\033[01;38;5;11m\]\h\[\033[00m\]   \[\033[01;38;5;26m\]\w\[\033[01;38;5;137m\]\n\[\033[01;38;5;15m\]> \[\033[00m\] '
else
    PS1='${debian_chroot:+($debian_chroot)}\[\033[01;38;5;11m\]\u\[\033[01;38;5;11m\]@\[\033[01;38;5;11m\]\h\[\033[00m\]   \[\033[01;38;5;26m\]\w\[\033[01;38;5;137m\]\n\[\033[01;38;5;15m\]> \[\033[00m\] '
fi
```

**Colorized and formatted prompt for unifi-controller:**
```bash
if [ "$color_prompt" = yes ]; then
    PS1='${debian_chroot:+($debian_chroot)}\[\033[01;38;5;62m\]\u\[\033[01;38;5;62m\]@\[\033[01;38;5;62m\]\h\[\033[00m\]   \[\033[01;38;5;87m\]\w\[\033[01;38;5;137m\]\n\[\033[01;38;5;15m\]> \[\033[00m\] '
else
    PS1='${debian_chroot:+($debian_chroot)}\[\033[01;38;5;62m\]\u\[\033[01;38;5;62m\]@\[\033[01;38;5;62m\]\h\[\033[00m\]   \[\033[01;38;5;87m\]\w\[\033[01;38;5;137m\]\n\[\033[01;38;5;15m\]> \[\033[00m\] '
fi
```