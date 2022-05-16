
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Inheritance – upgrading a legacy project and making it your own

<!-- badges: start -->
<!-- badges: end -->

This repo contains slides and supporting materials for my presentation
at the [2022 RStudio Conference](https://www.rstudio.com/conference/) in
Washington D.C, July 28-29.

> It happens to us all - a request to update a workflow or data started
> before your time. The materials left behind leave much to be desired;
> a few Word docs here, a couple Excel workbooks there, some scattered
> ArcGIS maps, and PDFs. But fear not! In this talk, we will cover how
> to complete a project intake by evaluating current workflows, data
> sources, and methods. Then, we will assess which tools to use,
> including packages like {groundhog}, {testthat}, and {rmarkdown} and
> version control with GitHub. We will cover code and file hygiene, and
> how to maintain your motivation when obstacles appear. Finally, we
> will explore strategies for making this legacy project your own and
> setting up the next round of updates for success.

# Dates, logistics, requirements, etc.

A *crisp* 20 minutes.

-   Mid-June: schedule brown-bag style runthrough
-   July 1: Have content mostly finalized
-   July 7: Deadline for outfit assembly, get haircut.  
-   July 12: Speaker Coaching Content Review  
-   July 21: Complete talk backup recording
-   July 24: FLIGHT TO DC!
-   July 25-27
    -   Practice first thing in the morning, just before bed.
    -   Exercise, go to bed early, no sweets the morning of!

# Presentation

Current plan is to use xaringan, but this might get difficult due to
challenges with HTML styling. Backup is MS PowerPoint.

This *shouldn’t* have any actual tabular data, but we will see.

I my previous experience with xaringinan makes me have some reservations
about using it for this talk. This talk may rely heavily on screenshots
and images. I also DREAD the constant scrolling up and down to get to
each slide and the messy outline panel.

This could potentially be remedied by modularization and clever
`results='asis'` chunks.

# Repo structure

-   `.\slides-reference.Rmd` is the standard xaringanthemer template.
    Will use for reference in `.\slides.Rmd`.  
-   `.\css\` contains all CSS data, including font files, colors, etc.
-   `.\fig\` contains plots, screenshots, etc.

<PRE class="fansi fansi-output"><CODE>## <span style='color: #0000BB; font-weight: bold;'>.</span>
## ├── LICENSE.md
## ├── <span style='color: #00BB00;'>README.Rmd</span>
## ├── README.md
## ├── <span style='color: #0000BB; font-weight: bold;'>README_files</span>
## ├── <span style='color: #0000BB; font-weight: bold;'>css</span>
## ├── <span style='color: #0000BB; font-weight: bold;'>fig</span>
## ├── rstudioconf22-inheritance.Rproj
## ├── <span style='color: #00BB00;'>slides-reference.Rmd</span>
## ├── <span style='color: #00BB00;'>slides.Rmd</span>
## ├── slides.html
## ├── <span style='color: #0000BB; font-weight: bold;'>slides_files</span>
## └── xaringan-themer.css
</CODE></PRE>
