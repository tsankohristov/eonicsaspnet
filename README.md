# eonicsaspnet


docker build -t eonicsaspnet .
docker run -it --rm -p 5001:80 --name eonics eonicsaspnet

curl http://localhost:5001/api/values