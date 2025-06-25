Welcome to my Engineering Cad Portfolio, below are my most impressive CAD projects.

# Catalytic Converter

This was for work with Incolmotos Yamaha in Colombia, we were tasked with improving the design and manufacture of the catalytic converter in their XTZ-125 model motorcycle, which was made completely of metal parts. We did this by changing the channel geometry to a triangular one, which optimized channel size and therefore airflow while maintaining surface area the same, and changing the base material to ceramic. Ceramic catalytic converters are used in cars, they're much cheaper to make. We found no evidence against using ceramic catalytic converters in motorcycles, it's not used much but they do exist mostly in India for some reason. In total, 3 channel geometries were devised (square, hexagonal, triangular), of which triangular proved to have the largest channel size, hence why it was chosen. Below are the designs created in the process, with supporting simulations further down. I also created a CAD replica of the original in order to run simulations. CADs were created with Autodesk Fusion 360, and simulations were done with ANSYS.

## CADs

### Original

<div style="display:inline;">
<img style="width:48.6%" src="fusion_360/original_catalyzer_top_view.png">
<img style="width:24.6%" src="fusion_360/original_catalyzer_full_view.png">
<img style="width:24.4%" src="fusion_360/original_catalyzer_full_view_no_sleeve.png">
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
<img style="width:32.5%" src="ansys/catalytic_converter/original/volumetric_inverse_section_3.png">
<img style="width:32.5%" src="ansys/catalytic_converter/original/volumetric_inverse_section_2.png">
<img style="width:32.5%" src="ansys/catalytic_converter/original/volumetric_inverse_section_1.png">
</div>

#### Triangular Channels (Best Option)

<div style="display:inline;">
<img style="width:32.5%" src="ansys/catalytic_converter/triangles/volumetric_inverse_section_3.png">
<img style="width:32.5%" src="ansys/catalytic_converter/triangles/volumetric_inverse_section_2.png">
<img style="width:32.5%" src="ansys/catalytic_converter/triangles/volumetric_inverse_section_1.png">
</div>

### Results

As can be seen, the triangular channels have much lower inlet, outlet, and cross-area pressures, and much higher velocities in all areas compared to the original design.

#### Original - Fluid Flow

These images are slightly confusing, especially the last 2, but they show particle paths at key sections inside the catalyzer, specifically from the exhaust into the catalyzer's channels. This view was chosen specifically because it shows how air particles interact with the channel's cross section, allowing to see how much they slow down, or if they get "stuck".

<div style="display:inline;">
<img style="width:32.5%" src="ansys/catalytic_converter/original/volumetric_inverse_section_simulation_12_fluid_flow.jpg">
<img style="width:32.5%" src="ansys/catalytic_converter/original/volumetric_inverse_section_simulation_13_fluid_flow_at_intersection.png">
<img style="width:32.5%" src="ansys/catalytic_converter/original/volumetric_inverse_section_simulation_14_fluid_flow_at_intersection.png">
</div>

#### Original - Pressure

<div style="display:inline;">
<img style="width:49.5%" src="ansys/catalytic_converter/original/volumetric_inverse_section_simulation_1_reference_view.png">
<img style="width:49.5%" src="ansys/catalytic_converter/original/volumetric_inverse_section_simulation_2_inlet_and_outlet_pressures.png">
<img style="width:41.75%" src="ansys/catalytic_converter/original/volumetric_inverse_section_simulation_4_transversal_pressure.png">
<img style="width:28.51%" src="ansys/catalytic_converter/original/volumetric_inverse_section_simulation_6_inlet_pressure.png">
<img style="width:28.4%" src="ansys/catalytic_converter/original/volumetric_inverse_section_simulation_8_inlet_and_outlet_pressure.jpg">
<img style="width:38.3%" src="ansys/catalytic_converter/original/volumetric_inverse_section_simulation_3_inlet_and_outlet_pressures.png">
</div>
<img style="width:31.45%" src="ansys/catalytic_converter/original/volumetric_inverse_section_simulation_9_inlet_and_outlet_pressure.png">
<img style="width:28.75%" src="ansys/catalytic_converter/original/volumetric_inverse_section_simulation_7_transversal_pressure.png">

#### Original - Velocity

<div style="display:inline;">
<img style="width:41.65%" src="ansys/catalytic_converter/original/volumetric_inverse_section_simulation_5_transversal_velocity.png">
<img style="width:28.4%" src="ansys/catalytic_converter/original/volumetric_inverse_section_simulation_10_inlet_and_outlet_velocity.jpg">
<img style="width:28.4%" src="ansys/catalytic_converter/original/volumetric_inverse_section_simulation_11_inlet_and_outlet_velocity.png">
</div>

#### Triangles - Fluid Flow

<div style="display:inline;">
<img style="width:32.75%" src="ansys/catalytic_converter/triangles/volumetric_inverse_section_simulation_12_fluid_flow.jpg">
<img style="width:32.75%" src="ansys/catalytic_converter/triangles/volumetric_inverse_section_simulation_13_fluid_flow_at_intersection.jpg">
<img style="width:32.75%" src="ansys/catalytic_converter/triangles/volumetric_inverse_section_simulation_14_fluid_flow_at_intersection.jpg">
</div>

#### Triangles - Pressure

<div style="display:inline;">
<img style="width:48%" src="ansys/catalytic_converter/triangles/volumetric_inverse_section_simulation_1_reference_view.png">
<img style="width:50.75%" src="ansys/catalytic_converter/triangles/volumetric_inverse_section_simulation_2_inlet_and_outlet_pressures.png">
<img style="width:42.3%" src="ansys/catalytic_converter/triangles/volumetric_inverse_section_simulation_4_transversal_pressure.png">
<img style="width:28.1%" src="ansys/catalytic_converter/triangles/volumetric_inverse_section_simulation_6_inlet_pressure.png">
<img style="width:28.05%" src="ansys/catalytic_converter/triangles/volumetric_inverse_section_simulation_8_inlet_and_outlet_pressure.jpg">
<img style="width:37.9%" src="ansys/catalytic_converter/triangles/volumetric_inverse_section_simulation_3_inlet_and_outlet_pressures.png">
</div>
<img style="width:30.25%" src="ansys/catalytic_converter/triangles/volumetric_inverse_section_simulation_9_inlet_and_outlet_pressure.png">
<img style="width:30.3%" src="ansys/catalytic_converter/triangles/volumetric_inverse_section_simulation_7_transversal_pressure.png">

#### Triangles - Velocity

<div style="display:inline;">
<img style="width:41%" src="ansys/catalytic_converter/triangles/volumetric_inverse_section_simulation_5_transversal_velocity.png">
<img style="width:28.8%" src="ansys/catalytic_converter/triangles/volumetric_inverse_section_simulation_10_inlet_and_outlet_velocity.jpg">
<img style="width:28.85%" src="ansys/catalytic_converter/triangles/volumetric_inverse_section_simulation_11_inlet_and_outlet_velocity.jpg">
</div>