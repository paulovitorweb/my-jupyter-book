# Geodata-JP

[Geodata-JP](https://github.com/paulovitorweb/geodata-jp) é um repositório que contém com arquivos GeoJSON simplificados da cidade de João Pessoa, ideal para uso em projetos web.

Aqui, compartilho alguns notebooks construídos a partir dos dados contidos no repositório.

## Relacionado
- [geodata-jp-notebooks](https://github.com/paulovitorweb/geodata-jp-notebooks): notebooks com exemplos de uso dos dados;
- [GeoJampa](https://paulovitorweb.github.io/geojampa/): visualização dos dados vetoriais no browser.

## Concepção
Os arquivos são coletados em portais públicos de dados abertos nos formatos shapefile e CSV, transformados para WSG84 EPSG:4326 e convertidos para o formato GeoJSON, simplificados para coordenadas com precisão de 6 casas decimais para ocupar menor espaço de armazenamento e facilitar a transferência de dados via API.

Cada arquivo GeoJSON possui um campo `source` que identifica a fonte dos dados.