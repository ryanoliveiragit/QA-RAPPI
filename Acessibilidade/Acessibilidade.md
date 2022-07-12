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

# Zoom
### [user-scalable="no"] is used in the <meta name="viewport"> element or the [maximum-scale] attribute is less than 5.
Desativar o zoom é problemático para usuários com baixa visão que dependem da ampliação da tela para ver corretamente o conteúdo de uma página da web

width=device-width
Isso significa que estamos dizendo ao navegador “meu site se adapta à largura do seu dispositivo”.

initial-scale
Isso define a escala do site. Esse parâmetro define o nível de zoom inicial, o que significa que 1 pixel CSS é igual a 1 pixel da janela de visualização. Este parâmetro ajuda quando você está alterando a orientação ou impedindo o zoom padrão. Sem esse parâmetro, o site responsivo não funcionará.

maximum-scale
A escala máxima define o zoom máximo. Quando você acessa o site, a prioridade máxima é maximum-scale=1 e não permitirá que o usuário faça zoom.

minimum-scale
A escala mínima define o zoom mínimo. Isso funciona da mesma forma que acima, mas define a escala mínima. Isso é útil quando a escala máxima é grande e você deseja definir a escala mínima.

They are viewport meta tags, and is most applicable on mobile browsers.

width=device-width
This means, we are telling to the browser “my website adapts to your device width”.

initial-scale
This defines the scale of the website, This parameter sets the initial zoom level, which means 1 CSS pixel is equal to 1 viewport pixel. This parameter help when you're changing orientation, or preventing default zooming. Without this parameter, responsive site won't work.

maximum-scale
Maximum-scale defines the maximum zoom. When you access the website, top priority is maximum-scale=1, and it won’t allow the user to zoom.

minimum-scale
Minimum-scale defines the minimum zoom. This works the same as above, but it defines the minimum scale. This is useful, when maximum-scale is large, and you want to set minimum-scale.

user-scalable
Escalável pelo usuário atribuído a 1.0 significa que o site permite que o usuário aumente ou diminua o zoom.
Mas se você atribuí-lo a user-scalable=no, significa que o site não está permitindo que o usuário aumente ou diminua o zoom.

## Screenshot
![App Screenshot](https://cdn.discordapp.com/attachments/993982266273452053/996461449947914240/unknown.png)
# UL LI
Os leitores de tela têm uma maneira específica de anunciar listas. Garantir a estrutura de lista adequada ajuda na saída do leitor de tela
