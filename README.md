# Air::Plugin::Hilite

## SYNOPSIS

```raku
use Air::Functional :BASE;
use Air::Base;
use Air::Plugin::Hilite;

sub SITE is export {
    site :register[Hilite.new],
        index
            main
                hilite 'say "yo, baby!"';
}
```

DESCRIPTION
===========

Air::Plugin::Hilite is a plugin for websites authored in the raku [Air](https://github.com/librasteve/Air) module

It acts as a Receptacle (fancy word for socket) for the raku [Hilite](https://github.com/librasteve/Hilite) module and enables it for the Air eco-system.

AUTHOR
======

librasteve <librasteve@furnival.net>

COPYRIGHT AND LICENSE
=====================

Copyright 2025 Henley Cloud Consulting Ltd.

This library is free software; you can redistribute it and/or modify it under the Artistic License 2.0.

