Change Log
==========
- 1.0.6

  - Fixed an issue with catalogue generation due to refractive index info updating their file structure.
  
- 1.0.5

  - added support for simple effective medium
  - fixed a bug causing install script to crash if RII database was selected but
    not downloaded.

- 1.0.4

  - added centimeter as wavelength unit
  - added support for loading tabulated data defined through real part of
    refractive index plus absorption coefficient (in inverse centimeters)

- 1.0.3

  - fixed bug where rebuilding single catalogue modules failed.

- 1.0.2

  - fixed bug where installation script failed if no configuration file was present.

- 1.0.1

  - fixed incorrect paths for RefractiveIndexInfo module.

  - improved tests to include installation

  - fixed error caused by effective media with length 1 spectra.

  - register_alias now works properly with a slice of the database.

- 1.0.0

  - first full release.

  - added config option to supress YAML package warnings.

  - fixed incorrect name of the setup script in the documentation.

  - added angstrom as a valid unit for wavelength spectrums.

  - added support for loading .nk files.

  - .txt and .csv files can now have colons in their metadata.

  - updated PyYAML dependency to v5.4

- 0.1.0.beta5

  - order of elements no longer reversed when inverting spectrum

  - Bruggeman effective medium model should provide physical solutions for
    non-absorbing media.

- 0.1.0.beta4

  - automatic github integration with pypi database.

- 0.1.0.beta3

  - automatic github integration with test pypi database.

- 0.1.0.beta2

  - numerous typos fixed

  - enabled plotting using the matplotlib package

  - when taking the inverse of a spectrum, the order of the data is now reversed

  - added qgrid installation information to documentation

  - added rounding to 9 decimal places when converting to energy

  - added the Tauc Lorentz Model for permittivity

  - added the EffectiveMedium class for effective mediums of multiple materials

  - MaxwellGarnett and Bruggeman provide the respective effective media

  - updated the DrudeLorentz model definition to include oscillator strength

  - when converting spectrum_type and unit using inplace=True, the spectrum_type
    and unit will not be converted as well as the values
