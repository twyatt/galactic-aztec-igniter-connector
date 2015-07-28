# About
[![OSHPark PCB Top Thumbnail](artwork/thumb_top.png?raw=true)](artwork/top.png?raw=true)
[![OSHPark PCB Bottom Thumbnail](artwork/thumb_bottom.png?raw=true)](artwork/bottom.png?raw=true)

Custom board used to convert igniter ethernet plugs to 2-position terminal blocks for the [Galactic Aztec] rocket. The board was designed to interface with the [Galactic Aztec Raspberry Pi Add-on: Igniter] board.

Custom EagleCAD parts on this board can be found in the [SDSU Rocket Eagle Libraries].

## Wiring
The ethernet ports adhere to the following [T-568B] wiring configurations:

### Igniter
| Pin | Color        | Function       |
|:---:|:------------:|:--------------:|
| 1   | Orange/White | Supply Voltage |
| 2   | Orange       | Ground         |
| 3   | Green/White  | Supply Voltage |
| 4   | Blue         | Ground         |
| 5   | Blue/White   | Supply Voltage |
| 6   | Green        | Ground         |
| 7   | Brown/White  | Supply Voltage |
| 8   | Brown        | Ground         |

### Break Wire
| Pin | Color        | Function       |
|:---:|:------------:|:--------------:|
| 1   | Orange/White | 3.3V           |
| 2   | Orange       | Signal         |
| 3   | Green/White  | 3.3V           |
| 4   | Blue         | Signal         |
| 5   | Blue/White   | 3.3V           |
| 6   | Green        | Signal         |
| 7   | Brown/White  | 3.3V           |
| 8   | Brown        | Signal         |

## Launch
For the [Galactic Aztec April 18th, 2015 launch], a strand of solder was screwed into one side of the terminal block labeled "Break" then run thru the igniter and back to the other side of the "Break" terminal block. The "Break" terminal block does not have a polarity and simply opens or closes the connection between 3.3V and Signal.

# Bill of Materials
| Qty | Description                               | Part Number       | Vendor   |
|:---:|-------------------------------------------|------------------:|----------|
| 1   | Jack RJ45 CAT5/CAT5e                      | [380-1046-ND]     | DigiKey  |
| 1   | LED Red Vf=1.8V If=2mA 0603               | [475-1195-2-ND]   | DigiKey  |
| 1   | Resistor 12kΩ 1/4W 1% 0603                | [RHM12.0KADCT-ND] | DigiKey  |
| 3   | Terminal Block 0.2" Pitch Plug            | [A98223-ND]       | DigiKey  |
| 3   | Terminal Block 0.2" Pitch Socket          | [A98235-ND]       | DigiKey  |


[Galactic Aztec]: http://rocket.sdsu.edu/rockets
[Galactic Aztec Raspberry Pi Add-on: Igniter]: https://github.com/twyatt/galactic-aztec-rpi-addon-igniter
[SDSU Rocket Eagle Libraries]: https://github.com/twyatt/SDSURocket-Eagle-Libraries
[T-568B]: https://en.wikipedia.org/wiki/TIA/EIA-568#Wiring
[Galactic Aztec April 18th, 2015 launch]: https://github.com/twyatt/galactic-aztec-launch-data
[380-1046-ND]: http://www.digikey.com/product-detail/en/SS-7188-NF/380-1046-ND/388308
[475-1195-2-ND]: http://www.digikey.com/product-detail/en/LS%20L29K-H1J2-1-Z/475-1195-1-ND/810356
[RHM12.0KADCT-ND]: http://www.digikey.com/product-detail/en/ESR03EZPF1202/RHM12.0KADCT-ND/1983756
[A98223-ND]: http://www.digikey.com/product-detail/en/796634-2/A98223-ND/1827082
[A98235-ND]: http://www.digikey.com/product-detail/en/796638-2/A98235-ND/1827094