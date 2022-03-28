# Collection of Useful Mac Information

## Mac First-Time System Set Up and Configuration
- Install these programs

   -- Chrome, Slack
   
   -- Xquartz, Aquamacs
   
   -- Homebrew
   
   -- Xcode and Command Line Tools (via the command: sudo xcode-select --install; location: /Library/Developer/CommandLineTools
   
   -- SVN command line tools (no longer provided by Xcode) via Homebrew with command: brew install svn)
   
   -- Mac Office Suite
   
   -- Windows Office Suite
- Alter Shell
  -- For bash shell: chsh -s /bin/bash

## Command Line Tips  
- `file` command: provides information as to 32-bit or 64-bit for executables  
- `lipo -info` command: gives information as to 32-bit or 64-bit for libraries  
- `ulimit -n 9999` command: login as sudo in order to make the read file limit 9999 (and exceed standardly imposed file read limitation)

## Useful Websites
- HomeBrew directory location: /usr/local/Cellar
- Relevant website: HPC for Macs: http://hpc.sourceforge.net/

## Python Packages
- astropy, scipy
- Tables (e.g., pip install --user tables)
- Plotly
- h5py
- healpy (conda config --add channels conda-forge; conda install healpy)
- jupyterlab, volia
- vaex
- 
