FROM continuumio/anaconda3
EXPOSE 8888
RUN mkdir /opt/notebooks
RUN pip3 install --upgrade pip
RUN pip3 install psycopg2-binary
RUN pip3 install cx_Oracle
RUN pip3 install plotly
RUN pip3 install requests-toolbelt
RUN pip3 install Pillow
# RUN pip3 install tensorflow
RUN pip3 install grpcio
RUN pip3 install grpcio-tools
RUN pip3 install tinkoff-investments
# RUN pip3 install xhtml2pdf
CMD jupyter notebook --notebook-dir=/opt/notebooks --ip='*' --port=8888 --no-browser --allow-root --NotebookApp.token='1111'