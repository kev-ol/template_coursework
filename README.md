## Session Outline 

### Template Coursework Repository

1. Create a new Github repository called `template_coursework`, [remote first](https://happygitwithr.com/new-github-first). 
2. Download and copy into that directory the contents of `msc-statistics-coursework-template/`
3. Create a new file *.gitignore* and includle `MSc_Statistics_coursework_quarto.pdf` and `MSc_Statistics_coursework_quarto.html`. 
4. Save, add and commit your changes
5. Push to your remote repository. 

### Checking that the report renders 

1. Look through `MSc_Statistics_coursework_quarto.html` and `MSc_Statistics_coursework_quarto.pdf`
2. Open `MSc_Statistics_coursework_quarto.qmd` in RStudio.
3. Add your CID as the author and use "Render" to update the HTML version.
4. Use the drop-down menu by "Render" to update the PDF version. 
	- Note: You may need to install [tinytex](https://quarto.org/docs/output-formats/pdf-engine.html) for this step.


### Refining your workflow 

Now it's over to you! Using the provided template and the examples in `refining-your-workflows.qmd` as a guide, in this session you should either: 

1) Reproduce the simulations and analyses of the palmenr penguins dataset in the coursework template.

2) Adapt the the simulations and analyses of the palmenr penguins dataset to instead use the `ChickWeight` dataset that comes with R.

By the end of today you should have a coursework template populated where you have: 

- Your own meta-data in the YAML header
- Created at least 1 Section
- Created at least 1 Table
- Created at least 1 Figure
- Created at least 1 Figure with Subfigures
- Labelled and referenced in the main text all of the above.
- Cited at least one external source that was not mentioned in the template or guide
- Deliberately hidden / displayed at least one code block 
- Have a populated template coursework that renders to both HTML and PDF format. 

As you go, I encourage you to make regular commits and occasional pushes to track your work.

