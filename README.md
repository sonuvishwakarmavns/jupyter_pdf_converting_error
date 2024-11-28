# jupyter_pdf_converting_error
Solution of pdf converting in jupyter notebook.

# Solution of pdf converting in jupyter notebook.


# steps:
- step 1) Install miktex 
    - here is the link : https://miktex.org/download
    - install simply next -next 
    - package install select - yes

- step 2) Install pandoc
    - here is the link : https://github.com/jgm/pandoc/releases/tag/3.5
    - for windows user install
        -  pandoc-3.5-windows-x86_64.msi

    - step 3) Copy path
        - go to path like:
         ```cmd
            C:\
            └── Program Files
                └── MiKTeX
                   └── miktex
                        └── bin
                            └── x64

    
    
    - `C:\Program Files\MiKTeX\miktex\bin\x64`
    - copy the path

- step 3) setup environment variable

    - search for environment variable
    -go to system variable under path section 
    - double tap on that
    - select new and paste the path you copied :
        - `C:\Program Files\MiKTeX\miktex\bin\x64`

# note
now close and re - open your jupyter notebook and try to export the code into pdf it will be converted into pdf without any error.
