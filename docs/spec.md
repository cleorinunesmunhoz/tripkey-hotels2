# Especificação Técnica - TripKey Hotels

## Versões das Tecnologias

* **Materialize CSS:** `v1.0.0` (Usado para o layout responsivo, cards e modais).
* **jQuery:** `v3.7.1` (Usado para os efeitos e componentes interativos).
* **JSON Server:** `v0.17.4` (Usado para simular o banco de dados de usuários e favoritos).

---

## APIs Externas

### 1. ViaCEP (Consulta de Endereço)
* **Link:** `https://viacep.com.br/ws/{cep}/json/`
* **Função:** Preenche a rua, bairro e cidade ao digitar o CEP.

### 2. OpenWeather (Previsão do Tempo)
* **Link:** `https://api.openweathermap.org/data/2.5/weather`
* **Função:** Mostra o clima e a temperatura da cidade do hotel.
