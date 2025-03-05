# Pink Noise Generator

![LB0002 prototype build](https://raw.githubusercontent.com/simtelic/lab0002-pink-noise-generator/refs/heads/main/resources/lab0002.png)

This kit offers a simple yet effective DIY pink noise generator. It features a compact and user-friendly design that utilizes only three transistors and one operational amplifier, making it a cost-effective and educational option for exploring the unique characteristics of pink noise. All components are through-hole, ensuring that assembly is straightforward and suitable for hobbyists of varying skill levels.

The pink-noise generator operates with a DC power supply ranging from 12V to 18V and includes a single audio output that can be directly connected to a power amplifier or preamplifier for further amplification and playback.

This is an open hardware project, and all design files are available in this repository. You can also [order an unassembled DIY kit from Simtelic](https://simtelic.com/product/pink-noise-generator/), which includes the PCB and all the necessary components for assembly and testing.

[PCBWay](https://www.pcbway.com) sponsors this project, and you can [directly order the PCB](https://www.pcbway.com/project/shareproject/Analog_pink_noise_generator_595b019c.html) from them as well.

The [datasheet](https://simtelic.com/datasheet.php?id=lb0002) and [user manual](https://simtelic.com/datasheet.php?id=lb0002) for this project are available at [simtelic.com](https://simtelic.com).

## Bill of Materials

| Designator               | Value                                                             | Quantity | Notes                                                                               |
|--------------------------|-------------------------------------------------------------------|----------|-------------------------------------------------------------------------------------|
| C101,C103                | [100μF/25V](https://s.click.aliexpress.com/e/_omJ0Eoy)            | 2        |                                                                                     |
| C102,C104                | [1000μF/25V](https://s.click.aliexpress.com/e/_olrI524)           | 2        |                                                                                     |
| C105,C106,C114           | [10μF/25V](https://s.click.aliexpress.com/e/_ompkcr2)             | 3        |                                                                                     |
| C107,C115,C116           | [0.1μF/50V](https://s.click.aliexpress.com/e/_okANxdw)            | 3        |                                                                                     |
| C108                     | [0.033μF/50V](https://s.click.aliexpress.com/e/_onlJl4o)          | 1        |                                                                                     |
| C109                     | [0.01μF/50V](https://s.click.aliexpress.com/e/_okQIYzA)           | 1        |                                                                                     |
| C110                     | [0.0033μF/50V](https://s.click.aliexpress.com/e/_oDFPQX2)         | 1        |                                                                                     |
| C111                     | [0.001μF/50V](https://s.click.aliexpress.com/e/_oDFPQX2)          | 1        |                                                                                     |
| C112                     | [330PF/50V](https://s.click.aliexpress.com/e/_oBugdCo)            | 1        |                                                                                     |
| C113                     | [100PF/50V](https://s.click.aliexpress.com/e/_oBugdCo)            | 1        |                                                                                     |
| R101,R102,R104,R105,R106 | [1KΩ(5% 1W)](https://s.click.aliexpress.com/e/_oFf5dpE)           | 5        |                                                                                     |
| R103,R107                | [2.2Ω(5% 1W)](https://s.click.aliexpress.com/e/_oFf5dpE)          | 2        |                                                                                     |
| R108,R109,R115           | [100KΩ](https://s.click.aliexpress.com/e/_onyWV8u)                | 3        |                                                                                     |
| R110,R111,R117           | [10KΩ](https://s.click.aliexpress.com/e/_onyWV8u)                 | 3        |                                                                                     |
| R112                     | [1.8MΩ](https://s.click.aliexpress.com/e/_onyWV8u)                | 1        |                                                                                     |
| R113                     | [1MΩ](https://s.click.aliexpress.com/e/_onyWV8u)                  | 1        |                                                                                     |
| R114                     | [330KΩ](https://s.click.aliexpress.com/e/_onyWV8u)                | 1        |                                                                                     |
| R116                     | [33KΩ](https://s.click.aliexpress.com/e/_onyWV8u)                 | 1        |                                                                                     |
| R118                     | [3.3KΩ](https://s.click.aliexpress.com/e/_onyWV8u)                | 1        |                                                                                     |
| D101,D102                | [1N4007](https://s.click.aliexpress.com/e/_oC87JiG)               | 2        | https://www.vishay.com/docs/88503/1n4001.pdf                                        |
| Q101                     | [TIP31](https://s.click.aliexpress.com/e/_oDikbdi)                | 1        | https://www.onsemi.com/download/data-sheet/pdf/tip31a-d.pdf                         |
| Q102                     | [TIP32](https://s.click.aliexpress.com/e/_oDikbdi)                | 1        | https://www.onsemi.com/download/data-sheet/pdf/tip32c-d.pdf                         |
| Q103                     | [2SC945](https://s.click.aliexpress.com/e/_oCgKZjW)               | 1        | https://datasheet.octopart.com/2SC945-Inchange-Semiconductor-datasheet-15979352.pdf |
| U101                     | [NJM4558](https://s.click.aliexpress.com/e/_onCjzLQ)              | 1        | https://www.nisshinbo-microdevices.co.jp/en/pdf/datasheet/NJM4558_E.pdf             |
| J101                     | [5.5mm DC Jack Socket](https://s.click.aliexpress.com/e/_o2awuTE) | 1        |                                                                                     |
| J102                     | [RCA Jack Socket](https://s.click.aliexpress.com/e/_oEL5MTS)      | 1        |                                                                                     |
| TP101                    | [Test pin (optional)](https://s.click.aliexpress.com/e/_olBI9cC)  | 1        |                                                                                     |

*All resistors are 5% 1/4W unless otherwise noted*
