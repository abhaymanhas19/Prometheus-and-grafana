## Documentation

Documentation is available on https://prometheus.github.io/client_python

## python package

This package can be found on [PyPI](https://pypi.python.org/pypi/prometheus_client)

## python library for prometheus

If you require more custom metrics or are working in a non-Django environment, prometheus-client provides the necessary flexibility and control.

pip install prometheus-client

## for django 

For most Django applications, django-prometheus is the preferred choice due to its ease of use and comprehensive automatic instrumentation

pip install django-prometheus


## create a prometheus.yml file

Add  required configuration to [prometheus.yml] file

## Note
To monitor CPU and memory usage with Prometheus, you typically use the Node Exporter. The Node Exporter is a Prometheus exporter for hardware and OS metrics exposed by *nix kernels. 


## Add prometheus docker image in docker compose file 

Add docker image configuration in [docker_compose_prometheus.yml] file

## Add grafana image 

Add docker image configuration in [docker_compose_grafana.yml] file