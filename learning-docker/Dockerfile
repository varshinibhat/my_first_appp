FROM python:3
RUN pip install Pillow
RUN  mkdir WORK_REPO
RUN  cd  WORK_REPO
WORKDIR  /WORK_REPO
ADD download.png .
ADD hello-world.py .
CMD ["python", "-u", "hello-world.py"]