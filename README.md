# tiny-stack-vm

An interpreter for make.fun's tiny stack ISA v1, written for the
[Build a tiny stack virtual machine, 22 November 2026](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
bounty on make.fun.

![bounty](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)
![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/Irc-7/tiny-stack-vm/rank.svg)
![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/Irc-7/tiny-stack-vm/reward.svg)

`main.ts` reads every `/input/<id>/` (`program.bin`, `input.bin`) and writes
`/output/<id>/stdout.bin` and `/output/<id>/exit.txt`. Both directories can be
overridden with `MAKEFUN_INPUT_DIR` and `MAKEFUN_OUTPUT_DIR`; run it with `node main.ts`.
