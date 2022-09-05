[Link do projeto no figma](https://www.figma.com/file/ibWktwVpnog76rMYOdVhks/Dispondo-elementos-com-flexbox-e-grid?node-id=54%3A2358)


<h2>Objetivos do projeto:
<h4>Relacionar o flexbox com maneiras já conhecidas de posicionamento de elementos
<h4>Ver o flexbox e suas propriedades para o posicionamento de elementos
<h4>Produzir o cabeçalho utilizando as ferramentas do flexbox
<h4>Identificar as limitações do flexbox
<h4>Diferenciar o flexbox do grid
<h4>Prototipar o layout de um cartão utilizando propriedades básicas do grid
<h4>Reconhecer no layout do figma o que pode fazer parte de um grid
<h4>Associar as propriedades novas com o que já existe de estrutura no projeto
<h4>Ver como o layout atual se comporta em um dispositivo diferente
<h4>Resolver os problemas com novas propriedades de grid
<h4>Produzir o restante do layout com novas propriedades de grid
<h4>Identificar problemas como: repetição de código, manutenção e unidades de medida
<h4>Entender as vantagens de se utilizar a abordagem do grid
<h4>Planejar como pode ser a construção das outras páginas do projeto utilizando as técnicas aprendidas




















# Guia de estilos

Toda a estilização que será usada no projeto dentro do figma.

[Link do projeto no figma](https://www.figma.com/file/ibWktwVpnog76rMYOdVhks/Dispondo-elementos-com-flexbox-e-grid?node-id=54%3A2358)

## Fonte

```html
Open Sans:
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link
  rel="stylesheet"
  href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap"
/>
```

## Cores

corpo: `#1D232A`

cabeçalho: `#1D232A`

cabeçalho mobile: `#15191C`

menu lateral: `#15191C`

cartão: `#2C343A`

fonte: `#FFFFFF`

fonte alternativa: `#95999C`

links: `#0480DC`

botão: `#0480DC`

sombras: `0px 4px 4px rgba(0, 0, 0, 0.16)`

## Ícones

Estão dentro do arquivo de fonte `icones.ttf`. Para usar, primeiro importe a fonte no projeto usando `@font-face` e depois utilize os códigos abaixo para exibir o ícone.

```css
@font-face {
  font-family: "icones";
  src: url(../font/icones.ttf);
}
```

> Cuidado com a localização do arquivo `icones.ttf`

Camisas = `\e900`

Carrinho = `\e901`

Inicio = `\e902`

Integrantes = `\e903`

Menu = `\e904`

Moeda = `\e905`

Notificação = `\e906`

Pico = `\e908`

Picos = `\e909`

Pinturas = `\e90a`

Play = `\e90b`

Relogio = `\e90c`

Seta-baixo = `\e90d`

Videos = `\e90e`

Visualizacao = `\e90f`

## Espaçamentos

Espaço interno botão: `8px`

Espaço entre elementos do botão: `8px`

Espaço entre elementos: `16px/8px`

Espaçamento interno do corpo: `16px`

Espaçamento entre o título do cartão de recentes e seus itens: `24px`

## Tamanhos

Tamanho do dispositivo mobile: `360px`

Tamanho do dispositivo desktop: `1440px`

Largura máxima do conteúdo principal: `1120px`

Largura máxima de um cartão desktop: `256px`

Altura mínima de um cartão: `320px`
