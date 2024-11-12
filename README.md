# Apple-1

The repository contains build details for the Apple-1 computer. You can find the parts list (and specific parts that I used in my build) below.

Apple-1 motherboards are available for sale at [https://www.kalinchuk.com/product-page/apple-1-replica-pcb-gold-plated](https://www.kalinchuk.com/product-page/apple-1-replica-pcb-gold-plated). The ACI (Apple Cassette Interface) boards are also available at [https://www.kalinchuk.com/product-page/aci-apple-cassette-interface-pcb-for-the-apple-1-gold-plated](https://www.kalinchuk.com/product-page/aci-apple-cassette-interface-pcb-for-the-apple-1-gold-plated).

This repository was created in conjunction with the [Building the Apple-1 YouTube video](https://youtu.be/XG5PeAzQp0w).

## Parts

| PART     | DESCRIPTION     | QUANTITY  | SOURCE |
|----------|-----------------|-----------|-------------------------|
| 2513     | Char. generator  | 1         | eBay; Can be substituted with CM2140) |
| 8T97     | Bus driver       | 2        | eBay                    |
| MMI 3601 | 256x4 PROM (A1 & A2) | 2    | [apple-1-replica.com](https://www.apple-1-replica.com/shop/Apple-1-PROMs-Wozmon-p561222037) or eBay |
| 2504v    | Shift register   | 7        | [apple-1-replica.com](https://www.apple-1-replica.com/shop/AM-2804PC-Shift-Register-Set-of-7-p561219796) or eBay; Can be substituted with AM2804 |
| 2519b    | Shift register   | 1        | eBay |
| 6820     | Parallel interface adapter  | 1 | [apple-1-replica.com](https://www.apple-1-replica.com/shop/Rockwell-PIA-6520-11-p561207316) or eBay; Can be substituted with a 6520 |
| DS0025C  | Clock driver     | 1        | eBay                   |
| 6502     | CPU              | 1        | eBay                   |
| 7400     | Quad NAND gate   | 3        | DigiKey; Jameco; eBay  |
| 7402     | Quad NOR gate    | 1        | DigiKey; Jameco; eBay  |
| 7404     | Hex inverter     | 1        | DigiKey; Jameco; eBay  |
| 7408     | Quad and gate    | 1        | DigiKey; Jameco; eBay  |
| 7410     | Three input nand | 2        | DigiKey; Jameco; eBay  |
| 74123    | Dual one-shot    | 1        | DigiKey; Jameco; eBay  |
| 74154    | 4:16 demux       | 1        | DigiKey; Jameco; eBay  |
| 74157    | 2:1 selector     | 2        | DigiKey; Jameco; eBay  |
| 74160    | 4 bit counter    | 1        | DigiKey; Jameco; eBay  |
| 74161    | 4 bit counter    | 5        | DigiKey; Jameco; eBay  |
| 74166    | Shift register   | 1        | DigiKey; Jameco; eBay  |
| 74174    | Hex flip flop    | 1        | DigiKey; Jameco; eBay  |
| 74175    | Quad flip flop   | 1        | DigiKey; Jameco; eBay  |
| 7427     | Triple 3 input nor gates | 1        | DigiKey; Jameco; eBay  |
| 7432     | Quad or gate     | 1        | DigiKey; Jameco; eBay  |
| 7450     | 2 input and gate | 1        | DigiKey; Jameco; eBay  |
| 74S257   | 2:1 selector     | 4        | DigiKey; Jameco; eBay  |
| MK4096   | 4kx1 DRAM        | 16 (8 min) | [apple-1-replica.com](https://www.apple-1-replica.com/shop/Intersil-MK4027N-3-set-of-16-p561208071) or eBay; Can be substituted with an MK4027 |
| NE555    | Cursor timer     | 1        | DigiKey; Jameco        |
| SCM 22D  | 44 pin expansion connector | 1 | [here](https://www.mjtronix.co.uk/products/genuine-scm-44-pin-pcb-edge-connector-used-in-apple-one) or eBay or use a substitute 44 pin connector |
| Power Connector | 6 pin 3.96mm connector  | 1 | DigiKey |
| Video Connector | 4 pin 3.96mm connector | 1 | DigiKey |
| Power header | 6 pin header | 1 | DigiKey |
| Video header | 4 pin header | 1 | DigiKey |
| P-8667 | Stancor transformer | 1 | [rs-online](https://us.rs-online.com/product/stancor/p-8667/70213277) or eBay |
| P-8380 | Stancor transformer | 1 | [rs-online](https://us.rs-online.com/product/stancor/p-8380/70600584) or eBay |
| 100 ohm | Pot video adjust | 1 | DigiKey; Jameco |
| 330 ohm | Orange-orange-brown | 1 | DigiKey; Jameco |
| 390 ohm | Orange-white-brown | 2 | DigiKey; Jameco |
| 1500 ohm | Brown-green-red | 1 | DigiKey; Jameco |
| 3000 ohm | Orange-black-red | 12 | DigiKey; Jameco |
| 7.5K ohm | Voilet-green-red | 6 | DigiKey; Jameco |
| 10K ohm | Brown-black-orange | 3 | DigiKey; Jameco |
| 27K ohm | Red-violet-orange | 1 | DigiKey; Jameco |
| .001uF | Ceramic capacitor | 1 | DigiKey; Jameco |
| .01uF | Ceramic capacitor | 4 | DigiKey; Jameco |
| .1uF | Ceramic capacitor | 17 | DigiKey; Jameco |
| 47pF | Mica capacitor for video | 1 | DigiKey; Jameco |
| 22uF | Electrolytic capacitor | 5 | DigiKey; Jameco |
| 2400uf | Electrolytic capacitor | 2 | DigiKey; Jameco |
| 5300uF | Electrolytic capacitor | 1 | DigiKey; Jameco |
| 1n914 | Diode | 4 | DigiKey; Jameco |
| 1N4001 | Rectifier | 4 | DigiKey; Jameco |
| MR500/A14F | Rectifier | 4 | DigiKey; Jameco |
| MPS3704 | Video output transistor | 1 | DigiKey; Jameco |
| 14.31818 MHz | Crystal oscillator | 1 | DigiKey; Jameco |
| LM323K | +5 volt regulator | 1 | DigiKey; Jameco |
| LM340 MP-12 (LM7812) | +12 volt regulator | 1 | DigiKey; Jameco |
| LM320 MP-12 (LM7912) | -12 volt regulator | 1 | DigiKey; Jameco |
| LM320 MP-5 (LM7905) | -5 volt regulator | 1 | DigiKey; Jameco |
| heatsink for LM323K | | 1 | DigiKey; Jameco |
| 16 pin socket | | 42 | DigiKey; Jameco |
| 14 pin socket | | 12 | DigiKey; Jameco |
| 8 pin socket | | 1 | DigiKey; Jameco |
| 24 pin socket | | 2 | DigiKey; Jameco |
| 40 pin socket | | 2 | DigiKey; Jameco |
