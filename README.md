# Cycloidal Drive for NEMA17 Stepper Motor 

+ 240929 Simply roller support on housing ring 
  + Eliminate roller support frame
+ 240923 Update
  + Cycloidal disk profile offset=0.0mm 
  + Cycloidal disk height 9mm
  + Output shaft / pin plate height 4.5mm 
+ 240915 Ratio 11:1 update for NEMA17 22mm shaft
  + cycloidal disk height 8mm 
  + rollers 3x25mm
  + height of the reducer 30mm 
+ 240909 Revised for Ratio 11:1
+ 240908 Initial package of ratio 19:1 

## Design Parameters for Ratio 11 

+ Number of rollers: 12
+ Eccentricity: 0.5mm 
+ Roller diameter: 3mm 
+ Roller circle diameter: 30mm 
+ Pressure angle limit: 50 deg 
+ ~~Pressure angle offset: 0.1mm~~ 

![initial package](Stepper_Cycloidal_Drive_Ratio11.png)

## Design Paramters for Ratio 19 

+ Numer of rollers: 20 
+ Eccentricity: 0.5mm 
+ Roller diameter: 3mm 
+ Roller circle diameter: 32mm 
+ Pressure angle limit: 50 deg 
+ Pressure angle offset: 0.0mm

![Ratio19](Stepper_Cycloidal_Drive_Ratio19.png)

## Parts 

+ Bearing: MF128ZZ x 5, Nominal d8D12H3.5 vs. measured 7.92x11.93x3.41mm 
+ Roller: D3x25mm x (12+6), measured D2.93x24.70mm 

## Design Software 

+ FreeCAD [0.21.2](https://github.com/FreeCAD/FreeCAD/releases/tag/0.21.2)
+ [FreeCAD_Assembly4](https://github.com/Zolko-123/FreeCAD_Assembly4)
+ [FreeCAD_FastenersWB](https://github.com/shaise/FreeCAD_FastenersWB)
