# YARD QED

[Website](http://github.com/rubyworks/yard-qed) |
[Source Code](http://github.com/rubyworls/yard-qed) |
[Mailing List](http://groups.google.com/group/rubyworks-mailinglist) |
[IRC](#rubyworks)


## Description

Automatically add QED docs to YARD docs without need to create
any intermediary files.


## Usage

As with most YARD plugins.

    $ yardoc --plugin qed

This will look for one of the default `qed`, `demo` or `spec` directories,
and use the files located there.


## Limitations

* It is assume all your QED docs are in one format. Mixing and matching
between RDoc and Markdown might cause some rendering issues.

* There is currently no way to set
the location or file globs to anything else --patches welcome.


## Copying

Copyright (c) 2011 Rubyworks. All rights reserved.

YARD QED is distributable in accordance with the terms of
the *BSD-2-Clause* license.

See LICENSE.txt for details.
