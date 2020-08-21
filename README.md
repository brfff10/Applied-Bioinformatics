# Applied Bioinformatics
Welcome to the Applied Bioinformatics course offered at [The Scripps Research Institute](https://www.scripps.edu//). </br>
Course materials from previous years are available [here](https://github.com/SuLab/Applied-Bioinformatics/tree/master). </br> 

Instructors: Dr. Andrew I Su ([@andrewsu](https://github.com/andrewsu)) and Dr. Sabah Ul-Hasan ([@sabahzero](https://github.com/sabahzero)) </br>
Teaching Assistants (TAs): Huitian Yolanda Diao ([@Huitian](https://github.com/Yolanda-HT)), Karthik Gangavarapu ([@gkarthik](https://github.com/gkarthik)), Shang-Fu Chen ([@ShaunFChen](https://github.com/ShaunFChen)) </br> 

This course is available in [2] parts and operates under the Computational Biology & Bioinformatics (CBB) core track: </br>
* Unit A:    Fundamentals of Scientific Computing (FSC), 4 weeks (1 credit) </br>
1. Learn and utilize the Bash (Unix shell) for file manipulation and navigation of the file system </br>
2. Learn and utilize R code to perform exploratory data analysis of data in files </br>
3. Learn and utilize Jupyter Notebook for R code </br>
4. Learn and utilize Git and GitHub for code versioning (tracking changes of source code) </br>
* Units B-C: Applied Bioinformatics and Computational Biology (ABCB), 8 weeks (2 credits) </br>
1. Learn the fundamentals of RNA-Seq, and its application in the larger biological research schema. </br>
2. Application of R in analyses of RNA-Seq data, from raw data to publishable statistics and figures. </br>
3. Practice and present on learned R skillset through published data via Capstone project. </br>
4. Understand and practice of peer review through self-evaluation and evaluation of peers. </br> 

The reasoning for this internal breakdown of the course is to give individuals an opportunity to "learn from scratch" and then go more in-depth, or choose either or path (solely partake in Unit A or Units B-C) depending on the individuals' needs. </br>

## Prerequisites

* An enthusiasm for learning, at whatever level of experience you may or may not be
* A Windows 10 or MacOS laptop (inform instructors if you need access to one of these)
* Software installation prior to arrival (by Sep 4th @ 5 PM PST): </br>
Command line (for Unix shell), R, and Jupyter Notebook (using Anaconda, includes Python 3) [here](Configuration.md) 
* Expectations: Individuals following this course either on their own or for credit should conduct professional and considerate behavior, likewise for TAs and Instructors. Individuals can typically anticipate feedback within a 48-hour time period during typical business hours.

## Schedule at a Glance

Each week consists of two 90-minute classes starting at 8:15 AM PST and ending at 9:45 AM PST from Sep 8th through Dec 10th, paired with one homework assignment (per week, weeks 1-9, 8 assignments in total). Within each class are two 45-minute sessions comprising of ~15-min lectures and ~30-min hands-on exercises with a brief recap at the end of the 90-minute period. </br> 
* Unit A (4 wks): </br> 
Fundamentals of Scientific Computing (FSC), or STBIO 400
  * Week 1: Course Introduction + Jupyter Notebook + Bash Basics  
  * Week 2: Bash in-depth + Git + HPC 
  * Week 3: Intro to R 
  * Week 4: Data Analysis and Plotting in R 
--
* Unit B (5 wks): </br>
Understanding and Exploration RNA-Seq, or STBIO 440i
  * Week 5: Continutation of R
  * Week 6: Introduction to RNA-Seq + Raw Data Ouput
  * Week 7: Introduction to Capstone Project + RNA-Seq Data Pre-processing
  * Week 8: RNA-Seq Data Pre-processing cnt'd + RNA-Seq Data Post-processing
  * Week 9: RNA-Seq Data Post-processing cnt'd + DESeq2
* Unit C (3 wks): </br>
Capstone Projects and Overview of the Bioinformatics Data Workflow Spectrum, or STBIO 440ii
  * Week 10: Capstone Project Workshop
  * Week 11: An Overview of Additional Bioinformatics Workflows (Metagenomics, Proteomics, and others) 
  * Week 12: Capstone Project Presentations

## Course Materials

### Unit A: Bash, R, Jupyter and Git
* A.1a (Sep 8): Intro and Bash Basics, [slides](https://docs.google.com/presentation/d/1cjYM4cq7nQxLqPT0840vcCYzDGUvpBtMaUNLRv6jrWU/edit?usp=sharing) and HW 1
* A.1b (Sep 10): Bash cnt'd, [slides](https://docs.google.com/presentation/d/12mHX_9_4X_49OO0mjyKCPKdoISATsVtKjPIn82Afcbg/edit?usp=sharing) 
* A.2a (Sep 15): Bash in-depth [slides](https://docs.google.com/presentation/d/1LsJTwx4qhoYWvyZzQDp_31RvuF68yy7Mv3QrBYINo-c/edit?usp=sharing) and HW 2
  * HW 1 Due @ 8 AM PST
* A.2b (Sep 17): Loops, Git, and HPC [slides](https://docs.google.com/presentation/d/16a_K8RNdvgDlTHZcZd-k826Y2EyAseFyYh3kP8SvdVo/edit?usp=sharing) 
* A.3a (Sep 22): Introduction to R [slides](https://docs.google.com/presentation/d/1nbw7FwPeiJrwZkstIvBDhuJGVFlwzJfl_NgKWWvMq5g/edit?usp=sharing) and HW 3
  * HW 2 Due @ 8 AM PST
* A.3b (Sep 24): R Objects and Operations [slides](https://docs.google.com/presentation/d/1Lg7rBrtMu2vYGLRNsaIexD1zmF8NfnSZhnNXVZCJ6pQ/edit?usp=sharing) 
* A.4a (Sep 29): Data Analysis and Function in R [slides](https://docs.google.com/presentation/d/1KP9Lt0zy_9OE8puUY4AhYMl1F4pgtKeDbU19aK43Xgo/edit?usp=sharing) 
  * HW 3 Due @ 8 AM PST
* A.4b (Oct 1): Plotting in R [slides](https://docs.google.com/presentation/d/1cRHx9g4CqMOBzItsAWl1E7b2et75LauO0S5LG5_i428/edit?usp=sharing) 

---

### Unit B: Exploration of RNA-Seq via Utilizing R
R Packages to be used for RNA-Seq Analyses [here](Configuration_RNAseq.md)
* B.5a (Oct 6): Overview of Unit A
  * HW 1 Due @ 8 AM PST
* B.5b (Oct 8): Introduction to R [slides](https://github.com/SuLab/Applied-Bioinformatics/raw/master/Unit1-module2-R/R-1.pptx) and [notebook](Unit1-module2-R/R.intro.1.ipynb) with [sample answer](Unit1-module2-R/R.intro.1.practice2.1.ipynb)
* B.6a (Oct 13): R operations [slides](https://github.com/SuLab/Applied-Bioinformatics/raw/master/Unit1-module2-R/R-2.pptx) and [notebook](Unit1-module2-R/R.intro.2.ipynb) with sample answers [2](Unit1-module2-R/R.intro.1.practice2.2.ipynb) and [3](Unit1-module2-R/R.intro.1.practice2.3.ipynb) 
  * HW 2 Due @ 8 AM PST
* B.6b (Oct 15): R review [slides](https://github.com/SuLab/Applied-Bioinformatics/raw/master/Unit1-module2-R/R-3.pptx) and sample answer [4](Unit1-module2-R/R.intro.1.practice2.4.ipynb) with [extension info on loops](https://docs.google.com/presentation/d/1y0Yoyvejc8mp3MZWKPAw_u4sj5-wN4CSAi2U30IkWAs/)
* B.7a (Oct 20): Data visualization in R [slides](Unit1-module2-R/2.5_plotting.pdf) and [notebook](Unit1-module2-R/2.5_plotting_1.ipynb)
  * HW 3 Due @ 8 AM PST
* B.7b (Oct 22): Overview of RNA-Seq [slides](https://docs.google.com/presentation/d/1UJ_aLFQuwR_ZByDbpDjaaqGBhVZwA_8VHhy0RqWufN0/edit?usp=sharing)
* B.8a (Oct 27): Introduction to RNA-Seq data [slides](https://drive.google.com/open?id=1HMJQ6KhuneSVr7Obx8SBOTbda8BSXlmF) and [notebook](Unit2-RNAseq/3.1_raw-rnaseq-data.ipynb) with [sample answer](Unit2-RNAseq/3.1_exercise_solutions.ipynb) 
  * HW 4 Due @ 8 AM PST
* B.8b (Oct 29): Pre-processing SAM files [slides](https://drive.google.com/open?id=1QdEsymay8bQrqoIUZE4ofKfMEqgBs1xm) and [notebook](Unit2-RNAseq/3.2_sam_and_htseq.ipynb) with sample answer [2](Unit2-RNAseq/3.2_exercise_solutions.ipynb)
* B.9a (Nov 3): Expression count analysis [slides](https://drive.google.com/open?id=1B7TiySFOo92vmwzr9YNwjdgxnhiDEMlW) and [notebook](Unit2-RNAseq/3.3_counts-based-pipeline.ipynb)
  * HW 5 Due @ 8 AM PST
* B.9b (Nov 5): Post-processing data for DESeq2 [slides](https://drive.google.com/open?id=1lDPbBNhdCZBajNED64Pcrr4foG0Zspqq) and notebooks [1](Unit2-RNAseq/3.4_DESeq2_import_data.ipynb) and [2](Unit2-RNAseq/3.5_DESeq2_expression_analysis.ipynb)
  * DeSeq2 continued [slides](https://drive.google.com/open?id=1deq5uIjmpa3G1zfb9PZqE1sT38uBsxGe) and [notebook](Unit2-RNAseq/3.6_DESeq2_differential_expression_analysis.ipynb), and more on enrichment via [slides](https://drive.google.com/file/d/1SE0LZBVgkB52l9SU0XHpmcvO6RyJMMzW/view?usp=sharing)

### Unit C: Capstone Project, and Overview of Pipelines
* C.10 a(Nov 10) - b(Nov 12): Workshop
* C.11a: Invited talks on applied bioinformatics research and career journeys
  * Dr. Chiranjit Mukherjee ([@cm0109](https://github.com/cm0109)) - microbiomes, Dr. Joel Babdor ([@joelBabdor](https://github.com/joelBabdor)) - immunology, Dr. Mario Banuelos ([@MBanuelos](https://github.com/MBanuelos)) - predictive modeling, Dr. Sally Chang - non-model organisms and genomics
* C.11b: Panel
  * Dr. Daniel Murin (CA) - Postdoctoral Associate / Graduate Alumn, Dr. Gogce Crynen (FL) - Bioinformatics Analyst , Dr. Jean-Christophe Ducom (CA) - HPC Director / IT, Dr. Pabalu Karunadharma (FL) - Genomics Core Director, and Dr. Padmaja Natarajan (CA) - Bioinformatics Analyst 
* C.12 a(Dec 1) - b (Dec 3): Presentations
  * cnt'd Dec 8 and Dec 10 (if necessary)

## How to Get Help? 
1. Is there a possibility the answer to my question is available online?
If the answer is available, post the original question and answer you found [as an Issue](https://github.com/SuLab/Applied-Bioinformatics/labels) with the 'question' label. Be sure to close the issue with the answer you found (including relevant resource links) after opening it. You will need [a Github account](https://www.youtube.com/watch?v=f_XsJIHSLRg) to do this.
2. If the answer is not available online, post it as a question-labeled Issue and pend for a response from the Instructors or TAs. Who knows, perhaps another student had also encountered the same issue and can answer it too!
3. If the obstacle is something more personal, such as a specific installation issue unique to your computer alone, reach out to the instructors. Any question is better than no question at all, and often we all learn from them (not just students)!
