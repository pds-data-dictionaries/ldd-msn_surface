# Surface Mission Information Local Data Dictionary (LDD)

The Surface Mission Dictionary contains classes, attributes, and rules for specifying metadata elements which are specific to the data products of surface missions but are common among multiple such missions.

Steward: [IMG Node](https://pds-imaging.jpl.nasa.gov/)

## Current Source

Only one LDD source version is kept such that it can be managed by github.

- [1.D.0.0_1.2.0.0](src)

## Versions

A Local Data Dictionary (LDD) is built for selected versions of the [PDS4 Information Model](https://pds.nasa.gov/pds4/doc/im/).
The build process insures compatiblity of the LDD with the core information model.

## Builds

This LDD has been built for the following versions of the PDS4 information models.

- [1.D.0.0_1.2.0.0](build/1.D.0.0_1.2.0.0)
- [1.D.0.0_1.1.1.0](build/1.D.0.0_1.1.1.0)
- older versions available as tagged releases

## Tagged Releases

This LDD has been tagged for release for the following versions of the PDS4 information model:

- [PDS4 IM v1.D.0.0  (MSN SURFACE LDD v1.2.0.0)](https://github.com/nasa-pds-data-dictionaries/ldd-msn/releases/tag/v1.2.0.0)
- [PDS4 IM v1.D.0.0  (MSN SURFACE LDD v1.1.1.0)](https://github.com/nasa-pds-data-dictionaries/ldd-msn/releases/tag/v1.1.1.0)
- [PDS4 IM v1.11.0.0 (MSN_SURFACE LDD v1.1.0.0)](https://github.com/nasa-pds-data-dictionaries/ldd-msn/releases/tag/v1.1.0.0)
- [PDS4 IM v1.10.1.0 (MSN_SURFACE LDD v1.0.0.0)](https://github.com/nasa-pds-data-dictionaries/ldd-msn/releases/tag/v1.0.0.0)

## Notes

Each build is generated using the [lddtool](https://pds.nasa.gov/tools/about/ldd/) specific to a version of the [PDS4 Information Model](https://pds.nasa.gov/datastandards/documents/im/). The build command used is:

```
lddtool -lpsnJ ldd-file.xml
```



# Contribute

Have a bug or feature request? Create one in the [PDS4 Issue Repo](https://github.com/pds-data-dictionaries/PDS4-LDD-Issue-Repo/issues/new/choose).


# Support

See the [PDS Data Dictionaries Support page](https://pds-data-dictionaries.github.io/support/) for more Support information.

