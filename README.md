# sala-de-reuniao-dio
 
- Projeto para gerenciamento de salas de reunião com API Rest, Spring Boot e Angular

- Ao acessar a API ela redireciona automaticamente para para `http://localhost:4200/rooms` onde é listado todas as reservas ja realizadas.
![room1](https://user-images.githubusercontent.com/30246572/134071458-c26b78da-f03b-4270-9c3b-1ce99d31be7c.png)

- Ao acessar `http://localhost:4200/add` traz a possibilidade de adicionar uma nova reserva.

![room2](https://user-images.githubusercontent.com/30246572/134071500-fe3e4de6-5b59-493d-965c-4e2fda9acb08.png)


- Ao acessar `http://localhost:4200/update/:id` ela exibe um formulario onde é possivel atualizar a reserva, onde id é a indentificaçao da reserva obtida automaticamente pela api
![room3](https://user-images.githubusercontent.com/30246572/134071580-233fb625-ead2-4a9e-a866-808f7ce34089.png)


- Ao acessar `http://localhost:4200/details/:id` ela exibe uma tela com todas as informações da reserva especifica, onde id é a indentificaçao da reserva obtida automaticamente pela api!

![room4](https://user-images.githubusercontent.com/30246572/134071706-e1b283a1-6dfe-490f-821b-bcf3f766b959.png)


- A API faz integração com o BackEnd pelo endereço `http://localhost:8082/api/v1/rooms`

# Tecnologias utilizadas
- Angular 12
- TypeScript
- JavaScript
- HTML5
- CSS3
- Java 11
- Maven
- Spring Boot
- DB H2

# Como compilar e executar o programa

- Executar `ng serve` em um servidor de desenvolvimento na pasta client-room-front. Navegar para `http://localhost:4200/rooms`. 
- Importar o projeto maven para a IDE e executar a classe SaladereuniaoApplication.java.
