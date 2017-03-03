
# Fold Repository

All standard packages for the Fold programming language are destributed with
[OPAM](https://opam.ocaml.org) and are managed by this repository.


## Packages

- [x] `pratt` – Pratt parser library used in the implementation of the language.
- [ ] `fold` – Main package with the compiler for the language.
- [ ] `pure` – Minimal modulear base library.
- [ ] `elements` – Unified standard library.
- [ ] `ppx_monad` – Syntax extensions for monadic computations.


## Installation

To install a Fold package first add the repository to OPAM:

```
$ opam remote add -k git fold https://github.com/fold-lang/repository
```

Now `opam` can be used to install Fold packages:

```
$ opam install pratt
```

