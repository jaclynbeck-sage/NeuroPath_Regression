FROM rocker/tidyverse

RUN apt-get update -y && apt-get upgrade -y
RUN apt-get install -y ssh nano less curl python3 python3-pip python3-venv python3-virtualenv
RUN apt-get install -y libpng-dev libglpk-dev libxt-dev liblzma-dev libbz2-dev

USER rstudio

RUN R -e "install.packages('synapser', repos = c('http://ran.synapse.org', 'http://cran.fhcrc.org'))"
RUN R -e "install.packages(c('plyr', 'doParallel', 'Hmisc', 'reshape2'))"
RUN R -e "devtools::install_github('brian-bot/githubr')"
RUN R -e "BiocManager::install('biomaRt')"

RUN cd /home/rstudio && git clone https://github.com/jaclynbeck-sage/NeuroPath_Regression.git

USER root
