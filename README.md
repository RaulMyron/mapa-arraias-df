# Mapa de Arraiás - Distrito Federal (2026)

Uma aplicação web interativa desenvolvida para mapear, visualizar e filtrar as festas juninas programadas para o Distrito Federal durante os meses de maio e junho de 2026. 

## Funcionalidades

* **Visualização Geoespacial:** Marcadores distribuídos pelo mapa do DF indicando os locais exatos ou as regiões administrativas das festas.
* **Filtro de Período:** Sistema de seleção de datas (início e fim) para renderizar dinamicamente apenas os eventos que ocorrem no intervalo temporal desejado pelo usuário.
* **Identificação Visual de Custo:** Marcadores verdes sinalizam eventos com entrada gratuita, enquanto marcadores vermelhos sinalizam eventos com entrada paga.
* **Pop-ups Informativos:** Interação via clique nos marcadores para exibição de detalhes resumidos: nome da festa, local, período de realização e status de entrada.

## Tecnologias Utilizadas

A solução foi arquitetada como uma aplicação estática (Static Site), focada em leveza e sem a necessidade de instâncias de back-end, utilizando:

* **HTML5, CSS3 e JavaScript (Vanilla)**
* **Leaflet.js:** Biblioteca open-source em JavaScript para mapas interativos.
* **OpenStreetMap:** Provedor da base cartográfica.

## Como Executar Localmente

O projeto não exige instalação de pacotes ou processos de build de framework. Para rodar a aplicação no seu ambiente local:

1. Clone este repositório:
   ```bash
   git clone [https://github.com/raulmyron/mapa-arraias-df.git](https://github.com/raulmyron/mapa-arraias-df.git)
