# Técnicas avançadas de css

## Padrões arquiteturais

Abordagens arquiteturais usadas:

- OOCSS (Object Oriented CSS)
- SMACSS (Scalable And Modular Architecture for CSS)
- DRY CSS (Don't repeat yourself)

## OOCSS 
Porque é muito intuitiva, simples de desenvolver e manter. Pois fiz uma separação entre propriedades de estrutura e de skin.

Exemplo: Classe `button` como classe de estrutura e `btn-primary` como a de skin.

## SMACSS 
Porque podemos usar o Css Reset ou Normalize.

Exemplo: Fazendo um Css Reset no elemento html `header`.

## DRY CSS 
Porque há um reaproveitamento de classes e permite agrupar determinadas propriedades ou estilos.

Exemplo: Não é necessário redeclarar a estrutura do botão, pois a classe `button` serve para a estrutura de todos.

## Considerações finais
De acordo com o escopo do projeto não é interessante usar todos os recursos do SMACSS (Scalable And Modular Architecture for CSS) pois existe a funcionalidade de informar as classes layout com o prefixo 'l-' e não focamos em gerenciar o estado.

Sobre o BEM (Block, Element, Modifier) foca na nomenclatura dos descendentes, e isso tem suas vantages de organização porém dessa forma é necessário ter mais classes, por isso não escolhi. 