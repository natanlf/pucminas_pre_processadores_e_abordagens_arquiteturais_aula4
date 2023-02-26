# Técnicas avançadas de css

## Pré processadores e padrões arquiteturais

Abordagens arquiteturais usadas:

- OOCSS (Object Oriented CSS)
- SMACSS (Scalable And Modular Architecture for CSS)
- Dry Css (Don't repeat yourself)

## OOCSS 
Porque é muito intuitiva, simples de desenvolver e manter. Pois fiz uma separação entre propriedades de estrutura e de skin.

## SMACSS 
Porque podemos usar o Css Reset ou Normalize.

## Dry Css 
Porque há um reaproveitamento de classes e permite agrupar determinadas propriedades ou estilos. 

## Considerações finais

De acordo com o escopo do projeto não achei interessante usar todos os recursos do SMACSS (Scalable And Modular Architecture for CSS) pois existe a funcionalidade de informar as classes layout com o prefixo 'l-' e não focamos em gerenciar o estado.

Sobre o BEM (Block, Element, Modifier) foca na nomenclatura dos descendentes, e isso tem suas vantages de organização porém dessa forma é necessário ter mais classes, por isso não escolhi. 