# Throat plates for circular table saws

3D models designed in FreeCAD (0.20 or later)

## Designed for high manufacturability and low cost

* Machined from 10-12 mm sheet (depending on elasticity)
* Designed for 3-axis machining
* Low tolerance requirements
* Floor fillets in pockets?
  * Do they add cost if a _Bull Nose End Mill_ is used and its radius matches the floor fillet?
  * Should the design include fillets, or _Bull Nose End Mill_ be specified separately for the pockets.
* Undercutting/T-Slot (Slotting Cutter)?
  What are the standard diameters, height and "reach" of the T-Slot mills?
* Drill holes in sides of 10 mm plate?
  Does the object need to be mounted vertically? Cost?
* Chamfering bottom edge of object?
  Does the object (sheet) need to be turned, or can a fillet be made using a dovetail mill?


## Mill Tools

* End Mill
  An end mill is the most common type of tooling and can typically cut in 3 directions. They come in various styles such as flat, corner radius, roughing, ball and taper to name a few. They are characterised by the number of flutes, helix angles, base material and coating material.
* Face Mill
  A face mill is designed to cut across a large surface area, i.e. facing. Its cutting edges are typically on the edge of the tool and the teeth are usually carbide inserts.
* Thread Mill
  A thread mill is designed to create threads, it works by rotation around the shank in a helical pattern to cut in the thread shape.
* Slotting Cutter
  These types of cutter are used to create t-slots along the length of a part. The tool must enter and exit from an open side of the material due to its geometry.
* Chamfer Mill
* Backside Chamfer Mill
* Rounding End Mill (fillets)

## Materials

Important properties: low elasticity, low cost, low friction, availability of colors (blue, red, yellow, green).

| Material | Other Names | Flexural Modulus | Coefficient of Friction, Static | Notes |
| :--- | :--- | :--- | :--- | :--- |
| [Acetal, Copolymer (unreinforced, extruded)](https://www.matweb.com/search/DataSheet.aspx?MatGUID=41729a655cb24c949f1361cc6b5b1a5d) | POM-C | 2.66 GPa	| |
| [Acetal, Homopolymer (unreinforced, extruded)](https://www.matweb.com/search/DataSheet.aspx?MatGUID=c6564de5b78a4887850d777d445c9ca7) | POM-H, Delrin | 3.45 GPa | |
| [Nylon 66  (unreinforced, extruded)](https://www.matweb.com/search/DataSheet.aspx?MatGUID=25c36a3b22a44c0784cc29aae943a550) | Polyamide 66, PA 66 | 3.10 GPa | | |
| Aluminum 2011 | | 70.3 GPa | | [Machinability: 90%](https://www.matweb.com/search/DataSheet.aspx?MatGUID=8c05024423d64aaab0148295c5a57067) |
| Aluminum 3003 | | 68.9 GPa | | [Machinability: 30%](https://www.matweb.com/search/DataSheet.aspx?MatGUID=fd4a40f87d3f4912925e5e6eab1fbc40) |
| [Aluminum](https://en.wikipedia.org/wiki/Aluminium_alloy#Wrought_alloys), 6061 | | [68.9 GPa](https://www.matweb.com/search/datasheet.aspx?MatGUID=626ec8cdca604f1994be4fc2bc6f7f63) | | [Machinability: 30%](https://www.matweb.com/search/datasheet.aspx?MatGUID=626ec8cdca604f1994be4fc2bc6f7f63) |
| Aluminum 1100 | | [68.9 GPa](https://www.matweb.com/search/DataSheet.aspx?MatGUID=db0307742df14c8f817bd8d62207368e) | | [Machinability: 10%](https://www.matweb.com/search/datasheet.aspx?matguid=db0307742df14c8f817bd8d62207368e) |

## CNC Machining Suppliers

* [Alibaba Search](https://www.alibaba.com/trade/search?fsb=y&IndexArea=product_en&categoryId=100004566&keywords=cnc+milling&knowledgeGraphId=100000004-10000000053%2C100001543-10000048389%2C100007633-10000050672&tab=all&viewtype=L&)
  * [Dongguan Qixin Plastic hardware Co., LTD](https://www.alibaba.com/product-detail/High-Precision-Factory-Direct-Turning-Milling_1600640947291.html)
  * [Shenzhen Tuofa Technology Co., Ltd](https://www.tuofa-cncmachining.com/cnc-machining-service/cnc-milling/)  ([Alibaba](https://www.alibaba.com/product-detail/Custom-Cnc-Machining-Milling-Turning-Plastic_1600122747548.html))
  * [Shenzhen View Well Industry Co., Ltd.](https://www.alibaba.com/product-detail/High-precision-custom-cnc-machining-parts_1600209551326.html)
  * [Dezhou Weichuang Rubber & Plastic ...](https://www.alibaba.com/product-detail/Customized-Plastic-Nylon-POM-HDPE-CNC_1600462421882.html)
  * [Dongguan Shuangxin Industry Co., Ltd.](https://www.alibaba.com/product-detail/Custom-CNC-Machining-Milling-Milled-Turning_1600380920277.html)
  * [Shenzhen Ruixing Precision MFG](https://www.alibaba.com/product-detail/Customized-Cnc-Turned-Milling-Peek-Pom_1600584209321.html)
  * [Jiangyin Yolanda Metal Technology ...](https://www.alibaba.com/product-detail/POM-Nylon-PEEK-ABS-Various-Colors_1600598442696.html)
  * [Xiamen Jingfeng Mechanical Engineering ...](https://www.alibaba.com/product-detail/Free-sample-5-Axis-Peek-Plastic_1600607551764.html)
* China, Instant Quote
  * [RapidDirect](https://www.rapiddirect.com/services/cnc-milling/) (China, instant quote)
  * [PCBWay](https://www.pcbway.com/rapid-prototyping/manufacture/?type=1&reffercode=TOP) (China, instant quote)
  * [UnionFab](https://www.unionfab.com/service/cnc-milling) (China, instant quote, Nylon-66 only?)
  * [FirstPart](https://firstpart.com/cnc-milling/) (China, instant quote)
  * [HLH Prototypes](https://www.hlhprototypes.com/cnc-machining/)
* China, website (Google)
  * [China Shenzhen Tuofa Precision CNC Machining Manufacturer](https://www.tuofa-cncmachining.com/cnc-machining-service/cnc-milling/)
  * [KAIAO](https://www.kaiaorapid.com/cnc-machining/)
  * [Kintech](https://www.kintec-machining.com/CNC-Milling-Services.html)
  * [CNC Now](https://cncnow.com/cnc-milling-services/)
* EU, Instant Quote
  * [Xometry](https://xometry.eu/en/cnc-milling/)  (USA/Europe, instant quote)
  * [Hubs](https://www.hubs.com/cnc-machining/cnc-milling-service/) (USA/EU, instant quote)
* Previous Contact
  * https://sinorisemfg.com/ (China, previous offers via Alibaba)
  * [Qingdao Tongxingrui Metal Products Co., Ltd](https://www.company-list.org/qingdao_tongxingrui_metal_products_co_ltd.html) (China, previous orders via Alibaba, aluminum)

## DeWalt zero clearance insert

For DW945, ... TODO

