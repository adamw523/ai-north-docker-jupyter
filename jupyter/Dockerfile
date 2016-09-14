FROM jupyter/datascience-notebook

# Install TensorFlow
RUN pip install --upgrade https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-0.10.0rc0-cp35-cp35m-linux_x86_64.whl --ignore-installed

USER root
RUN apt-get update
RUN apt-get -y install mysql-server mysql-client

RUN conda install pymysql

