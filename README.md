# documentation_project


A test of dynamic creation of the connector lines between imagemap points and text blocks

The image map is created manually in GIMP; the IDs are taken from the UIbinding project.
The JS code is generated by ChatGPT 4 (with small improvements added by Kristian). The script basically finds geometric centers of the imagemap active areas and draws a line from this center to the relevant text block (identified by the id).
In this version, the imagemap does not work as a regular image map (it makes little sense in the two-column layout).

The number of referenced items is definitely too many.
