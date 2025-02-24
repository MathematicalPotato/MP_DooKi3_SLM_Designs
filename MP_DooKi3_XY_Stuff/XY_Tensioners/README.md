# SLM XY Tensioner Stack for the Z Axis of DooKi3 or Annex Engineering K3
These files are designed to be SLM printed out of aluminum.

## Notes
There are Y Spacers are modeled as 20 or 21mm tall.  I orderd the 20mm and they came out as 20.3-20.4mm.  They will need sanded to the correct dimensions based on the rails and toolhead used for the machine.
The following Y Spacer thicknesses are required for a total toolhead plate thickness of 6.4mm: 
6.5mm thick rails = 19.9mm
6.0mm thick rails = 20.4mm
5.6mm thick rails = 20.8mm

The rail carriage mount only uses three bolts.  This allows the tensioner to remain installed with two bolts while the cross rails are removed so belt tension can be preserved during maintenance. There are many rail thickness options, it is recommended to get the size for your specific rails, however the smaller ones can be used with thicker rails if needed.  The larger options would need shims on the rails to work with smaller rails so it is not recommended to oversize.

These should be the approximate weights for these parts in aluminum:
- MP_DooKi3_SLM_XY_Tensioner_V4_10mm: 13.9g
- MP_DooKi3_SLM_XY_Tensioner_V4_12mm: 15.6g
- MP_DooKi3_SLM_XY_Rail_Mount_V2: 3.9g
- MP_DooKi3_SLM_Y_Spacer_V2: 6.2g

Total:
- 10mm X total: 17.8g per side
- 10mm Y total: 24.0g per side
- 12mm X total: 19.5g per side
- 12mm Y total: 25.7g per side

## Updates
### 2025-02-24
- Added additional rail mount sizes
  - 5.0mm thick rails
  - 5.5mm thick rails

### 2025-02-20
- Added additional rail mount sizes
  - 5.6mm thick rails
  - 6.0mm thick rails
- Added 21mm thick Y spacer

### 2024-10-29
- Updated tensioners to V6.
  - Increased wall thickness for 2.4mm tapping holes to allow better fitment for helicoils.

### 2024-09-06
- Updated tensioners to V5.
  - Widened belt slots to improve fitment and ease of insertion.
- Updated rail mounts to V4.
  - Widened rail and magnet spaces for better fitment and clearances.
 
### 2024-08-20
- Updated tensioners to V4.
  - This version adds tensioning parts that are compatible with 12mm wide belts.
    - 12mm will require the SLM idlers here: https://github.com/MathematicalPotato/MP_DooKi3_SLM_Designs/tree/main/MP_DooKi3_XY_Stuff/XY_Idlers.  See the README for additional considerations. 
  - This version mainly included CAD workflow changes to make the tensioners easier to modify in the future.  This version is slightly heavier as a result.

### 2024-08-07
- Reorganized the outdated parts folder and added version numbers for better tracking.
  - V1 are the original files.
  - V2 have updated clearances and should be slightly lighter.
- Updated XY tensioners to V3 to allow for the use of up to 10mm wide belts.
  - This version is also compatible with 9mm belts and is recommended for all belt thicknesses.
  - This version will require the use of the 10mm versions of the tensioning sliders.

## Images
![XY_Tensioner_1](Images/XY_Tensioner_1.png)
![XY_Tensioner_2](Images/XY_Tensioner_2.png)
![XY_Tensioner_3](Images/XY_Tensioner_3.png)
