# RSA of Liu & Gardner (2018, J Neurosci)
The aim of this datalad/git annex repo is to illustrate perhaps surprising properties of
representational similarity analysis (RSA).

## How this repo was created
Because I will forget next time I do this.

``` sh
mkdir contrast_orientation
cd !$
datalad create
git annex addurl --file BOLD_data_cinvor.zip https://osf.io/vpzgq/download
datalad run unzip BOLD_data_cinvor.zip -d ./ -x *.DS_Store* -x *__MACOSX*
git rm BOLD_data_cinvor.zip
```

## References
* [Original paper](https://doi.org/10.1523/JNEUROSCI.2453-17.2017)
* [OSF repository with data from authors](https://osf.io/9d3ex/)
* [datalad](https://datalad.org)
