<p align="left">
<a href="#logo" name="logo"><img src="https://raw.githubusercontent.com/bionanoimaging/UC2-GIT/master/IMAGES/UC2_logo_text.png" width="400"></a>
</p>


# ImSwitch + UC2 Cheatsheet
---


## Prerequirements

To simplify life, we host a dropbox folder containing all the necessary drivers and Software pieces for this workshop. It will run on a Windows 10 64 Bit system:

<p align="left">
<a href="https://www.dropbox.com/sh/pea63wifrq3edsl/AAChzXEGA55uUt2Kjxxfk_Dka?dl=0" name="logo"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/78/Dropbox_Icon.svg/86px-Dropbox_Icon.svg.png" width="40"></a>
</p>

### List of files

- **Arduino IDE:** `arduino-1.8.18-windows.exe`
- **ESP32 USB driver:** `CH341SER.exe`
- **ImSwitch (UC2 version)**: `ImSwitch-master.zip`(2022-05-05)
- **ImSwitch Configs (UC2 version)**: `ImSwitchConfig-master.zip`(2022-05-05)
- **NanoImagingPack (Python library)** `nanoimagingpack-master.zip`
- **Anaconda PYthon distro**: `Anaconda3-2021.11-Windows-x86_64.exe`
- **Necessary ESP32 libraries** `BenesArduinoLibraries-master.zip`
- **optional: Teamviewer** `TeamViewer_Setup_x64`

*for the Thorcam:*
- **optional: ThorCam drivers**: `DCx_Camera_Interfaces_2018_09.zip`
- **optional: ThorCam drivers**: `Thorlabs Scientific Imaging Software x64.exe`
- **optional: ThorCam drivers python wrappers**: `devwraps-master.zip`

*if you want to stay up to date*
- **optional: Github Desktop**: `Git-2.36.0-64-bit.exe`
- **optional: Github Desktop**: `GitHubDesktopSetup-x64.exe`


### Installation

**Download and Extract**

1. Download the Software package from [Dropbox](https://www.dropbox.com/sh/pea63wifrq3edsl/AAChzXEGA55uUt2Kjxxfk_Dka?dl=0) (see above)
2. Install Anaconda (*Important:* When you're asked to add Anaconda to the `PATH` environment, say `YES`!)
3. Install the Arduino IDE (including all drivers if you are asked during the installation)
4. Install the CH340 USB Serial driver
5. *Optional* Install ThorCam drivers (`DCx_Camera_Interfaces_2018_09.zip` and `Thorlabs Scientific Imaging Software x64.exe`)
6. *Optional* Extract `devwraps-master.zip` to `/User/$USER$/Documents/devwraps-master` (`$USER$` is your username)
7. Extract `nanoimagingpack-master.zip` to `/User/$USER$/Documents/nanoimagingpack-master` (alternative: clone from [GitLab](https://gitlab.com/bionanoimaging/nanoimagingpack))
8. Extract `ImSwitch.zip` to `/User/$USER$/Documents/ImSwitch` (alternative: clone from [GitHub](https://github.com/beniroquai/ImSwitch))
9. Extract `ImSwitchConfig.zip` to `/User/$USER$/Documents/ImSwitchConfig` (clone or download from [GitHub](https://github.com/beniroquai/ImSwitchConfig))
10. Extract `BenesArduinoLibraries-master.zip` to `/User/$USER$/Documents/Aduino/libraries`

- *Optional*: Install Visual Studio Code + the Python plugin => setup the Visual studio code IDE for Python

**Install ImSwitch for UC2**

Open the command prompt (`Win + R`, type `CMD`, hit enter) and do the following:

**Create a conda environment:**

```
conda create -n imswitch python=3.9 -y
conda activate imswitch
```

#### Install Thorcam python drivers
1. `cd /User/$USER$/Documents/devwraps-master`
2. `pip install devwraps-0.1.26-cp39-cp39-win_amd64.whl`
or
2. `pip install devwraps-0.1.26-cp38-cp38-win_amd64.whl` (if you run python 3.8)

#### Install NanoImagingPack
1. `cd /User/$USER$/Documents/nanoimagingpack-master`
2. `pip install ./

#### Install ImSwitch
1. `cd /User/$USER$/Documents/ImSwitch`
2. `pip install -r requirements.txt --user`
3. `pip install -e ./`

## Start ImSwitch

You should be all set, now type:

```
imswitch
```
or alternatively
```
cd imswitch
python __main__.py
```

For additional information see https://github.com/beniroquai/ImSwitch
