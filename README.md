# AutoRoom: Gestão Inteligente e Eficiência Energética de Ambientes

O **AutoRoom** é uma solução de automação voltada para a eliminação de desperdícios energéticos e financeiros em espaços coletivos, como salas de aula, auditórios, laboratórios e escritórios.

Em ambientes com múltiplos usuários, é recorrente que sistemas de climatização, projetores e luminárias permaneçam ligados por horas a fio sem qualquer utilização real. O AutoRoom resolve essa ineficiência cruzando regras de agendamento com a percepção contínua de presença, garantindo que a energia só seja consumida quando o espaço estiver de fato ocupado.

---

##  O Problema

* **Consumo Ocioso:** Climatização e iluminação mantidas em funcionamento pleno em salas sem público.
* **Degradação de Equipamentos:** Projetores e aparelhos multimídia ligados desnecessariamente, reduzindo a vida útil de lâmpadas e componentes sensíveis.
* **Dependência do Fator Humano:** Dependência exclusiva da proatividade de usuários ou equipes de apoio para o desligamento manual ao final das atividades.
* **Ausência de Indicadores:** Dificuldade da gestão predial em mensurar com exatidão o custo do tempo ocioso em cada setor da instituição.

---

##  Como Funciona

O sistema atua com base em duas camadas complementares de decisão:

1. **Grade de Agendamento:**
   Os equipamentos têm seus ciclos de funcionamento atrelados ao cronograma de uso de cada espaço, garantindo que o ambiente esteja pronto no momento do início das atividades.
2. **Percepção Ativa de Ocupação:**
   O ambiente é monitorado constantemente. Caso uma sala agendada permaneça desocupada por um intervalo predeterminado (por exemplo, 15 minutos), o sistema sobrepõe a regra horária e executa o desligamento de segurança de todos os equipamentos.

---

##  Funcionalidades Centrais

* **Controle Autônomo de Climatização e Datashow:** Acionamento e desligamento de equipamentos sem necessidade de intervenção física nos aparelhos via infravermelho.
* **Gestão Integrada de Iluminação:** Controle direto e inteligente dos circuitos de iluminação do ambiente (via relés/Sonoff).
* **Painel Central de Operações:** Interface operacional com visibilidade em tempo real do estado de cada sala (presença humana, equipamentos ativos e horários programados).
* **Métricas Financeiras e de Sustentabilidade:** Conversão direta do tempo ocioso evitado em economia financeira (R$), permitindo análises comparativas de consumo diário, mensal e anual.
* **Detecção de Falhas e Quedas de Energia:** Identificação automática de ambientes desconectados ou sem fornecimento elétrico, com bloqueio preventivo de controles e alertas visuais à equipe técnica.
* **Desligamento em Lote com Regra de Horário:** Função para corte geral de energia com camada de proteção (confirmação obrigatória antes do horário padrão de término das atividades).

---

##  Estrutura do Painel de Gestão

A experiência visual foi estruturada sob o conceito *Digital Dash*, trazendo foco para dados críticos e resposta rápida:

* **Controle de Ambiente:** Indicador dinâmico de consumo atual (kW/h), registros de ativação/próximo agendamento e acionamento manual individualizado.
* **Visão Panorâmica de Salas:** Interface escalável que lista múltiplos ambientes em linha, exibindo leitura de temperatura local, status de cada carga e acionamento por lote.
* **Inteligência Energética:** Gráficos interativos com curvas de histórico semanal, divisão de carga por categoria de aparelho e comparativos de desempenho mês contra mês (MoM) e ano contra ano (YoY).

---

##  Impacto Esperado

* Redução substancial e mensurável na fatura de energia elétrica da instituição.
* Preservação da vida útil de aparelhos multimídia e de climatização.
* Mitigação das emissões indiretas de carbono decorrentes do uso racional da energia.
* Retorno sobre o investimento (ROI) acelerado pela eliminação direta do desperdício invisível.
