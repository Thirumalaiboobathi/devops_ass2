args: ["--vm", "1", "--vm-bytes", "128M", "--vm-hang", "1"]
This runs a memory stress test using the stress command with the following options:

Arg	Meaning
--vm 1	Run 1 memory-hungry worker (spins up 1 process that uses memory)
--vm-bytes 128M	Each worker tries to allocate 128 MB memory
--vm-hang 1	Keep memory allocated for a long time (don't immediately release it)

