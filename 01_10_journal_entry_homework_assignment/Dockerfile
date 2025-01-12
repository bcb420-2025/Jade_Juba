FROM risserlin/bcb420-base-image:winter2025

# install packages
RUN R -e "install.packages(c('BioManager'), repos = 'http://cran.us.r-project.org')"  && R -e "BiocManager::install(c('DESeq2', 'pheatmap', 'enrichplot'))"