:start geometry:
name = chamber_body
library = egs_cones
type = EGS_ConeStack
axis = 0.985 0 0 -1 0 0 # x-axis
### sensitive volume (cylindrical portion)
:start layer:
thickness = 2.03
top radii = 0.05 0.305 0.355 2.0
bottom radii = 0.05 0.305 0.355 2.0
media = c552 air c552 water
:stop layer:
