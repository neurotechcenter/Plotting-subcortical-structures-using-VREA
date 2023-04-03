# Plotting-subcortical-structures-using-VREA
a tutorial for plotting subcortical structures using VERa


Make a 3D model from ASERG+APRARC segmentation.

ASEG is a volume segmentation (for example, it will give you labels for cortex, white matter, hippocampus, and thalamus), but in ASEG, all cortex will just be labeled cortex.

APRARC is a type of cortical segmentation (insula, premotor, ...). ASERG+APRARC combines those two together.

Within the SEEG_full pipeline of VERA, the identifier ASEG will use aseg+aparc from Freesurfer.

There is a component called "LabelVolume2Surface." Use as ASEG and an appropriate surface identifier name. And then use a matouput component to save it as mat file.

An example of MATLAB code visualizing just some parts of the 3d model is included.
