# BSTestApps

Simple workspace with one projects that just loads BSManagedDocument. ARC and
non-ARC targets are provided (the ARC version just flips on -fobjc-arc when
compiling BSManagedDocument.m).

This serves two purposes:

1. It provides test applications as examples of using the class.
2. It provides a convenient place to put the unit tests.

This is in a separate branch so that projects that want to use the class as a
subrepasitory can opt to use the branch that only includes the class files not
the examples or the test scaffolding.
