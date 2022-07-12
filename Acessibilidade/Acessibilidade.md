# Acessibilidade
![App Screenshot](https://cdn.discordapp.com/attachments/993982266273452053/996466922986164354/unknown.png)
#### Essas verificações destacam oportunidades para melhorar a acessibilidade do seu aplicativo da web. Apenas um subconjunto de problemas de acessibilidade pode ser detectado automaticamente, portanto, o teste manual também é incentivado.
-----------------------------------------------------------------------------------------------------------------------
# Nome acessivel
### Os links não têm um nome discernível
```bash
Quando um elemento não tem um nome acessível, os leitores de tela o anunciam com um nome genérico,
tornando-o inutilizável para usuários que dependem de leitores de tela.
```
## Screenshot
![App Screenshot](https://media.discordapp.net/attachments/993982266273452053/996450231388487690/unknown.png)
------------------------------------------------------------------------------------------------------------------------
# Nome acessivel
### os elementos button, link e menuitem não possuem nomes acessíveis
```bash
Quando um elemento não tem um nome acessível, os leitores de tela o anunciam com um nome genérico,
tornando-o inutilizável para usuários que dependem de leitores de tela.
```
- Role = Função.
## Screenshot
![App Screenshot](https://media.discordapp.net/attachments/993982266273452053/996450443918069862/unknown.png)

# Zoom Mobile
### [user-scalable="no"] is used in the <meta name="viewport"> element or the [maximum-scale] attribute is less than 5.
Desativar o zoom é problemático para usuários com baixa visão que dependem da ampliação da tela para ver corretamente o conteúdo de uma página da web
```bash
width=device-width
Isso significa que estamos dizendo ao navegador “meu site se adapta à largura do seu dispositivo”.

initial-scale
Isso define a escala do site. Esse parâmetro define o nível de zoom inicial, o que significa que
1 pixel CSS é igual a 1 pixel da janela de visualização. Este parâmetro ajuda quando você está alterando
a orientação ou impedindo o zoom padrão. Sem esse parâmetro, o site responsivo não funcionará.

maximum-scale
A escala máxima define o zoom máximo. Quando você acessa o site, a prioridade máxima é maximum-scale=1 e não
permitirá que o usuário faça zoom.

minimum-scale
A escala mínima define o zoom mínimo. Isso funciona da mesma forma que acima, mas define a escala mínima.
Isso é útil quando a escala máxima é grande e você deseja definir a escala mínima.
```
## Screenshot
![App Screenshot](https://cdn.discordapp.com/attachments/993982266273452053/996461449947914240/unknown.png)
