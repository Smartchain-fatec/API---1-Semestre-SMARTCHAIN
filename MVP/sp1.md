# 📌 MVP - [Tratamento dos dados da RAIS e dashboards no Power BI para mapeamento do ecossistema industrial e de serviços de São José dos Campos]

## 🎯 Objetivo do MVP

> O MVP visa transformar a base pública da RAIS em uma base municipal tratada em Python, para exibir em dashboards no Power BI o perfil industrial e de serviços de São José dos Campos.

- **Qual problema resolve?** A base da RAIS é muito extensa e exige preparação prévia para ser usada com eficiência. Sem filtragem e limpeza, é difícil enxergar quais setores concentram vínculos empregatícios, como são os estabelecimentos e onde estão localizados.

- **Qual hipótese será validada?** A hipótese de que filtrar a base da RAIS para o município com Python, limpá-la e apresentá-la em um painel de BI interativo permite compreender o ecossistema industrial e de serviços de São José dos Campos de forma mais rápida e confiável.

- **Qual valor será entregue ao usuário final?** Uma base de dados organizada e confiável, além de visualizações claras que apoiam decisões sobre qualificação profissional, geração de emprego e mobilidade.

---

## 📝 Descrição da Solução

> Desenvolvimento de um pipeline de tratamento de dados em Python, integrado a dashboards no Power BI, para filtrar a RAIS de São José dos Campos, limpar a base e explorar indicadores do ecossistema industrial.

- **Funcionalidades principais incluídas:**
  - Filtragem da base da RAIS para o município de São José dos Campos com Python.
  - Limpeza e organização da base, com identificação e remoção de duplicidades e inconsistências.
  - Dashboards iniciais no Power BI com: vínculos empregatícios por CNAE, vínculos por setor e subsetor, estabelecimentos por porte, distribuição geográfica dos vínculos e natureza jurídica.

- **Limitações conhecidas:**
  - Os dashboards estão em fase inicial de construção (iniciados nesta sprint).
  - A atualização depende da execução manual dos scripts e do reenvio da base ao Power BI.
  - A análise se restringe aos dados da RAIS filtrados para São José dos Campos.
  - O período de referência dos dados da RAIS ainda precisa ser registrado.

- **Escopo reduzido:** Foco no tratamento da base da RAIS e na visualização inicial dos indicadores do ecossistema industrial e de serviços do município.

---

## 👥 Personas / Usuários-Alvo

- **Persona 1:** Gestor / Tomador de decisão público ou institucional (cliente do projeto): precisa de dados confiáveis e visualizações claras para entender o perfil produtivo do município e embasar ações de qualificação profissional, geração de emprego e mobilidade.
- **Persona 2:** Analista de dados / Pesquisador do ecossistema industrial: precisa de uma base tratada e organizada para consultar setores, subsetores, porte e natureza jurídica dos estabelecimentos sem lidar com a base bruta da RAIS.

---

## 🔑 User Stories (Backlog do MVP)

| ID  | User Story                                                                                                                                                                      | Prioridade | Estimativa |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ---------- |
| US1 | Como analista de dados, quero que a base da RAIS seja filtrada para o município de São José dos Campos usando Python, para reduzir o tamanho do arquivo e viabilizar o tratamento. | Altíssima  | A definir  |
| US2 | Como analista de dados, quero que a base filtrada seja limpa e organizada (duplicidades e inconsistências removidas), para ter uma base confiável para análise.                  | Alta       | A definir  |
| US3 | Como gestor, quero dashboards interativos no Power BI com os indicadores do ecossistema industrial de São José dos Campos, para consultar e interpretar os dados com facilidade.  | Alta       | A definir  |

---

## 📅 Sprint(s) Relacionadas

| Sprint | Entregas Principais                                                                                                                                  | Status    |
| ------ | ---------------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| 01     | Filtragem da RAIS para São José dos Campos com Python; limpeza e organização da base; envio da base tratada (19/09); início dos dashboards no Power BI | Concluído |
| 02     | Finalização e refinamento dos dashboards no Power BI                                                                                                 | A fazer   |
| 02     | Relatório técnico (fontes de dados, metodologia e análises realizadas)                                                                               | A fazer   |
| 02     | Tutorial "Mapeamentos do Ecossistema Industrial e de Serviços de SJC"                                                                                | A fazer   |

---

## 📊 Critérios de Aceitação

- A base da RAIS deve estar filtrada apenas para o município de São José dos Campos.
- A base tratada não deve conter duplicidades e inconsistências identificadas na limpeza.
- A base tratada deve estar disponível para uso no Power BI.
- Os dashboards devem permitir consultar: vínculos por CNAE, vínculos por setor e subsetor, estabelecimentos por porte, distribuição geográfica dos vínculos e natureza jurídica.
- Todas as entregas da sprint devem estar publicadas no GitHub no formato orientado pelo cliente.

---

## 📈 Métricas de Validação

- Número de usuários que testaram o MVP
- Feedback qualitativo do cliente (positivo/negativo)
- Redução do tamanho da base após a filtragem para o município
- Percentual de tarefas da sprint concluídas (Sprint 1: 18 de 19 atividades, 94,7%)

---

## 🚀 Próximos Passos

- Finalizar e refinar os dashboards no Power BI com base no feedback do cliente
- Concluir o relatório técnico e o tutorial "Mapeamentos do Ecossistema Industrial e de Serviços de SJC"
- Registrar o período de referência dos dados da RAIS
- Publicar todas as entregas no GitHub no formato orientado e manter a planilha 5W2H atualizada

---

## 📂 Anexos / Evidências

- Base RAIS: <https://drive.google.com/file/d/15lLRUwtJCNYyRlthFJIyRTdSkgRHrXD2/view?usp=drive_link>
- Relatório da 1ª Sprint e Relatório 5W2H: Dados/ATA Sprint 1/ATA-API_ SmartChain 1.docx
- ATA nº 01/2026 (reunião de 21/09/2026): [inserir link/arquivo no repositório]
- Vídeo de demonstração: [inserir link]
