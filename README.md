# Formulations Imaging

The following is a simple webcam script to image the liquid formulation samples I am preparing as part of my PhD, in order to take images to analyse their phase stability via computer vision techniques later. 

The script can be used to control generic webcams. In my case, a Logitech C930 webcam was used. The camera is controlled via the `opencv` python module.
The script must be executed in the relevant directory opened up in a command window/terminal with `python -m webcam_image`

This brings up a pop-up window showing what the camera sees. Press the space bar to capture an image. Here it prompts me to enter a sample name etc. to automatically save the image with it's sample ID and whether it was stable or not.

## Dependencies 

`pip install -r requirements.txt`
