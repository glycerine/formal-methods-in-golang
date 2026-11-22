Formal methods in Golang (Go)
========================

# g3

g3 is a complete port of Z3 (4.7.1 + Duality and Craig Interpolation) SMT solver. This
is an automated theorem prover.

https://github.com/glycerine/g3


# GoIvy 

GoIvy is a port of the Ivy formal verfication language by Ken McMillan and Oded Padon et al.

https://github.com/glycerine/ivy


# ABC in Go

GoIvy contains a port to Go of the C hardware verification suite ABC.

https://github.com/glycerine/ivy/tree/master/pyivy/ivy/submodules/abc/abcgo

original: https://github.com/berkeley-abc/abc https://github.com/berkeley-abc/abc-zz 

# Apalache-Go

Apalache-Go is a port to Go of the symbolic model checker Apalache.

https://github.com/glycerine/apalache-go

The original (in scala) is: https://github.com/apalache-mc/apalache

Like Ivy, symbolic model checkers can handle infinite state systems. The traditional TLC
model checker checks finite (small) systems.


# Quint-Go

Quint-Go https://github.com/glycerine/quint-go is a port of the Quint verification language to Go.

Original: https://quint.sh/ and https://github.com/quint-co/quint

Quint is a modern verification language aimed at being more familiar to programmers.
Quint compiles to TLA+. Quint uses Apalache (Quint-Go uses Apalache-Go).

For completeness, I’ll also mention tlago, which is my previously announced


# TLA-Go: TLA+ and TLC model checker in Go 

The original TLA+ toolbox and was in Java.

https://github.com/glycerine/tlago

This is a full port to Go of the TLC model checker and the TLA+ toolkit.

-------
Jason E. Aten, Ph.D.
