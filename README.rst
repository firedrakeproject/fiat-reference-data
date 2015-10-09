-------------------
FIAT reference data
-------------------

This repository contains data used by the regression tests for the
FInite element Automatic Tabulator (FIAT). The reference data are stored in a
separate repository to minimize the size of the main FIAT repository.

This repository is intended to be checked out inside the fiat repository as:

    <fiatdir>/test/regression/fiat-reference-data/

while the fiat repository contains the file:

    <fiatdir>/test/regression/fiat-reference-data-id

which should contain a git commit id from the fiat-reference-data repository.
This commit id acts as a link from any fiat commit to any fiat-reference-data commit,
showing which regression data version should be used for which fiat repository version.

Downloading and uploading data from/to this repository is automatically
handled by the scripts:

    <fiatdir>/tests/regression/scripts/download
    <fiatdir>/tests/regression/scripts/upload

which are documented in <fiatdir>/tests/regression/README.rst.

