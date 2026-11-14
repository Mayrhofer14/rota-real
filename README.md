# Rota Real

Jogo de corrida 3D no navegador. Escolha largada e chegada como num app de mapas, ou um circuito de Fórmula 1 / Fórmula Indy, e corra sobre fotos de satélite com relevo real, contra o grid.

Jogar: https://mayrhofer14.github.io/rota-real/

## Fornecedores de mapa

| Uso | Com chave ArcGIS (uso comercial) | Sem chave (testes e uso pessoal) |
|---|---|---|
| Fotos de satélite | Esri World Imagery (ArcGIS Location Platform) | Esri World Imagery, acesso público |
| Busca de endereço | Esri World Geocoding | Photon (Komoot) e Nominatim |
| Rotas | Esri Routing | OSRM |
| Mapa do menu | OpenFreeMap (sempre) | OpenFreeMap |
| Ruas, prédios, nomes | OpenFreeMap / OpenMapTiles (sempre) | idem |
| Relevo | Terrain Tiles, AWS Open Data (sempre) | idem |

A chave fica em `KEYS.arcgis`, no começo do script de `index.html`. É uma chave pública de navegador: restrinja-a no painel da Esri aos endereços onde o jogo roda.

## Créditos

- Imagens de satélite: Esri, Maxar, Earthstar Geographics e comunidade de usuários do GIS
- Ruas, prédios e nomes: OpenFreeMap © OpenMapTiles, dados © colaboradores do OpenStreetMap (ODbL)
- Relevo: Terrain Tiles (Mapzen, AWS Open Data), dados SRTM, GMTED, ETOPO1 e outros
- Traçados de Fórmula 1: [bacinger/f1-circuits](https://github.com/bacinger/f1-circuits) (MIT)
- Traçados da Fórmula Indy: OpenStreetMap (ODbL)
- Fórmula 1, Indy e nomes de circuitos pertencem aos seus donos; este jogo não tem ligação com eles.
