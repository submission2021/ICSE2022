This directory contains the molecular watchdog timer subject tests.

For the specification tests (S), 
Input-S.csv is used to specfic the concrete input values.
InputIDs-S.csv maps the concrete inputs to abstract tests.
Tests-S.csv specifies abstract test properties as well as which type of test
(1 for functional, 2 for metamorphic, 3 for tests requiring recursive PCLTL evaluation)

For the invariant tests (F, IN, F+IN, INwRC, IR, F+IN+IR),
All use the same input file, Input-INVAR.csv, since these tests have no constraints on the input.
Each test suite does require its own InputIDs-*.csv to map the inputs to the abstrast tests.
Each test suite has its own Tests-*.csv to define the properties the invariants stated. 
All invaraint tests are functional or internal tests in our study.