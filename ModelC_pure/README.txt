These codes simulate model C for a pure material (one order parameter and one thermal field), as described in the text. They are structured in modular form, and students an encouraged to build more complex codes using this structure. The file "manager.f" is the highest level of control, co-ordinating, so to speak, the sequence to calls to to solvers, initializations, etc. The module solver_mod.f90 contains the  solver routines. The module util_mod.f90 contains functions called upon to do various i/o.

To compile the codes into an executable, type: "make"
To run, type ./<name_of_executable>