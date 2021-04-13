pipenv shell
pipenv install [pkg-name]
pipenv install -r requirements.txt
pipenv lock -r > requirements.txt


docker build -t sushantsahu/hello-world:latest .
docker run sushantsahu/hello-world:latest