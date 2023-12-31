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
> Default timeout is 10s, to ignore timeout, use flag `--no-timeout` \
> Example: `xreport "command" --no-timeout`
### Example command output report:
![image](https://github.com/GNU-Szmelc/xreport/assets/95081005/c39f43d7-7a7b-45ff-a921-4b868c454bdb)

### Upcoming features:
> More flags like `--verbose` \
> Optional wide spectrum hardware / software / firmware info logs \
> Optional screenshot flags (to attach a screenshot to that log) \
> Optional session mode based on [asciinema](https://asciinema.org/) to let user send entire re-playable terminal sessions 1:1 \
> Optional flags for user case description and contact information
