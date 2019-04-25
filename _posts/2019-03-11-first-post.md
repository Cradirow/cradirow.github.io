---
title: "[TroubleShooting] permission denied when you installing npm services"
date: 2019-03-13 14:31:28 -0400
categories: npm troubleshooting
---
When you get an error about 'permission denied', there is a simple way to solve it.

1. Use `sudo` command before your install command.

2. Set `--unsafe-perm` command flag to true.

3. Use `--allow-root` command.

for example,
`sudo npm i (module) --unsafe-perm=true --allow-root`

those command will help your installation.
