# Linux Process Managment
## Outline
- init
- fork/exec
- ps
- kill
- fg/bg/jobs

## Starting/Stopping
start a process
[command]

replace current process with another process:
exec [command]

see processes in your shell:
ps f

## Killing Processes
kill -15 [pid]     <- sends sigterm
kill     [pid]     <- also sends sigterm
kill -2  [pid]     <- sends sigint
kill -1  [pid]     <- sends sighup
kill -9  [pid]     <- sends sigkill

suspend process running in foreground:
ctrl-z

list jobs table:
jobs

send stopped process to background:
bg
bg [jobnum]

bring process to foreground:
