# Earth Core Robot Design Specifications

###### This document is not professional at all unlike the other one... ignore. I took more time on that one and this is just a rough draft

- Materials
  - Would need to withstand 5,500° C
    - How would this work? Potentially tungsten or tantalum carbide?
      - It will use **Tantalum Hafnium Carbide Alloy**. The melting point of it at 1 atmosphere is 3990℃, while the melting point of iron (what the core is made up of) is 1538°C. The immense pressure would raise the melting point of each material when under 3 million atmospheres. The iron at the center of the Earth is suspected to have a melting point of 6230 ± 500 Kelvin.
  - Would need to withhold 3 Million atmospheres of pressure
    - **Diamond-anvil-cell-like design**??
      - **Yes**
  - Radiation shielding
    - The core most likely has radiation. Potential shielding with lead, tungsten or combination of materials?
      - It will use **Lead.**
- Propulsion
  - Laser?
    - Traditional drilling methods wouldn’t work, potentially using high-powered lasers or microwaves to melt rock??
      - It will use an **extremely high powered laser**, powered by the **nuclear reactor**
- Power source
  - **Nuclear Fission**
    - A **powerful nuclear reactor** would provide sustainable energy that is required
- Additional features:
  - Self-repair mechanisms
    - **High temperature metallic microwelding**
      - It could have a special **3d printer** which uses **metal filaments** infused with **high-temperature nanoparticles**, which would be triggered by sensors.
    - **Modular design**
      - Basically like the **Framework Laptop** - if something goes wrong, there are spare parts. If a component fails, the robot could detach it, retrieve a spare, and swap them.

# Travel plan through layers

| Layer        | Distance to travel through layer | Target speed within layer | Estimated time through layer | Temperature   |
|--------------|----------------------------------|---------------------------|------------------------------|---------------|
| Crust        | 30 km                            | 10 km/hr                  | 3 hours                      | 200-400°C     |
| Mantle       | 2,900 km                         | 20 km/hr                  | 145 hours                    | 1,000-2,700°C |
| Lithosphere  | 100 km                           | 10 km/hr                  | 10 hours                     | 300-500°C     |
| Asthenosphere| 2,800 km                         | 20 km/hr                  | 140 hours                    | 1,300-2,200°C |
| Outer Core   | 2,200 km                         | 50 km/hr                  | 44 hours                     | 4,500-5,500°C |
| Inner Core   | 1,200 km                         | 30 km/hr                  | 40 hours                     | 5,200-6,000°C |
