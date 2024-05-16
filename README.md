### Running the code
* *Optional* - Edit [data_paths.m](data_paths.m) so that `data_dir` variable points to the right location on your machine. This step is not necessary if the data and code directories are located in the same overarching project directory:

```
project_directory/
  DTS-MVCO/
    analysis/
    processing/
    data_paths.m
    master_dts_analysis.m
    master_dts_processing.m
    README.md
  DTS-MVCO-data/
    archive_Isle_mooring/
    DTS_MVCO_cal/
    DTS_MVCO_nc/
```

* *Optional* - Run [master_dts_processing.m](master_dts_processing.m) to generate processed and calibrated DTS data in NetCDF format.
* Run [master_dts_analysis.m](master_dts_analysis.m) to generate figures.

Code has been run using MATLAB R2015a (Mac) using versions of software specified above.
