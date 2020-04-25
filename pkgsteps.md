# Package Creation Steps
1. Navigate to location where you want to create the package directory
2. In RStudio click `File > New Project > New Directory > R Package`
3. Enter package name and click `Create a git repository`
4. All temp files and folders will be created
5. Load packages `devtools` and `roxygen2`
6. Write R scripts in `roxygen2` format in the `/R` folder
7. Run `devtools::document()` - this will generade `.Rm` in the `/man` documentation folder
8. Run `usethis::use_gpl3_license()` (or another license) to generate `LICENSE.md` file
9. Run `devtools::build_vignettes()` to create `vignettes` folder with an example
10. Populate `DESCRIPTION` file with appropriate information
11. Click the `Build > Install and Restart` button
12. Click the `Build > Check` button (make sure there are no errors or warning)
13. Complete vignette `.Rmd` file
14. Configure GitHub (terminal)
    * Create github repo (no initialization including README)
    * Navigate to package folder
    * `git status` to check all the files that have not been added and commited
    * `git remote add origin git@github.com:[REPO NAME]` to add a remote
    * 
