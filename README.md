# Focus Log

> **Focus 6.0** — feito por humanos, para humanos. Orgânico, pessoal e único.

O **Focus Log** é o registro público da evolução do Focus: o que mudou entre versões, quais experiências chegaram ao produto e quais builds estão disponíveis para uso.

O Focus nasceu como uma ferramenta de foco e foi sendo remodelado através de meses de uso real em trabalho, estudos, projetos e rotina pessoal. Bugs, atritos, ideias que pareciam pequenas e funcionalidades que se tornaram indispensáveis ajudaram a definir o produto que existe hoje.

Este repositório também é o ponto oficial de distribuição do **Focus — Palm para Android**. O código-fonte do produto permanece privado; aqui ficam apenas builds públicas, metadados de atualização, checksums, histórico e documentação de distribuição.

## Focus 6.0

A versão 6.0 transforma o Focus de um timer com ferramentas de produtividade em uma experiência diária mais integrada.

### Hoje

A tela **Hoje** concentra o que merece atenção agora:

- plano do dia;
- próxima ação;
- tarefas planejadas;
- agendamento e prazo;
- prioridades diárias;
- alertas de urgência;
- estimativa de foco;
- progresso e ritmo;
- conquistas;
- calendário de atividade.

### Tarefas + Timer

Tarefas e sessões de foco passam a fazer parte do mesmo fluxo:

- selecionar uma tarefa diretamente no Timer;
- iniciar foco pelo Dashboard ou pela própria tarefa;
- manter a tarefa ativa sincronizada;
- registrar automaticamente o tempo realizado;
- comparar tempo estimado e realizado;
- acompanhar o progresso da tarefa;
- ao terminar uma sessão, continuar focando, concluir a tarefa, iniciar uma pausa ou escolher outra tarefa.

### FocushoMe

O **FocushoMe** representa a identidade de foco construída pelo uso real do aplicativo. Ele observa como você planeja, executa, conclui, retoma e mantém seu ritmo, transformando comportamento em uma identidade visual que evolui junto com você.

### Conquistas

O Focus possui um sistema de conquistas e insígnias ligado à constância e ao uso do produto. As conquistas já obtidas permanecem registradas mesmo quando uma sequência diária é interrompida.

### O restante da experiência

A versão pública também reúne:

- Timer de foco, pausa curta e pausa longa;
- tarefas e projetos;
- metas;
- histórico e streaks;
- Analytics;
- calendários de atividade;
- notificações;
- widgets Android;
- português do Brasil e inglês;
- sincronização dos dados da conta;
- atualizador interno seguro no Android.

## Plataformas

### Focus — Palm

**Android — público**

A versão móvel principal do Focus. A partir do ciclo 6.0, builds de distribuição direta podem receber novas versões pelo atualizador interno seguro.

**iPhone e iPad — em testes privados**

A experiência Palm para o ecossistema Apple continua em desenvolvimento e não faz parte da distribuição pública deste repositório.

### Focus — Horizon

**macOS e Windows — público**

A experiência desktop do Focus foi criada para sessões longas de estudo, trabalho e projetos, mantendo Timer, planejamento, tarefas, projetos, metas e Analytics disponíveis sem depender de uma aba do navegador.

### Focus — Web

**Navegador — público**

Acesso ao Focus sem instalação, com a experiência principal disponível diretamente pela web.

### Focus — Pulse

**Wear OS — testes privados**

A experiência para relógio continua em validação antes de uma distribuição pública.

### Focus — Extension

**Chrome — testes privados**

A extensão permanece em desenvolvimento para o ciclo seguinte do produto.

## Histórico público

| Versão | Status | O que representa |
| --- | --- | --- |
| **6.0.0** | Pública | Nova experiência Hoje, integração Tarefas ↔ Timer, evolução do FocushoMe e base de atualização interna para os próximos ciclos. |
| **5.0.4** | Pública | Atualização de validação do updater Android, sem novas funcionalidades de produto. |
| **5.0.3** | Pública | Base com configuração corrigida do atualizador interno. |
| **5.0.2** | Pública | Atualização de validação da cadeia de atualização Android. |
| **5.0.1** | Pública | Baseline pública updater-ready da série 5.0. |

As versões antigas permanecem disponíveis para histórico e verificação. A versão recomendada para novos usuários é sempre a release estável mais recente.

## Downloads oficiais

Os binários públicos ficam em **Releases** deste repositório:

- [Ver todas as releases](../../releases)
- [Focus Palm 6.0.0](../../releases/tag/v6.0.0)
- [Focus Site](https://focus-website-seven.vercel.app/)
- [Focus Web](https://pomodoro-1ktl-theta.vercel.app/)

## Identidade oficial do Android

- Package: `com.mateusgomes.focusapp`
- Certificado de assinatura SHA-256: `66ef952ba112112325e03a5964f9b3102810cd22f3db50bdce796831cc943dab`
- Canal de distribuição: `stable`

Cada APK público é distribuído por HTTPS e acompanhado por SHA-256. Antes de abrir o instalador Android, o Focus valida arquivo, package, versão e certificado de assinatura.

A release só passa a ser oferecida automaticamente quando o manifesto estável é atualizado. O manifesto é publicado por último.

## Instalação e segurança

- [Instruções de instalação Android](docs/android-installation.md)
- [Política de segurança](SECURITY.md)

## Sobre este registro

O Focus passou por muitas versões antes de chegar a uma experiência que eu considero utilizável todos os dias. Este espaço existe para registrar essa evolução de forma pública: decisões, versões, recursos que sobreviveram ao uso real e as melhorias que continuam moldando o produto.

**Seu foco, nas suas mãos.**
