FROM continuumio/anaconda3
EXPOSE 8888
RUN mkdir /opt/notebooks
RUN pip3 install xhtml2pdf
RUN pip3 install tensorflow
CMD jupyter notebook --notebook-dir=/opt/notebooks --ip='*' --port=8888 --no-browser --allow-root --NotebookApp.token='1111'