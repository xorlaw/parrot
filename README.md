# parrot

 Parrot is an extremely simple and small tool to prevent spelling mistakes in commands.

## [01] What is Parrot?

 As said before, Parrot is an extremely simple, small tool that prevents spelling mistakes in commands. All it does is wait for a user to give it a command by including `prt` at the start of their command,
 then it will echo the command back to them and ensure they want to continue. Thats it.

## [02] Who is it for?

Anyone that runs commands that have a big downside if spelt wrong, but mainly for people build OSes like Arch, Gentoo, or Artix base. I have installed all of them, and I know how painful it is to get 30 minutes
into an installation to realise you made a spelling mistake early on that now cannot be reverted, like with mounting. It could also be used for formatting partitions to ensure you don't accidentally destroy
data on a disk.

## [03] How do I use it?

As Parrot is still in early development and I am still learning about Shell scripting, you can download the `prt.sh` file, make it executable with `chmod +x prt.sh`, then running `prt [command]` in the same
directory as the SH file. For installing operating systems, move it to the Home or Root directory (badly organized, I know) so you can use the commands there as most installlation commands most likely wont
work in a subdirectory. Or, you could wait until I find out how to add SH apps to PATH.

## [04] Contributing, configuring, etc.

Since Parrot is a TINY shell script (34 lines as of version 1.0), configuring it is very easy. I added in a lot of code comments to try and give people an idea of the flow of the program and what it actually does.
There is no config file for Parrot as it would add clutter and would in general just be bloat. If you find a bug you want to fix, add a new feature, anything like that, open a pull request.

## [05] Licensing

See [LICENSE](LICENSE.md)
