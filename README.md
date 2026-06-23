# Alias-Menu-Linux

I built a small terminal launcher to avoid retyping long Linux paths like Unreal Engine’s executable.

It lets you save commands under simple names (e.g. unreal) and run them from a quick menu instead of typing full paths.

Aliases are stored in a local JSON file, so they persist across reboots, and it supports any single-line shell command, including env vars and directory switches.

It’s a lightweight Python TUI using subprocess, made just to reduce terminal friction on Linux.
