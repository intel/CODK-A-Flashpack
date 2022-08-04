DISCONTINUATION OF PROJECT.

This project will no longer be maintained by Intel.

Intel has ceased development and contributions including, but not limited to, maintenance, bug fixes, new releases, or updates, to this project. 

Intel no longer accepts patches to this project.

If you have an ongoing need to use this project, are interested in independently developing it, or would like to maintain patches for the open source software community, please create your own fork of this project. 
# Arduino/Genuino 101 flashpack

This framework is used to package the firmware and flashing scripts. The
scripts flash the required firmware images via DFU, using dfu-util.

See DFU-UTIL.README for license and source information

## Use
After building the firmware source code, generate a flashpack by:

`./create_flasher.sh [tag]`

where "tag" is an optional string that will be appended to the flashpack
filename.

#License

The bash scripts are GPLv2 licensed. Every other software used by these bash
scripts has its own license. Consult them to know the terms.

