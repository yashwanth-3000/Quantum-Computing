# Quantum computing labs

`originals/` contains the seven imported notebooks with original names. Embedded credentials are replaced with environment-variable access and saved outputs are cleared. Local source files are unchanged.

`updated/` contains seven concept-named, commented revisions. Lab 2 and Untitled are duplicate source experiments. Lab 7 is an empty documented placeholder.

Use Python with qiskit, qiskit-aer, numpy, matplotlib, pylatexenc, and IPython. Run updated notebooks top to bottom; all experiments run locally without hardware submissions.

The manifest records observed filesystem creation timestamps in Asia/Kolkata and original source hashes. Filesystem birth dates are provenance, not proof that a Git commit occurred then. Historical import commits can use these dates; revisions were prepared on 2026-11-06.

Validation: all six nonempty updated notebooks execute successfully in the local Qiskit environment. The seventh is a markdown-only placeholder. Bit/phase repetition recovery is checked at all three locations, and teleportation and Shor examples verify unit recovery fidelity. Source originals are preserved as historical experiments and may contain the errors described in the revisions.

## Deutsch–Jozsa and Simon

`updated/dj-algo.ipynb` and `updated/simons-algo.ipynb` build Uf from an editable three-bit input table named `fx`. Edit the table and run all cells. DJ requires a constant or balanced function; Simon requires a two-to-one function with a common nonzero XOR period. The current DJ example is constant zero. Simon uses secret 110. Oracle checks covered all 72 promised DJ tables and examples for all seven nonzero Simon secrets.
