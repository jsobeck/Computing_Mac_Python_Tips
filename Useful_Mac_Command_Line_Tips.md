# Collection of Useful Mac Information

## Mac First-Time System Set Up and Configuration
### Essential Software/Code 
- Chrome
- Slack
- Xquartz
- Aquamacs
- Homebrew Mac Package Manager
   - Rely on for installation of basic utilities such as sftp, wget, svn (and associated command line tools),...
   - Installation command: `homebrew % /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
   - Homebew package installation (sample) command: `brew install svn`
   - HomeBrew directory location: /opt/homebrew (formerly: /usr/local/Cellar)
- Xcode and Command Line Tools
  - Installation command: `sudo xcode-select --install`
  - Xcode directory location: /Library/Developer/CommandLineTools
- Mac Office Suite
- Windows Office Suite
- Java
- [MacTex](https://tug.org/mactex/mactex-download.html)
  
### Astronomy-Related Software
- [ds9](https://sites.google.com/cfa.harvard.edu/saoimageds9)
- [QFitsView](https://www.mpe.mpg.de/~ott/QFitsView/)
- [TopCat](https://www.star.bris.ac.uk/~mbt/topcat/)
- CFITSIO
   
### Shell Modification 
- Default Mac shell is z-shell (zsh; with shell specifications .zprofile)
- To change to bash shell: `chsh -s /bin/bash`

## Command Line Tips  
- `file` command: provides information as to 32-bit or 64-bit for executables  
- `lipo -info` command: gives information as to 32-bit or 64-bit for libraries  
- `ulimit -n 9999` command: login as sudo in order to make the read file limit 9999 (and exceed standardly imposed file read limitation)

## Useful Websites
- HPC for Macs: http://hpc.sourceforge.net/

## Python and Python Packages
- Python (current version 3.12)
- Numpy
- Scipy
- Astropy (specutils)
- Pandas
- Jupyter
  - jupyter-lab (conda installation command: `conda install -c conda-forge jupyterlab`)
  - ipywidgets
  - voila
- Tables (e.g., pip install --user tables)
- Plotting/Visualization Programs: Bokeh, Plotly, Seaborn
- Data Ingestion/Storage: h5py, asdf
- healpy (conda config --add channels conda-forge; conda install healpy)
- vaex
- pytest
- pyarrow, apache spark
- pdflatex, pandoc

## Command Line Interface (CLI) tools
- GitHub CLI (via homebrew: `brew install gh`)
     
## The Cloud

