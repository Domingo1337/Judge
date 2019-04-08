# Judge the Proof Checker
`Judge` reads proofs of logic formulas written in natural deduction system and validates them.

## Requirements
* OCaml
* ocamlbuild

## Building
`ocamlbuild judge.native`  
should create directory _build and a link to executable `judge.native`.  
To clean the built app simply use `ocamlbuild -clean`.  

## Usage
`Judge` reads from standard input, so example command would look like this:  
`./judge.native < example.pf`  


