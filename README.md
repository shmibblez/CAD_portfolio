Welcome to my Engineering Cad Portfolio, below are my most impressive CAD projects.

# Catalytic Converter

This was for work with Incolmotos Yamaha in Colombia, we were tasked with improving the design and manufacture of the catalytic converter in their XTZ-125 model motorcycle, which was made with fully metal parts. We did this by changing the channel geometry to a triangular one, which optimized channel size and therefore airflow while maintaining surface area the same, and changing the base material to ceramic. Ceramic catalytic converters are used in cars, they're much cheaper to make. We found no evidence against using ceramic catalytic converters in motorcycles, it's not used much but they do exist mostly in India for some reason. In total, 3 channel geometries were devised (square, hexagonal, triangular), of which triangular proved to have the largest channel size, hence why it was chosen. Below are the designs created in the process, with supporting simulations further down. I also created a CAD replica of the original in order to run simulations. CADs were created with Autodesk Fusion 360, and simulations were done with ANSYS.

## CADs

### Original

<div style="display:inline;">
<img style="width:48%" src="fusion_360/original_catalyzer_top_view.png">
<img style="width:24.3%" src="fusion_360/original_catalyzer_full_view.png">
<img style="width:24.1%" src="fusion_360/original_catalyzer_full_view_no_sleeve.png">
</div>

### Original & Triangle, Hexagon, and Square Channel Alternatives
<div style="display:inline;">
<img style="width:49.5%" src="fusion_360/original_catalyzer_diagonal_view.png">
<img style="width:49%" src="fusion_360/hexagons_catalyzer_diagonal_view.png">
<img style="width:49.7%" src="fusion_360/triangles__catalyzer_diagonal_view.png">
<img style="width:48.5%" src="fusion_360/squares_catalyzer_diagonal_view.png">
</div>

## Simulation

### Setup

#### Original

<div style="display:inline;">
<img style="width:32%" src="ansys/catalytic_converter/original/volumetric_inverse_section_3.png">
<img style="width:32%" src="ansys/catalytic_converter/original/volumetric_inverse_section_2.png">
<img style="width:32%" src="ansys/catalytic_converter/original/volumetric_inverse_section_1.png">
</div>

#### Triangular Channels (best option)

<div style="display:inline;">
<img style="width:32%" src="ansys/catalytic_converter/triangles/volumetric_inverse_section_3.png">
<img style="width:32%" src="ansys/catalytic_converter/triangles/volumetric_inverse_section_2.png">
<img style="width:32%" src="ansys/catalytic_converter/triangles/volumetric_inverse_section_1.png">
</div>

### Results

#### Original



#### Triangular Channels