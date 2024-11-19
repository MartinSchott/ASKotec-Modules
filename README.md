# #ASKotec inspired mini Modules

> A new generation of [#ASKotec](https://ASKotec.openculture.agency) inspired mini Training Kits with use-case specific layer options and a DIN A4 blueprint reference

- If you have any suggestions, please make sure to file an [Issue](https://github.com/opencultureagency/ASKotec-Modules/issues)
- Feel free to Fork this Repository in Order to send in your own Module Designs or Additional Material to merge via [Pull Request](https://github.com/opencultureagency/ASKotec-Modules/pulls)
- Respect the Open Source [License Note below](README.md#license-references)

## [Work in Progress] ... under Development

![](assets/prototyping.jpg)

![](assets/prototyping-2.jpg)

## ToDo
- [x] Design a Concept
- [x] Upload Grid Base Plate for prototyping
- [x] Build first Protoype for Repair
- [x] Build First Prototype for Radio
- [x] Build first Prototype for Multimedia
- [ ] Build first Prototype for Solar
- [ ] Upload Spreadsheet for available BOMs
- [ ] Provide Meta Instructions on all Training Kits
- [ ] Double Check Folder/File Structure
- [ ] Double Check CAD Versioning vs. Repo Versioning
- [ ] more to come



# Training Kits [WIP]

## Repair - Basic Tools

**Modules (Layer 1-4)**

- Module M001: Basic Essensials
- Module M002: Basic Soldoring Tools
- Module M003: Basic Mobile Repair Tools
- Module M004: Basic Mechanical Tools

## Radio - DIY

**Modules (Layer 1-3)**

- Module M002: Basic Soldoring Tools
- Module M005: Radio Accessories
- Module M006: Radio Assembly

## Multimedia - Hub

**Modules (Layer 1-4)**

- Module M007: Media Controle
- Module M008: Media Center
- Module M009: Audio Extras
- Module M010: Media Accessories

---

---


# CAD

## Grid Base Plate

> Current CAD/2D Drawing designed in FreeCAD v0.21.2 using the workbenches `Part Design`, `Spreadsheet` and `TechDraw`.
>
> Designed to work in combination with a [MAX300](https://xenotec-shop.de/produkt/max300/) case (but can be adjusted/used in other forms/packings as well as it fits DIN A4 Paper format)
>
> Technical Specs of the Grid-Base-Plate see Drawing below:

![](CAD/Grid-Base-Plate/TechnicalDrawing+16mm.svg)

- Reference Design will have 32mm+16mm Double Grid and R20 Corners currently
- Older variations can be found via [Archive](Archive/)
- FreeCAD Files and Exports in [PDF](CAD/Grid-Base-Plate/TechnicalDrawing+16mm.pdf) for reference, and [SVG](CAD/Grid-Base-Plate/Base-16grid-9x6+8x6+1+16mm_R20.svg), [DXF](CAD/Grid-Base-Plate/Base-16grid-9x6+8x6+1+16mm_R20.dxf) for manufacturing are available for Adoption/Scaling/Lasercutting etc.
- > Note: If you make adjustments and play around in the parameters (parametric Spreadsheed reference), in some cases you need to fix the TechDraw measurements


---

### **Optimized Version 32mm x 32mm + 16mm Offset**

> 5mm Boring Holes  
>
> Base Grid: 6x9 (x32mm) +16mm = 208x288mm (close to DIN A4)
>
> Extra Grid: 6x8 (x32mm) with 16mm Offset
>
> 20mm Corner Radius
>
> [SVG](CAD/Grid-Base-Plate/Base-16grid-9x6+8x6+1+16mm_R20.svg), [DXF](CAD/Grid-Base-Plate/Base-16grid-9x6+8x6+1+16mm_R20.dxf) for manufacturing are available and for editing [FreeCAD](CAD/Grid-Base-Plate/32-grid-Base-Plate+16mm.FCStd)

![](CAD/Grid-Base-Plate/Base-16grid-9x6+8x6+1+16mm_R20.svg)


### [old] **Original Version 32mm x 32mm**

> 5mm Boring Holes  
>
> Base Grid: 6x9 (x32mm) = 192x288mm 
>
> 20mm Corner Radius
>
> **Only for Reference** (will not fit perfectly in the case)

![](CAD/Grid-Base-Plate/Archive/Base-32grid-9x6_R20.svg)


---

---


# Software

For some of the Kits (e.g. Multimedia - Hub) a software setup will be needed to complete the build. Those instructions and further details are available in the [Software/README.md](Software/README.md).

---

---


# LICENSE References

- **All Documentation** is Licensed as [CC-BY-SA 4.0](LICENSE_CC_BY_SA_4.0.md) and for further collaboration/integration all **Module CAD Designs** are also available under [CERN OHL W 2.0](CAD/LICENSE_cern_ohl_w_v2.txt). 
- (Future Software Packages might also Reference other compatible Licenses here as MIT, Apache or a respective GPL License)
- > Original Inspiration comes from [#ASKotec Main Repo](https://github.com/opencultureagency/ASKotec) under CC-BY-SA 4.0 (though this new design is developed from the ground up)