<div align="center">
<h1>reptAUR 🦖</h1>
<p>REPosiTory/AUR package manager</p>
<p><code>reptaur</code> is a simple <code>pacman</code>/AUR wrapper written in Bash</p>

<a href='#'><img src="https://img.shields.io/badge/Made%20with-Bash-&?style=flat-square&labelColor=232329&color=46b152&logo=gnu-bash"/></a>
<a href='#'><img src="https://img.shields.io/badge/Maintained%3F-Yes-green.svg?style=flat-square&labelColor=232329&color=8e7dbe"></img></a>
<a href="https://discord.gg/W4mQqNnfSq">
<img src="https://discordapp.com/api/guilds/913584348937207839/widget.png?style=shield"/></a>
</div>

## Why?
#### Q: Why write it in Bash?
A: This is exactly the type of thing Bash was intended for. Automation of the AUR is a well suited use-case for a simple shell script. Bash is widely available as well as the coreutils, making it an obvious choice. It's more than performant enough for the task since Bash excels in text manipulation and bulk of the process is relying on your network connection

#### Q: Why write it at all, when more featured alternatives like `yay` and `paru` already exists?
A: Exactly that.. To me `yay`, `paru` and the likes are a bit too featured. Why install a compiler or blindly execute some pre-compiled binary if you don't need to? The purpose of this project is much more simple. It needs to handle the essential functions one would expect when interacting with the AUR via some automation and nothing more. `reptaur` is portable, dead simple to use and proficient at what it does

## Acquisition
Download
`git clone https://github.com/wick3dr0se/reptaur; cd reptaur`

## Execution
`bash reptaur` or `./reptaur`

## Usage
```
reptaur [OPERATION] [PACKAGE]
[sync, -s, --sync]
<info, -i, --info> [PACKAGE]
<query, -q, --query> <PACKAGE>
<install, -I, --install> <PACKAGE>
<remove, -r, --remove> <PACKAGE>
```
