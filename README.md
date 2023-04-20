### Installing required software

- install WaveForms following the getting started guide:
  - [WaveForms Getting Started Guide](https://digilent.com/reference/software/waveforms/waveforms-3/getting-started-guide)

- install Visual Studio Code following the platform-specific instructions below:
  - [macOS](https://code.visualstudio.com/docs/setup/mac)
  - [Linux](https://code.visualstudio.com/docs/setup/linux)
  - [Windows](https://code.visualstudio.com/docs/setup/windows)

- install the following Visual Studio Code extensions:
  - [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
  - [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
  - [Micromamba](https://marketplace.visualstudio.com/items?itemName=corker.vscode-micromamba)

- download this repository by cloning it using git or by downloading and unzipping [waveforms-notebooks-master.zip](https://github.com/pavel-demin/waveforms-notebooks/archive/refs/heads/master.zip)

- open waveforms-notebooks folder in Visual Studio Code
  - from the "File" menu select "Open Folder"
  - in the "Open Folder" dialog select waveforms-notebooks folder and click "Open"

- create micromamba environment
  - from the "View” menu select "Command Palette”
  - type "micromamba create environment”

### Working with notebooks

- open one of the notebooks in Visual Studio Code

- make sure the micromamba environment called "default" is selected in the kernel/environment selector in the top right corner of the notebook view

- run the code cells one by one by clicking the play icon in the top left corner of each cell
