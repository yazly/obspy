FROM fedora:21

MAINTAINER Lion Krischer

# Can fail on occasion.
RUN yum -y upgrade || true
RUN yum install -y gcc numpy scipy python-matplotlib python-sqlalchemy python-lxml python-mock python-basemap python-basemap-data python-tornado python-pip
RUN pip install flake8 suds-jurko future
