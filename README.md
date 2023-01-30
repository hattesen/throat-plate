# Throat plates for circular table saws

3D models designed in FreeCAD (0.20 or later)

## Design questions for manufacturability and cost

* Machined from 10-12 mm sheet (depending on elasticity)
* Floor fillets in pockets
  * Do they add cost if a _Bull Nose End Mill_ is used and its radius matches the floor fillet?
  * Should the design include fillets, or _Bull Nose End Mill_ be specified separately for the pockets.
* Undercutting / T-Slot
  * What are the standard diameters, height and "reach" of the T-Slot mills?
* Drill holes in sides of 10 mm plate.
  * Does the object need to be mounted vertically? Cost?
* Chamfering bottom edge of object.
  * Does the object (sheet) need to be turned, or can a fillet be made using a dovetail mill?

## Material

Important properties: low elasticity, low cost, low friction, availability of colors (blue, red, yellow, green).

| Material | Other Names | Flexural Modulus | Coefficient of Friction, Static | Notes |
| :--- | :--- | :--- | :--- | :--- |
| Acetal, Copolymer | POM-C, Delrin | [3.07 GPa (0.586 - 11.7)](https://www.matweb.com/search/DataSheet.aspx?MatGUID=c3039ef87c9245448cdebe961b19a54c) | [0.144 (0.11 - 0.27)](https://www.matweb.com/search/DataSheet.aspx?MatGUID=c3039ef87c9245448cdebe961b19a54c) |
| Acetal, Homopolymer | POM-H | [2.77 GPa (1.38 - 3.90)](https://www.matweb.com/search/DataSheet.aspx?MatGUID=ae460978fb0a4d7b8c3ce6bf8f4bf52b) | [0.228 (0.14 - 0.45)](https://www.matweb.com/search/DataSheet.aspx?MatGUID=ae460978fb0a4d7b8c3ce6bf8f4bf52b) |
| [Nylon 12 (unfilled)](https://en.wikipedia.org/wiki/Nylon_12) | Polyamide 12, PA 12 | [0.912 GPa (0.332 - 2.23)]() | | |
| Aluminum 2011 | (Alloy) | 70.3 GPa | | [Machinability: 90%](https://www.matweb.com/search/DataSheet.aspx?MatGUID=8c05024423d64aaab0148295c5a57067) |
| Aluminum 3003 | (Alloy) | 68.9 GPa | | [Machinability: 30%](https://www.matweb.com/search/DataSheet.aspx?MatGUID=fd4a40f87d3f4912925e5e6eab1fbc40) |
| [Aluminum](https://www.weerg.com/guides/aluminium-alloy-grades-and-applications), 6061-O | *** (Alloy) | [68.9 GPa](https://www.matweb.com/search/datasheet.aspx?MatGUID=626ec8cdca604f1994be4fc2bc6f7f63) | | [Machinability: 30%](https://www.matweb.com/search/datasheet.aspx?MatGUID=626ec8cdca604f1994be4fc2bc6f7f63) |
| Aluminum 1100 | (99% pure) | [68.9 GPa](https://www.matweb.com/search/DataSheet.aspx?MatGUID=db0307742df14c8f817bd8d62207368e) | | [Machinability: 10%](https://www.matweb.com/search/datasheet.aspx?matguid=db0307742df14c8f817bd8d62207368e) |


## DeWalt zero clearance insert

For DW945, ... TODO

