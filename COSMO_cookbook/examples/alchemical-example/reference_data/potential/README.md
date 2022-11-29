Parameter files for an alchemical-compression potential for a set of 25 transition metal elements.

The potential contains a pair term that treats all atom pairs separately, an alchemically-compressed three-body potential (`n_al=4`) and a NN term built on top of the compressed 3-body features. 

The potential has been optimized including both energies and forces, (first 24000 energy-only structures and 100 forces, increasing up to 24000 energies and 1000 force-containing structures). 
The force weights have been tuned to get a good balance between energy and force errors (~9.7 meV/atom and 180 meV/Å MAE). 

