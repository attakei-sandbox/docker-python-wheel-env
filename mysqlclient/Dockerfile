FROM attakei/wheel-py36
MAINTAINER Kazuya Takei


# Install python 3.6
RUN yum install -y mysql-devel
RUN git clone https://github.com/PyMySQL/mysqlclient-python -b 1.3.12 project

WORKDIR /project
CMD ["python3.6", "setup.py", "bdist_wheel"]