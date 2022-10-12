# ror-data

This repository contains ROR data releases generated through the community curation process managed in [ror-community/ror-updates](https://github.com/ror-community/ror-updates).

- New releases are generated approximately quarterly.
- A detailed list of changes in each release can be found in [ror-community/ror-updates/milestones](https://github.com/ror-community/ror-updates/milestones).
- This repository is subject to change. ROR releases are stored in [Zenodo (ror-data community)](https://zenodo.org/communities/ror-data) for long-term preservation/access.
- To request additions/changes to ROR data, see [Requesting changes to ROR](https://github.com/ror-community/ror-updates#requesting-changes-to-ror). Please do not open issues in this repository.

## Release versioning

From Apr 2019 to Sep 2021, changes to ROR data happened in collaboration with [GRID](https://grid.ac/). After each GRID release, ROR assigned new IDs to each new organization in GRID and published an new ROR release that corresponded to the most recent GRID release. Releases were named with with a date, ex 2021-09-23-ror-data.zip.

GRID announced the sunset of its public data offering in [July 2022](https://ror.org/blog/2021-07-12-ror-grid-the-way-forward/) and published its final data release in Sept 2021. ROR published a corresponding data release (2021-09-23-ror-data.zip) in Sept 2021. Both releases contained the same set of organizations, with GRID and ROR IDs assigned to all.

Beginning with its Mar 2022 release, ROR is curated independently from GRID. Semantic versioning beginning with v1.0 has been added to reflect this departure from GRID, however, the data structure has not changed. From March 2022 onward, data releases are versioned as follows:

- **Minor versions (ex 1.1, 1.2, 1.3):** Contain changes to data, such as a new records and updates to existing records. No changes to the data model/structure.
- **Patch versions (ex 1.0.1):** Used infrequently to correct errors in a release. No changes to the data model/structure.
- **Major versions (ex 1.x, 2.x, 3.x):** Contains changes to data model/structure, as well as the data itself. Major versions will be released with significant advance notice.

## Support

For help using ROR data, visit the [ROR support site](https://ror.readme.io) or post in the [ROR Tech Support Google Group](https://groups.google.com/a/ror.org/g/ror-tech)
