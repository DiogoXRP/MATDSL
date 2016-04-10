# MATDSL

This project shall define a DSL able to
specify matrix computations by considering
variables as matrices.
The project shall develop a framework that
extracts the DSL code (e.g., between /*
@MATDSL … */) from Java programs,
process it, generate the Java code
functionally equivalent, and include this
code in the Java program just after the DSL
code. The operations shall include: *
(multiplication), + (addition), ‘ (transpose),
etc.
The DSL shall allow the possibility to express
expressions using part of the matrices, such
as:
C(0:99) = D(0:99)+A(0:99);

