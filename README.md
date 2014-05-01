Wearable-Platform
=================

# The Wearable Platform
A modular hardware platform for creating wearable tech containing a bluetooth 4.0 and 3-axis accelerometer. The goal of this project is to make the hardware cheap and cost-effective to produce. I was able to create a BOM of close to $10. I have reviewed the layout and have talked to many different people in order to remove as much noise from the board as possible. So far contains Altium Design files ready for production. Board size is around 40mm x 25 mm.

# Specs
| Core              | Spec                  | Cost (order of 1)  |
| ------------------|:-----------------:    | ------------------:|
| MCU/Bluetooth     | Nordic nRF51822       | $2.90             |
| IMU               | MMA8653FCR1CT         | $1.00             |
| RGB LED           | SML-LX0404SIUPGUSB    | $1.20             |
| JTAG Header       | FTSH-105-01-L-DV      | $1.10             |
| CR2032 BAT Holder | BU2032SM-BT-GCT ND    | $0.60             |

+ There are also other misc. passives

# Images

2-d view: ![](/Hardware/Media/2d.jpg)

3-d front: ![](/Hardware/Media/3d-front.jpg)

3-d side: ![](/Hardware/Media/3d-side.jpg)

3-d back: ![](/Hardware/Media/3d-back.jpg)

# Next Steps
I haven't had the time or funding to actually get this board manufactured. My hope is someone will try to keep this project going as I think this can really go places.
- Make it even cheaper by removing JTAG header and just making it exposed pads for programming
- Exploring the recharable battery option
- Create software examples