# Benefícios da Computação em Nuvem

### Alta Disponibilidade

A alta disponibilidade se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer. Está muito associada à SLA (Service Level Agreement). A provedora da nuvem se compromete a garantir a qualidade do serviço pelo tempo acordado. No caso da Azure, as SLAs estão ligadas a % de Uptime. Caso a porcentagem acordada não seja atingida, a Microsoft retornará um valor em forma de crédito.

**SLA** | **Tempo de Inatividade por Semana** | **Tempo de Inatividade por Mês** | **Tempo de Inatividade por Ano**
--- | --- | --- | ---
99% | 1,68 horas | 7,2 horas | 3,65 dias
99,90% | 10,1 minutos | 43,2 minutos | 8,76 horas
99,95% | 5 minutos | 21,6 minutos | 4,38 horas
99,99% | 1,01 minutos | 4,32 minutos | 52,56 minutos
99,999% | 6 segundos | 25,9 segundos | 5,26 minutos

### Escalabilidade

A escalabilidade refere-se à capacidade de ajustar recursos para atender à demanda. Significa que você poderá adicionar mais recursos para lidar melhor com o aumento de demanda.

**Outros Benefícios da Escalabilidade:**
- Você não paga além do necessário pelos serviços.
- Como a nuvem é um modelo baseado em consumo, você paga apenas pelo que usa.
- Se a demanda cair, você poderá reduzir seus recursos e, assim, reduzir seus custos.

### Elasticidade

Com a elasticidade, se você experimentar um salto repentino na demanda, seus recursos implantados podem ser expandidos (automaticamente ou manualmente). Da mesma forma, se houver uma queda significativa na demanda, os recursos podem ser reduzidos horizontalmente.

**Exemplo:**
- Adicionar Máquinas Virtuais ou containers por meio da expansão.
- Reduzir recursos quando a demanda diminuir.

### Confiabilidade

Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente. Mesmo que ocorra um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento.

### Previsibilidade

A previsibilidade na nuvem permite que você avance com confiança, seja no desempenho ou no custo. Ambas são influenciadas pelo Microsoft Azure Well-Architected Framework.

### Segurança

A Nuvem oferece ferramentas de segurança que atendem às necessidades dos clientes, mas é importante lembrar que a implementação de muitas delas deve ser realizada pelo cliente.

**Exemplo:**
- Criação de security groups.

Se você deseja controle máximo da segurança, a infraestrutura como serviço fornece recursos físicos, mas permite que você gerencie os sistemas operacionais e o software instalado, incluindo a aplicação de patches e manutenção.

Se preferir que a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de plataforma como serviço ou software como serviço podem ser as melhores estratégias de nuvem para você.

### Governança

A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação. Dependendo do seu modelo operacional, patches de software e atualizações podem ser aplicados automaticamente, o que ajuda na governança e na segurança.

**Governança x Segurança:**
Governança e Segurança caminham juntas. Governança foca em atender padrões corporativos e regras internas, enquanto a Segurança trata da proteção dos dados e recursos.

**Exemplo:**
- Optar por bloquear determinados serviços em uma região específica da nuvem.

### Gerenciabilidade

Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento. Existem dois tipos de capacidade de gerenciamento para computação em nuvem:

- **Gerenciamento de Recursos:** 
  - Escalar automaticamente a implantação de recursos com base na necessidade.
  - Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.

- **Gerenciamento do Ambiente de Nuvem:**
  - Por meio de um portal da Web
  - Usando uma interface de linha de comando
  - Usando APIs
  - Usando Powershell
  - Usando Terraform
