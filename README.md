# awesome-annotation-tools
Just another awesome list - of tools for creating training data

## About the list
This list started as a slack thread, but grew too big. This space is moving quickly, and I'm adding new tools as I become aware of them. However, this is not meant to be a comprehensive list - such a list would be too long and confusing.

I am working on adding better notes to this.

## Commercial options

- **prodi.gy**: From the makers of Spacy, a perpetual license annotation tool that is very customizable for anyone using python. Active learning/Model-in-the-loop comes out of the box. Needless to say, very good integration with Spacy.
- **hasty.ai**: Platform focused exclusively on images, for you and your team.
- **snorkel.ai**: A platform for making heuristic-based rules for a type of ensemble-based traningdata.
- **AWS Sagemaker Label jobs**: MTurk under the hood, a quick way to create labeling jobs with crowd or your own labeling workforce. $0.08 per object + worker cost. Model-in-the-loop option, and built-in templates for common annotation types.
- **Amazon Mechanical Turk**: Very flexible platform for doing any type of task.
- **surgehq.ai**: Workforce-as-a-service annotation platform - sales pitch includes "less garbage results than MTurk".
- **Superannotate**: Cloud application, focused on images. https://opencv.org/superannotate

## Open source:

- **CVAT**: Computer Vision Annotation Tool https://github.com/openvinotoolkit/cvat
- **LabelImg**: a graphical image annotation tool and label object bounding boxes in imageshttps://github.com/tzutalin/labelImg
- **BMW-Labeltool-Lite**: Labeling tool for images. https://github.com/BMW-InnovationLab/BMW-Labeltool-Lite
- **Visual Object Tagging Tool**: An electron app for building end to end Object Detection Models from Images and Videos https://github.com/microsoft/VoTT
- https://opencv.org/superannotate-desktop/
- **Rubrix**: python package focused on onnotation tabular data, works well with pandas, and good options for visual bulk-labeling. https://github.com/recognai/rubrix


## Comparison table

This is under construction, and I don't give a 100% guarantee for the correctness. Some tools face rapid development too, and features change.

| tool                  | Text classification  | image classification  | Image bounding box | image lasso | NER     | Entity resolution | Audio | Video | 
-------------------:    |----------------------|-----------------------|--------------------|-------------|---------|-------------------|-------|-------|
|Prodigy                |✅                    |✅                      |✅                  |✅           |✅        |✅                 |✅     |❓      |
|AWS Sagemaker          |✅                    |✅                      |✅                  |✅           |✅        |❌                 |❓     |✅      |
|Surge HQ               |✅                    |❌                      |❌                  |❌           |✅        |✅                 |❓     |❓      |
|hasty.ai               |❌                    |✅                      |✅                  |❌           |❌        |❌                 |❌     |❓      |
|snorkel.ai*            |✅                    |❓                      |❓                  |❓           |✅        |❓                 |❓     |❓      |
|Mechanical Turk        |✅                    |✅                      |✅                  |✅           |✅        |❌                 |❓     |✅      |
|Superannotate          |❌                    |✅                      |✅                  |✅           |❌        |❌                 |❌     |❓      |
|Rubrix                 |✅                    |❌                      |❌                  |❌           |❌        |❌                 |❌     |❌      |
|CVAT                   |❌                    |❌                      |✅                  |✅           |❌        |❌                 |❌     |✅      |
|LabelImg               |❌                    |✅                      |❓                  |❓           |❌        |❌                 |❌     |❓      |
|BMW-Labeltool-Lite     |❌                    |✅                      |✅                  |❌           |❌        |❌                 |❌     |❓      |
|VoTT                   |❌                    |✅                      |❓                  |❓           |❌        |❌                 |❓     |❓      |
|superannotate-desktop  |❌                    |✅                      |✅                  |✅           |❌        |❌                 |❌     |❓      |


