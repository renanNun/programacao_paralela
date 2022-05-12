# Programação Paralela

- Imagem que está sendo utilizada [Docker MPICH](https://hub.docker.com/r/nlknguyen/alpine-mpich)

## Instalando a imagem do mpich

- Utilizando outros terminais

```
$ docker run --rm -it -v $(pwd):/project programacao_paralela
```

- Utilizando o powershell

```
$ docker run --rm -it -v ${pwd}:/project my-custom-image
```

## Compilando e Executando o Projeto

```
mpicc <nome_do_executavel> <nome_do_executavel>.c
```

```
mpirun -n <numero_nucleos> <nome_do_executavel>
```
