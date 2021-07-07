# Collection of Useful Mac Information

## Command Line Tips  
- `file` command: provides information as to 32-bit or 64-bit for executables  
- `lipo -info` command: gives information as to 32-bit or 64-bit for libraries  
- `ulimit -n 9999` command: login as sudo in order to make the read file limit 9999 (and exceed standardly imposed file read limitation)

## Useful Websites
- HomeBrew directory location: /usr/local/Cellar
- Relevant website: HPC for Macs: http://hpc.sourceforge.net/

## Mac System Set-Up and Configuration
- Install Homebrew
- Install Xcode
- Install command line tools via the command: sudo xcode-select --install
  -- These should be located here: /Library/Developer/CommandLineTools
- Install SVN command line tools (no longer provided by Xcode) via Homebrew with command: brew install svn)


## Python Packages
- Tables (e.g., pip install --user tables)
- Plotly
- h5py
- healpy (conda config --add channels conda-forge; conda install healpy)
- jupyterlab
- vaex
- 
