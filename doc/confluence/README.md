Folder for Quarto documents to be published to Confluence

`quarto_to_confluence_template.qmd` - Quarto template file 
for reports to be published on the SciLifeLab Confluence, 
as typically done for NBIS peer-review/WABI projects.

To preview the document locally, run:

```
pixi run quarto preview quarto_to_confluence_template.qmd
```

To publish the document on Confluence, run:

```
pixi run quarto publish quarto_to_confluence_template.qmd
```

This will prompt for additional information such as 
the Confluence credentials and the parent page URL, 
and upload the document. 