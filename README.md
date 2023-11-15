# isolating_bioelectrical_current

This code cleans up a bioelectric current recorded during a voltage-clamp time series.

START WITH:
The jupyter notebook named 'leak_subtraction_TUTORIAL.ipynb' walks through the analysis and context.

MORE:
The python script named 'leak_subtraction_BATCH.py' performs the analysis described in
the jupyter notebook, but from the command line using positional arguments. There are helpful
comments that check the data if something is askew.

Example Command:

"$ python leak_subtraction_BATCH.py vc_file Cm ljp"

   vc_file -- is the voltage clamp time series file.
   Cm -- is the cell capacitance
   ljp -- is the liquid junction potential
