[![DOI](https://zenodo.org/badge/437832906.svg)](https://zenodo.org/badge/latestdoi/437832906)

# Bioinformatics training materials

Do you like this collection? You're going to love [glittr.org](https://glittr.org)! The collection below is still maintained but updated by glittr.org. So, if you have anything to add or to ask, see you there!

[![](assets/logo-with-domain-tagline.svg)](https://glittr.org)

If you haven't stopped reading, you're one of the few that still prefer the old school `README` :neckbeard:. Nice!

Below you'll find a curated list of **bioinformatics training material**. All material is:

- In a GitHub or GitLab repository (repositories in self-managed instances of GitLab are not supported anymore..)
- Free to use
- Written in markdown or similar

**NOTE:** This list of courses is selected *only* based on the above criteria. There are *no* checks on quality.

## Contents

- [Scripting and languages](#scripting-and-languages)
  - [Version control](#version-control)
  - [Unix/Linux](#unix/linux)
  - [Python](#python)
  - [R](#r)
  - [Quarto](#quarto)
  - [Shiny](#shiny)
  - [Julia](#julia)
  - [Data visualization](#data-visualization)
  - [Java](#java)
  - [GNU Make](#gnu-make)
  - [MATLAB/Octave](#matlab/octave)
  - [SQL](#sql)
  - [C/C++](#c/c++)
- [Computational methods and pipelines](#computational-methods-and-pipelines)
  - [Containerization](#containerization)
  - [Galaxy](#galaxy)
  - [High performance computing](#high-performance-computing)
  - [Workflows](#workflows)
  - [Image analysis](#image-analysis)
  - [Cloud computing](#cloud-computing)
- [Omics analysis](#omics-analysis)
  - [Genomics](#genomics)
  - [Next generation sequencing](#next-generation-sequencing)
  - [Transcriptomics](#transcriptomics)
  - [RNA-seq](#rna-seq)
  - [Single-cell sequencing](#single-cell-sequencing)
  - [Variant analysis](#variant-analysis)
  - [ChIP-seq](#chip-seq)
  - [Comparative genomics](#comparative-genomics)
  - [Epigenetics](#epigenetics)
  - [Genome annotation](#genome-annotation)
  - [Genome assembly](#genome-assembly)
  - [Metagenomics](#metagenomics)
  - [Epidemiology](#epidemiology)
  - [Multiomics](#multiomics)
  - [Spatial transcriptomics](#spatial-transcriptomics)
  - [Long read sequencing](#long-read-sequencing)
  - [Metabolomics](#metabolomics)
  - [Proteomics](#proteomics)
  - [Pathways and Networks](#pathways-and-networks)
- [Reproducibility and data management](#reproducibility-and-data-management)
  - [Data management](#data-management)
  - [FAIR data](#fair-data)
  - [Reproducibility](#reproducibility)
- [Statistics and machine learning](#statistics-and-machine-learning)
  - [Data science](#data-science)
  - [Statistics](#statistics)
  - [Machine learning](#machine-learning)
- [Others](#others)
  - [General](#general)

## Scripting and languages


### Version control

- [**Software Carpentry** swcarpentry/git-novice](https://github.com/swcarpentry/git-novice) | [website](http://swcarpentry.github.io/git-novice/)
- [**BioinfGuru** BioinfGuru/gitTutorial](https://github.com/BioinfGuru/gitTutorial)
- [**Kottans** kottans/git-course](https://github.com/kottans/git-course) | [website](https://kottans.org/git-course/)
- [**Gerard Capes** gcapes/git-course](https://github.com/gcapes/git-course) | [website](http://gcapes.github.io/git-course/)
- [**carpentries-incubator** carpentries-incubator/gitlab-novice](https://github.com/carpentries-incubator/gitlab-novice) | [website](https://carpentries-incubator.github.io/gitlab-novice/)
- [**Data Carpentry** datacarpentry/rr-version-control](https://github.com/datacarpentry/rr-version-control) | [website](http://www.datacarpentry.org/rr-version-control/)
- [**VIB Technologies: Bioinformatics and software projects** vibbits/introduction-github](https://github.com/vibbits/introduction-github)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/module-versioning-dm-practices](https://github.com/NBISweden/module-versioning-dm-practices/) | [website](https://nbisweden.github.io/module-versioning-dm-practices/)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/module-versioning-dm-practices](https://github.com/nbisweden/module-versioning-dm-practices) | [website](https://nbisweden.github.io/module-versioning-dm-practices/)
- [**Sergio Martínez Cuesta** semacu/20190927_IntroductionGithub_HDRUK](https://github.com/semacu/20190927_IntroductionGithub_HDRUK)
- [**Sergio Martínez Cuesta** semacu/20181003_Intro_git_GitHub](https://github.com/semacu/20181003_Intro_git_GitHub)
- [**Sergio Martínez Cuesta** semacu/20171024_GitHub_Chemistry_Cambridge](https://github.com/semacu/20171024_GitHub_Chemistry_Cambridge)

### Unix/Linux

- [**Data Carpentry** datacarpentry/shell-genomics](https://github.com/datacarpentry/shell-genomics) | [website](https://datacarpentry.org/shell-genomics)
- [**Teaching materials at the Harvard Chan Bioinformatics Core** hbctraining/Intro-to-shell-flipped](https://github.com/hbctraining/Intro-to-shell-flipped) | [website](https://hbctraining.github.io/Intro-to-shell-flipped/)
- [**Ted Laderas** laderast/bash_for_bioinformatics](https://github.com/laderast/bash_for_bioinformatics) | [website](https://laderast.github.io/bash_for_bioinformatics/)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/unix-first-steps-training](https://github.com/sib-swiss/unix-first-steps-training)
- [**Software Carpentry** swcarpentry/shell-novice](https://github.com/swcarpentry/shell-novice) | [website](http://swcarpentry.github.io/shell-novice/)
- [**Sundeep Agarwal** learnbyexample/cli_text_processing_coreutils](https://github.com/learnbyexample/cli_text_processing_coreutils) | [website](https://learnbyexample.github.io/cli_text_processing_coreutils/)
- [**Sundeep Agarwal** learnbyexample/cli-computing](https://github.com/learnbyexample/cli-computing) | [website](https://learnbyexample.github.io/cli-computing/)
- [**Sundeep Agarwal** learnbyexample/learn_gnuawk](https://github.com/learnbyexample/learn_gnuawk) | [website](https://learnbyexample.github.io/learn_gnuawk/)
- [**Sundeep Agarwal** learnbyexample/learn_gnused](https://github.com/learnbyexample/learn_gnused) | [website](https://learnbyexample.github.io/learn_gnused/)
- [**Sundeep Agarwal** learnbyexample/learn_gnugrep_ripgrep](https://github.com/learnbyexample/learn_gnugrep_ripgrep) | [website](https://learnbyexample.github.io/learn_gnugrep_ripgrep/)
- [**slackermedia** slackermedia/bashcrawl](https://gitlab.com/slackermedia/bashcrawl)
- [**carpentries-incubator** carpentries-incubator/shell-extras](https://github.com/carpentries-incubator/shell-extras) | [website](http://carpentries-incubator.github.io/shell-extras/)
- [**The Carpentries Lab** carpentries-lab/metagenomics-shell](https://github.com/carpentries-lab/metagenomics-shell) | [website](https://carpentries-lab.github.io/metagenomics-shell/)
- [**UC Davis Bioinformatics Core Training Page** ucdavis-bioinformatics-training/2023-September-Introduction-to-the-Command-Line-for-Bioinformatics](https://github.com/ucdavis-bioinformatics-training/2023-September-Introduction-to-the-Command-Line-for-Bioinformatics)
- [**Cloud-SPAN** Cloud-SPAN/prenomics00-intro](https://github.com/cloud-span/prenomics00-intro) | [website](https://cloud-span.github.io/prenomics00-intro/)
- [**Sergio Martínez Cuesta** semacu/20180726_TrainMalta_Unix_R](https://github.com/semacu/20180726_TrainMalta_Unix_R)
- [**Bobby Iliev** bobbyiliev/introduction-to-bash-scripting](https://github.com/bobbyiliev/introduction-to-bash-scripting) | [website](https://ebook.bobby.sh)

### Python

- [**carpentries-incubator** carpentries-incubator/introduction-to-conda-for-data-scientists](https://github.com/carpentries-incubator/introduction-to-conda-for-data-scientists) | [website](https://carpentries-incubator.github.io/introduction-to-conda-for-data-scientists/)
- [**carpentries-incubator** carpentries-incubator/python-interactive-data-visualizations](https://github.com/carpentries-incubator/python-interactive-data-visualizations) | [website](https://carpentries-incubator.github.io/python-interactive-data-visualizations/)
- [**Jake Vanderplas** jakevdp/PythonDataScienceHandbook](https://github.com/jakevdp/PythonDataScienceHandbook) | [website](http://jakevdp.github.io/PythonDataScienceHandbook)
- [**Jake Vanderplas** jakevdp/WhirlwindTourOfPython](https://github.com/jakevdp/WhirlwindTourOfPython)
- [**Plants&Python** PlantsAndPython/PlantsAndPython](https://github.com/PlantsAndPython/PlantsAndPython)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/first-steps-with-python-training](https://github.com/sib-swiss/first-steps-with-python-training)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/intermediate-python-training](https://github.com/sib-swiss/intermediate-python-training)
- [**Software Carpentry** swcarpentry/python-novice-inflammation](https://github.com/swcarpentry/python-novice-inflammation) | [website](http://swcarpentry.github.io/python-novice-inflammation/)
- [**VIB Technologies: Bioinformatics and software projects** vibbits/gentle-hands-on-python](https://github.com/vibbits/gentle-hands-on-python)
- [**Talk Python** talkpython/python-for-absolute-beginners-course](https://github.com/talkpython/python-for-absolute-beginners-course) | [website](https://training.talkpython.fm/courses/explore_beginners/python-for-absolute-beginners)
- [**Sundeep Agarwal** learnbyexample/py_regular_expressions](https://github.com/learnbyexample/py_regular_expressions) | [website](https://learnbyexample.github.io/py_regular_expressions/)
- [**Sundeep Agarwal** learnbyexample/100_page_python_intro](https://github.com/learnbyexample/100_page_python_intro) | [website](https://learnbyexample.github.io/100_page_python_intro/)
- [**Alex Hall** alexmojaki/futurecoder](https://github.com/alexmojaki/futurecoder) | [website](https://futurecoder.io)
- [**Guillaume Gautier** guilgautier/sdia-python](https://github.com/guilgautier/sdia-python)
- [**cambiotraining** cambiotraining/python-data-science](https://github.com/cambiotraining/python-data-science)
- [**carpentries-incubator** carpentries-incubator/python-text-analysis](https://github.com/carpentries-incubator/python-text-analysis) | [website](https://carpentries-incubator.github.io/python-text-analysis/)
- [**carpentries-incubator** carpentries-incubator/python_packaging](https://github.com/carpentries-incubator/python_packaging) | [website](https://carpentries-incubator.github.io/python_packaging)
- [**carpentries-incubator** carpentries-incubator/python-testing](https://github.com/carpentries-incubator/python-testing) | [website](http://carpentries-incubator.github.io/python-testing/)
- [**carpentries-incubator** carpentries-incubator/python-intermediate-development](https://github.com/carpentries-incubator/python-intermediate-development) | [website](https://carpentries-incubator.github.io/python-intermediate-development/)
- [**carpentries-incubator** carpentries-incubator/python-packaging-publishing](https://github.com/carpentries-incubator/python-packaging-publishing) | [website](https://carpentries-incubator.github.io/python-packaging-publishing/)
- [**carpentries-incubator** carpentries-incubator/lesson-parallel-python](https://github.com/carpentries-incubator/lesson-parallel-python) | [website](https://carpentries-incubator.github.io/lesson-parallel-python/)
- [**Data Carpentry** datacarpentry/python-ecology-lesson](https://github.com/datacarpentry/python-ecology-lesson) | [website](https://datacarpentry.org/python-ecology-lesson)
- [**carpentries-incubator** carpentries-incubator/python-intermediate-development](https://github.com/carpentries-incubator/python-intermediate-development/) | [website](https://carpentries-incubator.github.io/python-intermediate-development/)
- [**The Algorithms** TheAlgorithms/Python](https://github.com/TheAlgorithms/Python) | [website](https://the-algorithms.com)
- [**Oleksii Trekhleb** trekhleb/learn-python](https://github.com/trekhleb/learn-python)
- [**João Ventura** joaoventura/full-speed-python](https://github.com/joaoventura/full-speed-python)
- [**Sebastian Raschka** rasbt/python_reference](https://github.com/rasbt/python_reference)
- [**Jeffrey Hu** zhiwehu/Python-programming-exercises](https://github.com/zhiwehu/Python-programming-exercises)
- [**LiaBooks ... by LiaScript** LiaBooks/How-To-Code-in-Python-3](https://github.com/LiaBooks/How-To-Code-in-Python-3) | [website](https://liascript.github.io/course/)
- [**LiaPlayground** LiaPlayground/PythonProgramming](https://github.com/LiaPlayground/PythonProgramming)
- [**Valentin Danchev** valdanchev/reproducible-data-science-python](https://github.com/valdanchev/reproducible-data-science-python)
- [**Girls Who Code at U-M DCMB** GWC-DCMB/GWC-DCMB](https://github.com/GWC-DCMB/GWC-DCMB) | [website](http://umich.edu/~girlswc/)
- [**UC Davis Bioinformatics Core Training Page** ucdavis-bioinformatics-training/2023-July-Introduction-To-Python-For-Bioinformatics](https://github.com/ucdavis-bioinformatics-training/2023-July-Introduction-To-Python-For-Bioinformatics)
- [**The Gulbenkian Training Programme in Bioinformatics** GTPB/PPB18](https://github.com/gtpb/PPB18) | [website](https://gtpb.github.io/PPB18/)
- [**Swaroop CH** swaroopch/byte-of-python](https://github.com/swaroopch/byte-of-python) | [website](https://python.swaroopch.com)
- [**S.Lott** slott56/building-skills-oo-design-book](https://github.com/slott56/building-skills-oo-design-book) | [website](https://slott56.github.io/building-skills-oo-design-book/build/html/index.html)
- [**Real Python** realpython/python-guide](https://github.com/realpython/python-guide) | [website](https://docs.python-guide.org)
- [**OpenTechSchool** OpenTechSchool/python-beginners](https://github.com/OpenTechSchool/python-beginners) | [website](http://opentechschool.github.io/python-beginners/)
- [**Ankit Mahato** animator/learn-python](https://github.com/animator/learn-python) | [website](https://animator.github.io/learn-python/)
- [**Sundeep Agarwal** learnbyexample/practice_python_projects](https://github.com/learnbyexample/practice_python_projects) | [website](https://learnbyexample.github.io/practice_python_projects/)
- [**SoftUni** SoftUni/Programming-Basics-Book-Python-EN](https://github.com/SoftUni/Programming-Basics-Book-Python-EN) | [website](https://python-book.softuni.org)
- [**Akuli** Akuli/python-tutorial](https://github.com/Akuli/python-tutorial)
- [**Charles Severance** csev/py4e](https://github.com/csev/py4e) | [website](http://www.py4e.com)
- [**Kushal Das** kushaldas/pym](https://github.com/kushaldas/pym)
- [**Greg Malcolm** gregmalcolm/python_koans](https://github.com/gregmalcolm/python_koans)

### R

- [**Bruno Rodrigues** b-rodrigues/rap4mads](https://github.com/b-rodrigues/rap4mads) | [website](https://b-rodrigues.github.io/rap4mads/)
- [**BHKLAB** bhklab/bioc2020workshop](https://github.com/bhklab/bioc2020workshop) | [website](http://bhklab.ca/bioc2020workshop/articles/GxWorkshop.html)
- [**Bioconductor** Bioconductor/bioconductor_docker](https://github.com/Bioconductor/bioconductor_docker) | [website](https://bioconductor.org/help/docker/)
- [**Biocore@CRG** biocorecrg/CRG_R_tidyverse_2021](https://github.com/biocorecrg/CRG_R_tidyverse_2021)
- [**Biocore@CRG** biocorecrg/CRG_RIntroduction_2021](https://github.com/biocorecrg/CRG_RIntroduction_2021)
- [**Canadian Bioinformatics Workshops** bioinformatics-ca/AUR_2021](https://github.com/bioinformatics-ca/AUR_2021)
- [**Canadian Bioinformatics Workshops** bioinformatics-ca/INR_2021](https://github.com/bioinformatics-ca/INR_2021)
- [**CRUK CI Bioinformatics Core** bioinformatics-core-shared-training/linear-models-r](https://github.com/bioinformatics-core-shared-training/linear-models-r) | [website](https://bioinformatics-core-shared-training.github.io/linear-models-r/)
- [**Bradley Boehmke** bradleyboehmke/Intro-to-R-Bootcamp](https://github.com/bradleyboehmke/Intro-to-R-Bootcamp)
- [**carpentries-incubator** carpentries-incubator/bioc-project](https://github.com/carpentries-incubator/bioc-project) | [website](https://carpentries-incubator.github.io/bioc-project)
- [**carpentries-incubator** carpentries-incubator/high-dimensional-stats-r](https://github.com/carpentries-incubator/high-dimensional-stats-r) | [website](https://carpentries-incubator.github.io/high-dimensional-stats-r)
- [**Colautti Lab** ColauttiLab/RCrashCourse_Book](https://github.com/ColauttiLab/RCrashCourse_Book)
- [**Computational Cancer Biology and Epigenomics** CompEpigen/BasicR](https://github.com/CompEpigen/BasicR) | [website](https://compepigen.github.io/BasicR/)
- [**Colin Gillespie** csgillespie/efficientR](https://github.com/csgillespie/efficientR) | [website](https://csgillespie.github.io/efficientR/)
- [**C. Li** cxli233/Online_R_learning](https://github.com/cxli233/Online_R_learning)
- [**Davis Laboratory** DavisLaboratory/GenesetAnalysisWorkflow](https://github.com/DavisLaboratory/GenesetAnalysisWorkflow) | [website](https://davislaboratory.github.io/GenesetAnalysisWorkflow/)
- [**David Robinson** dgrtwo/tidy-text-mining](https://github.com/dgrtwo/tidy-text-mining) | [website](http://tidytextmining.com)
- [**Danielle Navarro** djnavarro/rbook](https://github.com/djnavarro/rbook) | [website](https://learningstatisticswithr.com)
- [**Duke Department of Statistical Science** DukeStatSci/introds](https://github.com/DukeStatSci/introds) | [website](https://introds-duke.netlify.app)
- [**Hadley Wickham** hadley/adv-r](https://github.com/hadley/adv-r) | [website](http://adv-r.hadley.nz)
- [**Hadley Wickham** hadley/r4ds](https://github.com/hadley/r4ds) | [website](http://r4ds.hadley.nz)
- [**Teaching materials at the Harvard Chan Bioinformatics Core** hbctraining/Intro-to-R-flipped](https://github.com/hbctraining/Intro-to-R-flipped) | [website](https://hbctraining.github.io/Intro-to-R-flipped/)
- [**ICS 80 - Introduction to Data Science** ics80-fa21/website](https://github.com/ics80-fa21/website) | [website](https://ics80-fa21.github.io/website/)
- [**Introduction to Data Science - 2020 - Semester 1** ids-s1-20/website](https://github.com/ids-s1-20/website) | [website](https://introds.org)
- [**Jennifer (Jenny) Bryan** jennybc/purrr-tutorial](https://github.com/jennybc/purrr-tutorial) | [website](https://jennybc.github.io/purrr-tutorial/)
- [**James W. MacDonald** jmacdon/Bioc2020Anno](https://github.com/jmacdon/Bioc2020Anno)
- [**James W. MacDonald** jmacdon/Bioc2022Anno](https://github.com/jmacdon/Bioc2022Anno)
- [**Joachim Goedhart** JoachimGoedhart/DataViz-protocols](https://github.com/JoachimGoedhart/DataViz-protocols) | [website](https://joachimgoedhart.github.io/DataViz-protocols/)
- [**Jemma Stachelek** jsta/r-docker-tutorial](https://github.com/jsta/r-docker-tutorial) | [website](http://jsta.github.io/r-docker-tutorial)
- [**Tom Mock** jthomasmock/rmd-nhs](https://github.com/jthomasmock/rmd-nhs) | [website](https://jthomasmock.github.io/rmd-nhs/)
- [**Ted Laderas** laderast/gradual_shiny](https://github.com/laderast/gradual_shiny) | [website](http://laderast.github.io/gradual_shiny)
- [**Ted Laderas** laderast/RBootcamp](https://github.com/laderast/RBootcamp) | [website](http://r-bootcamp.netlify.app)
- [**Qian Liu** Liubuntu/Bioc2020RCWL](https://github.com/liubuntu/Bioc2020Rcwl)
- [**Norm Matloff** matloff/fasteR](https://github.com/matloff/fasteR)
- [**Melbourne Bioinformatics** melbournebioinformatics/r-intro-biologists](https://github.com/melbournebioinformatics/r-intro-biologists)
- [**ModernDive** moderndive/ModernDive_book](https://github.com/moderndive/ModernDive_book) | [website](https://www.moderndive.com)
- [**Nathaniel Phillips** ndphillips/ThePiratesGuideToR](https://github.com/ndphillips/ThePiratesGuideToR) | [website](https://bookdown.org/ndphillips/YaRrr/)
- [**Openscapes** Openscapes/quarto-website-tutorial](https://github.com/Openscapes/quarto-website-tutorial) | [website](https://openscapes.github.io/quarto-website-tutorial)
- [**Oscar Baruffa** oscarbaruffa/BigBookofR](https://github.com/oscarbaruffa/BigBookofR) | [website](https://www.bigbookofr.com)
- [**Rafael A Irizarry** rafalab/dsbook](https://github.com/rafalab/dsbook)
- [**rstudio::conf(2022)** rstudio-conf-2022/art-from-code](https://github.com/rstudio-conf-2022/art-from-code) | [website](https://art-from-code.netlify.app)
- [**rstudio::conf(2022)** rstudio-conf-2022/build-tidy-tools](https://github.com/rstudio-conf-2022/build-tidy-tools) | [website](https://rstd.io/btt)
- [**rstudio::conf(2022)** rstudio-conf-2022/get-started-quarto](https://github.com/rstudio-conf-2022/get-started-quarto) | [website](https://rstudio-conf-2022.github.io/get-started-quarto/)
- [**rstudio::conf(2022)** rstudio-conf-2022/get-started-shiny](https://github.com/rstudio-conf-2022/get-started-shiny) | [website](https://rstd.io/start-shiny)
- [**rstudio::conf(2022)** rstudio-conf-2022/ggplot2-graphic-design](https://github.com/rstudio-conf-2022/ggplot2-graphic-design) | [website](https://rstudio-conf-2022.github.io/ggplot2-graphic-design/)
- [**rstudio::conf(2022)** rstudio-conf-2022/intro-to-tidyverse](https://github.com/rstudio-conf-2022/intro-to-tidyverse) | [website](https://conf22-intro-tidyverse.netlify.app)
- [**rstudio::conf(2022)** rstudio-conf-2022/shiny-prod-apps](https://github.com/rstudio-conf-2022/shiny-prod-apps) | [website](https://shinyprod.com)
- [**rstudio::conf(2022)** rstudio-conf-2022/teach-ds](https://github.com/rstudio-conf-2022/teach-ds) | [website](https://rstd.io/teach-ds-conf22)
- [**rstudio::conf(2022)** rstudio-conf-2022/wtf-rstats](https://github.com/rstudio-conf-2022/wtf-rstats)
- [**RStudio Education** tidyverse/datascience-box](https://github.com/rstudio-education/datascience-box) | [website](https://datasciencebox.org)
- [**RStudio** rstudio/rmarkdown-book](https://github.com/rstudio/rmarkdown-book) | [website](https://bookdown.org/yihui/rmarkdown)
- [**Saskia** SaskiaFreytag/biocommons-r-intro](https://github.com/SaskiaFreytag/biocommons-r-intro) | [website](https://saskiafreytag.github.io/biocommons-r-intro/)
- [**Sean Davis** seandavi/ITR](https://github.com/seandavi/ITR) | [website](https://seandavi.github.io/ITR)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/enrichment-analysis-training](https://github.com/sib-swiss/enrichment-analysis-training)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/first-steps-with-R-training](https://github.com/sib-swiss/first-steps-with-R-training)
- [**Software Carpentry** swcarpentry/r-novice-gapminder](https://github.com/swcarpentry/r-novice-gapminder) | [website](http://swcarpentry.github.io/r-novice-gapminder/)
- [**Research IT, University of Manchester, UK** UoMResearchIT/r-tidyverse-intro](https://github.com/UoMResearchIT/r-tidyverse-intro) | [website](https://UoMResearchIT.github.io/r-tidyverse-intro)
- [**Waldron Lab at the CUNY SPH** waldronlab/enrichOmics](https://github.com/waldronlab/enrichOmics)
- [**Jennifer (Jenny) Bryan** jennybc/happy-git-with-r](https://github.com/jennybc/happy-git-with-r) | [website](https://happygitwithr.com)
- [**Bioinformatics, Rockefeller University** RockefellerUniversity/Bioconductor_Introduction](https://github.com/RockefellerUniversity/Bioconductor_Introduction) | [website](https://rockefelleruniversity.github.io/Bioconductor_Introduction/)
- [**Bioinformatics, Rockefeller University** RockefellerUniversity/Intro_To_R_1Day](https://github.com/RockefellerUniversity/Intro_To_R_1Day) | [website](https://rockefelleruniversity.github.io/Intro_To_R_1Day/)
- [**Bioinformatics, Rockefeller University** RockefellerUniversity/RU_reproducibleR](https://github.com/RockefellerUniversity/RU_reproducibleR) | [website](https://rockefelleruniversity.github.io/RU_reproducibleR/)
- [**Bioinformatics, Rockefeller University** RockefellerUniversity/RU_tidyverse_core](https://github.com/RockefellerUniversity/RU_tidyverse_core) | [website](https://rockefelleruniversity.github.io/RU_tidyverse_core/)
- [**Bioinformatics, Rockefeller University** RockefellerUniversity/RU_GenomicVariants](https://github.com/RockefellerUniversity/RU_GenomicVariants)
- [**Hadley Wickham** hadley/r-pkgs](https://github.com/hadley/r-pkgs) | [website](https://r-pkgs.org)
- [**Hadley Wickham** hadley/mastering-shiny](https://github.com/hadley/mastering-shiny) | [website](https://mastering-shiny.org)
- [**Dirk Eddelbuettel** eddelbuettel/gsir-te](https://github.com/eddelbuettel/gsir-te)
- [**carpentries-incubator** carpentries-incubator/bioc-intro](https://github.com/carpentries-incubator/bioc-intro) | [website](https://carpentries-incubator.github.io/bioc-intro)
- [**Will Landau** wlandau/targets-tutorial](https://github.com/wlandau/targets-tutorial) | [website](https://rstudio.cloud/project/1699460)
- [**R Programming @ University of Cincinnati** uc-r/Advanced-R](https://github.com/uc-r/Advanced-R)
- [**R Programming @ University of Cincinnati** uc-r/Intro-R](https://github.com/uc-r/Intro-R)
- [**R Programming @ University of Cincinnati** uc-r/Intermediate-R](https://github.com/uc-r/Intermediate-R)
- [**RStudio Education** rstudio-education/advanced-shiny-az](https://github.com/rstudio-education/advanced-shiny-az) | [website](https://rstd.io/adv-shiny-az)
- [**RStudio** rstudio/learnr](https://github.com/rstudio/learnr) | [website](https://pkgs.rstudio.com/learnr)
- [**dcruvolo** davidruvolo51/shinyAppTutorials](https://github.com/davidruvolo51/shinyAppTutorials) | [website](https://davidruvolo51.github.io/shinytutorials/)
- [**Max Planck Institute of Immunobiology and Epigenetics** maxplanck-ie/Rintro](https://github.com/maxplanck-ie/Rintro/)
- [**CRUK CI Bioinformatics Core** bioinformatics-core-shared-training/r-basics](https://github.com/bioinformatics-core-shared-training/r-basics)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/workshop-data-visualization-r](https://github.com/NBISweden/workshop-data-visualization-r)
- [**carpentries-incubator** carpentries-incubator/lc-litsearchr](https://github.com/carpentries-incubator/lc-litsearchr) | [website](https://carpentries-incubator.github.io/lc-litsearchr/)
- [**carpentries-incubator** carpentries-incubator/R-ecology-lesson](https://github.com/carpentries-incubator/R-ecology-lesson) | [website](https://carpentries-incubator.github.io/R-ecology-lesson/)
- [**carpentries-incubator** carpentries-incubator/R-ecology-lesson-intermediate](https://github.com/carpentries-incubator/R-ecology-lesson-intermediate) | [website](https://carpentries-incubator.github.io/R-ecology-lesson-intermediate/)
- [**carpentries-incubator** carpentries-incubator/open-science-with-r](https://github.com/carpentries-incubator/open-science-with-r) | [website](https://carpentries-incubator.github.io/open-science-with-r/)
- [**carpentries-incubator** carpentries-incubator/Reproducible-Publications-with-RStudio](https://github.com/carpentries-incubator/Reproducible-Publications-with-RStudio) | [website](https://carpentries-incubator.github.io/Reproducible-Publications-with-RStudio)
- [**Data Carpentry** datacarpentry/R-ecology-lesson](https://github.com/datacarpentry/R-ecology-lesson) | [website](https://datacarpentry.org/R-ecology-lesson)
- [**Data Carpentry** datacarpentry/genomics-r-intro](https://github.com/datacarpentry/genomics-r-intro) | [website](https://datacarpentry.org/genomics-r-intro/)
- [**Data Carpentry** datacarpentry/rr-automation](https://github.com/datacarpentry/rr-automation) | [website](http://www.datacarpentry.org/rr-automation/)
- [**Data Carpentry** datacarpentry/rr-literate-programming](https://github.com/datacarpentry/rr-literate-programming)
- [**RStudio Education** rstudio-education/stat545](https://github.com/rstudio-education/stat545) | [website](https://stat545.com)
- [**nullranges** tidyomics/tidy-ranges-tutorial](https://github.com/nullranges/tidy-ranges-tutorial) | [website](https://tidyomics.github.io/tidy-ranges-tutorial/)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/workshop-epigenomics-RTDs](https://github.com/NBISweden/workshop-epigenomics-RTDs/) | [website](https://nbis-workshop-epigenomics.readthedocs.io/en/latest/)
- [**Library Data Services** UNC-Libraries-data/R-Open-Labs](https://github.com/UNC-Libraries-data/R-Open-Labs)
- [**Greg Wilson** gvwilson/tidynomicon](https://github.com/gvwilson/tidynomicon) | [website](http://tidynomicon.github.io/tidynomicon)
- [**Vince Carey** vjcitn/BiocPyInterop](https://github.com/vjcitn/BiocPyInterop) | [website](https://vjcitn.github.io/BiocPyInterop/)
- [**Bioinformatics, Rockefeller University** RockefellerUniversity/RU_VisualizingGenomicsData](https://github.com/RockefellerUniversity/RU_VisualizingGenomicsData)
- [**genomicsclass** genomicsclass/book](https://github.com/genomicsclass/book) | [website](http://genomicsclass.github.io/book/)
- [**Kristyna Kupkova** kkupkova/GenomicDistributionsBioC2022](https://github.com/kkupkova/GenomicDistributions_BioC2022)
- [**Workflow Languages in R** rworkflow/RcwlWorkshop](https://github.com/rworkflow/RcwlWorkshop) | [website](http://rcwl.org/RcwlWorkshop/)
- [**tidybiology** tidyomics/tidyomicsWorkshopBioc2023](https://github.com/tidybiology/tidyomicsWorkshopBioc2023) | [website](https://tidyomics.github.io/tidyomicsWorkshopBioc2023)
- [**Surgical Informatics** SurgicalInformatics/healthyr_book](https://github.com/SurgicalInformatics/healthyr_book/tree/master) | [website](https://argoshare.is.ed.ac.uk/healthyr_book/)
- [**Trevor French** TrevorFrench/R-for-Data-Analysis](https://github.com/TrevorFrench/R-for-Data-Analysis) | [website](https://trevorfrench.github.io/R-for-Data-Analysis/)
- [**UM Carpentries** UMCarpentries/intro-curriculum-r](https://github.com/UMCarpentries/intro-curriculum-r/) | [website](https://umcarpentries.org/intro-curriculum-r/)
- [**rostools** rostools/r-cubed-intro](https://github.com/rostools/r-cubed-intro) | [website](https://r-cubed-intro.rostools.org)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/module-rstudio-intro-dm-practices](https://github.com/NBISweden/module-rstudio-intro-dm-practices/) | [website](https://nbisweden.github.io/module-rstudio-intro-dm-practices/)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/module-r-intro-dm-practices](https://github.com/NBISweden/module-r-intro-dm-practices/) | [website](https://nbisweden.github.io/module-r-intro-dm-practices/)
- [**bioinformatics.ca** bioinformaticsdotca/AUR_2023](https://github.com/bioinformaticsdotca/AUR_2023)
- [**Computational Biology and Bioinformatics at UCLouvain** UCLouvain-CBIO/WSBIM1207](https://github.com/UCLouvain-CBIO/WSBIM1207) | [website](https://UCLouvain-CBIO.github.io/WSBIM1207/)
- [**UC Davis Bioinformatics Core Training Page** ucdavis-bioinformatics-training/2023-June-Introduction-to-R-for-Bioinformatics](https://github.com/ucdavis-bioinformatics-training/2023-June-Introduction-to-R-for-Bioinformatics)
- [**Institut Français de Bioinformatique (IFB)** IFB-ElixirFr/IFB_Shiny_training](https://github.com/IFB-ElixirFr/IFB_Shiny_training) | [website](https://ifb-elixirfr.github.io/IFB_Shiny_training/)
- [**bioinformatics.ca** bioinformaticsdotca/INR_2023](https://github.com/bioinformaticsdotca/INR_2023)
- [**ELIXIR Estonia** ELIXIREstonia/2023-10-24-R-basic](https://github.com/ELIXIREstonia/2023-10-24-R-basic) | [website](https://elixir.ut.ee/node/552)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/module-rstudio-intro-dm-practices](https://github.com/nbisweden/module-rstudio-intro-dm-practices) | [website](https://nbisweden.github.io/module-rstudio-intro-dm-practices/)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/module-r-intro-dm-practices](https://github.com/nbisweden/module-r-intro-dm-practices) | [website](https://nbisweden.github.io/module-r-intro-dm-practices/)
- [**The Gulbenkian Training Programme in Bioinformatics** GTPB/ABSTAT18](https://github.com/gtpb/ABSTAT18) | [website](https://gtpb.github.io/ABSTAT18/)
- [**Hugo Tavares** tavareshugo/2018-06-28-cambridge](https://github.com/tavareshugo/2018-06-28-cambridge) | [website](https://tavareshugo.github.io/2018-06-28-cambridge/)
- [**Sergio Martínez Cuesta** semacu/20180531_DataVisualisationRggplot2_Wolfson_Cambridge](https://github.com/semacu/20180531_DataVisualisationRggplot2_Wolfson_Cambridge)
- [**Data Carpentry** datacarpentry/ecology-workshop](https://github.com/datacarpentry/ecology-workshop) | [website](http://www.datacarpentry.org/ecology-workshop/)
- [**Jacques van Helden** jvanheld/stats_avec_RStudio_EBA](https://github.com/jvanheld/stats_avec_RStudio_EBA) | [website](http://jvanheld.github.io/stats_avec_RStudio_EBA/)
- [**proback** proback/BeyondMLR](https://github.com/proback/BeyondMLR)
- [**Data Challenge Lab Open Content** dcl-docs/prog](https://github.com/dcl-docs/prog) | [website](https://dcl-prog.stanford.edu)
- [**G. Jay Kerns** gjkerns/IPSUR](https://github.com/gjkerns/IPSUR) | [website](http://ipsur.org)
- [**Roger D. Peng** rdpeng/rprogdatascience](https://github.com/rdpeng/rprogdatascience)

### Quarto

- [**UCSB-MEDS** UCSB-MEDS/customizing-quarto-websites](https://github.com/UCSB-MEDS/customizing-quarto-websites) | [website](https://ucsb-meds.github.io/customizing-quarto-websites/)
- [**UCSB-MEDS** UCSB-MEDS/creating-quarto-websites](https://github.com/UCSB-MEDS/creating-quarto-websites) | [website](https://ucsb-meds.github.io/creating-quarto-websites/)

### Shiny

- [**Martin J Frigaard** mjfrigaard/shinyap](https://github.com/mjfrigaard/shinyap) | [website](https://mjfrigaard.github.io/shinyap/)

### Julia

- [**Antonello Lobianco** sylvaticus/juliatutorial](https://github.com/sylvaticus/juliatutorial)
- [**JuliaAcademy** JuliaAcademy/JuliaTutorials](https://github.com/JuliaAcademy/JuliaTutorials) | [website](https://julialang.org/learning/)
- [**JuliaAcademy** JuliaAcademy/DataScience](https://github.com/JuliaAcademy/DataScience) | [website](https://juliaacademy.com/p/julia-for-data-science)
- [**JuliaAcademy** JuliaAcademy/Introduction-to-Julia](https://github.com/JuliaAcademy/Introduction-to-Julia) | [website](https://juliaacademy.com/p/intro-to-julia)
- [**JuliaAcademy** JuliaAcademy/JuliaProgrammingForNervousBeginners](https://github.com/JuliaAcademy/JuliaProgrammingForNervousBeginners) | [website](https://juliaacademy.com/p/julia-programming-for-nervous-beginners)
- [**JuliaAcademy** JuliaAcademy/DataFrames](https://github.com/JuliaAcademy/DataFrames)
- [**JuliaAcademy** JuliaAcademy/Foundations-of-Machine-Learning](https://github.com/JuliaAcademy/Foundations-of-Machine-Learning) | [website](https://juliaacademy.com/p/introduction-to-machine-learning)
- [**carpentries-incubator** carpentries-incubator/julia-novice](https://github.com/carpentries-incubator/julia-novice) | [website](https://carpentries-incubator.github.io/julia-novice)
- [**Antonello Lobianco** sylvaticus/SPMLJ](https://github.com/sylvaticus/SPMLJ) | [website](https://sylvaticus.github.io/SPMLJ/stable)
- [**Ben Lauwens** BenLauwens/ThinkJulia.jl](https://github.com/BenLauwens/ThinkJulia.jl)

### Data visualization

- [**Bioinformatics, Rockefeller University** RockefellerUniversity/IGV_course](https://github.com/RockefellerUniversity/IGV_course) | [website](https://rockefelleruniversity.github.io/IGV_course/)
- [**Hadley Wickham** hadley/ggplot2-book](https://github.com/hadley/ggplot2-book) | [website](https://ggplot2-book.org)
- [**Christian Burkhart** ch-bu/ggplot2-fundamentals](https://github.com/ch-bu/ggplot2-fundamentals) | [website](https://ggplot2tor.com/courses/ggplot2fundamentals)
- [**carpentries-incubator** carpentries-incubator/intro-data-viz](https://github.com/carpentries-incubator/intro-data-viz) | [website](https://carpentries-incubator.github.io/intro-data-viz/)
- [**Teaching materials at the Harvard Chan Bioinformatics Core** hbctraining/publication_perfect](https://github.com/hbctraining/publication_perfect) | [website](https://hbctraining.github.io/publication_perfect/)
- [**C. Li** cxli233/FriendsDontLetFriends](https://github.com/cxli233/FriendsDontLetFriends)

### Java

- [**BioJava** biojava/biojava-tutorial](https://github.com/biojava/biojava-tutorial) | [website](http://www.biojava.org)

### GNU Make

- [**Software Carpentry** swcarpentry/make-novice](https://github.com/swcarpentry/make-novice) | [website](http://swcarpentry.github.io/make-novice)
- [**Chase Lambert** theicfire/makefiletutorial](https://github.com/theicfire/makefiletutorial) | [website](http://makefiletutorial.com)

### MATLAB/Octave

- [**Software Carpentry** swcarpentry/matlab-novice-inflammation](https://github.com/swcarpentry/matlab-novice-inflammation) | [website](http://swcarpentry.github.io/matlab-novice-inflammation/)

### SQL

- [**Data Carpentry** datacarpentry/sql-ecology-lesson](https://github.com/datacarpentry/sql-ecology-lesson) | [website](http://datacarpentry.github.io/sql-ecology-lesson)
- [**Department of Bioinformatics - BiGCaT** BiGCAT-UM/SPARQLTutorialBioSB2019](https://github.com/bigcat-um/SPARQLTutorialBioSB2019)

### C/C++

- [**LiaBooks ... by LiaScript** LiaBooks/C-Programming](https://github.com/LiaBooks/C-Programming) | [website](https://liascript.github.io/course/)

## Computational methods and pipelines


### Containerization

- [**awesome-workshop** awesome-workshop/docker-singularity-hats](https://github.com/awesome-workshop/docker-singularity-hats) | [website](https://awesome-workshop.github.io/docker-singularity-hats/index.html)
- [**carpentries-incubator** carpentries-incubator/docker-introduction](https://github.com/carpentries-incubator/docker-introduction) | [website](https://carpentries-incubator.github.io/docker-introduction/)
- [**carpentries-incubator** carpentries-incubator/singularity-introduction](https://github.com/carpentries-incubator/singularity-introduction) | [website](https://carpentries-incubator.github.io/singularity-introduction)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/containers-introduction-training](https://github.com/sib-swiss/containers-introduction-training) | [website](https://sib-swiss.github.io/containers-introduction-training/)
- [**PerMedCoE** PerMedCoE/mpi-in-container](https://github.com/permedcoe/mpi-in-container)

### Galaxy

- [**Galaxy Project** galaxyproject/training-material](https://github.com/galaxyproject/training-material) | [website](https://training.galaxyproject.org)
- [**Erasmus Medical Center** ErasmusMC-Bioinformatics/galaxy-courses](https://github.com/ErasmusMC-Bioinformatics/galaxy-courses)

### High performance computing

- [**carpentries-incubator** carpentries-incubator/hpc-intro](https://github.com/carpentries-incubator/hpc-intro) | [website](https://carpentries-incubator.github.io/hpc-intro/)
- [**ngs-docs** ngs-docs/2021-august-remote-computing](https://github.com/ngs-docs/2021-august-remote-computing) | [website](https://ngs-docs.github.io/2021-august-remote-computing)
- [**cambiotraining** cambiotraining/hpc-intro](https://github.com/cambiotraining/hpc-intro) | [website](https://cambiotraining.github.io/hpc-intro/)
- [**carpentries-incubator** carpentries-incubator/lesson-gpu-programming](https://github.com/carpentries-incubator/lesson-gpu-programming) | [website](https://carpentries-incubator.github.io/lesson-gpu-programming/)
- [**PerMedCoE** PerMedCoE/cluster-tutorial](https://github.com/permedcoe/cluster-tutorial)

### Workflows

- [**Biocore@CRG** biocorecrg/CoursesCRG_Containers_Nextflow_May_2022](https://github.com/biocorecrg/CoursesCRG_Containers_Nextflow_May_2022) | [website](https://biocorecrg.github.io/CoursesCRG_Containers_Nextflow_May_2022/)
- [**Biocore@CRG** biocorecrg/ELIXIR_containers_nextflow](https://github.com/biocorecrg/ELIXIR_containers_nextflow) | [website](https://biocorecrg.github.io/ELIXIR_containers_nextflow/)
- [**Biocore@CRG** biocorecrg/SIB_course_nextflow_Nov_2021](https://github.com/biocorecrg/SIB_course_nextflow_Nov_2021) | [website](https://biocorecrg.github.io/SIB_course_nextflow_Nov_2021/docs/)
- [**Biodata Analysis Group** BiodataAnalysisGroup/intro-to-cwl-docker](https://github.com/BiodataAnalysisGroup/intro-to-cwl-docker) | [website](https://biodataanalysisgroup.github.io/intro-to-cwl-docker/)
- [**CRUK CI Bioinformatics Core** bioinformatics-core-shared-training/nextflow_september_2021](https://github.com/bioinformatics-core-shared-training/nextflow_september_2021)
- [**BovReg** BovReg/nf-workshop20](https://github.com/bovreg/nf-workshop20)
- [**carpentries-incubator** carpentries-incubator/snakemake-novice-bioinformatics](https://github.com/carpentries-incubator/snakemake-novice-bioinformatics) | [website](https://carpentries-incubator.github.io/snakemake-novice-bioinformatics)
- [**carpentries-incubator** carpentries-incubator/workflows-nextflow](https://github.com/carpentries-incubator/workflows-nextflow) | [website](https://carpentries-incubator.github.io/workflows-nextflow/)
- [**carpentries-incubator** carpentries-incubator/workflows-snakemake](https://github.com/carpentries-incubator/workflows-snakemake) | [website](https://carpentries-incubator.github.io/workflows-snakemake/)
- [**Sateesh_Peri** sateeshperi/nextflow_varcal](https://github.com/sateeshperi/nextflow_varcal) | [website](https://sateeshperi.github.io/nextflow_varcal/nextflow/)
- [**Seqera** nextflow-io/training](https://github.com/seqeralabs/nf-training-public) | [website](https://training.nextflow.io)
- [**VIB Technologies: Bioinformatics and software projects** vibbits/nextflow-workshop](https://github.com/vibbits/nextflow-workshop)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/containers-snakemake-training](https://github.com/sib-swiss/containers-snakemake-training) | [website](https://sib-swiss.github.io/containers-snakemake-training/)
- [**carpentries-incubator** carpentries-incubator/cwl-novice-tutorial](https://github.com/carpentries-incubator/cwl-novice-tutorial) | [website](https://carpentries-incubator.github.io/cwl-novice-tutorial/)
- [**Romain Feron** RomainFeron/workshop-snakemake-sibdays2022](https://github.com/RomainFeron/workshop-snakemake-sibdays2022)

### Image analysis

- [**Andrew Jahn** andrewjahn/AndysBrainBook](https://github.com/andrewjahn/AndysBrainBook)
- [**carpentries-incubator** carpentries-incubator/SDC-BIDS-fMRI](https://github.com/carpentries-incubator/SDC-BIDS-fMRI) | [website](https://carpentries-incubator.github.io/SDC-BIDS-fMRI/)
- [**carpentries-incubator** carpentries-incubator/SDC-BIDS-IntroMRI](https://github.com/carpentries-incubator/SDC-BIDS-IntroMRI) | [website](https://carpentries-incubator.github.io/SDC-BIDS-IntroMRI)
- [**carpentries-incubator** carpentries-incubator/SDC-BIDS-sMRI](https://github.com/carpentries-incubator/SDC-BIDS-sMRI) | [website](https://carpentries-incubator.github.io/SDC-BIDS-sMRI/)
- [**carpentries-incubator** carpentries-incubator/SDC-BIDS-dMRI](https://github.com/carpentries-incubator/SDC-BIDS-dMRI) | [website](https://carpentries-incubator.github.io/SDC-BIDS-dMRI/)
- [**Data Carpentry** datacarpentry/image-processing](https://github.com/datacarpentry/image-processing) | [website](https://datacarpentry.org/image-processing)
- [**Dominic Waithe** dwaithe/model-training](https://github.com/dwaithe/model-training)

### Cloud computing

- [**Data Carpentry** datacarpentry/cloud-genomics](https://github.com/datacarpentry/cloud-genomics) | [website](https://datacarpentry.org/cloud-genomics/)
- [**AWS Samples** aws-samples/aws-hpc-tutorials](https://github.com/aws-samples/aws-hpc-tutorials) | [website](https://hpcworkshops.com)
- [**Eija Korpelainen** ekorpela/cloud-vm-workshop](https://github.com/ekorpela/cloud-vm-workshop/tree/master/materials)

## Omics analysis


### Genomics

- [**Canadian Bioinformatics Workshops** bioinformatics-ca/CAN_2021](https://github.com/bioinformatics-ca/CAN_2021)
- [**Canadian Bioinformatics Workshops** bioinformatics-ca/HTG_2021](https://github.com/bioinformatics-ca/HTG_2021)
- [**Papenfuss Lab** PapenfussLab/IntroductionToGenomicsWorkshop](https://github.com/PapenfussLab/IntroductionToGenomicsWorkshop)
- [**Computational Metagenomics** metagenomics/denbi-nanopore-training](https://github.com/metagenomics/denbi-nanopore-training)
- [**Computational Genomics with R** compgenomr/book](https://github.com/compgenomr/book) | [website](http://compgenomr.github.io/book)
- [**Wellcome Connecting Science** WCSCourses/SARS-COV-2_B4B](https://github.com/WCSCourses/SARS-COV-2_B4B) | [website](https://wcscourses.github.io/SARS-COV-2_B4B/)
- [**Functional Genomics Laboratory** Functional-Genomics-Lab/Applied-Genomics](https://github.com/Functional-Genomics-Lab/Applied-Genomics) | [website](https://functional-genomics-lab.github.io/Applied-Genomics/)
- [**cambiotraining** cambiotraining/sars-cov-2-genomics](https://github.com/cambiotraining/sars-cov-2-genomics) | [website](http://cambiotraining.github.io/sars-cov-2-genomics/)
- [**Data Carpentry** datacarpentry/genomics-workshop](https://github.com/datacarpentry/genomics-workshop) | [website](https://datacarpentry.org/genomics-workshop)
- [**Data Carpentry** datacarpentry/organization-genomics](https://github.com/datacarpentry/organization-genomics) | [website](https://datacarpentry.org/organization-genomics)
- [**The Gulbenkian Training Programme in Bioinformatics** GTPB/ELB19F](https://github.com/gtpb/ELB19F) | [website](https://gtpb.github.io/ELB19F/)

### Next generation sequencing

- [**CRUK CI Bioinformatics Core** bioinformatics-core-shared-training/cruk-summer-school-2020](https://github.com/bioinformatics-core-shared-training/cruk-summer-school-2020) | [website](https://bioinformatics-core-shared-training.github.io/cruk-summer-school-2020/ )
- [**Data Carpentry** datacarpentry/wrangling-genomics](https://github.com/datacarpentry/wrangling-genomics) | [website](https://datacarpentry.org/wrangling-genomics/)
- [**Teaching materials at the Harvard Chan Bioinformatics Core** hbctraining/Accessing_public_genomic_data](https://github.com/hbctraining/Accessing_public_genomic_data) | [website](https://hbctraining.github.io/Accessing_public_genomic_data)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/NGS-introduction-training](https://github.com/sib-swiss/NGS-introduction-training) | [website](https://sib-swiss.github.io/NGS-introduction-training/)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/NGS-variants-training](https://github.com/sib-swiss/NGS-variants-training) | [website](https://sib-swiss.github.io/NGS-variants-training/)
- [**Waldron Lab at the CUNY SPH** waldronlab/CNVWorkshop](https://github.com/waldronlab/CNVWorkshop) | [website](https://waldronlab.io/CNVWorkshop)
- [**The Griffith Lab** griffithlab/pmbio.org](https://github.com/griffithlab/pmbio.org) | [website](http://pmbio.org)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/workshop-ngsintro](https://github.com/NBISweden/workshop-ngsintro) | [website](https://NBISweden.github.io/workshop-ngsintro)
- [**Institut Français de Bioinformatique (IFB)** IFB-ElixirFr/EBAII](https://github.com/IFB-ElixirFr/EBAII) | [website](https://ifb-elixirfr.github.io/EBAII/)
- [**Cloud-SPAN** Cloud-SPAN/00genomics](https://github.com/cloud-span/00genomics) | [website](https://cloud-span.github.io/00genomics/)

### Transcriptomics

- [**Biocore@CRG** biocorecrg/RNAseq_course_2019](https://github.com/biocorecrg/RNAseq_course_2019) | [website](https://biocorecrg.github.io/RNAseq_course_2019/)
- [**Canadian Bioinformatics Workshops** bioinformatics-ca/RNA_2021](https://github.com/bioinformatics-ca/RNA_2021)
- [**CRUK CI Bioinformatics Core** bioinformatics-core-shared-training/Bulk_RNASeq_Course_Nov21](https://github.com/bioinformatics-core-shared-training/Bulk_RNASeq_Course_Nov21) | [website](https://bioinformatics-core-shared-training.github.io/Bulk_RNASeq_Course_Nov21/)
- [**carpentries-incubator** carpentries-incubator/bioc-rnaseq](https://github.com/carpentries-incubator/bioc-rnaseq) | [website](https://carpentries-incubator.github.io/bioc-rnaseq)
- [**Teaching materials at the Harvard Chan Bioinformatics Core** hbctraining/DGE_workshop_salmon_online](https://github.com/hbctraining/DGE_workshop_salmon_online) | [website](https://hbctraining.github.io/DGE_workshop_salmon_online/)
- [**Teaching materials at the Harvard Chan Bioinformatics Core** hbctraining/Intro-to-rnaseq-hpc-salmon-flipped](https://github.com/hbctraining/Intro-to-rnaseq-hpc-salmon-flipped) | [website](https://hbctraining.github.io/Intro-to-rnaseq-hpc-salmon-flipped/)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/RNAseq-introduction-training](https://github.com/sib-swiss/RNAseq-introduction-training)
- [**Stefano Mangiola** stemangiola/bioc_2020_tidytranscriptomics](https://github.com/stemangiola/bioc_2020_tidytranscriptomics) | [website](https://stemangiola.github.io/bioc_2020_tidytranscriptomics/)
- [**Tidy-transcriptomics workshops** tidytranscriptomics-workshops/bioc2022_tidytranscriptomics](https://github.com/tidytranscriptomics-workshops/bioc2022_tidytranscriptomics) | [website](https://tidytranscriptomics-workshops.github.io/bioc2022_tidytranscriptomics/index.html)
- [**Xueyi Dong** XueyiDong/RNAseq123workshop](https://github.com/XueyiDong/RNAseq123workshop)
- [**Amarinder** amarinderthind/RNA-seq-tutorial-for-gene-differential-expression-analysis](https://github.com/amarinderthind/RNA-seq-tutorial-for-gene-differential-expression-analysis)
- [**CRUK CI Bioinformatics Core** bioinformatics-core-shared-training/Bulk_RNASeq_Course_March23](https://github.com/bioinformatics-core-shared-training/Bulk_RNASeq_Course_March23) | [website](https://bioinformatics-core-shared-training.github.io/Bulk_RNASeq_Course_March23/)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/workshop-RNAseq](https://github.com/NBISweden/workshop-RNAseq) | [website](https://NBISweden.github.io/workshop-RNAseq)
- [**Health Data Science Sandbox** hds-sandbox/bulk_RNAseq_course](https://github.com/hds-sandbox/bulk_RNAseq_course) | [website](https://hds-sandbox.github.io/bulk_RNAseq_course/)
- [**Computational Biology and Bioinformatics at UCLouvain** UCLouvain-CBIO/WSBIM2122](https://github.com/UCLouvain-CBIO/WSBIM2122) | [website](https://uclouvain-cbio.github.io/WSBIM2122/)
- [**Saez Lab** saezlab/transcriptutorial](https://github.com/saezlab/transcriptutorial) | [website](https://saezlab.github.io/transcriptutorial/)
- [**The Gulbenkian Training Programme in Bioinformatics** GTPB/ADER19F](https://github.com/gtpb/ADER19F) | [website](http://gtpb.github.io/ADER19F)

### RNA-seq

- [**Teaching materials at the Harvard Chan Bioinformatics Core** hbctraining/BBS230B_2023](https://github.com/hbctraining/BBS230B_2023) | [website](https://hbctraining.github.io/BBS230B_2023/)
- [**Teaching materials at the Harvard Chan Bioinformatics Core** hbctraining/rnaseq-cb321](https://github.com/hbctraining/rnaseq-cb321)
- [**Teaching materials at the Harvard Chan Bioinformatics Core** hbctraining/RNA-seq-CB321qc_2022](https://github.com/hbctraining/RNA-seq-CB321qc_2022)
- [**Teaching materials at the Harvard Chan Bioinformatics Core** hbctraining/rnaseq_overview](https://github.com/hbctraining/rnaseq_overview)
- [**UC Davis Bioinformatics Core Training Page** ucdavis-bioinformatics-training/2023-June-RNA-Seq-Analysis](https://github.com/ucdavis-bioinformatics-training/2023-June-RNA-Seq-Analysis)
- [**bioinformatics.ca** bioinformaticsdotca/RNA_2023](https://github.com/bioinformaticsdotca/RNA_2023)
- [**bioinformatics.ca** bioinformaticsdotca/PNA_2023](https://github.com/bioinformaticsdotca/PNA_2023)

### Single-cell sequencing

- [**Aedin Culhane** aedin/scRNAseqBasicWorkflow](https://github.com/aedin/scRNAseqBasicWorkflow)
- [**CRUK CI Bioinformatics Core** bioinformatics-core-shared-training/UnivCambridge_ScRnaSeq_Nov2021](https://github.com/bioinformatics-core-shared-training/UnivCambridge_ScRnaSeq_Nov2021) | [website](http://bioinformatics-core-shared-training.github.io/UnivCambridge_ScRnaSeq_Nov2021)
- [**fmicompbio** fmicompbio/adv_scrnaseq_2020](https://github.com/fmicompbio/adv_scrnaseq_2020)
- [**Teaching materials at the Harvard Chan Bioinformatics Core** hbctraining/scRNA-seq_online](https://github.com/hbctraining/scRNA-seq_online) | [website](https://hbctraining.github.io/scRNA-seq_online/.)
- [**Kelly Street** kstreet13/bioc2020trajectories](https://github.com/kstreet13/bioc2020trajectories) | [website](https://kstreet13.github.io/bioc2020trajectories/)
- [**Leiden Computational Biology Center** LeidenCBC/MGC-BioSB-SingleCellAnalysis2021](https://github.com/LeidenCBC/MGC-BioSB-SingleCellAnalysis2021)
- [**Martin Morgan** mtmorgan/HCABiocTraining](https://github.com/mtmorgan/HCABiocTraining) | [website](https://mtmorgan.github.io/HCABiocTraining/)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/excelerate-scRNAseq](https://github.com/NBISweden/excelerate-scRNAseq) | [website](https://nbisweden.github.io/excelerate-scRNAseq/)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/single-cell_sib_scilifelab_2021](https://github.com/NBISweden/single-cell_sib_scilifelab_2021)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/workshop-scRNAseq](https://github.com/nbisweden/workshop-scRNAseq) | [website](https://nbisweden.github.io/workshop-scRNAseq/)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/single-cell-training](https://github.com/sib-swiss/single-cell-training) | [website](https://sib-swiss.github.io/single-cell-training/)
- [**Yunshun Chen** yunshun/SingleCellWorkshop](https://github.com/yunshun/SingleCellWorkshop)
- [**Cellular Genetics Informatics** cellgeni/scRNA.seq.course](https://github.com/cellgeni/scRNA.seq.course) | [website](https://scrnaseq-course.cog.sanger.ac.uk/website/index.html)
- [**CRUK CI Bioinformatics Core** bioinformatics-core-shared-training/SingleCell_RNASeq_Jan23](https://github.com/bioinformatics-core-shared-training/SingleCell_RNASeq_Jan23) | [website](https://bioinformatics-core-shared-training.github.io/SingleCell_RNASeq_Jan23/)
- [**OSCA Source Code Management** OSCA-source/OSCA](https://github.com/OSCA-source/OSCA) | [website](https://bioconductor.org/checkResults/devel/books-LATEST/OSCA)
- [**carpentries-incubator** carpentries-incubator/scrna-seq-analysis](https://github.com/carpentries-incubator/scrna-seq-analysis) | [website](https://carpentries-incubator.github.io/scrna-seq-analysis/)
- [**Bioconductor** Bioconductor/ISMB.OSCA](https://github.com/Bioconductor/ISMB.OSCA) | [website](https://bioconductor.github.io/ISMB.OSCA/)
- [**Theis Lab** theislab/single-cell-best-practices](https://github.com/theislab/single-cell-best-practices) | [website](https://www.sc-best-practices.org)
- [**Health Data Science Sandbox** hds-sandbox/scRNASeq_course](https://github.com/hds-sandbox/scRNASeq_course) | [website](https://hds-sandbox.github.io/scRNASeq_course/)
- [**Broad Institute** broadinstitute/2020_scWorkshop](https://github.com/broadinstitute/2020_scWorkshop) | [website](https://broadinstitute.github.io/2020_scWorkshop/)
- [**Rhonda Bacher** rhondabacher/ISMB2019_SingleCellTutorial](https://github.com/rhondabacher/ISMB2019_SingleCellTutorial)
- [**UC Davis Bioinformatics Core Training Page** ucdavis-bioinformatics-training/2023-December-Single-Cell-RNA-Seq-Analysis](https://github.com/ucdavis-bioinformatics-training/2023-December-Single-Cell-RNA-Seq-Analysis)
- [**UC Davis Bioinformatics Core Training Page** ucdavis-bioinformatics-training/2023-June-Single-Cell-RNA-Seq-Analysis](https://github.com/ucdavis-bioinformatics-training/2023-June-Single-Cell-RNA-Seq-Analysis)
- [**UC Davis Bioinformatics Core Training Page** ucdavis-bioinformatics-training/2023-June-Advanced-Topics-in-Single-Cell-RNA-Seq-VDJ](https://github.com/ucdavis-bioinformatics-training/2023-June-Advanced-Topics-in-Single-Cell-RNA-Seq-VDJ)
- [**UC Davis Bioinformatics Core Training Page** ucdavis-bioinformatics-training/2020-Advanced_Single_Cell_RNA_Seq](https://github.com/ucdavis-bioinformatics-training/2020-Advanced_Single_Cell_RNA_Seq)
- [**UC Davis Bioinformatics Core Training Page** ucdavis-bioinformatics-training/2022-July-Advanced-Topics-in-Single-Cell-RNA-Seq-ATAC](https://github.com/ucdavis-bioinformatics-training/2022-July-Advanced-Topics-in-Single-Cell-RNA-Seq-ATAC)
- [**UC Davis Bioinformatics Core Training Page** ucdavis-bioinformatics-training/2021-August-Advanced-Topics-in-Single-Cell-RNA-Seq-Trajectory-and-Velocity](https://github.com/ucdavis-bioinformatics-training/2021-August-Advanced-Topics-in-Single-Cell-RNA-Seq-Trajectory-and-Velocity)
- [**bioinformatics.ca** bioinformaticsdotca/scRNA_2023](https://github.com/bioinformaticsdotca/scRNA_2023)

### Variant analysis

- [**Andries Marees** MareesAT/GWA_tutorial](https://github.com/MareesAT/GWA_tutorial)
- [**Teaching materials at the Harvard Chan Bioinformatics Core** hbctraining/variant_analysis](https://github.com/hbctraining/variant_analysis) | [website](https://hbctraining.github.io/variant_analysis/)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/workshop-pgip](https://github.com/NBISweden/workshop-pgip) | [website](https://nbisweden.github.io/workshop-pgip/)
- [**UC Davis Bioinformatics Core Training Page** ucdavis-bioinformatics-training/2020-Variant_Analysis_Workshop](https://github.com/ucdavis-bioinformatics-training/2020-Variant_Analysis_Workshop)
- [**UC Davis Bioinformatics Core Training Page** ucdavis-bioinformatics-training/2021-July-Genome-Wide-Association-Studies](https://github.com/ucdavis-bioinformatics-training/2021-July-Genome-Wide-Association-Studies)

### ChIP-seq

- [**CRUK CI Bioinformatics Core** bioinformatics-core-shared-training/Quantitative-ChIPseq-Workshop](https://github.com/bioinformatics-core-shared-training/Quantitative-ChIPseq-Workshop)
- [**Teaching materials at the Harvard Chan Bioinformatics Core** hbctraining/Intro-to-ChIPseq](https://github.com/hbctraining/Intro-to-ChIPseq) | [website](https://hbctraining.github.io/Intro-to-ChIPseq/)
- [**hukai916** hukai916/IntegratedChIPseqWorkshop](https://github.com/hukai916/IntegratedChIPseqWorkshop)
- [**Teaching materials at the Harvard Chan Bioinformatics Core** hbctraining/Intro-to-ChIPseq-flipped](https://github.com/hbctraining/Intro-to-ChIPseq-flipped) | [website](https://hbctraining.github.io/Intro-to-ChIPseq-flipped/)
- [**Teaching materials at the Harvard Chan Bioinformatics Core** hbctraining/Peak_analysis_workshop](https://github.com/hbctraining/Peak_analysis_workshop)
- [**Denis Puthier** dputhier/EBA_2015_ChIP-Seq](https://github.com/dputhier/EBA_2015_ChIP-Seq)

### Comparative genomics

- [**Steven M. Van Belleghem** StevenVB12/stevenvb12.github.io](https://github.com/StevenVB12/stevenvb12.github.io)
- [**The Gulbenkian Training Programme in Bioinformatics** GTPB/CPANG19](https://github.com/gtpb/CPANG19) | [website](https://gtpb.github.io/CPANG19/)

### Epigenetics

- [**Haibo Liu** haibol2016/ATACseqQCWorkshop](https://github.com/haibol2016/ATACseqQCWorkshop)
- [**bioinformatics.ca** bioinformaticsdotca/EPI_2023](https://github.com/bioinformaticsdotca/EPI_2023)
- [**UC Davis Bioinformatics Core Training Page** ucdavis-bioinformatics-training/2020-Epigenetics_Workshop](https://github.com/ucdavis-bioinformatics-training/2020-Epigenetics_Workshop)

### Genome annotation

- [**Katharina Hoff** KatharinaHoff/BRAKER-TSEBRA-Workshop](https://github.com/KatharinaHoff/BRAKER-TSEBRA-Workshop)

### Genome assembly

- [**UC Davis Bioinformatics Core Training Page** ucdavis-bioinformatics-training/2020-Genome_Assembly_Workshop](https://github.com/ucdavis-bioinformatics-training/2020-Genome_Assembly_Workshop)

### Metagenomics

- [**Canadian Bioinformatics Workshops** bioinformatics-ca/MIC_2021](https://github.com/bioinformatics-ca/MIC_2021)
- [**Matteo Calgaro** mcalgaro93/benchdamicWorkshop](https://github.com/mcalgaro93/benchdamicWorkshop)
- [**Waldron Lab at the CUNY SPH** waldronlab/curatedMetagenomicDataAnalyses](https://github.com/waldronlab/curatedMetagenomicDataAnalyses) | [website](https://waldronlab.io/curatedMetagenomicDataAnalyses/)
- [**The Carpentries Lab** carpentries-lab/metagenomics-workshop](https://github.com/carpentries-lab/metagenomics-workshop) | [website](https://carpentries-lab.github.io/metagenomics-workshop/)
- [**The Carpentries Lab** carpentries-lab/metagenomics-organization](https://github.com/carpentries-lab/metagenomics-organization) | [website](https://carpentries-lab.github.io/metagenomics-organization/)
- [**The Carpentries Lab** carpentries-lab/metagenomics-analysis](https://github.com/carpentries-lab/metagenomics-analysis) | [website](https://carpentries-lab.github.io/metagenomics-analysis/)
- [**The Carpentries Lab** carpentries-lab/metagenomics-R](https://github.com/carpentries-lab/metagenomics-R) | [website](https://carpentries-lab.github.io/metagenomics-R/)
- [**UC Davis Bioinformatics Core Training Page** ucdavis-bioinformatics-training/2021-May-Microbial-Community-Analysis](https://github.com/ucdavis-bioinformatics-training/2021-May-Microbial-Community-Analysis)
- [**bioinformatics.ca** bioinformaticsdotca/MIC_2023](https://github.com/bioinformaticsdotca/MIC_2023)
- [**bioinformatics.ca** bioinformaticsdotca/MIC_2022](https://github.com/bioinformaticsdotca/MIC_2022)

### Epidemiology

- [**Canadian Bioinformatics Workshops** bioinformatics-ca/EPI_2021](https://github.com/bioinformatics-ca/EPI_2021)
- [**Canadian Bioinformatics Workshops** bioinformatics-ca/IDE_2021](https://github.com/bioinformatics-ca/IDE_2021)
- [**Chloe Mirzayi** cmirzayi/EpiForBioWorkshop2020](https://github.com/cmirzayi/EpiForBioWorkshop2020) | [website](https://cmirzayi.github.io/EpiForBioWorkshop2020/)
- [**bioinformatics.ca** bioinformaticsdotca/IDE_2023](https://github.com/bioinformaticsdotca/IDE_2023)

### Multiomics

- [**Waldron Lab at the CUNY SPH** waldronlab/MultiAssayWorkshop](https://github.com/waldronlab/MultiAssayWorkshop) | [website](https://waldronlab.github.io/MultiAssayWorkshop)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/multiomics-data-analysis-and-integration-training](https://github.com/sib-swiss/multiomics-data-analysis-and-integration-training)

### Spatial transcriptomics

- [**Davis Laboratory** DavisLaboratory/GeoMXAnalysisWorkflow](https://github.com/DavisLaboratory/GeoMXAnalysisWorkflow) | [website](https://davislaboratory.github.io/GeoMXAnalysisWorkflow/)
- [**dario righelli** drighelli/SpatialExperiment_Bioc2021](https://github.com/drighelli/SpatialExperiment_Bioc2021)
- [**Integrative Computational Biology and Multiomics Research Group** ncl-icbam/ismb-tutorial-2023](https://github.com/ncl-icbam/ismb-tutorial-2023)
- [**Sydney Precision Data Science Centre** SydneyBioX/StatialBioc2023](https://github.com/SydneyBioX/StatialBioc2023) | [website](https://SydneyBioX.github.io/StatialBioc2023/)
- [**UC Davis Bioinformatics Core Training Page** ucdavis-bioinformatics-training/2022-December-Spatial-Transcriptomics](https://github.com/ucdavis-bioinformatics-training/2022-December-Spatial-Transcriptomics)

### Long read sequencing

- [**SIB Swiss Institute of Bioinformatics** sib-swiss/NGS-longreads-training](https://github.com/sib-swiss/NGS-longreads-training) | [website](https://sib-swiss.github.io/NGS-longreads-training/)
- [**UC Davis Bioinformatics Core Training Page** ucdavis-bioinformatics-training/2021-August-Iso-Seq](https://github.com/ucdavis-bioinformatics-training/2021-August-Iso-Seq)

### Metabolomics

- [**bioinformatics.ca** bioinformaticsdotca/MET_2023](https://github.com/bioinformaticsdotca/MET_2023)

### Proteomics

- [**Computational Biology and Bioinformatics at UCLouvain** UCLouvain-CBIO/LSTAT2340](https://github.com/UCLouvain-CBIO/LSTAT2340) | [website](https://uclouvain-cbio.github.io/LSTAT2340/)
- [**Health Data Science Sandbox** hds-sandbox/proteomics-sandbox](https://github.com/hds-sandbox/proteomics-sandbox) | [website](https://hds-sandbox.github.io/proteomics-sandbox/index.html)
- [**statOmics** statOmics/PDA](https://github.com/statomics/PDA)
- [**The Gulbenkian Training Programme in Bioinformatics** GTPB/IBIP19](https://github.com/gtpb/IBIP19) | [website](https://gtpb.github.io/IBIP19/)
- [**The Gulbenkian Training Programme in Bioinformatics** GTPB/PDA19](https://github.com/gtpb/PDA19) | [website](https://gtpb.github.io/PDA19/)

### Pathways and Networks

- [**Canadian Bioinformatics Workshops** bioinformatics-ca/PNA_2021](https://github.com/bioinformatics-ca/PNA_2021)
- [**Susan** Coort/tutorial-network-data](https://gitlab.com/Coort/tutorial-network-data)
- [**LaurenDupuis** LaurenDupuis/EJP-RD_Helis_Academy](https://github.com/laurendupuis/EJP-RD_Helis_Academy)
- [**LaurenDupuis** LaurenDupuis/EJP-RD_Helis_Academy](https://github.com/laurendupuis/EJP-RD_Helis_Academy)

## Reproducibility and data management


### Data management

- [**CRUK CI Bioinformatics Core** bioinformatics-core-shared-training/Managing-your-research-data](https://github.com/bioinformatics-core-shared-training/Managing-your-research-data) | [website](https://bioinformatics-core-shared-training.github.io/Managing-your-research-data/)
- [**carpentries-incubator** carpentries-incubator/capstone-novice-spreadsheet-biblio](https://github.com/carpentries-incubator/capstone-novice-spreadsheet-biblio) | [website](http://carpentries-incubator.github.io/capstone-novice-spreadsheet-biblio/)
- [**ELIXIR Belgium** ELIXIR-Belgium/rdm-guide](https://github.com/ELIXIR-Belgium/rdm-guide) | [website](https://rdm.elixir-belgium.org)
- [**ELIXIR Europe** elixir-europe/rdmkit](https://github.com/elixir-europe/rdmkit) | [website](https://rdmkit.elixir-europe.org)
- [**Korbinian Bösl** ELIXIR-Norway-Training/DMP-writing-workshop](https://github.com/korbinib/DMP-writing-workshop) | [website](https://elixir.no)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/sparql-training](https://github.com/sib-swiss/sparql-training)
- [**OpenSciency** opensciency/sprint-content](https://github.com/opensciency/sprint-content) | [website](https://opensciency.github.io/sprint-content/)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/ena-seqdata-training](https://github.com/sib-swiss/ena-seqdata-training) | [website](https://sib-swiss.github.io/ena-seqdata-training/)
- [**VIB Technologies: Bioinformatics and software projects** vibbits/rdm-introductory-course](https://github.com/vibbits/rdm-introductory-course)
- [**Utrecht University** UtrechtUniversity/dataprivacyhandbook](https://github.com/utrechtuniversity/dataprivacyhandbook) | [website](https://utrechtuniversity.github.io/dataprivacyhandbook/)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/module-dmp-dm-practices](https://github.com/NBISweden/module-dmp-dm-practices/) | [website](https://nbisweden.github.io/module-dmp-dm-practices/)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/module-data-publication-dm-practices](https://github.com/NBISweden/module-data-publication-dm-practices/) | [website](https://nbisweden.github.io/module-data-publication-dm-practices/)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/module-metadata-dm-practices](https://github.com/NBISweden/module-metadata-dm-practices/) | [website](https://nbisweden.github.io/module-metadata-dm-practices/)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/module-organising-data-dm-practices](https://github.com/NBISweden/module-organising-data-dm-practices/) | [website](https://nbisweden.github.io/module-organising-data-dm-practices/)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/module-open-science-dm-practices](https://github.com/NBISweden/module-open-science-dm-practices/) | [website](https://nbisweden.github.io/module-open-science-dm-practices/index.html)
- [**Health Data Science Sandbox** hds-sandbox/RDM_NGS_course](https://github.com/hds-sandbox/RDM_NGS_course) | [website](https://hds-sandbox.github.io/RDM_NGS_course/)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/Introduction-FAIR-RDM-DMP](https://github.com/sib-swiss/Introduction-FAIR-RDM-DMP) | [website](https://sib-swiss.github.io/Introduction-FAIR-RDM-DMP/)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/module-dmp-dm-practices](https://github.com/nbisweden/module-dmp-dm-practices) | [website](https://nbisweden.github.io/module-dmp-dm-practices/)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/module-openrefine-dm-practices](https://github.com/nbisweden/module-openrefine-dm-practices) | [website](https://nbisweden.github.io/module-openrefine-dm-practices/)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/module-data-publication-dm-practices](https://github.com/nbisweden/module-data-publication-dm-practices) | [website](https://nbisweden.github.io/module-data-publication-dm-practices/)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/module-metadata-dm-practices](https://github.com/nbisweden/module-metadata-dm-practices) | [website](https://nbisweden.github.io/module-metadata-dm-practices/)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/module-organising-data-dm-practices](https://github.com/nbisweden/module-organising-data-dm-practices) | [website](https://nbisweden.github.io/module-organising-data-dm-practices/)
- [**BioData.pt** BioData-PT/Ready4BioDataManagement](https://github.com/BioData-PT/Ready4BioDataManagement)

### FAIR data

- [**carpentries-incubator** carpentries-incubator/fair-bio-practice](https://github.com/carpentries-incubator/fair-bio-practice) | [website](https://carpentries-incubator.github.io/fair-bio-practice/)
- [**carpentries-incubator** carpentries-incubator/fair-for-leaders](https://github.com/carpentries-incubator/fair-for-leaders) | [website](https://carpentries-incubator.github.io/fair-for-leaders/)
- [**elixir-oslo** ELIXIR-Norway-Training/fair-dm-lifesci-june-2022](https://github.com/elixir-oslo/fair-dm-lifesci-june-2022)
- [**FAIRplus** FAIRplus/the-fair-cookbook](https://github.com/FAIRplus/the-fair-cookbook) | [website](https://faircookbook.elixir-europe.org)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/module-repository-submission-dm-practices](https://github.com/NBISweden/module-repository-submission-dm-practices)
- [**ELIXIR Europe Training** elixir-europe-training/ELIXIR-TrP-FAIR-training-handbook](https://github.com/elixir-europe-training/ELIXIR-TrP-FAIR-training-handbook) | [website](https://elixir-europe-training.github.io/ELIXIR-TrP-FAIR-training-handbook/)
- [**ELIXIR Europe Training** elixir-europe-training/ELIXIR-TrP-FAIR-Converge](https://github.com/elixir-europe-training/ELIXIR-TrP-FAIR-Converge) | [website](https://elixir-europe-training.github.io/ELIXIR-TrP-FAIR-Converge/)
- [**Institut Français de Bioinformatique (IFB)** IFB-ElixirFr/IFB-FAIR-bioinfo-training](https://github.com/IFB-ElixirFr/IFB-FAIR-bioinfo-training) | [website](https://ifb-elixirfr.github.io/IFB-FAIR-bioinfo-training)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/module-open-science-dm-practices](https://github.com/nbisweden/module-open-science-dm-practices) | [website](https://nbisweden.github.io/module-open-science-dm-practices/index.html)
- [**Institut Français de Bioinformatique (IFB)** IFB-ElixirFr/IFB-FAIR-data-training](https://github.com/ifb-elixirfr/IFB-FAIR-data-training)
- [**Sergio Martínez Cuesta** semacu/20180223_ORCID_Chemistry_Cambridge](https://github.com/semacu/20180223_ORCID_Chemistry_Cambridge)

### Reproducibility

- [**Teaching materials at the Harvard Chan Bioinformatics Core** hbctraining/reproducibility-tools](https://github.com/hbctraining/reproducibility-tools) | [website](https://hbctraining.github.io/reproducibility-tools/)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/workshop-reproducible-research](https://github.com/NBISweden/workshop-reproducible-research)
- [**carpentries-incubator** carpentries-incubator/managing-computational-projects](https://github.com/carpentries-incubator/managing-computational-projects) | [website](https://carpentries-incubator.github.io/managing-computational-projects)
- [**carpentries-incubator** carpentries-incubator/jekyll-pages-novice](https://github.com/carpentries-incubator/jekyll-pages-novice) | [website](https://carpentries-incubator.github.io/jekyll-pages-novice/)
- [**carpentries-incubator** carpentries-lab/good-enough-practices](https://github.com/carpentries-incubator/good-enough-practices) | [website](https://carpentries-lab.github.io/good-enough-practices/)
- [**Data Carpentry** datacarpentry/rr-organization1](https://github.com/datacarpentry/rr-organization1) | [website](http://www.datacarpentry.org/rr-organization1/)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/reproducible-analysis-training](https://github.com/sib-swiss/reproducible-analysis-training) | [website](https://sib-swiss.github.io/reproducible-analysis-training/)
- [**ELIXIR Europe Training** elixir-europe-training/ELIXIR-TrP-ContainersPython-CodeRep](https://github.com/elixir-europe-training/ELIXIR-TrP-ContainersPython-CodeRep) | [website](https://elixir-europe-training.github.io/ELIXIR-TrP-ContainersPython-CodeRep/)
- [**ELIXIR Europe Training** elixir-europe-training/ELIXIR-TrP-LiterateProgrammingR-CodeRep](https://github.com/elixir-europe-training/ELIXIR-TrP-LiterateProgrammingR-CodeRep) | [website](https://elixir-europe-training.github.io/ELIXIR-TrP-LiterateProgrammingR-CodeRep/)

## Statistics and machine learning


### Data science

- [**Stephanie Hicks** stephaniehicks/superwomen](https://github.com/stephaniehicks/superwomen) | [website](https://www.stephaniehicks.com/superwomen/)
- [**Hacking for Science** h4sci/h4sci-course](https://github.com/h4sci/h4sci-course)
- [**DataTalksClub** DataTalksClub/data-engineering-zoomcamp](https://github.com/DataTalksClub/data-engineering-zoomcamp)
- [**Jose A Dianes** jadianes/data-science-your-way](https://github.com/jadianes/data-science-your-way) | [website](http://jadianes.github.io/data-science-your-way)
- [**Jose A Dianes** jadianes/spark-r-notebooks](https://github.com/jadianes/spark-r-notebooks) | [website](http://jadianes.github.io/spark-r-notebooks)
- [**Data Carpentry** datacarpentry/spreadsheet-ecology-lesson](https://github.com/datacarpentry/spreadsheet-ecology-lesson) | [website](https://datacarpentry.org/spreadsheet-ecology-lesson)
- [**Data Science in Practice** DataScienceInPractice/Site](https://github.com/datascienceinpractice/Site) | [website](https://datascienceinpractice.github.io)
- [**Shawn Rhoads** shawnrhoads/gu-psyc-347](https://github.com/shawnrhoads/gu-psyc-347) | [website](https://shawnrhoads.github.io/gu-psyc-347/)
- [**NBIS - National Bioinformatics Infrastructure Sweden** NBISweden/module-openrefine-dm-practices](https://github.com/NBISweden/module-openrefine-dm-practices/) | [website](https://nbisweden.github.io/module-openrefine-dm-practices/)

### Statistics

- [**Aedin Culhane** aedin/PCAworkshop](https://github.com/aedin/PCAworkshop) | [website](https://aedin.github.io/PCAworkshop/)
- [**CRUK CI Bioinformatics Core** bioinformatics-core-shared-training/experimental-design](https://github.com/bioinformatics-core-shared-training/experimental-design) | [website](http://bioinformatics-core-shared-training.github.io/experimental-design)
- [**CRUK CI Bioinformatics Core** bioinformatics-core-shared-training/IntroductionToStats](https://github.com/bioinformatics-core-shared-training/IntroductionToStats) | [website](http://bioinformatics-core-shared-training.github.io/IntroductionToStats/)
- [**carpentries-incubator** carpentries-incubator/statistical-thinking-public-health](https://github.com/carpentries-incubator/statistical-thinking-public-health) | [website](https://carpentries-incubator.github.io/statistical-thinking-public-health)
- [**Richard McElreath** rmcelreath/stat_rethinking_2022](https://github.com/rmcelreath/stat_rethinking_2022)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/advanced-statistics](https://github.com/sib-swiss/advanced-statistics)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/intro-bayesian-statistics-training](https://github.com/sib-swiss/intro-bayesian-statistics-training)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/introduction-to-statistics-with-python-training](https://github.com/sib-swiss/introduction-to-statistics-with-python-training)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/Introduction-to-statistics-with-R](https://github.com/sib-swiss/Introduction-to-statistics-with-R)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/statistics-and-machine-learning-training](https://github.com/sib-swiss/statistics-and-machine-learning-training)
- [**Richard McElreath** rmcelreath/stat_rethinking_2023](https://github.com/rmcelreath/stat_rethinking_2023)
- [**David Dalpiaz** daviddalpiaz/appliedstats](https://github.com/daviddalpiaz/appliedstats) | [website](https://book.stat420.org)
- [**cambiotraining** cambiotraining/corestats](https://github.com/cambiotraining/corestats) | [website](https://cambiotraining.github.io/corestats/)
- [**David Dalpiaz** daviddalpiaz/r4sl](https://github.com/daviddalpiaz/r4sl) | [website](https://daviddalpiaz.github.io/r4sl/)
- [**Mojtaba Barzegari** mbarzegary/educational-bayesian](https://github.com/mbarzegary/educational-bayesian)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/Data-analysis-in-practice](https://github.com/sib-swiss/Data-analysis-in-practice)
- [**The Gulbenkian Training Programme in Bioinformatics** GTPB/PSLS22](https://github.com/gtpb/PSLS22) | [website](https://gtpb.github.io/PSLS22/)
- [**The Gulbenkian Training Programme in Bioinformatics** GTPB/PGDH19](https://github.com/gtpb/PGDH19) | [website](https://gtpb.github.io/PGDH19/)
- [**The Gulbenkian Training Programme in Bioinformatics** GTPB/PSLS20](https://github.com/gtpb/PSLS20) | [website](https://gtpb.github.io/PSLS20/)

### Machine learning

- [**Canadian Bioinformatics Workshops** bioinformatics-ca/MLE_2021](https://github.com/bioinformatics-ca/MLE_2021)
- [**carpentries-incubator** carpentries-incubator/machine-learning-novice-python](https://github.com/carpentries-incubator/machine-learning-novice-python) | [website](https://carpentries-incubator.github.io/machine-learning-novice-python/)
- [**carpentries-incubator** carpentries-incubator/machine-learning-novice-sklearn](https://github.com/carpentries-incubator/machine-learning-novice-sklearn) | [website](https://carpentries-incubator.github.io/machine-learning-novice-sklearn/)
- [**fast.ai** fastai/course20](https://github.com/fastai/course20) | [website](https://book.fast.ai)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/intro-machine-learning-training](https://github.com/sib-swiss/intro-machine-learning-training)
- [**Phillip Lippe** phlippe/uvadlc_notebooks](https://github.com/phlippe/uvadlc_notebooks/) | [website](https://uvadlc-notebooks.readthedocs.io/en/latest/)
- [**carpentries-incubator** carpentries-incubator/ml4bio-workshop](https://github.com/carpentries-incubator/ml4bio-workshop) | [website](https://carpentries-incubator.github.io/ml4bio-workshop/)
- [**Instill AI** instillai/TensorFlow-Course](https://github.com/instillai/TensorFlow-Course)
- [**Yury Kashnitsky** Yorko/mlcourse.ai](https://github.com/Yorko/mlcourse.ai) | [website](https://mlcourse.ai)
- [**fast.ai** fastai/course-nlp](https://github.com/fastai/course-nlp) | [website](https://www.fast.ai/2019/07/08/fastai-nlp/)
- [**girafe.ai** girafe-ai/ml-course](https://github.com/girafe-ai/ml-course)
- [**Paderborn University - LEA** upb-lea/reinforcement_learning_course_materials](https://github.com/upb-lea/reinforcement_learning_course_materials)
- [**Lex Fridman** lexfridman/mit-deep-learning](https://github.com/lexfridman/mit-deep-learning) | [website](https://deeplearning.mit.edu)
- [**cambiotraining** cambiotraining/intro-machine-learning](https://github.com/cambiotraining/intro-machine-learning/) | [website](https://cambiotraining.github.io/intro-machine-learning/)
- [**carpentries-incubator** carpentries-incubator/data-science-ai-senior-researchers](https://github.com/carpentries-incubator/data-science-ai-senior-researchers) | [website](https://carpentries-incubator.github.io/data-science-ai-senior-researchers/)
- [**carpentries-incubator** carpentries-incubator/deep-learning-intro](https://github.com/carpentries-incubator/deep-learning-intro) | [website](https://carpentries-incubator.github.io/deep-learning-intro/)
- [**Sven Degroeve** sdgroeve/Machine-Learning-Course-2days](https://github.com/sdgroeve/Machine-Learning-Course-2days)
- [**Philip Bowsher** philbowsher/Workshop-R-Tensorflow-Scientific-Computing](https://github.com/philbowsher/Workshop-R-Tensorflow-Scientific-Computing)
- [**Nicola Rennie** nrennie/r-pharma-2023-tidymodels](https://github.com/nrennie/r-pharma-2023-tidymodels) | [website](https://nrennie.github.io/r-pharma-2023-tidymodels/)
- [**udlbook** udlbook/udlbook](https://github.com/udlbook/udlbook)
- [**bioinformatics.ca** bioinformaticsdotca/MLE_2023](https://github.com/bioinformaticsdotca/MLE_2023)
- [**SIB Swiss Institute of Bioinformatics** sib-swiss/pytorch-practical-training](https://github.com/sib-swiss/pytorch-practical-training)

## Others


### General

- [**Amanda Miotto** amandamiotto/HackyHourBookmarks](https://github.com/amandamiotto/HackyHourBookmarks)
- [**biodatascience** biodatascience/compbio](https://github.com/biodatascience/compbio) | [website](https://biodatascience.github.io/compbio/)
- [**Bradley Boehmke** bradleyboehmke/data-science-learning-resources](https://github.com/bradleyboehmke/data-science-learning-resources)
- [**Ming Tang** crazyhottommy/getting-started-with-genomics-tools-and-resources](https://github.com/crazyhottommy/getting-started-with-genomics-tools-and-resources)
- [**Teaching materials at the Harvard Chan Bioinformatics Core** hbctraining/Training-modules](https://github.com/hbctraining/Training-modules) | [website](https://hbctraining.github.io/Training-modules/)
- [**Genome Informatics Facility** ISUgenomics/bioinformatics-workbook](https://github.com/ISUgenomics/bioinformatics-workbook) | [website](https://bioinformaticsworkbook.org)
- [**Melbourne Bioinformatics** melbournebioinformatics/MelBioInf_docs](https://github.com/melbournebioinformatics/MelBioInf_docs)
- [**Mike Lee** AstrobioMike/AstrobioMike.github.io](https://github.com/AstrobioMike/AstrobioMike.github.io) | [website](https://astrobiomike.github.io)
- [**liulab-dfci** liulab-dfci/bioinfo-combio](https://github.com/liulab-dfci/bioinfo-combio)
- [**Leighton Pritchard** widdowquinn/Teaching-IBioIC-Intro-to-Bioinformatics](https://github.com/widdowquinn/Teaching-IBioIC-Intro-to-Bioinformatics) | [website](https://widdowquinn.github.io/Teaching-IBioIC-Intro-to-Bioinformatics/)
- [**Ujjwal Karn** ujjwalkarn/DataScienceR](https://github.com/ujjwalkarn/DataScienceR)
- [**Salvatore Raieli** SalvatoreRa/tutorial](https://github.com/SalvatoreRa/tutorial)
- [**Alex's Lemonade Stand Foundation** AlexsLemonade/training-modules](https://github.com/alexslemonade/training-modules)
- [**Andrea Telatin** telatin/microbiome-bioinformatics](https://github.com/telatin/microbiome-bioinformatics/) | [website](https://telatin.github.io/microbiome-bioinformatics)
- [**Ronan Harrington** rnnh/bioinfo-notebook](https://github.com/rnnh/bioinfo-notebook) | [website](https://rnnh.github.io/bioinfo-notebook/)
- [**Women In Bioinformatics and Data Science Latin America** WomenBioinfoDataScLA/Workshops](https://github.com/WomenBioinfoDataScLA/Workshops)
- [**Common Fund Data Ecosystem** nih-cfde/training-and-engagement](https://github.com/nih-cfde/training-and-engagement) | [website](https://training.nih-cfde.org)
- [**Thomas Denecker** thomasdenecker/FAIR_Bioinfo](https://github.com/thomasdenecker/FAIR_Bioinfo)
- [**Eric C. Anderson** eriqande/eca-bioinf-handbook](https://github.com/eriqande/eca-bioinf-handbook)
- [**Computational Biology and Bioinformatics at UCLouvain** UCLouvain-CBIO/WSBIM1322](https://github.com/UCLouvain-CBIO/WSBIM1322) | [website](https://uclouvain-cbio.github.io/WSBIM1322/)
- [**UC Davis Bioinformatics Core Training Page** ucdavis-bioinformatics-training/2020-Bioinformatics_Prerequisites_Workshop](https://github.com/ucdavis-bioinformatics-training/2020-Bioinformatics_Prerequisites_Workshop) | [website](https://ucdavis-bioinformatics-training.github.io/2020-Bioinformatics_Prerequisites_Workshop/)
