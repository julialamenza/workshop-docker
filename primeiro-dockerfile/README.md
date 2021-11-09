#### BUILD

```
docker build -t meu-dockerfile .

```
#### RUN

* O parâmetro **–name**  nomeia o container e o paramêtro **-p**  mapeia a porta 80 do Host para a porta 80 do container 

```
docker run --name meu-dockerfile -p 80:80 meu-dockerfile

```