# IODA gimbal

Opto-mechanics which is mounted on [ToF PCB](https://github.com/plex1/Tof_PCB). See also main project [ioda_lidar](https://github.com/plex1/ioda_lidar) for more info.

## Components
- Laser Tower: Collimator of outgoing laser beam.
   - Collimator Lens: [LA1116-B - N-BK7](https://www.thorlabs.com/thorproduct.cfm?partnumber=LA1116-B) Plano-Convex Lens, Ø6.0 mm, f = 10 mm, AR Coating: 650 - 1050 nm
   - Deflection Mirror: [PF03-03-P01](https://www.thorlabs.com/thorproduct.cfm?partnumber=PF03-03-P01) - Ø7.0 mm Protected Silver Mirror
- Laser Corner Tower: Deflection of outputgoing laser beam withing main barrel.
   - Deflection Mirror: [PF03-03-P01](https://www.thorlabs.com/thorproduct.cfm?partnumber=PF03-03-P01) - Ø7.0 mm Protected Silver Mirror
- Tof Assembly Tower: Focusing of incoming laser signal and 2 degrees of freeedom gimbal
   - Focusing Lens: [LA1951-B](https://www.thorlabs.com/thorproduct.cfm?partnumber=LA1951-B0) - N-BK7 Plano-Convex Lens, Ø1", f = 25 mm, AR Coating: 650 - 1050 nm
   - 2x Deflection Mirror: [PFE10-P01](https://www.thorlabs.com/thorproduct.cfm?partnumber=PFE10-P010) - 1" Protected Silver Elliptical Mirror, 450 nm - 20 µm
   - 2x Stepper Motor: NEMA 8, Motion King 8H2A33402, 1.8deg/step, Shaft Length: 20mm

## Manufacturing
The individual components which consist of several bodies which are glued together with super glue (UHU Sekundenkleber). The individual components can rotate freely giving two degrees of freedom. Bearings are made with direct plastic contacts without bearings. The parts are printed with PLA and 0.2mm layer height on a 3D printer.

For the primary pinion gear (attached to the motor shaft) a LEGO technics gear with 8 teeth was used. With an electric drill a 4mm hole was drilled out to match the shaft of the motors. First a 3.5mm drill bit and then a 4mm drill bit was used to achieved this. These gears are not shown in the darwing.
## Motors

| Parameter           | Value            |
|---------------------|------------------|
| Size Category       | NEMA 8           |
| Manufacturer        | Motion King      |
| Type                | 8H2A33402        |
| Deg/Step            | 1.8              |
| Max Voltage         | 5V               |
| Rated Current       | 200mA            |
| Dimensions (Body)   | 20.3x20.3x33 mm³ |
| Shaft Length        | 20mm             |
| Torque              | 2.0 N cm         |


## Gears
| Gear                        | # Teeth     | Pressure Angle | Diameter | Module | Manufacturing|
|-----------------------------|-------------|----------------|----------|--------| -------------|
| 2x Pinion                   | npineon=8   | 20 deg         | 8 mm     | 1      | Lego         |
| Outer ring gear horizontal  | nouter=64   | ca 20 deg      | 64 mm    | 1      | 3D printed   |
| Outer ring gear vertical    | nouter=64   | ca 20 deg      | 69 mm    | 1.08   | 3D printed   |
| Lower gear (horizontal)     | nlower=42   | ca 20 deg      | 44 mm    | 1.05   | 3D printed   |
| Upper gear (vertical)       | nupper=42   | ca 20 deg      | 44 mm    | 1.05   | 3D printed   |

## Illustrations
![Screenshot](./images/screenshot.PNG)
![Render](./images/render.PNG)
![Crosssection](./images/crosssection.PNG)
