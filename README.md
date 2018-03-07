# eonicsaspnet

## Build
```
docker build -t eonicsaspnet .
```

## Run
```
docker run -it --rm -p 5001:80 --name eonics eonicsaspnet
```

## Test
```
curl http://localhost:5001/api/values
```
