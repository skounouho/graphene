# Running the Graphene Waveload Example

![Image of the graphene system](system.jpg "Graphene")

- After downloading LAMMPS, compile LAMMPS with the MANYBODY package enabled.
- Run `in.lammps` with `CH.rebo` and `data.graphene_272C` in the same directory (or modify the filepaths in `in.lammps` appropriately).
- The dump file `dump.graphene` will save the atom IDs, position, velocity, and force on each timestep.
