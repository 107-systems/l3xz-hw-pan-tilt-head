# Fusion 360 exporter

Fusion 360 was used to build the models for this project. Because Fusion is a cloud-based service, this python script is used to export the design files to git. This script is based
on [a script written by aconz2](https://github.com/aconz2/Fusion360Exporter) and exports 
files as both f3d (the Fusion 360 native format) and the industry standard step format.

# Installation

The script is in a directory as Fusion requires this for add-ins. To add it to your Fusion instance simply open
utilities > Add-ins > Scripts, click on the "+" beside "My Scripts", and point to the directory this readme is in.
You can then run the script to initiate an export.
