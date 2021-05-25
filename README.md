# awesome-annotation-tools
Just another awesome list - of tools for creating training data

## About the list
This list started as a slack thread, but grew too big. This space is moving quickly, and I'm adding new tools as I become aware of them. However, this is not meant to be a comprehensive list - such a list would be too long and confusing.

I am working on adding better notes to this.

## Commercial options

- prodi.gy
  - From the makers of Spacy, a perpetual license annotation tool that is very customizable for anyone using python. Active learning/Model-in-the-loop comes out of the box. Needless to say, very good integration with Spacy.
- hasty.ai
- snorkel.ai
  - Platform for making heuristic-based rules for a type of ensemble-based traningdata.
- AWS Sagemaker Label jobs
  - MTurk under the hood, a quick way to create labeling jobs with crowd or your own labeling workforce. $0.08 per object + worker cost. Model-in-the-loop option, and built-in templates for common annotation types.
- Amazon Mechanical Turk
  - Very flexible platform for doing any type of task.
- https://www.surgehq.ai/
  - Workforce-as-a-service annotation platform - sales pitch includes "less garbage results than MTurk".
- https://opencv.org/superannotate
  - Cloud application, focused on images.

## Open source:

- https://github.com/openvinotoolkit/cvat
- https://github.com/tzutalin/labelImg
- https://github.com/BMW-InnovationLab/BMW-Labeltool-Lite
- https://github.com/microsoft/VoTT
- https://opencv.org/superannotate-desktop/
- https://github.com/recognai/rubrix
  - python package focused on onnotation tabular data, works well with pandas, and good options for visual bulk-labeling.


||tool          ||Text classification ||image classification  ||Image bounding box  ||image lasso ||NER ||Entity linking  ||Audio ||Video ||
--------------------------------------------------------------------------------------------------------------------------------------
|Prodigy        |YES                   |Yes                   |Yes                  |Yes          |YES  |YES              |YES    |?      |
|AWS Sagemaker  |Yes                   |Yes                   |Yes                  |Yes          |Yes  |NO               |??     |Yes    |
|Surge HQ       |Yes                   |Yes?                  |Yes?                 |Yes?         |Yes  |NO               |??     |?      |
