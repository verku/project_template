Folder to store Quarto report files and rendered outputs. 

`_extensions/nbis` - Folder with custom Quarto extensions 
for NBIS reports.
`quarto_report_template.qmd` - Quarto template file for 
standalone reports, e.g. for NBIS user-fee projects.
`quarto_to_confluence_template.qmd` - Quarto template file 
for reports to be published on the SciLifeLab Confluence, 
as typically done for NBIS peer-review/WABI projects.
`references.bib` - Bibliography file in bibTex format for 
citations in Quarto standalone reports. 

Requires Quarto to be installed (https://quarto.org/). 

To render a standalone report in HTML or PDF format, run 
the following command: 

```
pixi run quarto render quarto_report_template.qmd
```

To publish a report on Confluence, run:

```
pixi run quarto publish quarto_to_confluence_template.qmd
```

This command will ask for additional information such as 
the email address of the Confluence user and the parent 
page URL. 