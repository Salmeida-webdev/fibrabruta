# Mapa completo de módulos para um sistema de gestão de provedor de internet

A estrutura abaixo considera um provedor brasileiro de banda larga, com operação por fibra, rádio ou modelo híbrido. O sistema deve acompanhar o ciclo inteiro do serviço: **venda, viabilidade, instalação, ativação, cobrança, suporte, manutenção e encerramento**.

O ideal é que os módulos compartilhem os mesmos dados. Assim, uma visita técnica, uma falha de rede ou uma negociação com o cliente aparece no histórico e nas tarefas das equipes envolvidas.

## 1. Painel de gestão

Uma visão diária para gestores e responsáveis pela operação, com indicadores e pendências prioritárias.

- Clientes ativos, bloqueados, em instalação e cancelados.
- Receita recorrente, inadimplência, pagamentos recebidos e previsões.
- Ordens de instalação, reparo e manutenção em aberto.
- Falhas de rede, indisponibilidade por região e equipamentos críticos.
- Chamados por prioridade, tempo de atendimento e SLA vencido.
- Alertas de contratos, licenças, documentos, estoque e pagamentos próximos.
- Comparativos por período, cidade, bairro, plano e equipe.
- Atalhos para as tarefas que exigem ação.

Os indicadores precisam respeitar o perfil de acesso: cada usuário vê apenas os dados necessários à sua função.

## 2. Clientes, contatos e CRM

Cadastro unificado de clientes residenciais, empresariais e condomínios.

- Dados pessoais ou empresariais, contatos e endereço.
- Endereços adicionais e locais de instalação.
- Pessoas autorizadas a tratar da conta.
- Histórico de propostas, contratos, chamados, visitas e pagamentos.
- Preferências de contato e registro de consentimentos aplicáveis.
- Mapa de clientes por região.
- Identificação de clientes com várias instalações ou serviços.
- Sinalização de cadastro incompleto, duplicado ou desatualizado.

## 3. Vendas e oportunidades

Organiza a prospecção até a contratação.

- Funil configurável: lead, contato, análise de cobertura, proposta, negociação e ganho ou perda.
- Origem do lead: site, WhatsApp, indicação, loja, campanha ou vendedor.
- Tarefas de retorno, lembretes e prazos de negociação.
- Histórico de contatos e justificativa de perda.
- Metas, conversões e resultados por vendedor ou canal.
- Propostas com plano, preço, instalação, descontos e validade.
- Conversão da proposta aprovada em cliente e ordem de instalação.
- Campanhas, cupons, indicações e regras comerciais.

## 4. Cobertura e viabilidade técnica

Ajuda a evitar vendas em locais onde o serviço não pode ser instalado ou atenderia com limitações.

- Mapa de cobertura por rua, bairro, município, CTO, POP, torre ou setor.
- Consulta de disponibilidade por endereço ou coordenada.
- Capacidade disponível por porta, CTO, OLT, enlace ou setor de rádio.
- Registro de locais em expansão ou aguardando obra.
- Regras para reservar capacidade durante a venda.
- Histórico de consultas e motivos de inviabilidade.
- Estimativa de custo e prazo para atender novos locais.
- Integração com mapas e sistemas de projeto da rede.

## 5. Planos, ofertas e catálogo de serviços

Cadastro central das ofertas vendidas e serviços adicionais.

- Velocidade, tecnologia, franquias ou políticas de uso, quando aplicáveis.
- Preço, vencimento, taxa de instalação e regras promocionais.
- Equipamentos incluídos, comodato, venda ou locação.
- Serviços adicionais, como IP fixo, telefonia, Wi-Fi gerenciado ou suporte diferenciado.
- Regras de elegibilidade por região e tipo de cliente.
- Vigência, reajuste e condições comerciais.
- Histórico de alterações para identificar qual oferta foi contratada em cada período.
- Documentos da oferta associados à proposta e ao contrato.

## 6. Contratos e documentos

Mantém os documentos ligados ao cliente, à oferta e ao serviço contratado.

- Geração de contrato e anexos a partir de modelos.
- Assinatura eletrônica e acompanhamento do status.
- Armazenamento de comprovantes, autorizações e documentos enviados.
- Registro da versão da oferta aceita e da data de contratação.
- Alertas de vencimento, renovação, reajuste ou pendência de assinatura.
- Histórico de alterações, aditivos, suspensões e encerramentos.
- Acesso controlado e trilha de auditoria.

O módulo precisa refletir as regras aplicáveis à prestação de telecomunicações e ao atendimento ao consumidor. O RGC da Anatel abrange o SCM, e a Resolução nº 765 teve dispositivos com entrada em vigor em 1º de setembro de 2025; detalhes de aplicação devem ser confirmados para o perfil de cada prestadora.&#x20;

## 7. Ciclo de vida do assinante e provisionamento

Controla a passagem do contrato para o serviço funcionando.

- Solicitação de instalação, agendamento e confirmação.
- Registro de materiais, equipamento e número de série usados.
- Vínculo entre cliente, endereço, plano e equipamento de rede.
- Provisionamento ou alteração de velocidade e serviços.
- Ativação, suspensão, bloqueio, desbloqueio e cancelamento.
- Registro do motivo e do responsável por cada mudança.
- Validações para impedir ativação sem contrato, endereço ou recurso técnico válido.
- Integração com RADIUS, BNG, OLT, roteadores ou sistemas de aprovisionamento, conforme a infraestrutura.

## 8. Faturamento e cobrança

Um dos módulos centrais para manter a operação financeira organizada.

- Geração recorrente de cobranças e controle de vencimentos.
- Cobrança proporcional em instalação, mudança ou alteração de plano.
- Pix, boleto, cartão, débito e baixa por retorno bancário, conforme os meios usados.
- Emissão e armazenamento de documentos fiscais aplicáveis ao serviço.
- Conciliação de pagamentos, estornos, descontos e créditos.
- Régua de cobrança configurável por atraso e perfil do cliente.
- Avisos de vencimento, atraso, suspensão e regularização.
- Controle de acordos, parcelamentos e contestação de cobrança.
- Indicadores de inadimplência, receita recorrente, churn e recebimento previsto.
- Integração com contabilidade e sistemas fiscais.

## 9. Financeiro, caixa e controladoria

Apresenta a saúde financeira do provedor, além das cobranças dos clientes.

- Contas a pagar e a receber.
- Fluxo de caixa previsto e realizado.
- Despesas por centro de custo, unidade e projeto.
- Receitas por plano, região, serviço e canal.
- Conciliação bancária e acompanhamento de taxas.
- Orçamento, custos recorrentes e compromissos futuros.
- Relatórios de margem e custo por assinante ou região.
- Aprovação de pagamentos e despesas por alçada.
- Exportação para contabilidade e prestação de contas.

## 10. Atendimento e central de relacionamento

Reúne os canais e o histórico de atendimento em uma única fila de trabalho.

- Chamados por telefone, WhatsApp, e-mail, portal e atendimento presencial.
- Identificação automática do cliente e da situação financeira ou técnica.
- Filas por assunto, região, prioridade e equipe.
- Respostas padrão, artigos de ajuda e roteiros de diagnóstico.
- Registro de protocolo, interações, anexos e solução.
- Encaminhamento entre atendimento, suporte técnico, financeiro e campo.
- SLA por tipo de chamado, com alertas de risco e atraso.
- Pesquisa de satisfação e motivos de reabertura.
- Relatórios de volume, tempo de primeira resposta e resolução.

## 11. Suporte técnico e problemas de conectividade

Faz a triagem antes de enviar uma equipe ao local.

- Diagnóstico guiado: sem conexão, lentidão, Wi-Fi, equipamento ou falha regional.
- Consulta de status do cliente, autenticação e equipamento associado.
- Testes remotos disponíveis conforme as integrações.
- Registro de evidências e resultados dos testes.
- Associação do chamado a uma falha coletiva existente.
- Detecção de chamados repetidos no mesmo endereço ou trecho.
- Regras para escalar o caso para NOC ou equipe de campo.
- Comunicação de andamento e encerramento ao cliente.

## 12. NOC e monitoramento da rede

Acompanha a disponibilidade e a saúde da infraestrutura.

- Mapa lógico e, quando disponível, geográfico da rede.
- Monitoramento de POPs, OLTs, ONUs, enlaces, torres, roteadores e energia.
- Disponibilidade, latência, perda de pacotes, uso de banda e temperatura.
- Alertas por limiar, evento ou indisponibilidade.
- Correlação de alarmes para reconhecer falhas que afetam vários clientes.
- Registro de incidentes, impacto, causa, responsável e solução.
- Comunicação de manutenção programada e indisponibilidade.
- Histórico de mudanças na rede.
- Painel de capacidade e saturação por enlace, porta, setor ou equipamento.
- Integração por SNMP, syslog, APIs ou ferramentas de monitoramento existentes.

## 13. Gestão da rede e endereçamento

Mantém inventário técnico e configuração organizada.

- Cadastro de POPs, caixas, CTOs, postes, dutos, torres, fibras, enlaces e equipamentos.
- Topologia e vínculo entre equipamentos e clientes atendidos.
- Plano de endereçamento IPv4 e IPv6.
- Controle de IPs públicos, privados e compartilhados.
- Rastreabilidade de sessões e alocações técnicas conforme as obrigações aplicáveis.
- Registro de VLANs, rotas, enlaces, portas e configurações.
- Backup versionado de configurações e registro de mudanças.
- Controle de acesso às credenciais e aos sistemas de rede.
- Integração com fabricantes e equipamentos utilizados pelo provedor.

Para prestadores que oferecem conexão à internet, há obrigação de manter registros de conexão pelo prazo mínimo previsto na regulamentação. A norma da Anatel também define informações como data e hora de início e término, duração, endereço IP e, quando necessário para identificação inequívoca em compartilhamento de IP público, a porta lógica. Esse módulo deve ser desenhado com sigilo, controle de acesso e retenção adequada, sem transformar registros técnicos em acesso ao conteúdo das comunicações.&#x20;

## 14. Ordens de serviço e equipes de campo

Organiza instalações, reparos, mudanças e vistorias.

- Tipos de ordem e checklists específicos.
- Priorização por impacto, prazo e localização.
- Agenda por equipe, técnico, região e janela de atendimento.
- Roteirização e visualização das visitas no mapa.
- Confirmação com o cliente e registro de chegada e conclusão.
- Fotos, observações, medições e assinatura do cliente.
- Materiais utilizados e equipamentos recolhidos.
- Motivo de visita improdutiva e necessidade de retorno.
- Indicadores de cumprimento de agenda, reincidência e produtividade.

## 15. Calendário, lembretes e tarefas

Esse recurso deve atravessar todos os módulos, em vez de funcionar como uma agenda isolada.

- Visitas técnicas, instalações e manutenções.
- Retornos comerciais e contatos com clientes.
- Vencimentos de contratos, licenças, documentos e pagamentos.
- Reajustes, renovações, inspeções e manutenções preventivas.
- Tarefas individuais e de equipe, com responsável e substituto.
- Prazos, recorrência, prioridade, dependências e anexos.
- Lembretes por painel, e-mail, SMS ou WhatsApp, conforme integrações.
- Regras para reatribuir tarefas vencidas e escalar atrasos.
- Visualização diária, semanal, mensal e por equipe.
- Histórico do que foi concluído, adiado, cancelado ou reatribuído.

## 16. Processos e automação de fluxos

Permite acompanhar cada processo do início ao fim, com responsáveis e prazos definidos.

- Fluxos configuráveis para venda, instalação, reparo, cobrança, cancelamento e expansão.
- Etapas, responsáveis, documentos e critérios para avançar.
- Aprovações para descontos, despesas, cancelamentos e alterações sensíveis.
- Gatilhos por evento: pagamento confirmado, chamado criado, falha detectada ou contrato assinado.
- Ações automáticas: criar tarefa, atualizar status, enviar aviso ou abrir ordem de serviço.
- Tratamento de exceções, falhas de integração e tentativas repetidas.
- Registro de cada mudança, responsável, data e justificativa.
- Visão de processos parados, atrasados e com dependências pendentes.

## 17. Estoque, almoxarifado e equipamentos

Controla os materiais usados na rede e nas visitas.

- ONUs, roteadores, fontes, cabos, conectores, caixas e ferramentas.
- Número de série, lote, estado, localização e fornecedor.
- Estoque por unidade, veículo, equipe e depósito.
- Reservas para instalações e projetos.
- Entradas, saídas, devoluções, perdas e itens danificados.
- Equipamentos emprestados ou em comodato ligados ao cliente.
- Alertas de estoque mínimo, validade ou manutenção.
- Inventário físico e divergências.
- Custos e histórico de aquisição.

## 18. Ativos, manutenção e expansão da rede

Gerencia a vida útil da infraestrutura e as obras.

- Cadastro de ativos, localização, propriedade, garantia e vida útil.
- Plano de manutenção preventiva e inspeções recorrentes.
- Histórico de falhas, reparos e peças substituídas.
- Ordens de obra, expansão, troca de equipamento e adequação.
- Orçamento, cronograma, equipe e fornecedores do projeto.
- Materiais previstos e consumidos.
- Aprovações e evidências da execução.
- Capacidade adicional esperada e data estimada de liberação.
- Custos, atrasos e pendências por projeto.

## 19. Fornecedores, trânsito IP e contratos operacionais

Acompanha dependências externas que podem afetar a prestação do serviço.

- Operadoras de transporte, trânsito IP, energia, postes, dutos e manutenção.
- Contratos, valores, vigência, reajustes, contatos e documentos.
- SLA contratado e indicadores de cumprimento.
- Chamados abertos com terceiros e protocolos.
- Dependências críticas por POP ou rota.
- Faturas, medições e divergências.
- Alertas de renovação, vencimento e reajuste.

## 20. Pessoas, equipes e segurança do trabalho

Apoia a gestão dos funcionários e prestadores de serviço.

- Usuários, equipes, cargos, turnos, unidades e áreas.
- Escalas, plantões, férias, ausências e substituições.
- Atribuição de tarefas por competência e disponibilidade.
- Treinamentos, certificações e documentos necessários.
- Permissões de acesso aos módulos e dados.
- Indicadores de carga de trabalho e cumprimento de atividades.
- Registros de segurança, equipamentos de proteção e incidentes, quando aplicável.

## 21. Portal do cliente e autoatendimento

Reduz tarefas repetitivas e dá ao assinante acesso aos próprios serviços.

- Visualização de plano, contrato, endereço e serviços ativos.
- Faturas, pagamentos, comprovantes e segunda via.
- Solicitação de suporte, acompanhamento de protocolo e envio de evidências.
- Consulta de indisponibilidade na região.
- Solicitação de mudança, upgrade ou cancelamento.
- Agendamento ou confirmação de visitas.
- Dados de contato e preferências de comunicação.
- Avisos de manutenção e histórico de notificações.
- Acesso acessível e compatível com celular.

## 22. Comunicação e avisos

Centraliza as mensagens enviadas a clientes e equipes.

- Modelos de aviso de cobrança, instalação, visita, manutenção e falha.
- Envio individual ou por grupos afetados por uma ocorrência.
- Canais configuráveis e histórico de entrega.
- Comunicação interna para incidentes, plantões e mudanças.
- Controle de mensagens duplicadas e falhas de envio.
- Registro do conteúdo comunicado e do público destinatário.

## 23. Relatórios e inteligência de negócio

Transforma os dados operacionais em decisões.

- Crescimento, cancelamento, inadimplência e receita recorrente.
- Vendas, conversão e desempenho de canais.
- Instalações, reparos, retornos e tempo de atendimento.
- Disponibilidade, capacidade, incidentes e clientes afetados.
- Custos por cliente, plano, região, equipe e infraestrutura.
- Rentabilidade e previsão de expansão.
- Relatórios programados e exportação com permissões.
- Definições padronizadas para que os indicadores tenham o mesmo significado em todas as áreas.

## 24. Administração, auditoria e integrações

Controla o próprio sistema e suas conexões externas.

- Usuários, perfis, permissões por ação e escopo regional.
- Autenticação segura, sessões e política de senhas.
- Registro de login, consulta e alterações importantes.
- Auditoria de quem alterou o quê, quando e por qual motivo.
- Configurações da empresa, filiais, impostos, horários e feriados.
- APIs, webhooks e integração com sistemas financeiros, fiscais, CRM, atendimento e monitoramento.
- Fila de integrações, logs, alertas e reprocessamento de falhas.
- Backups, restauração e plano de continuidade.
- Exportação e exclusão de dados conforme política de retenção e obrigações aplicáveis.

Como o sistema tratará dados pessoais e dados operacionais sensíveis, privacidade, segurança, controle de acesso e resposta a incidentes devem estar previstos desde o desenho. A ANPD mantém orientações e medidas de segurança para agentes de tratamento, inclusive de pequeno porte.&#x20;

## Fluxo principal que precisa ficar rastreável

1. Lead entra e consulta a cobertura.
2. Provedor valida a viabilidade e envia uma oferta documentada.
3. Cliente aceita e assina o contrato.
4. Sistema reserva capacidade e cria a instalação.
5. Técnico executa a ordem, registra materiais e ativa o serviço.
6. Sistema provisiona o plano e inicia o faturamento.
7. Atendimento e NOC acompanham chamados, incidentes e qualidade.
8. Financeiro trata pagamentos, atrasos, acordos e conciliação.
9. Mudanças, reparos e visitas ficam no histórico do assinante.
10. No cancelamento, o sistema encerra o serviço e controla equipamentos, pendências e documentação.

## Papéis de acesso recomendados

- **Administrador:** configura o sistema e gerencia usuários.
- **Gestor:** acompanha indicadores e aprova processos.
- **Comercial:** leads, propostas, cobertura e contratos.
- **Atendimento:** cadastro, protocolos e comunicação com clientes.
- **Financeiro:** cobranças, pagamentos, acordos e relatórios financeiros.
- **NOC:** rede, alarmes, incidentes e capacidade.
- **Técnico de campo:** ordens atribuídas, checklist e materiais.
- **Almoxarifado:** estoque, reservas e movimentações.
- **Auditoria ou compliance:** consulta autorizada a registros e documentos.

As permissões devem ser configuráveis por ação: visualizar, criar, editar, aprovar, cancelar, exportar e administrar. Alterações críticas devem deixar trilha de auditoria.