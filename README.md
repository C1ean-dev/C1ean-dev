## Documentação 
- [Objetivos](#Objetivos)
- [Testes](#Testes)
- [EndPoints](#EndPoints)
- [Codigo](#EndPoints)

## Objetivos
Criar um sistema para um estacionamento, nesta parte foi criada a API backend com as funcionalidades de CRUD e validaçao para o banco de dados.

Foi utilizado Java 17, com os frameworks SpringBoot e lombok para a criaçao da API 

## EndPoints
- [GET]  http://localhost:8080/help
- [GET]  http://localhost:8080/parking-spot/get
- [POST] http://localhost:8080/parking-spot/save
- [GET]  http://localhost:8080/parking-spot/get/{id}
- [DEL]  http://localhost:8080/parking-spot/delete/{id}
- [PUT]  http://localhost:8080/parking-spot/update/{id}

## Testes

- [X]	foi criado o inicio dos testes e sera posteriormente atualizado para melhor funcionamento.

## Codigo
O que vale resaltar é que o lombock nao foi utilizado como deveria,
praticamente nao interferindo no sistema futuramente pretendo atualizar utilizando melhor as suas funçoes 
parkingSpotDto é o unico local aonde foi utilizado:
```bash
import lombok.Data;
@Data
public class ParkingSpotDto {...}
```


##
Esse projeto pode ser utilizado e manipulado por todos, espero que gostem, qualquer melhoria sera analisada e implementada, nao hesite em fazer um pool request 