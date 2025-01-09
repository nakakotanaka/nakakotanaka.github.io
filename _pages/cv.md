---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Plant Biology with specialization in Ecology, Evolution, and Behavior, Michigan State University, 2022
* B.S. in Clinical Plant Science, Hosei University, 2019

Work experience
======
* May 2023 - Present: Laboratory Technologist
  * Veterinary Diagnostic Laboratory, Michigan State University
  * Duties includes: molecular Diagnostic, development of bioinformatics pipeline
    
* January 2022 - May 2023: Instructor
  * Biological Sciences Program, Michigan State University
  * Duties included: Lectures, demonstration of molecular biology techniques, facilitattion of student-led research

  
Skills
======
* Bioinformatics
  * Language: R, Unix, Python
  * Operation and development of reproducible and scalable bioinformatics pipeline on HPCC
    * Tools: Nextflow, snakemake, git, conda, “renv” package
  * Experiences in viral metagenomic analysis, phylogenetic analysis, variant calling analysis
  * GUI tools: Geneious, CLC genomics workbench, 
* Molecular Biology
  * DNA/RNA extraction, PCR, RT-PCR, Agarose gel electrophoresis, Sanger sequencing, QIAxcel operation
  * Library preparation for Illumina-based sequencing platform
* Plant Virology
  * Maintenance of aphid culture, aphid-borne viruses, and plants
  * Plant virus inoculation with plant sap, insect, and grafting
  * Viral particle purification

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Presentation
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
