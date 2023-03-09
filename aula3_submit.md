# BD: Guião 3


## ​Problema 3.1
 
### *a)*

```
Cliente(NIF, nome, endereço, num_carta)
Aluguer(número, duracao, data)
Balcao(número, nome, endereço)
Veiculo(matrícula, ano, marca)
Tipo_veiculo(codigo, arcondicionado, designacao)
Similaridade()
Ligeiro(codigo, combustivel, portas, numlugares)
Pesado(código, peso, passageiros)
```


### *b)* 

```
Cliente:
- Chaves candidatas: NIF, num_carta
- Chave primária: NIF
- Chaves estrangeiras: ---

Aluguer:
- Chaves candidatas: número
- Chave primária: número
- Chave estrangeira: NIF(Cliente), matrícula(Veiculo), numero(Balcão)

Balcão:
- Chaves candidatas: numero
- Chave primária: numero
- Chaves estrangeiras: ---

Veículo:
- Chaves candidatas: matricula
- Chave primária: matricula
- Chave estrangeira: codigo(tipo_veiculo)

Tipo_veiculo:
- Chaves candidatas: codigo
- Chave primária: codigo
- Chaves estrangeiras: ---

Similaridade:
- Chaves candidatas: codigo_1, codigo_2
- Chaves pirmárias: codigo_1, codigo_2
- Chaves estrangeiras: codigo_1, codigo_2

Ligeiro:
- Chaves candidatas: codigo
- Chave primária: codigo
- Chaves estrangeiras: codigo

Pesado:
- Chaves candidatas: codigo
- Chave primária: codigo
- Chaves estrangeiras: codigo
```


### *c)* 

![ex_3_1c!](ex_3_1c.svg "AnImage")


## ​Problema 3.2

### *a)*

```
... Write here your answer ...
```


### *b)* 

```
... Write here your answer ...
```


### *c)* 

![ex_3_2c!](ex_3_2c.jpg "AnImage")


## ​Problema 3.3


### *a)* 2.1

![ex_3_3_a!](ex_3_3a.jpg "AnImage")

### *b)* 2.2

![ex_3_3_b!](ex_3_3b.jpg "AnImage")

### *c)* 2.3

![ex_3_3_c!](ex_3_3c.jpg "AnImage")

### *d)* 2.4

![ex_3_3_d!](ex_3_3d.jpg "AnImage")