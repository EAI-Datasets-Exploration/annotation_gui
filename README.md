# annotation-gui

contact: slwanna@utexas.edu

TODO

## Setup Instructions
- ```$ conda env create -f environment.yml```
- ```$ conda activate annotation-gui```
- ```$ make dev_install```

## How to Run
- Alter or setup your preferred experiment configuration in ```annotation-gui/config.ini```.
- ```$ python -m annotation_gui```

**WARNING: THIS SCRIPT ASSUMES ACCESS TO GPU RESOURCES. ADJUST BATCH SIZES IN SOME OF THE FEATURE ACQUISITION FUNCTIONS TO BETTER SUIT YOUR OWN MACHINES.**

## Before you commit!

1. Ensure you code "works" otherwise save to an appropriate branch
2. run ```$ make format``` 
3. run ```$ make lint``` 