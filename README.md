# dummy_lkm
This is a dummy Loadable Kernel Module, just for testing and learning purposes.

Compile:
`KSRC=/home/andrei/kernel/src make`

Adjust your `KSRC` accordingly.

Load:
`insmod Hello.ko param_var=123`

`123` is an arbitrary number.

Remove:
`rmmod Hello`

Check dmesg for the messages.
