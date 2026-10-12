# airway_intubation_model

# Assembly instructions

These instructions are for the assembly of the model once each individual component has been completed. Further instructions for the silicone casting of individual components to follow.

## Materials & equipment

### Hardware
- M4 screws:
  - 5 x 8mm
  - 8 x 10mm
  - 2 x 12mm
  - 12 x 20mm
- M3 screws:
  - 8 x 10mm
  - 2 x 14mm
  - 4 x 18mm
- 4 x M3 nuts
- Clamp

### Printing
- Polylactic Acid (PLA)
- Flexible filament (TPE, etc.)
- Fused Deposition Modelling 3D printer

### Casting
- Two-part Platinum Cure Silicone Rubber
  - Ecoflex 00-20: Available from [Smooth-On](https://www.smooth-on.com/products/ecoflex-00-20/)
  - Ecoflex 00-30: Available from [Smooth-On](https://www.smooth-on.com/products/ecoflex-00-30/)
- Degas Chamber (Optional)
- Mold release agent: Available from [Smooth-On](https://www.smooth-on.com/product-line/universal-mold-release/)
- Silc Pig silicone pigments in blood and skin tone of choice: Available from [Smooth-On](https://www.smooth-on.com/products/silc-pig/)
- Mesh stretch fabric (nylon, polyester, etc.)
- Glue gun

## Components
### Printed components
To be printed in hard plastic (PLA, etc.):
- base cover ([intubation_base_cover.stl](https://github.com/tgh-apil/airway_intubation_model/blob/main/stl_files/base/intubation_base_cover.stl))
- base ([intubation_base.stl](https://github.com/tgh-apil/airway_intubation_model/blob/main/stl_files/base/intubation_base.stl))
- skull ([skull.stl](https://github.com/tgh-apil/airway_intubation_model/blob/main/stl_files/base/skull.stl))
- pharynx ([upper_jaw_pharynx.stl](https://github.com/tgh-apil/airway_intubation_model/blob/main/stl_files/pharynx_casting/upper_jaw_pharynx.stl))
- mandible ([mandible.stl](https://github.com/tgh-apil/airway_intubation_model/blob/main/stl_files/mandible_and_tongue_casting/mandible.stl))
- epiglottis casting plate ([epiglottis_plate.stl](https://github.com/tgh-apil/airway_intubation_model/blob/main/stl_files/mandible_and_tongue_casting/epiglottis_plate.stl))
- forehead and neck bars ([skin_forehead_bar.stl](https://github.com/tgh-apil/airway_intubation_model/blob/main/stl_files/skin_casting/skin_forehead_bar.stl); [skin_neck_bar.stl](https://github.com/tgh-apil/airway_intubation_model/blob/main/stl_files/skin_casting/skin_neck_bar.stl))
- top thyroid connector ([thyroid_connector_top.stl](https://github.com/tgh-apil/airway_intubation_model/blob/main/stl_files/thyroid_cartilage_and_connector/thyroid_connector_top.stl))
- bottom thyroid connectors; left and right ([thyroid_connector_bottom_L.stl](https://github.com/tgh-apil/airway_intubation_model/blob/main/stl_files/thyroid_cartilage_and_connector/thyroid_connector_bottom_L.stl); [thyroid_connector_bottom_R.stl](https://github.com/tgh-apil/airway_intubation_model/blob/main/stl_files/thyroid_cartilage_and_connector/thyroid_connector_bottom_R.stl))
  - Note that the pathological vocal folds variant requires a different right bottom thyroid connector component ([thyroid_connector_bottom_R_tumor.stl](https://github.com/tgh-apil/airway_intubation_model/blob/main/stl_files/vocal_folds/pathological_anatomy/thyroid_connector_bottom_R_tumor.stl))
- vocal fold wings; left and right ([vocal_fold_wing_L.stl](https://github.com/tgh-apil/airway_intubation_model/blob/main/stl_files/vocal_folds/vocal_fold_wing_L.stl); [vocal_fold_wing_R.stl](https://github.com/tgh-apil/airway_intubation_model/blob/main/stl_files/vocal_folds/vocal_fold_wing_R.stl))

To be printed in flexible plastic (TPE, etc.):
- nasal passage ([nasal_passage.stl](https://github.com/tgh-apil/airway_intubation_model/blob/main/stl_files/nasal_passage.stl))
- thyroid cartilage ([thyroid_cartilege.stl](https://github.com/tgh-apil/airway_intubation_model/blob/main/stl_files/thyroid_cartilage_and_connector/thyroid_cartilege.stl))
- trachea
  - healthy ([trachea_healthy_v3.stl](https://github.com/tgh-apil/airway_intubation_model/blob/main/stl_files/trachea/trachea_healthy_v3.stl)) and pathological ([trachea_tumor.stl](https://github.com/tgh-apil/airway_intubation_model/blob/main/stl_files/trachea/pathological/trachea_tumor.stl)) variants

### Silicone components
Instructions for casting and assembling these components are linked below.
- [pharynx](https://github.com/tgh-apil/airway_intubation_model/blob/main/pharynx_casting.md) *(cast with 3D printed pharynx component)*
- [mandible and tongue](https://github.com/tgh-apil/airway_intubation_model/blob/main/mandible_and_tongue_casting.md) *(cast with mandible and epiglottis plate components, and optionally with mesh fabric)*
  - healthy and pathological (base of tongue tumor) variants
- [vocal folds](https://github.com/tgh-apil/airway_intubation_model/blob/main/vocal_folds_casting.md) *(cast with vocal fold wing components)*
  - healthy and pathological (tumor) variants
- [skin](https://github.com/tgh-apil/airway_intubation_model/blob/main/skin_casting.md) *(cast with mesh fabric)*
- silicone hinges *(cast with mesh fabric)*
- trachea tumor
  - for [pathological trachea variant](https://github.com/tgh-apil/airway_intubation_model/blob/main/trachea_tumor_casting.md)

## Model Assembly Instructions
1. Attach the skull to the silicone-cast pharynx with four 10mm M4 screws.
<img src="https://github.com/tgh-apil/airway_intubation_model/blob/main/images/model_assembly_instructions/1_attaching_skull_pharynx.png" width="400">

2. Attach the nasal passage by first hooking the inner lip into the back opening of the pharynx, screwing it in place with five 8mm M4 screws, and popping the front beneath the nasal bone.
<img src="https://github.com/tgh-apil/airway_intubation_model/blob/main/images/model_assembly_instructions/2_attaching_nasal_passage.png" width="500">

3. Attach the head to the base, first by securing the pharynx from the bottom with two 20mm M4s, then the skull from the back with two 20mm M4s.
<img src="https://github.com/tgh-apil/airway_intubation_model/blob/main/images/model_assembly_instructions/3_attaching_base.png" width="400">

4. Attach the thyroid cartilage to the tongue with two 14mm M3s. To do so, align the thyroid cartilage to the tongue and pinch the epiglottis plate inside the tongue that the thyroid screws into.
<img src="https://github.com/tgh-apil/airway_intubation_model/blob/main/images/model_assembly_instructions/4_attaching_tongue_thyroid.png" width="400">

5. Assemble the vocal folds and trachea. First, sandwich the vocal folds between the top connector and both bottom connectors, then attach together with four 10mm M3s. Then attach the trachea below with four 18mm M3s and four M3 nuts.
    - Note that the pathological vocal folds variant should be attached with the pathological bottom right connector component.
<img src="https://github.com/tgh-apil/airway_intubation_model/blob/main/images/model_assembly_instructions/5_attaching_VF_thyroid connector.png" width="500">

6. Attach the vocal fold/trachea complex to the thyroid with four 10mm M3s.
<img src="https://github.com/tgh-apil/airway_intubation_model/blob/main/images/model_assembly_instructions/6_thyroid_complex_complete.png" width="400">

7. Attach the mandible to the skull with a silicone hinge on each side, slotting the vocal fold connectors into the channels of the base. (Note that if the bottom connectors should slide freely in the channels; if they don’t they may need to be sanded down.)
<img src="https://github.com/tgh-apil/airway_intubation_model/blob/main/images/model_assembly_instructions/7_attaching_anatomy_base.png" width="600">

8. Place the skin onto the base by setting the forehead and neck bars into their respective slots. Shift the skin so that it lays flat against the underlying bony anatomy: this is best done by pulling the mandible forward into the chin of the skin, then pulling each side of the skin over the edge and angle of the mandible. Screw the neck bar to the base with four 20mm M4s (sides of base), and the forehead bar with four 20mm M4s (sides of base) and two 12mm M4s (back of base).
<img src="https://github.com/tgh-apil/airway_intubation_model/blob/main/images/model_assembly_instructions/8_skin_attached.png" width="400">

9. Slide on the base cover to hide the trachea. This may need sanding after printing to ensure it is easily attachable.

10. Clamp the model to a table to prevent it from moving when in use.
