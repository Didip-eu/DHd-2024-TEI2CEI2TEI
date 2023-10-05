# TEI2CEI2TEI
This repository is a placeholder that collects and refers to DiDip's current work-in-progress endeavors to validate XML data and create transformations, fuelled by data inference and profiling. Approximates refer to the following graphic:
![alt text](https://raw.githubusercontent.com/Didip-eu/TEI2CEI2TEI/main/workflow.svg)

Recent commits and changes to the data transformation are found in this [CEI2TEI fork](https://github.com/flamminger/CEI2TEI/tree/develop).
workflow.xsl ≈ existing transformation process
transform.xsl ≈ new transformation process
schema/tei_cei.xsd ≈ new schema

The previous schema is found [here](https://github.com/icaruseu/mom-ca/tree/888a9a1e92fc62fbd02efc2feceab23b7d885dc9/my/XRX/src/mom/app/cei/xsd).

Code relevant to large parts of this workflow is located [here](https://github.com/flamminger/2tei-validation); addtional validation in java [here](https://github.com/flamminger/2tei-rncValidation)

src/describe_xml.py ≈ inference process
src/validate_xml.py ≈ validation process
src/in_vs_out.py  ≈ evaluation process
src/xml_transform.py ≈ new transformation process helper
