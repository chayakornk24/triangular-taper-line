This folder contains simulation files for the
triangular taper transmission line.

Two types of simulations are provided.

1. Netlist Simulation (Ideal Transmission Line Model)
   Netlist simulations are used as an ideal
   electrical reference without geometry effects.

   - 10 sections, 50 to 100 ohm
     simulation/netlist/10_sections_50to100/

   - 20 sections, 50 to 100 to 50 ohm
     simulation/netlist/20_sections_50to100to50/

   The 20-section netlist simulation is used
   as the reference for comparison with
   geometry-based simulations.

2. Geometry Simulation (EM Model)
   Geometry simulations include electromagnetic
   effects and are used to study the impact
   of physical layout and boundary conditions.

   - Original box cell
     simulation/geometry/original_box/

   - Expanded box cell
     simulation/geometry/expanded_box/

3. Simulation Comparison
   The 20-section netlist simulation is compared
   with both geometry simulation configurations
   to evaluate the effects of geometry and
   simulation boundary.

   - simulation/comparison/

The expanded box cell geometry simulation
was used for the final comparison with
measurement results.
