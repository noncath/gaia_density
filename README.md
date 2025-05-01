# gaia_density python module
Calculates distance to the closest Gaia star for user-specified coordinates.

The module exports following methods:

- `mean(RA: float, DEC: float) -> float:` - returns mean distance (in arcsec) for RA:DEC coordinates (in degrees) basing on pre-calculated data
- `median(RA: float, DEC: float) -> float` - returns median distance basing on pre-calculated data
- `mean_approx(RA: float, DEC: float) -> float:` returns approximated mean distance basing on approximation formula
- `meidan_approx(RA: float, DEC: float) -> float:` returns approximated median distance basing on approximation formula

Also, the repository contains raw pre-calculated data in CSV and FITS formats:

- [stat_gaia_nndist_new.csv](https://github.com/noncath/gaia_density/raw/refs/heads/main/stat_gaia_nndist_new.csv)
- [Gaia_NN_statistics_768.fits](https://github.com/noncath/gaia_density/raw/refs/heads/main/Gaia_NN_statistics_768.fits)
