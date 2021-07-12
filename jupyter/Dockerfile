FROM python:3.7-slim

RUN mkdir /src/

WORKDIR /src/

RUN pip3 install jupyter jupyterlab

EXPOSE 8888

CMD ["jupyter-lab", "--ip=0.0.0.0", "--port=8888", "--allow-root", "--no-browser"]