# eval-tweaked-cc-plus
A fork of eval.tweaked.cc to add extra features that wouldn't fit in eval.tweaked.cc.

(Note: There's yet to be a public instance of this running.)

Take screenshots of ComputerCraft code

## Usage
```bash
$ curl -d '{"luaCode":"print("hello_world")", "termX": 51, "termY":19}' [url] | display
```

![A screenshot in ComputerCraft saying 'Just testing some code!'](docs/example.png)

## Limitations
 - Computers can run for at most 10 seconds.
 - There is some rate limiting on the number of requests one can send at once.
