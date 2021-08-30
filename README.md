# IMAGE TO CARTOON

#A python script to convert jpg/png files to cartoonish form.

# USAGE

Just enter your image file name or path and set the values according to your own need.

1) A larger line size means the thicker edges that will be emphasized in the image.

2) The larger blur value means fewer black noises appear in the image.

3) k value determines the number of colors we want to apply to the image.

4) To reduce the noise in the image we use a bilateral filter. It would give a bit blurred and sharpness-reducing effect to the image.

a) d — Diameter of each pixel neighborhood.

b) sigmaColor — A larger value of the parameter means larger areas of semi-equal color.

c) sigmaSpace –A larger value of the parameter means that farther pixels will influence each other as long as their colors are close enough.
