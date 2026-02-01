# Gaia Research Module  
### Working with Real Stellar Data in Jupyter Notebooks

Welcome to the **Gaia Research Module**.

This folder contains a sequence of Jupyter notebooks that will guide you through working with **real 
astronomical data from the Gaia space mission**. These notebooks are designed to help you learn how 
astronomers use data, not just how to run code.

If this is your first time using Jupyter notebooks or working with real scientific data, that is completely 
fine. The notebooks are written to be read slowly and worked through step by step.

---

## Before You Start: What You Need

To work with these notebooks, you need:

- A working Python environment (Anaconda recommended)
- Jupyter Notebook or JupyterLab
- Basic comfort running code cells (Shift + Enter)
- Patience when things don’t work on the first try

You do **not** need:
- advanced programming experience
- prior astronomy research experience
- to understand every line of code immediately

---

## Making Sure Jupyter Is Working

Before opening any Gaia notebook, confirm that:

1. You can launch Jupyter Notebook or JupyterLab from Anaconda
2. You can open a notebook file (`.ipynb`)
3. You can run a simple code cell without errors

If you see output below a code cell after running it, Jupyter is working.

If nothing happens:
- check that the cell is selected,
- press **Shift + Enter** (not just Enter),
- make sure the kernel is running.

---

## Required Python Packages

The notebooks use standard scientific Python packages:

- `numpy`
- `pandas`
- `matplotlib`
- `astroquery`
- `astropy`

Most Anaconda installations already include these.  
If a notebook fails to import a package, the error message will tell you which one is missing.

Do not panic. Installation instructions are provided in the first notebook.

---

## About Internet Access

Some school networks block access to astronomical databases, including the Gaia archive.

Because of this:
- some notebooks include **two options**:
  - querying the database directly (for home use)
  - loading a cached CSV file (for school use)

If you see instructions labeled **HOME ONLY**, skip them at school.

This is normal and expected.

---

## How to Use the Notebooks

Each notebook is meant to be completed **in order**.

You should:
- read the text cells carefully,
- run each code cell in sequence,
- pause to examine tables and plots before moving on,
- change parameters only when instructed.

If a plot looks strange, that is not a failure — it is something to investigate.

---

## Understanding the Output

You will frequently see:

### Tables
Tables represent collections of stars.
- Each **row** is one object
- Each **column** is a measured property (position, brightness, motion)

Not all values are trustworthy. Learning how to recognize this is part of the project.

### DataFrames
Most data will appear as **Pandas DataFrames**.
These are tables designed for analysis and plotting.

If you can:
- display a DataFrame,
- identify column names,
- and describe what a column represents,

you are doing well.

### Plots
Plots are central to astronomical analysis.

Every plot should have:
- labeled axes (with units when possible),
- a descriptive title,
- and an explanation in words of what it shows.

You are not graded on aesthetics — clarity matters more.

---

## Notebook Sequence

### 00_Getting_Started.ipynb
**Getting comfortable with tools and data**

This notebook helps you:
- understand what astronomical data look like,
- learn what tables and columns represent,
- understand units and uncertainties,
- and build confidence running notebooks.

---

### 01_ADQL_Foundations.ipynb
**Asking the Gaia database for data**

You will learn how to:
- write simple database queries,
- perform sky searches,
- limit and sort results,
- load data into Python for analysis.

The focus is on **how to ask questions**, not on astrophysics.

---

### 02_Gaia_Fundamentals.ipynb
**Understanding Gaia measurements**

This notebook explains:
- what Gaia measures,
- what parallax and proper motion mean,
- how brightness and color are defined,
- why uncertainty and data quality matter.

This notebook is about **avoiding common mistakes**.

---

### 03_HR_Diagram_Project.ipynb
**Building color–magnitude and HR diagrams**

You will:
- analyze a real region of the sky,
- build CMDs and HR diagrams,
- test how data quality choices affect results,
- create figures suitable for a research poster.

---

### 04_Cluster_Membership.ipynb
**Identifying star cluster members**

You will:
- identify clusters using proper motion,
- refine membership using parallax,
- separate cluster stars from background stars,
- build cluster-only HR diagrams.

---

## What Success Looks Like

Success in this module is measured by your ability to use Gaia data *intentionally*.

By the end of the notebook sequence, you should be able to:

- Identify which scientific questions Gaia data can realistically address
- Explain which Gaia measurements are relevant to a given question
- Distinguish between raw data and quality-controlled samples
- Justify basic selection criteria (for example, signal-to-noise or fit quality)
- Interpret tables and plots in terms of physical meaning, not just appearance

---

## Can or Cant do

Gaia is well suited to answering questions about:

- stellar positions and motions in the Milky Way
- relative distances to nearby stars
- stellar populations and sequences in color–magnitude space
- the identification of star clusters and moving groups
- large-scale structure in the solar neighborhood

Gaia is not designed to answer questions about:
- detailed stellar interiors,
- precise ages of individual stars,
- small-scale variability,
- or distant galaxies.
