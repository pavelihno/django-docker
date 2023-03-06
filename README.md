docker build . -t django


docker run -d -p 8000:8000 --name django_container django