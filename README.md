# Eury

Eury is the cutting-edge rocket launching program used at the International
Aerospace Center (IAC). It has various components managing different tasks
involved in the processing of launching a rocket, allowing anyone to schedule
launches, inspect rockets, time processes, remotely boost engines, and more.

## Features

- All-in-one bundle to administrate rocket launches
- Intuitive, clutter-free graphical interface
- Remote module inspection
- Flawless error-handling

## Installation

Have a rocket at home? You can use Eury to launch it too!

### Prerequisites

|               Item               |       Version        |
| :------------------------------: | :------------------: |
|     Rocket Operating System      |    15.6 or later     |
|        [Cann Manager][1]         |     3.0 or later     |
| [Ros development environment][2] | 2.6 or later; or 3.x |
|           [`rwdgt`][3]           |         Any          |
|            [Physx][4]            |     1.6 or later     |
|       [`time-precise`][5]        |         Any          |

[1]: #link01
[2]: #link02
[3]: #link03
[4]: #link04
[5]: #link05

### Download

To download, you can clone this repository with

```shell
git clone https://github.com/better-readme/eury.git
```

or download the latest source code [here](https://github.com/better-readme/eury/releases)
(be sure to extract it to a directory).

Then, in the command line, navigate to the directory where the source code is
stored using `cd`. We will compile Eury next.

### Compile & Install

See the `INSTALL` file for detailed installation instructions, including options
and features to enable. The basic installation goes as follows:

```shell
ros configure   # Configure Eury to your preferences
ros build       # Build (compile) the software
op ros install  # Install it
```

## License

Copyright (C) [International Aerospace Center](#iacwebsite). All Rights Reserved.

Licensed under the International Aerospace Center Open Software License. Please
refer to the terms in the `LICENSE` file included in the repository.

<!--

NOTE

This is an example README written by The Better README Project.

The Better README Project's home is found at https://betterreadme.tech

Items mentioned in this file such as the International Aerospace Center, the
Rocket Operating System, Cann Manager, Ros, rwdgt, etc., as well as the
compilation and installation processes shown are all work of imagination; they
don't actually exist.

The license information is also for demonstrational purposes and does NOT apply
to this work.

-->
