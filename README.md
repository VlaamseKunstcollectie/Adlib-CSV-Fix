# Adlib-CSV-Fix
Fix to convert Adlib XML export to CSV file

## Synopsis
This fix is used to convert an Adlib XML export to a CSV file using [Catmandu](http://librecat.org).

Command line client:

    catmandu convert XML --path '/adlibXML/recordList/record' to CSV --fields 'object_name,physical_description,date_general,creator_name,creator_name_adlib,creator_dob,creator_dod,material_description,dimension_h_value,dimension_w_value,dimension_h_unit,title_nl,object_number,inscriptions,acquisition' --fix adlib-records-to-csv.fix < input.xml > output.csv
