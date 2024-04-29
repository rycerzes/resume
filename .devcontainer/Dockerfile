FROM qmcgaw/latexdevcontainer

# Update tlmgr and install required LaTeX packages
RUN tlmgr update --self && \
    tlmgr install preprint titlesec marvosym enumitem hyperref fancyhdr babel tabularx geometry

RUN chsh -s /bin/bash

SHELL ["/bin/bash", "-c"]