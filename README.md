# PyMol Workshop

## Helpful 3rd party tutorials

## Visualising proteins in Pymol

## Analysis Tools

## Raytracing and image editing

```
# General environment
bg white
set ray_opaque_background, on
space cmyk

# Protein styling
hide lines
set cartoon_tube_radius, 1.2
set ribbon_width, 8

# Raytrace parameters
set ray_trace_mode, 0
set two_sided_lighting, 1
set antialias, 2
set surface_quality, 1
set surface_quality, 2
util.cbaw
set light_count,8
set spec_count,1
set shininess, 10
set specular, 0.25
set ambient,0
set direct,0
set reflect,1.5
set ray_shadow_decay_factor, 0.1
set ray_shadow_decay_range, 2
set depth_cue, 0
set defer_builds_mode, 3

#Extending colors with color-blindness friendly color palette
#References:
#http://jfly.iam.u-tokyo.ac.jp/html/color_cb/#pallet
#https://personal.sron.nl/~pault/colourschemes.pdf
set_color cb_blue, [51, 34, 136]
set_color cb_tan, [221, 204, 119]
set_color cb_lightblue, [136, 204, 238]
set_color cb_green, [17, 119, 51]
set_color cb_teal, [68, 170, 153]
set_color cb_gold, [153, 153, 51]
set_color cb_salmon, [204, 102, 119]
set_color cb_red, [136, 34, 85]
set_color cb_pink, [170, 68, 153]
```
