# Collection of Useful Mac Information

## Mac First-Time System Set Up and Configuration
- Install these programs

   - Chrome, Slack
   
   - Xquartz, Aquamacs
   
   - Homebrew (Mac Package Manager; employ for installation of basic utilities such as sftp, wget, svn and associated command line tools,...)
     - sample command: `brew install svn'
   
   -- Anaconda/mamba and python
   
   -- Xcode and Command Line Tools (via the command: `sudo xcode-select --install`; location: /Library/Developer/CommandLineTools
   
   
   -- Mac Office Suite
   
   -- Windows Office Suite
   
   -- Java
   
   -- MacTex (https://tug.org/mactex/mactex-download.html)
   
- Alter shell (zsh vs. bash)

  -- To change to bash shell: `chsh -s /bin/bash`

## Command Line Tips  
- `file` command: provides information as to 32-bit or 64-bit for executables  
- `lipo -info` command: gives information as to 32-bit or 64-bit for libraries  
- `ulimit -n 9999` command: login as sudo in order to make the read file limit 9999 (and exceed standardly imposed file read limitation)

## Useful Websites
- HPC for Macs: http://hpc.sourceforge.net/

## System Information
- HomeBrew directory location: /opt/homebrew (old location: /usr/local/Cellar)

## Python Packages
- numpy, scipy
- Astropy (specutils)
- Jupyter: jupyter-lab, ipywidgets, voila
- Tables (e.g., pip install --user tables)
- Plotting/Visualization Programs: Bokeh, Plotly, Seaborn
- Data Ingestion/Storage: h5py
- healpy (conda config --add channels conda-forge; conda install healpy)
- vaex
- pytest
- pyarrow, apache spark

## Astronomy-Related Software
- ds9
- QFitsView
- CFITSIO
- TopCat

