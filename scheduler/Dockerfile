FROM python
WORKDIR /home/myapp
COPY . /home/myapp/scheduler/
RUN pip install -r /home/myapp/scheduler/requirements.txt
CMD ["python", "/home/myapp/scheduler/scheduler.py"]