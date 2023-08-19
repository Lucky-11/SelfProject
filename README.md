# SelfProject
Contains a self project which i have made using verilog. The project is Asynchronous FIFO


In asynchronous FIFO, data read and write operations use different clock frequencies. Since write
and read clocks are not synchronized, it is referred to as asynchronous FIFO. Usually, these are used
in systems where data need to pass from one clock domain to another which is generally termed as
‘clock domain crossing’.
Efforts to synchronize multiple signals from one clock domain to a new clock domain, ensuring the
synchronization of all these signals in the new domain, has proven to be problematic. In designs,
First-In-First-Out (FIFO) structures are used in designs to securely transfer multi-bit data chunks from
one clock domain to other. These data chunks are inserted into a FIFO buffer memory array through
control signals in one clock domain, and the removal of data chunks occurs through another port of
the same FIFO buffer memory array using control signals from a different clock domain.
The challenges associated with FIFO design arise primarily from devising the FIFO pointers and
identifying a dependable method for ascertaining the "full" and "empty" status of the FIFO.
