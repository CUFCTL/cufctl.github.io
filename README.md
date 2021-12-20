# cufctl.github.io

This repository contains the code for the CUFCTL website, based on the [uwsampa template](https://github.com/uwsampa/research-group-web). Refer to their README for more information about the template itself.

## Deployment

Since the site is deployed to Github Pages, you don't have to install `jekyll` or build the website unless you want to test your changes locally. The only thing you actually have to build is the publications list whenever it is changed. For this you only need to install is bibble:
```bash
conda env create -n bibble python=2.7
conda activate bibble
pip install bibble
```

## Bibliography

When updating the bibliography, each BibTeX item must have at least the following fields:
```
% conference paper
@inproceedings{proceedings,
  title={title},
  author={authors},
  booktitle={booktitle},
  year={year}
}

% journal paper
@article{article,
  title={title},
  author={authors},
  journal={journal},
  year={year}
}
```

You can get the BibTeX citation easily from Google Scholar, just search for your paper, click on the quote icon, then click the "BibTeX" link.
