# xreport
Simple tool to send automated output logs via Discord webhook
### Installation:
> Paste `xreport` file into any valid `$PATH` on your system, for example `/bin` \
> Run `chmod +x /bin/xreport` to make it executable

### Usage:
> Run any command with `xreport` prefix to send the command output + basic info via webhook \
> Like `xreport {command}` \
> Longer commands can be combined and joined if everytghing is enclosed within `""` \
> For example `xreport "echo $PATH && ls"` or `xreport "ls | figlet && cd Desktop && ls -a"`

### Extra notes:
> Default timeout is 10s, to disable timeout entirely, use optional flag `--no-timeout` \
> For example: `xreport "command" --no-timeout`
### Example command output report:
![image](https://github.com/GNU-Szmelc/xreport/assets/95081005/c39f43d7-7a7b-45ff-a921-4b868c454bdb)
