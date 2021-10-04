# DEIprocessing
## How to install DEIprocessing


### Install with the Contribution Manager

Add contributed tools by selecting the menu item _Tools_ → _Add Tool..._ This will open the Contribution Manager, where you can browse for DEIprocessing, or any other tool you want to install.

Not all available tools have been converted to show up in this menu. If a tool isn't there, it will need to be installed manually by following the instructions below.

### Manual Install

Contributed tools may be downloaded separately and manually placed within the `tools` folder of your Processing sketchbook. To find (and change) the Processing sketchbook location on your computer, open the Preferences window from the Processing application (PDE) and look for the "Sketchbook location" item at the top.

By default the following locations are used for your sketchbook folder: 
  * For Mac users, the sketchbook folder is located inside `~/Documents/Processing` 
  * For Windows users, the sketchbook folder is located inside `My Documents/Processing`

Download DEIprocessing from https://github.com/DuarteCarvalhoo/ProcessingCompiler2

Unzip and copy the contributed tool's folder into the `tools` folder in the Processing sketchbook. You will need to create this `tools` folder if it does not exist.
    
The folder structure for tool DEIprocessing should be as follows:

```
Processing
  tools
    DEIprocessing
      examples
      tool
        DEIprocessing.jar
      reference
      src
```
                      
Some folders like `examples` or `src` might be missing. After tool DEIprocessing has been successfully installed, restart the Processing application.

### Troubleshooting

If you're having trouble, try contacting the author [Duarte Carvalho](https://github.com/DuarteCarvalhoo).
