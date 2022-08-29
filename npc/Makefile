all:
	sim

sim:
	$(call git_commit, "sim RTL") # DO NOT REMOVE THIS LINE!!!
	verilator -Wall -cc --trace --exe --build csrc/main.cpp vsrc/top.v

include ../Makefile
