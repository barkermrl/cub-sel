# CUB-Sel

We release `CUB-Sel`, a relabeling of a portion of the [`CUB`](https://www.vision.caltech.edu/datasets/cub_200_2011/) bird classification image test set with individual soft labels per concept group (e.g., over wing color, beak shape, etc) as part of our upcoming [HCOMP paper](https://arxiv.org/abs/2306.08424). Each participant selected the concepts they thought were relveant for predicting the bird species from each image, following the [original group listing](https://worksheets.codalab.org/rest/bundles/0xd013a7ba2e88481bbc07e787f73109f5/contents/blob/attributes/attributes.txt).

The data for 900 selections (30 participants) is provided in the file `attribute_df_humans.csv`. Each row represents one image shown to one participant, with the values given in the first two columns. The remaining columns are the concepts, and contain eirther true/false depending on whether the subject selected the concept for that image.

## Citing

If you use our data, please consider the following bibtex entry: 

```
@article{barker2023selective,
  title={Selective Concept Models: Permitting Stakeholder Customisation at Test-Time},
  author={Barker, Matthew and Collins, Katherine M and Dvijotham, Krishnamurthy and Weller, Adrian and Bhatt, Umang},
  journal={arXiv preprint arXiv:2306.08424},
  year={2023}
}
```

## Questions?

If you have any questions about `CUB-Sel` use, elicitation, and/or creation, please do not hesitate to add a GitHub Issue and/or reach out to Katie Collins (`kmc61@cam.ac.uk`) and Matthew Barker (`mrlb3@cam.ac.uk`).
