# Nipy Demonstrations

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/effigies/nipy-demos/master)

> Demonstrations of nibabel and nipype

Presented by [Chris Markiewicz](https://github.com/effigies) at The University of Washington eScience Institute's [Neurohackweek 2019](https://neurohackweek.github.io/nhw2019/) course.

At present, it makes strong assumptions about the presence of data. Please install it with:

```Shell
datalad install -r ///labs/poldrack/ds003_fmriprep /data/bids/ds003_fmriprep
datalad get -r /data/bids/ds003_fmriprep/sub-01/func/*{space-MNI*2009*_desc-preproc_bold.nii.gz,.dtseries.nii,space-fsaverage5*.func.gii} \
               /data/bids/ds003_fmriprep/sourcedata/sub-01/*/*.nii.gz
```

This repository is derived from [Tal Yarkoni](https://github.com/tyarkoni)'s
[Python Tips and Tricks](https://github.com/neurohackweek/python-tips-and-tricks) repository, with
Binder additions by [Kirstie Whitaker](https://github.com/KirstieJane).
