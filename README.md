# TEI2CEI2TEI
This repository is a placeholder that collects and refers to DiDip's current work-in-progress endeavors to validate XML data and create transformations, fuelled by data inference and profiling. Approximates of inputs/outputs for this workflow refer to the parallelograms in the following graphic:

![workflow_graphic](https://raw.githubusercontent.com/Didip-eu/TEI2CEI2TEI/main/workflow-white-v2.svg)

| Description                       | Approximate       | Provenance |
|-----------------------------------|---------------------------------|-----------------|
| `workflow.xsl`                    | existing transformation process | [CEI2TEI fork](https://github.com/flamminger/CEI2TEI/tree/develop)      |
| `transform.xsl`                   | new transformation process      | [CEI2TEI fork](https://github.com/flamminger/CEI2TEI/tree/develop)       |
| `schema/tei_cei.xsd`              | new schema                      | [CEI2TEI fork](https://github.com/flamminger/CEI2TEI/tree/develop)        |
| `cei.xsd`                         | existing schema                 | [mom-ca](https://github.com/icaruseu/mom-ca/tree/888a9a1e92fc62fbd02efc2feceab23b7d885dc9/my/XRX/src/mom/app/cei/xsd) |
| `src/describe_xml.py`             | inference process               | [2tei-validation](https://github.com/flamminger/2tei-validation)      |
| `src/validate_xml.py`             | validation process              | [2tei-validation](https://github.com/flamminger/2tei-validation)    |
| `src/in_vs_out.py`                | evaluation process              | [2tei-validation](https://github.com/flamminger/2tei-validation)     |
| `src/xml_transform.py`            | new transformation process helper| [2tei-validation](https://github.com/flamminger/2tei-validation)     |


Validation in Java is provided [here](https://github.com/flamminger/2tei-rncValidation).
