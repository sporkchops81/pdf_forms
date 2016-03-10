*Instructions for using PyPDFtk

import pypdftk
create a dict with the data, using {'field_name': 'value'}
generate the PDF with pypdftk.fill_form('path to form', form_dict, 'output path')

if you need to pull field names, use the command line to run "pdftk form_name.pdf dump_data_fields > name_of_output.txt"


