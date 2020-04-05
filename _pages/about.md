---
title: "About me"
date: 2020-03-29 12:00:00 +0100
permalink: /about/
layout: single
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: assets/images/FUS-droplets_full.jpg
toc: True
gallery:
  - url: /assets/images/karate_arenasdojo.jpg
    image_path: /assets/images/karate_arenasdojo.jpg
    alt: "Uechi Ryu Kenyukai Spain"
    title: "At the Uechi Ryu Kenyukai Spain central dojo with Sensei Fujita and Sensei Arenas, 2017."
  - url: /assets/images/karate_honbudojo.jpg
    image_path: /assets/images/karate_honbudojo.jpg
    alt: "Uechi Ryu Kenyukai Okinawa"
    title: "At the Uechi Ryu Kenyukai central dojo in Okinawa with Hanshi Shinjo, 2015."
---

## Bio

My name is Miguel and I am a chemist by training, then evolved into a structural biologist by passion and with a strong interest in data science nowadays.

I studied a BSc & MSc in Chemistry at the University of Oviedo in my home region of Asturias, in northern Spain. I focused in Organic Chemistry, but I was always most interested in the biological side.

My first contact with structural biology happened during an *Erasmus* stay at the University of Florence (Italy). I had the opportunity to spend some months at the *Center of Magnetic Resonance (CERM)*, where I learned the basics of protein expression and purification, and **Nuclear Magnetic Resonance (NMR)**.

It was also during that period that I learned about **Intrinsically Disordered Proteins (IDPs)** for the first time, which quickly became my main area of interest. As a chemist stepping into molecular biology, these proteins defied my structure-centric mental schemes about molecular functions and cellular biology, sparking my curiosity.

Not less important, I met my now wife Sara during that *Erasmus* stay. She had transferred from Spain to Florence after having enjoyed a *Leonardo* grant there. I like to think that our relationship is a success for the European exchange initiatives and I strongly support such policies.

At the end of my time in Florence I met who would later be my PhD supervisor at the University of Barcelona, [Prof. Miquel Pons](https://bionmr.ub.edu). So, I moved to Barcelona in 2012 and did my MSc[^1] and then PhD studying the  the human proto-oncogene c-Src.

The thesis aimed to the characterization of a biologically important intrinsically disordered protein domain using mainly solution NMR. I was lucky to have a challenging project and an inspiring mentor, and our work allowed us to propose a general framework for the whole Src Family Kinases.

In the last year of my PhD, I spent three months with the group of [Prof. Hartmut Oschkinat](https://en.wikipedia.org/wiki/Hartmut_Oschkinat), at the **[Leibniz-Forschungsinstitut für Molekulare Pharmakologie (FMP)](https://www.leibniz-fmp.de/home.html)**. This gave me the opportunity to learn some solid state NMR and apply it to our intrinsically disordered system.

After defending my thesis in 2018, I moved to Berlin to join the Oschkinat group at the FMP as a postdoctoral researcher, where I continue to study disordered systems (but not only), now combining solution and solid state NMR.

[^1]: The adaptation of the former 5-year study plans to the [Bologna process](https://en.wikipedia.org/wiki/Bologna_Process) caught me in the middle. The equivalency of the *Licenciatura* title to BSc + MSc was only recognized after I had done a MSc to access the PhD program.

## Curriculum vitae & publications

You can see my academic CV [here](http://miguelarbesu.github.io/markdown-cv).

Please visit the [Research section](/research) for a detailed list of publications I have authored or collaborated on.

Under [Projects](/projects), you can see other works parallel to my research.

## Skills

### Experimental

Despite my degree in Organic Chemistry, I am unable to run a synthesis more
complex than the acetylation of salicylic acid. I am instead familiar with the
basics of **molecular biology** for cloning, expression and purification of proteins in bacteria. My experience includes obtention of **complex samples** such as short-lived, post-translationally modified Intrinsically Disordered
Protein constructs. Although my current position does not involve protein production, I still do enjoy significant wet lab work for sample preparation.

Regarding biophysical techniques, my main are of expertise is **NMR**, both in liquid and solid states. During my PhD I made use of *fast pulsing* solution NMR methods and *Non Uniform Sampling (NUS)*, which I continue to apply for *time resolved NMR* experiments. *Paramagnetic Relaxation Enhancement (PRE)* and *Chemical Shift Perturbation (CSP)* were the tools I used most extensively.

In the solid state, I have applied several *Magic Angle Spinning (MAS) NMR* methodologies to a variety of systems: <sup>13</sup>C-detection, <sup>1</sup>H-detection at very high MAS (≥ 100 KHz), and Dynamic Nuclear Polarization (DNP). Not an expert in any of those techniques, I am proficient to use them to answer relevant questions about the protein of study — or ask the right person how to do it!

Besides NMR, I have used a variety of biophysical techniques at a shallower level, such *Isothermal Titration Calorimetry (ITC)* or *Small Angle X-ray Scattering (SAXS)*.

### Analytical

As a GNU/Linux aficionado, I had learned basic shell scripting before I started my PhD. Then, I started learning **Python** in order to consistently process increasing amounts of heterogeneous data from multiple experimental sources.

Beginning with NMR peak lists, I used mostly `numpy`, `pandas`, and `matplotlib` for parsing, processing and plotting derived NMR parameters. Because of the exploratory and reporting nature of the work, I found `Jupyter` notebooks the perfect tool for *literate coding* in the context of structural biology research.

As the complexity of my workflows evolved, I then started writing proper Python scripts and modules and adopting common good practices (version control with `git`, unit testing, etc). I learned a lot from my colleague [João M.C. Teixeira](https://github.com/joaomcteixeira), a postdoc in the group then developing [FarSeer-NMR](https://github.com/Farseer-NMR), a full-fledged suite for the analysis of NMR peak lists.

Handling NMR data has given me a strong training on the specific software for acquisition and processing (`TopSpin`, `NmrPipe`) and analysis (`CcpNmr`, `Sparky`). Using *Non Uniform Sampling* made me learn more shell scripting and about the common NMR data formats, which led me to write automated workflows for processing and analysis.

Most recently, I am interested in using machine learning libraries to analyze NMR data (e.g. `scikit-learn`). Overlapping with this and thanks to
my recent collaboration with microscopists, I also explore how to apply image analysis tools as `scikit-image` to NMR, and use 3D viewers like `napari` for multidimensional NMR experiments.

In the context of data visualization, I have started using `bokeh` and `voila`, to make more efficient representations of my processed data by adding interactivity or making dashboards to share with collaborators.

My current workflow thus consists both on **bridging existing software with Python and Bash scripts, and developing new tools** for data analysis and visualization.

Finally, have also worked with other kinds of experimental data such as ITC titration curves or SAXS diffraction data in the context of integrative structural studies. I have also written pipelines to analyze public databases of protein structures and sequences ([e.g. the Protein Data Bank - PDB](https://www.rcsb.org/), or [Uniprot](https://www.uniprot.org/)) for genome-wide analysis using `make`/ `Snakemake`.

## Engagement with the local scientific community

After my arrival to Berlin in spring 2018, I enrolled the [FMP+MDC PostDoc Association](https://www.leibniz-fmp.de/education/fmp-postdoc-association.html). This group of volunteers from the FMP and the neighboring [Max Delbruck Center for Molecular Medicine](https://www.mdc-berlin.de/) at the Berlin-Buch Campus promotes networking between postdocs of the two institutes, by holding monthly meetings or lunch seminars about research and career development among other activities.

Additionally, the FMP+MDC PDA yearly organizes the **[PostDoc Day](https://postdoc-day.mdc-berlin.de/)**, a conference for postdocs in life sciences in the Berlin area. With a steady participation of > 100 scientists from all institutes in the city, we bring a top-tier keynote speaker to tell us about his/her career path and investigations, and select contributions from the participants as well.

## Karate

I practice Karate since I was 10 years old. I started practicing Shotokan style in my hometown, and then switched to Uechi Ryu karate after my Sensei Ángel Arenas. Under his supervision and with the approval of Hanshi Kyohide Shinjo, head of Uechi Ryu Kenyukai in Okinawa, I currently hold a **3rd dan black belt**.

{% include gallery caption="At the Uechi Ryu Kenyukai Spain & Okinawa central dojos" %}

I am also a member of the [International Organization of Sport and Traditional Karate (IOSTK)](http://www.iostk.com/) and I was an instructor for 2 years during my time in Barcelona, teaching Uechi Ryu.

While in Barcelona, I also practiced Shito Ryu karate under Sensei Carlos Fernández for 5 years.

Now in Berlin, I train with the Uechi Ryu Okikukai group located in Panketal led by sensei Holger Massek, who kindly accepted me as a Kenyukai guest.

---
