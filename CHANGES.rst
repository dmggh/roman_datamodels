0.6.0 (unreleased)
==================

- Added ability to add attributes to datamodels [#33]

- Added support for Saturation reference files. [#37]

- Update Ramp Pedestal Array to 2D. Fixed reference model casting in test_models. [#38]

- Implemented support and tests for linearity reference model. Corrected dimension order in factories. Added primary array definition to MaskRefModel. [#39]

- Updated tests and makers for exposure and optical_element requirements in reference files. [#42]

- Changed exposure ``start_time``, ``mid_time``, and ``end_time`` to string to match RAD update. [#40]

- Implemented support, tests, and maker utility for Super Bias reference files. [#45]  

- Created maker utility and tests for wfi photom reference files. [#43]

- Added support, tests, and maker utility for Pixel Area reference files. [#44]
  
  
0.5.2 (2021-08-26)
==================

- Updated ENGINEERING value to F213 in optical_element. [#29]

- Workaround for setuptools_scm issues with recent versions of pip. [#31]

0.5.1 (2021-08-24)
==================

- Added tests for mask maker utility. [#25]

- Added Dark Current model maker and tests. [#26]

- Added Readnoise maker utility and tests. [#23]

- Added Gain maker utility and tests. [#24]

0.5.0 (2021-08-07)
==================

0.4.0 (2021-08-06)
==================

- Added support for ScienceRawModel. Removed basic from ref_common in testing/utils. [#20]

- Added support for dq_init step in cal_step. [#18]

0.3.0 (2021-07-23)
==================

- Added code for DQ support. Added ramp and mask helper functions. Removed refout and zeroframe. [#17]

0.2.0 (2021-06-28)
==================

- Added support for ramp, ramp_fit_output, wfi_img_photom models. [#15]

- Set rad requirement to 0.2.0 and update factories and tests.  Add ``DarkRefModel``,
  ``GainRefModel``, and ``MaskRefModel``. [#11]
