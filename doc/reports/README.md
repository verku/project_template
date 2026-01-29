Folder to store Quarto report files and rendered outputs. 

`_extensions/nbis` - Folder with custom Quarto extensions 
for NBIS reports.
`quarto_report_template.qmd` - Quarto template file for 
standalone reports, e.g. for NBIS user-fee projects.
`references.bib` - Bibliography file in bibTex format for 
citations in Quarto standalone reports. 

Requires Quarto to be installed (https://quarto.org/). 

To render a standalone report in HTML or PDF format, run 
the following command: 

```
pixi run quarto render quarto_report_template.qmd
```

