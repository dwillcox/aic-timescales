# Energy Generation Profile Comparison

This evaluates the energy generation rate for a MESA profile using the
Starkiller Microphysics ECSN network and compares to the MESA energy
generation rate.

To link in the data files from Starkiller Microphysics, define the
environment variable MICROPHYSICS_HOME pointing to the Microphysics
directory and run `setup.sh`.

To run the notebook, also follow the setup instructions in
`Microphysics/python_library/StarKiller/README.md` where the
Microphysics python bindings are compiled with `NETWORK_DIR=ECSN`.

Tested with Python 3 and the development branch of Microphysics.
