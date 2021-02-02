C2RTL is a high-level synthesis (HLS) tool that generates verilog RTL from C code. It's primarily designed for generating RTL code for FIB lookup and packet classification algorithms. C2RTL is a GCC plugin.

License
==========
Copyright (c) 2020-2021 MD Iftakharul Islam (Tamim) <tamim@csebuet.org>.
All rights reserved.

Platform
==========
Linux.

Requirements:
============= 
GCC need to be installed on the system

* Build:

`make`

* Run:

`make cptrie_ip6`

It generates `top.v` and `top_tb.v` from `tests/cptrie_ip6.c`.

`make poptrie_ip6`

It generates `top.v` and `top_tb.v` from `tests/poptrie_ip6.c`.

`make sail_ip6`

It generates `top.v` and `top_tb.v` from `tests/sail_ip6.c`.

`make cutsplit`

It generates `top.v` and `top_tb.v` from `tests/cutsplit.c`.
