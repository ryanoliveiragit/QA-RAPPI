
## CENÁRIOS DE TESTES: LOGIN
```bash
BDD — Behavior Driven Development (Desenvolvimento Guiado por Comportamento).
```
- **DADO QUE** O USUÁRIO ESTÁ DESLOGADO
- **E** A TELA DE LOGIN ESTÁ EM VISTA
- **QUANDO** O USUÁRIO EXAMINAR A TELA
- **ENTÃO** O SEGUINTE SERÁ EXIBIDO:

```bash
BOTÃO PARA SELEÇÃO DE PAÍS
BOTÃO PARA LOGIN ATRAVÉS DO SISTEMA OPERACIONAL
BOTÃO PARA LOGIN ATRAVÉS DO NÚMERO DE TELEFONE
BOTÃO PARA LOGIN ATRAVÉS DO FACEBOOK
BOTÃO PARA LOGIN ATRAVÉS DE OUTROS MÉTODOS
```
-----------------------------------------------------------------
- **DADO QUE** O USUÁRIO ESTÁ DESLOGADO
- **QUANDO** O USUÁRIO ABRIR O APLICATIVO
- **E**SELECIONAR “CONTINUAR COM NÚMERO DE TELEFONE”
- **ENTÃO** O USUÁRIO É REDIRECIONADO PARA A TELA DE
LOGIN POR NÚMERO DE CELULAR
-----------------------------------------------------------------
 - **DADO** QUE O USUÁRIO ESTÁ NA TELA DE LOGIN POR
NÚMERO DE CELULAR
- **QUANDO** O USUÁRIO INSERIR OS PRIMEIROS QUATRO
DÍGITOS DO NÚMERO
- **ENTÃO** OS BOTÕES DE RECEBER CÓDIGO SÃO EXIBIDOS
-----------------------------------------------------------------
 - **DADO** QUE A TELA DE LOGIN POR NÚMERO DE CELULAR
ESTÁ EM VISTA
- **E** O CAMPO DO NÚMERO CELULAR ESTÁ PREENCHIDO
COM UM NÚMERO VÁLIDO
- **QUANDO** O USUÁRIO SELECIONAR O BOTÃO “RECEBER
CÓDIGO POR SMS”
- **ENTÃO** O USUÁRIO É REDIRECIONADO PARA A TELA DE
VALIDAÇÃO DE CÓDIGO
-**E** UMA NOTIFICAÇÃO É EXIBIDA INFORMANDO QUE O
CÓDIGO FOI ENVIADO
- **E** O USUÁRIO RECEBE O CÓDIGO POR SMS, NO NÚMERO
INFORMADO 
-----------------------------------------------------------------
## Video
![Screenshot](https://cdn.discordapp.com/attachments/993982266273452053/995828507454226563/8mb.video-Tjy-65JtJ8nQ-_3_.gif)

## Screenshot
![App Screenshot](https://media.discordapp.net/attachments/993982266273452053/995813069152325753/unknown.png?width=1329&height=683)



