#ispy_robot

This is a collection of modules for NAO robots that are required for the iSpy game in the HiLT lab. More info: https://github.com/iamadamhair/ispy_python

These files are intended to reside in `~/modules/`

In order to load them, you must edit the file `~/naoqi/preferences/autoload.ini` file to include the modules under the `[python]` section, e.g.:

    [python]
    /home/nao/modules/segmentation_module.py
    /home/nao/modules/sound_receiver_module.py
