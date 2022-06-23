# CoCoSim Helper

## How to use
Execute `./ccsh run` to execute the run command. The first time the run command
is executed it will:

1. Install dependencies
2. Clone all the CoCoSim related projects from git
3. Build all the CoCoSim related projects
4. Run a CoCoSim example

The subsecuent times the run command is executed it will just run the CoCoSim
example. The other steps can be repeated executing other commands. Execute
`./ccsh --help` and read `./config` for more information.

## dependencies
* pciutils
* lsb-release
* git
