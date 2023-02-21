# Satellite Antenna requirements
All about Antennas and some HFSS simulations on how they work and look like

The following questions shall be addressed for each of the desired antenna systems
• What is the operating frequency range of the system ?
• How much gain is required ?
• What kind of radiation pattern is desired?
• What is the maximum allowable VSWR?
• What polarization is required?
• What type of connector interface is required?
• How much power will the antenna have to handle?
• Where will the antenna be mounted?
• Is a radome required?
• What is the lifetime of the antenna?

Following Designs are certain requirements in the field of Satellite antenna systems.

## Electronically Steerable X-band High Aperture and High Gain Antenna

| Name of the Feature              | Value Expected                             | Remarks                                                                     |
|----------------------------------|--------------------------------------------|-----------------------------------------------------------------------------|
| Frequency Range                  | 9.5-10.5 GHz                               | SAR                                                                         |
| Gain and Flatness                | 30dB, 2dB flatness                         |                                                                             |
| Kind of Radiation Pattern Needed | Pointed Beam                               | Least side lobes, -70dBm                                                    |
| Allowable VSWR in the Range      | 3                                          |                                                                             |
| Polarization Requirements        | H and V individually                       |                                                                             |
| Type of Connector Interface      | SMA/Molex                                  | Individual for Different Polarization                                       |
| Power Handled by the Antenna     | 500W                                       |                                                                             |
| Antenna Mounting                 | Fixed on Zenith facing Satellite           | Temperatures seen, -50Deg to +90Deg                                         |
| Radome Requirement               | Thermal Shielding requirment at discretion |                                                                             |
| Lifetime of the Antenna          | > 5 years                                  | Small Satellite Lifetime                                                    |
| Steerability Accuracy            | 2 Deg E2E Main Lobe, steps of 0.01deg      | Can be relaxed                                                              |
| Extra Information                | Will be coated with protective coating     | Backside of the antenna if possible should be able to support Solar panels. |

## High Gain TX/RX Antenna using Meta Material Surface

| Name of the Feature              | Value Expected                             | Remarks                                                                     |
|----------------------------------|--------------------------------------------|-----------------------------------------------------------------------------|
| Frequency Range                  | 9.8 GHz Center, 60MHz band                 | Communication                                                               |
| Gain and Flatness                | 43dB, 3dB flatness                         |                                                                             |
| Kind of Radiation Pattern Needed | Pointed Beam                               | Side lobes acceptable upto -30dBm                                           |
| Allowable VSWR in the Range      | 3                                          |                                                                             |
| Polarization Requirements        | Circular (LHCP, Preferred)                 |                                                                             |
| Type of Connector Interface      | SMA/Molex                                  | LHCP and RHCP provisions                                                    |
| Power Handled by the Antenna     | 30W                                        |                                                                             |
| Antenna Mounting                 | Fixed on Zenith facing Satellite           | Temperatures seen, -50Deg to +90Deg                                         |
| Radome Requirement               | Thermal Shielding requirment at discretion |                                                                             |
| Lifetime of the Antenna          | > 10 years                                 | Small Satellite Lifetime                                                    |
| Steerability Accuracy            | 2 Deg E2E Main Lobe, steps of 0.01deg      | Can be relaxed                                                              |
| Extra Information                | Will be coated with protective coating     | Backside of the antenna if possible should be able to support Solar panels along with the ground plane |

Will need support design of wide band feed lines and waveguide structures.

## Design of Wide Band Top Side Ionosonde Antenna

| Name of the Feature              | Value Expected                             | Remarks                                                                     |
|----------------------------------|--------------------------------------------|-----------------------------------------------------------------------------|
| Frequency Range                  | 30MHz to 100MHz                            | SAR                                                                         |
| Gain and Flatness                | 6dB boreside                               |                                                                             |
| Kind of Radiation Pattern Needed | Earth Limb facing 60Deg HPBW               | Least side lobes, -30dBm                                                    |
| Allowable VSWR in the Range      | 3                                          |                                                                             |
| Polarization Requirements        | H and V individually                       |                                                                             |
| Type of Connector Interface      | SMA/Molex                                  | Individual for Different Polarization                                       |
| Power Handled by the Antenna     | 20W                                        |                                                                             |
| Antenna Mounting                 | Fixed on Zenith facing Satellite           | Temperatures seen, -50Deg to +90Deg                                         |
| Radome Requirement               | Thermal Shielding requirment at discretion |                                                                             |
| Lifetime of the Antenna          | > 5 years                                  | Small Satellite Lifetime                                                    |
| Steerability Accuracy            | NA                                         |                                                                             |
| Extra Information                | Will be coated with protective coating     | Deployable nature expected as the antenna maybe large.                      |

## Deployable Yagi Uda Antenna for high gain operations

| Name of the Feature              | Value Expected                             | Remarks                                                                     |
|----------------------------------|--------------------------------------------|-----------------------------------------------------------------------------|
| Frequency Range                  | 6GHz-9GHz, Bandwidth needed is 1MHz| Interplanetary Communication, High Throughput Communication, LEO to GEO Relay, Intersatellite Relay|
| Gain and Flatness                | 40dB                                       |                                                                             |
| Kind of Radiation Pattern Needed | Zenith Facing, tri pointed beam            | Least side lobes, -30dBm, One beam towards zenith, 2 at the 2 limbs of Earth|
| Allowable VSWR in the Range      | 3                                          |                                                                             |
| Polarization Requirements        | Circular                                   | RHCP, LHCP config                                                           |
| Type of Connector Interface      | SMA/Molex                                  | Individual for Different Polarization                                       |
| Power Handled by the Antenna     | Variable, 20W, 50W, and 100W               |                                                                             |
| Antenna Mounting                 | Fixed on Zenith facing Satellite           | Temperatures seen, -50Deg to +90Deg                                         |
| Radome Requirement               | Thermal Shielding requirment at discretion |                                                                             |
| Lifetime of the Antenna          | > 5 years                                  | Small Satellite Lifetime                                                    |
| Steerability Accuracy            | NA                                         |                                                                             |
| Extra Information                | Will be coated with protective coating     | Deployable nature expected as the antenna elements maybe large              |

## Deployable and Reconfigurable Antenna For Multi Band Operations

| Name of the Feature              | Value Expected                             | Remarks                                                                     |
|----------------------------------|--------------------------------------------|-----------------------------------------------------------------------------|
| Frequency Range                  | 6GHz-9GHz, Bandwidth needed is 1MHz| Interplanetary Communication, High Throughput Communication, LEO to GEO Relay, Intersatellite Relay|
| Gain and Flatness                | 40dB                                       |                                                                             |
| Kind of Radiation Pattern Needed | Zenith Facing, tri pointed beam            | Least side lobes, -30dBm, One beam towards zenith, 2 at the 2 limbs of Earth|
| Allowable VSWR in the Range      | 3                                          |                                                                             |
| Polarization Requirements        | Circular                                   | RHCP, LHCP config                                                           |
| Type of Connector Interface      | SMA/Molex                                  | Individual for Different Polarization                                       |
| Power Handled by the Antenna     | Variable, 20W, 50W, and 100W               |                                                                             |
| Antenna Mounting                 | Fixed on Zenith facing Satellite           | Temperatures seen, -50Deg to +90Deg                                         |
| Radome Requirement               | Thermal Shielding requirment at discretion |                                                                             |
| Lifetime of the Antenna          | > 5 years                                  | Small Satellite Lifetime                                                    |
| Steerability Accuracy            | NA                                         |                                                                             |
| Extra Information                | Will be coated with protective coating     | Deployable nature expected as the antenna elements maybe large              |
