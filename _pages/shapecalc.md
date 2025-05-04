---
layout: single
title: "ShapeCalc"
permalink: /shapecalc/
header:
  overlay_image: /assets/images/Banner_ShapeCalc.jpg
  overlay_filter: 0.1
---

## Estimate 3D crystal shapes from 2D data – robustly and consistently

**ShapeCalc is a free, Excel-based tool that estimates 3D crystal shapes from 2D intersection data — with greater accuracy and flexibility than previous methods.**


🔽 [**ShapeCalc: Direct Download**](https://github.com/MartinMangler/ShapeCalc/releases) 

📄 [Read the full documentation](https://github.com/MartinMangler/ShapeCalc/blob/main/ShapeCalc_documentation.pdf)    
📽️ [Jump to video demo](#how-shapecalc-works)  
[![GitHub Repo](https://img.shields.io/badge/GitHub-ShapeCalc-black?logo=github&style=flat)](https://github.com/MartinMangler/ShapeCalc)  

---

Understanding the **numbers, shapes and sizes of crystals in volcanic rocks** is key to reconstructing magmatic processes such as **magma storage**, **cooling and crystallisation rates**, and **magma ascent**. It is also essential for **Crystal Size Distribution (CSD) analysis**, a powerful method to reconstruct crystallisation histories.

Yet, estimating **3D crystal shapes from 2D thin sections** can be complex and prone to errors. For example, cut-section effects demand statistical treatment and stereological projection of 2D data to estimate 3D crystal shapes. Existing tools such as CSDslice often yield inaccurate results, especially when dealing with natural crystals that vary in shape and size. 

To address this challenge, we developed **ShapeCalc**. 

ShapeCalc is the most robust tool to calculate 3D crystal shape from 2D textural data because it:

- Resolves a wider range of **realistic crystal shapes** than any other comparable tool
- Provides **uncertainty estimates** for each 3D shape solution
- Uses the same algorithms as **CSDCorrections** (Higgins, 2000), enabling internally consistent CSD workflows

### Easy-to-Use and Accessible

ShapeCalc is designed for ease of use and can be run in **Excel**. All you need to provide are **2D crystal width and length measurements**, which can be obtained using tools like [ImageJ](https://imagej.net/ij/). The tool is simple to run, with no special software or complicated setups required.

### How ShapeCalc Works

ShapeCalc compares your 2D length and width data with 2D width-length distributions of randomly intersected **3D model shapes**. By matching your data to these models, ShapeCalc generates estimates of the corresponding 3D aspect ratios and provides uncertainty metrics for each shape.

Watch this short walkthrough of ShapeCalc in action:

<iframe width="560" height="315" src="https://www.youtube.com/embed/5qarOaO2ETA?si=7M0rntgv-MVsY39H" title="ShapeCalc video" frameborder="0" allowfullscreen></iframe>

---

### Why Use ShapeCalc?

Before the release of **ShapeCalc**, the most widely used tool for estimating **3D crystal shapes from 2D thin section data** was **CSDslice** (Morgan & Jerram, 2006). Like ShapeCalc, CSDslice estimates 3D crystal shapes by comparing natural 2D width–length measurements with synthetic 2D distributions derived from 3D model shapes. However, **ShapeCalc provides significantly more accurate and geologically meaningful results** — particularly for samples containing **multiple crystal populations** with varying shapes and sizes, as is common in igneous rocks ([Mangler et al., 2022](https://link.springer.com/article/10.1007/s00410-022-01922-9)).

In a direct comparison of synthetic 2D width–length distributions, **CSDslice produces non-unique outputs for prismatic model shapes** (e.g., short:intermediate dimension aspect ratio = 1:1). For example, CSDslice cannot reliably distinguish between a **single population of elongate crystals** and a **mixture of three populations with different shapes**. This can lead to erroneous results — such as returning a dominant prismatic shape even when the real sample contains more complex or varied textures (see Panel d in the figure below). 

![Comparison of model outputs from CSDslice and ShapeCalc for various 3D shapes](/assets/images/ShapeCalc_v_CSDslice.jpg)

*Fig: (a–c) Comparison of model 2D width/length distributions from CSDslice (dotted) and ShapeCalc (solid). Each is based on 10,000 (CSDslice) or 20,000 (ShapeCalc) random sections. (a) 1:2:4, (b) 1:10:10, (c) 1:1:10. Note significant mismatch for 1:1:10 model shape. (d) Mixing three CSDslice populations yields similar output to the 1:1:10 model, illustrating non-uniqueness and potential misinterpretation.*

For detailed documentation, example datasets, and installation instructions, visit the [ShapeCalc GitHub repository](https://github.com/MartinMangler/shapecalc).

---

## Further reading

[Mangler et al., 2022 – Petrology & ShapeCalc benchmarking](https://link.springer.com/article/10.1007/s00410-022-01922-9)  
[Full documentation PDF](https://github.com/MartinMangler/ShapeCalc/blob/main/ShapeCalc_documentation.pdf)

---

## Get started

[Download ShapeCalc](https://github.com/MartinMangler/ShapeCalc/releases)  
Questions or feedback? [Open an issue](https://github.com/MartinMangler/ShapeCalc/issues) or [contact me](/#contact)
