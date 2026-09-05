# Product Requirements Document (PRD) - TripKey Hotels

## Identificação
* **Autor:** Cleori Nunes Munhoz
* **Projeto:** TripKey Hotels (`tripkey-hotels2`)

## Descrição do Projeto
O **TripKey Hotels** é um sistema web interativo para busca, comparação e escolha de hospedagens. A aplicação resolve a dificuldade de viajantes em encontrar hotéis que atendam a seus orçamentos e preferências, permitindo filtrar acomodações por preço, favoritar opções desejadas para consulta posterior e realizar cadastro de hóspede com validação de dados em tempo real.

## Atores do Sistema
1. **Visitante (Não Autenticado):** Pode realizar buscas de hotéis, comparar preços, visualizar detalhes de hospedagens e acessar formulários de login e cadastro.
2. **Cliente Autenticado:** Pode salvar hotéis em sua lista de favoritos, visualizar sua página de perfil/favoritos salvos e simular reservas.

## Histórias de Usuário (User Stories)

### Módulo de Busca e Comparação
* **US01:** Como **Visitante**, quero pesquisar hotéis por destino ou faixa de preço para encontrar opções compatíveis com meu orçamento.
* **US02:** Como **Visitante**, quero visualizar detalhes de um hotel (fotos, avaliação, comodidades e preço por diária) para comparar opções.
* **US03:** Como **Visitante**, quero ver a previsão do tempo do destino do hotel selecionado para planejar melhor minha viagem.

### Módulo de Autenticação e Usuário
* **US04:** Como **Visitante**, quero criar uma conta informando meus dados pessoais e endereço para ter acesso às funcionalidades exclusivas.
* **US05:** Como **Visitante**, quero preencher meu CEP no formulário de cadastro para ter o endereço preenchido automaticamente via busca externa.
* **US06:** Como **Cliente**, quero fazer login informando e-mail e senha para acessar minha conta salva.

### Módulo de Favoritos e Interação
* **US07:** Como **Cliente Autenticado**, quero clicar em favoritar um hotel para salvá-lo em uma lista de fácil acesso.
* **US08:** Como **Cliente Autenticado**, quero gerenciar minha lista de hotéis favoritos (visualizar e remover) a qualquer momento.
