FROM ageron/handson-ml2
USER root
COPY docker/requirements.txt /tmp/
RUN pip install -r /tmp/requirements.txt
RUN jupyter contrib nbextensions install

RUN jupyter nbextension enable splitcell/splitcell
RUN jupyter nbextension enable hinterland/hinterland
RUN jupyter nbextension enable code_prettify/autopep8
RUN jupyter nbextension enable snippets_menu/main
RUN jupyter nbextension enable toc2/main
RUN jupyter nbextension enable collapsible_headings/main

RUN jupyter nbextension enable --py --sys-prefix widgetsnbextension
RUN jupyter nbextension enable --py --sys-prefix qgrid
RUN jupyter nbextension enable --py widgetsnbextension
