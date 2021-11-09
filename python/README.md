#### BUILD

```
docker build --tag my-python-app .

```

#### Tag image as my-python-app

```
docker run --name python-app -p 5000:5000 my-python-app

```

#### RUN

* O parâmetro **–name**  nomeia o container e o paramêtro **-p**  mapeia a porta 5000 do Host para a porta 5000 do container 
 doc

```
docker run --name python-app -p 5000:5000 my-python-app

```