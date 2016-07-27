#########################################################################

    Galaxy Toolkit
    Management, import, export app for ArchestrA supervision system
    -----------------------------------------------------------------
    
    Author            : Romain Vinders
    Prog. languages   : C#, GRAccess, SQL Server, XML, JSON

#########################################################################

Galaxy Toolkit is a C# application, using GRAccess and SQL to communicate with ArchestrA supervision system. 
It allows the user to easily modify/import/export lots of data, and to create documentation files 
about the current state of the ArchestrA project.

Glossary:
galaxy = ArchestrA project ;
template = object structure definition ;
instance = object based on a template.

- tab-control with multi-selection trees (hierarchical templates tree, tree with templates sorted by categories)
- advanced list view with icons, sortable columns, filter panel and filtering system
- display instances based on selected template(s) (and, optionally, their descendants too)
- display attributes of templates or instances, select/remove attributes
- snapshot system: load/save state of both templates trees
- search window with options, advanced list of results (sortable columns, filters), search history
- navigate from search result(s) to template trees and/or instance list
- responsive design, flat design, adjustable and resizable layout
- advanced log system (*.csv)

- export using selection list or export by category
- import/export ArchestrA data (as editable *.xlsx documents), choose attributes
- export data (as *.csv file) that can be imported in ArchestrA IDE
- export documentation about "galaxy" templates (*.docx with advanced styles, header, sections, ...), 
  choose document sections, titles, ..., load/save sections set (*.json)
- export documentation about "galaxy" measures/field attributes (*.xlsx with image, styles and header)
- export documentation about "galaxy" alarms (*.xlsx with image, styles and header)
