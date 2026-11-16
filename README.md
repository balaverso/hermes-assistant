# Hermes Assistant 🧠

Assistente pessoal inteligente baseado no **Hermes Agent**, com execução controlada pelo GitHub Actions e integração planejada com NVIDIA NIM.

O objetivo é construir um assistente capaz de apoiar atividades profissionais, projetos pessoais, organização de conhecimento e automações, mantendo segurança, privacidade e controle sobre suas ações.

## 🎯 Objetivos

- Apoiar atividades de Business Intelligence.
- Auxiliar na criação e revisão de SQL, DAX e Python.
- Apoiar projetos de desenvolvimento de software.
- Automatizar tarefas recorrentes.
- Organizar informações e conhecimento.
- Integrar diferentes ferramentas e serviços por meio de agentes.

## 🏗️ Arquitetura planejada

```text
              USUÁRIO
                 |
                 v
          Interface de acesso
                 |
                 v
           GitHub Actions
                 |
                 v
            Hermes Agent
                 |
                 v
             NVIDIA NIM
                 |
                 v
          Resposta / Resultado
```

### Tecnologias

| Tecnologia | Finalidade |
|---|---|
| Hermes Agent | Agente de IA principal |
| GitHub Actions | Execução automatizada |
| NVIDIA NIM | Provedor de modelos de IA |
| GitHub | Código, versionamento e documentação |
| Telegram | Interface de comunicação futura |
| Obsidian | Base de conhecimento futura |

## 🔐 Segurança e privacidade

A segurança é um requisito fundamental do projeto.

1. Repositório privado sempre que possível.
2. Credenciais armazenadas exclusivamente em GitHub Secrets.
3. Nunca publicar API Keys, tokens, senhas ou arquivos `.env`.
4. Utilizar permissões mínimas nos workflows.
5. Não executar alterações em arquivos ou sistemas sem autorização explícita.
6. Não acessar dados pessoais ou profissionais sem autorização.
7. Manter a integração com Obsidian desativada na primeira fase.
8. Não executar comandos destrutivos sem confirmação.

## 🚀 Plano de desenvolvimento

### Fase 1 — Fundação
- [ ] Estruturar o repositório.
- [ ] Documentar arquitetura e regras de segurança.
- [ ] Criar workflow manual no GitHub Actions.
- [ ] Validar a instalação do Hermes Agent.

### Fase 2 — Inteligência artificial
- [ ] Configurar NVIDIA NIM.
- [ ] Selecionar o modelo principal.
- [ ] Validar chamadas de inferência.
- [ ] Definir limites de consumo.

### Fase 3 — Integrações
- [ ] Integrar Telegram.
- [ ] Implementar controle de usuários autorizados.
- [ ] Avaliar integração com GitHub.
- [ ] Avaliar integração somente leitura com Obsidian.

### Fase 4 — Assistente pessoal
- [ ] Criar habilidades especializadas em BI.
- [ ] Criar habilidades para desenvolvimento.
- [ ] Implementar automações pessoais.
- [ ] Avaliar execução contínua em infraestrutura dedicada.

## 📌 Princípios do projeto

- Autonomia com responsabilidade.
- Segurança antes de conveniência.
- Aprovação humana para ações sensíveis.
- Baixo custo operacional.
- Arquitetura modular e expansível.
- Documentação e versionamento de todas as evoluções.

## 📍 Status

**Em desenvolvimento — Fase 1: Fundação.**

Este repositório será a base de evolução do Hermes Assistant.
