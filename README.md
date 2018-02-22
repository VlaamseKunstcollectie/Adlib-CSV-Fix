# Adlib-CSV-Fix
Fix to convert Adlib XML export to CSV file

Use
catmandu convert XML --path '/adlibXML/recordList/record' to CSV --fields "object_name,physical_description,date_general,creator_name,creator_name_adlib,creator_dob,creator_dod,material_description,dimension_h_value,dimension_w_value,dimension_h_unit,title_nl,object_number,inscriptions,acquisition" --fix adlib-records-to-csv.fix < adlib_export.xml
