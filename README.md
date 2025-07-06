# ghidra_cfg_scripts
Ghidra Graph Scripts for automation.

This repo includes a script which me and Radu Iulian made a while back.
I am modifying the scripts in order to make them quickly usable and to separate work.

## Requirements
* Ghidra
* The following Python packages
  ```
  pyghidra
  networkx
  pydot
  ```

## Usage:
Virtual Environments are recommended to use these scripts.
Simply make a virtual environment using:

```python -m venv <venv_name>```

Then use:
```source <venv_name>/bin/activate```

Install the requirements in the venv if you did not do so, and then you may run the scripts.
```python icfg_ghidra_dump.py <executable>```

## Attention:
* Pyghidra needs the Ghidra Installation Directory in a environment variable. In these scripts, we hardcoded the environment variable to our needs. Change it according to your setup in order for the script to run.
* For the DOT Archives, just concatenate the three parts into a single zip archive by using `cat` or `copy` 
