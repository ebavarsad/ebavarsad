# Astronomy Data Research Pipeline

Welcome to the Astronomy Data Research Pipeline!!

This directory contains a scaffolded, multi-stage research framework designed to introduce undergraduate and 
community college students to authentic astronomical research using professional survey data.

Rather than isolated labs or step-by-step exercises with predetermined outcomes, this pipeline is organized 
around the actual workflow used by astronomers:

scientific questions → database queries → data selection → analysis → interpretation → communication

Students work with real measurements, real uncertainties, and real limitations.  
The emphasis is on research literacy, reproducibility, and clear scientific reasoning — not on memorizing 
procedures or producing “perfect” plots.

---

## Who This Is For

This pipeline is designed for students who are:
- enrolled at community colleges or early undergraduate programs,
- interested in astronomy or data-driven science,
- planning to transfer into STEM fields,
- comfortable with basic algebra and introductory Python concepts.

No prior research experience is assumed.  
Curiosity and willingness to engage with data matter more than background.

---

## What Students Will Learn

By completing one or more modules in this pipeline, students learn how to:

- Work with large, publicly available astronomical datasets
- Retrieve observational data using structured database queries
- Interpret measurements with units, uncertainties, and selection effects
- Apply data quality criteria and explain why those choices matter
- Build and interpret scientifically meaningful plots
- Communicate results clearly, including assumptions and limitations
- Prepare poster-ready figures for presentations and symposia

The goal is not to arrive at a single “correct” answer, but to develop the ability to support claims with 
evidence and reasoning.

---

## How the Pipeline Is Organized

Each major astronomical survey or database is contained in its own folder (for example, `gaia/`, `sdss/`), and 
each module includes:
- a dedicated README describing the dataset and goals,
- a sequenced set of notebooks,
- and clearly stated learning outcomes.

Notebooks are meant to be completed in order within each module, while modules themselves may be used 
independently or combined depending on course goals.

---

## Current Modules

### Gaia Module (`gaia/`)
Focused on stellar astronomy using Gaia DR3 data.

Students engage with:
- large astrometric catalogs,
- color–magnitude and HR diagrams,
- stellar kinematics and proper motion,
- star cluster identification and membership reasoning.

---

### SDSS Module (`sdss/`) (in development) ( check in mid March :-) )
Focused on imaging and extragalactic astronomy.

Planned topics include:
- photometric catalogs,
- galaxy colors and populations,
- basic redshift concepts,
- and color–color diagram analysis.

---

## Student Deliverables

Depending on the course or instructor, students may produce:
- cleaned and documented datasets,
- clearly labeled scientific plots,
- short written analyses,
- research posters or oral presentations.

These deliverables are suitable for:
- department hallway displays,
- undergraduate research symposia,
- transfer, scholarship, or internship portfolios.

---

## Teaching Notes

- Internet access:  
  Some school networks block access to astronomical databases.  
  The notebooks support loading cached CSV files generated off-network.

- Assessment:
  Exercises and exit tickets are embedded throughout the notebooks and can be used for formative assessment, 
grading, or portfolio review.

- Adaptability:
  Instructors may shorten, extend, or remix modules to fit course structure, pacing, or student preparation.

---

## Data and Tools

Students work with real, publicly available astronomical data and professional tools, including:
- Survey data from missions such as Gaia and SDSS
- Python libraries commonly used in astronomy and data science:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `astroquery`
  - `astropy`

These tools reflect current practice in observational astronomy and related data-driven fields.

---

## Final Note

This pipeline is designed to move students from following instructions to making informed decisions with 
data.

By the end of the sequence, students should feel comfortable navigating unfamiliar datasets, questioning results 
that seem suspicious, explaining their methodological choices, and discussing both the strengths and limitations 
of their analysis.
