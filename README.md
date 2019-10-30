# cufctl.github.io

This repository contains the code for the CUFCTL website, based on the [uwsampa template](https://github.com/uwsampa/research-group-web). Refer to their README for more information about the template itself.

## Deployment

Since the site is deployed to Github Pages, you don't need to install and run Jekyll on your local machine unless you want to deploy the website locally for testing. However, since the `_includes/pubs.html` is auto-generated by bibble, you still need to run `make` and push the updated `_includes/pubs.html`, every time the publications list is updated. For this all you need to install is bibble (`pip install bibble`).

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
