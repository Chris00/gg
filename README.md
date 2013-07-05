Gg — Basic types for computer graphics programming in OCaml
-------------------------------------------------------------------------------
Release %%VERSION%%

Gg is an OCaml module providing basic types for computer graphics
programming.

It defines types and functions for floats, vectors, points, sizes,
matrices, quaternions, axis-aligned boxes, colors, color spaces, and
raster data.

Gg is made of a single, independent, module and distributed under the
BSD3 license. 

Home page: http://erratique.ch/software/gg  
Contact: Daniel Bünzli `<daniel.buenzli at erratique.ch>`

## Installation

Gg can be installed with `opam`:

    opam install gg

Otherwise to install Gg you need at least:

    OCaml %%OCAMLVERSION%% %%PPDEPS%%

If you have `findlib`, it can be installed by typing :

    ocaml setup.ml -configure
    ocaml setup.ml -build 
    ocaml setup.ml -install

If you don't, `gg.mli` and `gg.ml` contain everything, the code, the
documentation and the license.  Install the dependencies and use the
sources the way you want.

## Documentation

The documentation and API reference is automatically generated by
`ocamldoc` from `gg.mli`. It can be consulted [online][1] and there
is a generated version in the `doc` directory of the distribution. 

[1]: http://erratique.ch/software/gg/doc/Gg


## Sample programs

Sample programs are located in the `test` directory of the
distribution. They can be built with:

    ocamlbuild test/tests.otarget

The resulting binaries are in `_build/test` :

- `test.native` tests the library, nothing should fail.