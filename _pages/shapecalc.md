---
layout: single
title: "ShapeCalc"
permalink: /shapecalc/
header:
  overlay_image: /assets/images/Banner_ShapeCalc.jpg
  overlay_filter: 0.1
---

## ShapeCalc: Robust 3D Crystal Shape Estimation from 2D Data

The size, number, and shape of crystals in volcanic rocks tell a unique story of the magma’s journey through the Earth's crust. **Crystal shape** is a key petrological parameter, providing insights into magmatic conditions such as **cooling rates**, **melt composition**, and **crystallization processes**. It is also crucial for **Crystal Size Distribution (CSD) analysis**, a technique used to interpret pre-eruptive magmatic histories.

### The Challenge with Estimating 3D Crystal Shapes

Estimating 3D crystal shapes from 2D thin sections, as seen in microscopy, can be complex and prone to errors. For example, cut-section effects demand statistical treatment and stereological projection of 2D data to estimate 3D crystal shapes. Existing tools often yield inaccurate results, especially when dealing with natural crystals that vary in shape and size. 

Together with my co-workers, I demonstrated that existing methods can be unreliable, leading to misinterpretations [(Mangler et al., 2022)](https://link.springer.com/article/10.1007/s00410-022-01922-9). In response, we developed **ShapeCalc**—a free and open-source tool for generating more accurate 3D shape estimates based on 2D crystal intersection data.

### Why ShapeCalc is Different

ShapeCalc leverages **synthetic 3D model shapes** (such as equant, prismatic, and tabular models) to compare against your 2D data. The tool uses the same algorithms behind the widely-used [**CSDCorrections**](https://mdhiggins.ca/csdcorrections.html) tool (Higgins, 2000), which ensures **internally consistent** and **robust** CSDs when combined with ShapeCalc. This makes ShapeCalc the only tool that provides reliable 3D shape estimates that are consistent with standard CSD methods.

In addition to best-fit 3D shapes, ShapeCalc also provides **uncertainty estimates**, which help ensure that your interpretations are robust and reliable.

### Easy-to-Use and Accessible

ShapeCalc is designed for ease of use and can be run in **Excel**. All you need to provide are **2D crystal width and length measurements**, which can be obtained using tools like [**ImageJ**](https://imagej.net/ij/). The tool is simple to run, with no special software or complicated setups required.

### How ShapeCalc Works

ShapeCalc compares your 2D length and width data with 2D width-length distributions of randomly intersected **3D model shapes**. By matching your data to these models, ShapeCalc generates estimates of the corresponding 3D aspect ratios and provides uncertainty metrics for each shape.

### Learn More and Download ShapeCalc

Here’s a video showing how ShapeCalc works in practice:  
<iframe width="560" height="315" src="https://www.youtube.com/embed/5qarOaO2ETA?si=7M0rntgv-MVsY39H" title="ShapeCalc video" frameborder="0" allowfullscreen></iframe>

For detailed documentation, example datasets, and installation instructions, visit the [ShapeCalc GitHub repository](https://github.com/MartinMangler/shapecalc).

To download ShapeCalc directly, click below:  
**[Download ShapeCalc](https://github.com/MartinMangler/ShapeCalc/raw/refs/heads/main/Shapecalc_v1.0.xlsx)**

Planning to use ShapeCalc to calculate Crystal Size Distributions? - Click below to download the latest version of CSDCorrections:  
**[Download CSDCorrections 1.61](https://mdhiggins.ca/csdcorrections.html)**

---

### Key Features of ShapeCalc

- **Accurate 3D shape estimation** based on 2D crystal size data.
- **Uncertainty estimates** for more robust interpretations.
- Internally consistent and compatible with **CSDCorrections**.
- **Free and open-source** (Excel-based).
- Easy-to-use interface with no advanced software requirements.

---

### ShapeCalc in Action

By combining ShapeCalc with the gold-standard CSD tool CSDCorrections, you can achieve the most reliable and internally consistent CSDs, allowing for better geological interpretations. Whether you're studying volcanic rocks, plutonic formations, or other igneous rocks, ShapeCalc provides a powerful tool for shape analysis.

---

*Note: If you are planning to publish your CSD analysis or include it in scientific research, ShapeCalc's integrated uncertainties and consistent workflow make it ideal for high-quality, reproducible results.*

---

### Additional Resources

- [ShapeCalc Documentation](https://github.com/MartinMangler/ShapeCalc/blob/main/ShapeCalc_documentation.pdf)
- [ShapeCalc GitHub Repository](https://github.com/MartinMangler/shapecalc)


