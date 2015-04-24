The main aim of the project is to create a lightweight and very fast [python](http://www.python.org) interpreter, that could be embedded in any compiled application. This will be achieved through **transformation** of the original python source code into [flat assembler](http://flatassembler.net) (fasm) sources. For the transformation it is used the [TXL transformation system](http://www.txl.ca), that allows to define a set of the rules to transform C-code into fasm-code.


The fython is purposed to be fully binary compatible to python but much smaller and faster.