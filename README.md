# sciunit-photoz
Repository for notebooks and scripts related to the Rubin Photometric Redshifts Science Unit

## Committing notebooks

This repository uses `nbstripout` to automatically remove cell outputs from Jupyter notebooks before committing.
Users should install and run `nbstripout` following instructions [here](https://github.com/kynan/nbstripout).
If attempting to commit without running `nbstripout` the GitHub workflow will prevent the commit from being included in a pull request until the outputs are stripped.
