# Flexdashboard poster

Women in Statistics and Data Science (2017) conference poster using rmarkdown.



Built with the help of [this great template](https://odeleongt.github.io/flexdashboard-poster/).




## Dependencies

This poster template dependes on the following R packages

- rmarkdown [@rmarkdown]
- flexdashboard [@flexdashboard]
- webshot [@webshot]

To use `scripts/generic-content` you will need a GNU/Linux system
and a working installation of `imagemagick`.



## Preparing your analysis environment

In order to use this poster template, you need to:

1. Clone [`julia-wrobel/WSDS_poster`](https://github.com/julia-wrobel/WSDS_poster)
from github
1. Install the required packages  
`install.packages("rmarkdown", "flexdashboard", "webshot")`
1. Install the PhantomJS library  
`webshot::install_phantomjs()`
1. Edit the template to fit your needs
1. Run `scripts/render-poster.R`
