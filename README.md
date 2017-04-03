Workflows for an in-depth analysis of protein inference algorithms
=========

This repository contains the workflow used for the in-depth comparison of
protein inference algorithms, published in
http://dx.doi.org/10.1016/j.jprot.2016.08.002.

- `inference_comparison_workflow_KNIME3.3.knwf` -> updated workflow, which runs
in KNIME 3.3 with the stable PIA and OpenMS nodes (the other inference
algorithms need to be installed separately, see
[KNIME-OMICS/KNIME-ProteinProphet](https://github.com/KNIME-OMICS/KNIME-ProteinProphet),
[KNIME-OMICS/ProteinLP](https://github.com/KNIME-OMICS/ProteinLP) and
[KNIME-OMICS/MSBayesPro](https://github.com/KNIME-OMICS/MSBayesPro))
- `inference_comparison_workflow.zip` -> the original workflow for the
comparison of inference algorithms (this does unfortunately not run under KNIME
3.3 and above)
- `workflow_overview.png` -> an overview screenshot of the workflow
