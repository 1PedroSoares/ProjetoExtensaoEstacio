# ProjetoExtensaoEstacio

Funcionalidades Principais:
Cadastro de Músicos: Permitir o registro de músicos, incluindo informações como nome, qualificações, experiências e telefone.
Cadastro de Eventos: Registrar eventos, com data, horário e descrição.
Escala de Músicos: Associar músicos aos eventos de forma que a escala seja fácil de gerenciar.
Consulta de Profissionais: Permitir a busca por músicos com base em suas qualificações e experiências.
Justificativa de Ausências: Registrar ausências dos músicos e permitir justificativas.

Modelo de Dados
Tabelas Sugeridas:

Músicos

id_musico (PK)
nome
qualificacoes
experiencias
telefone

Eventos

id_evento (PK)
data_evento
horario_evento
descricao

Escala

id_escala (PK)
id_evento (FK para Eventos)
id_musico (FK para Músicos)
presenca (boolean)
justificativa.
