dotnet watch run

docker build -t dockernetexample .

docker run -d -p 8080:80 --name latest dockernetexample
