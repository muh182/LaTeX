# Install New Packages

* When I started working with `Tex Live` in Windows, I have realized how difficult is to get additional information about the process of adding a new package to the `Tex Live` in Windows. I use `TeXStudio` for the user interface. 

* `TeX Live Manager 2015` manages the installed packages for `TeX Live`. When you use the `tlmgr` tab and `Load` packages, there are pre-defined packages. If one needs to install any new styles such as `lineno.sty`, `titlesec.sty`, `paralist.sty`, the best way to add these packages are to download the packages from the official `CRAN` page and put them in the `C:\texlive\texmf-local\tex\latex\local` folder. Then, you just need to run `mktexlsr.exe` in the `C:\texlive\2014\bin\win32` folder. Running `mktexlsr.exe` make sure that the package is installed and ready to use in `TeX Studio`

