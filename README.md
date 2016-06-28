Name
====

opsboy - Automating deployment

Table of Contents
=================

* [Name](#name)
* [Description](#description)
* [Copyright & License](#copyright--license)

Description
===========

This is a rule-based script generator for system environment incremental deployment.

    # on the developer host machine
    ./opsboy samples/openresty-tester.ob -o openresty-tester.pl

    # on the target machine
    ./openresty-test.pl make t-ngx_lua tv-ngx_srcache --git-pull force=1

Installation on the Developer Host Machine

    $ sudo cpan Pegex File::Copy

    This is not required on the target machine though. The target
    machine only needs to have perl 5 installed.

Copyright & License
===================

The bundle itself is licensed under the 2-clause BSD license.

Copyright (c) 2012-2016, Yichun "agentzh" Zhang (章亦春) <agentzh@gmail.com>, CloudFlare Inc.

This module is licensed under the terms of the BSD license.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are
met:

* Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS
IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED
TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A
PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED
TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR
PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF
LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


