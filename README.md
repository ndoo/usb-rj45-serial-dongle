# USB RJ-45 Serial Dongle

A small USB to RS232 serial dongle, presented as a female RJ-45 jack that can be used with your choice of straight-through cable. Pinout is stanard Cisco RJ-45 console. Compatibility may vary with other vendors.

## Motivation

Commercial USB to Cisco-style serial cables are generally a single molded assembly, which means any issues with the RJ-45 jack (such as retention clip breaking) or forceful disconnection such as dropping your laptop, may neccesitate replacing the entire dongle.

By presenting a female RJ-45 jack, you now have the freedom to choose any length and quality of straight-through Ethernet cable, and replace it as clips break.

## Bill of Materials and Ordering

| Designator        | MPN                 | Qty | Link                                                                                                       |
|-------------------|---------------------|-----|------------------------------------------------------------------------------------------------------------|
| C1,C3             | CC0402MRX5R5BB475   | 2   |                                                                                                            |
| C2,C4,C5,C6,C7,C8 | CC0402KRX7R8BB104   | 6   |                                                                                                            |
| R1                | RC0402FR-071KL      | 1   |                                                                                                            |
| R2,R3             | RC0402FR-07330RL    | 2   |                                                                                                            |
| U1                | CP2102N-A01-GQFN20R | 1   | https://www.digikey.sg/product-detail/en/silicon-labs/CP2102N-A01-GQFN20R/336-4826-1-ND/8619802            |
| U2                | MAX202ECWE+         | 1   | https://www.digikey.sg/product-detail/en/maxim-integrated/MAX202ECWE/MAX202ECWE-ND/947811                  |
| U3                | SP0503BAHTG         | 1   | https://www.digikey.sg/product-detail/en/littelfuse-inc/SP0503BAHTG/F2715CT-ND/1154322                     |
| J1                | RJHSE-5081          | 1   | https://www.digikey.sg/product-detail/en/amphenol-icc-commercial-products/RJHSE-5081/RJHSE-5081-ND/1242688 |

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* USB connector is from USBPCB from Sparkfun's EAGLE libraries

