﻿# Serially

A REPL and tail for Serial Ports

![](Images\repl.gif)

    Serially: A REPL and tail for Serial Ports

    Format:
      serially [action] [port]
    [action]
      help: Show this message and exit
      tail: Tail the given port
      repl [default]: Open a CLI with the given port

    [port]
      A Windows COM port, e.g. COM1

    Examples:
      Open a REPL on COM1: serially COM1
               Equivalent: serially repl COM1
           Just tail COM2: serially tail COM2

## Serially.Core

Serially.Core is a pure .NET 5.0 library for serial communication. 

## Serially.App

Serially.App provides an a REPL (Real-Eval-Print Loop) for two-way communication with serial devices.

For the REPL, Basic ASCII escaping and mapping is provided. Currently supported special keys: 
    - Arrow Keys
    - Delete

Serially.App can also just tail the device i.e. for logging.

## NuGet


## License

Serially is a fork derivative work of OpenNETCF. Its license is provided in LICENSE.txt.