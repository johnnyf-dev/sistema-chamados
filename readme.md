# Sistema de Chamados

Aplicação de gerenciamento de chamados internos.  
Este projeto faz parte de um teste técnico e tem como objetivo entregar um MVP funcional com cadastro de usuários, abertura e aprovação de chamados, notificações e relatórios básicos.

## Escopo do MVP
- Cadastro de usuários
- Cadastro e gerenciamento de chamados
- Fluxo de aprovação
- Notificações básicas
- Kanban de chamados
- Relatórios simples

## Qualidade de código
- O projeto utiliza ESLint configurado para Node (backend) e Browser (frontend),
garantindo padronização e qualidade em ambos os ambientes.

## 📌 Histórico de Commits

Este projeto segue uma estratégia de commits granulares e organizados, para facilitar a compreensão de novos programadores e demonstrar maturidade técnica.

### Commits Granulares
- **docs: adiciona README inicial com instruções do projeto**  
  Criação do arquivo README com informações básicas e instruções iniciais.

- **chore: configura linting completo com ESLint (JS, JSON, Markdown, CSS)**  
  Configuração do ESLint para garantir qualidade de código e padronização.

- **chore: adiciona .gitignore e exemplo de configuração de ambiente (.env.example)**  
  Criação do `.gitignore` para proteger arquivos sensíveis e inclusão do `.env.example` para orientar configuração de ambiente.

### Commit Final
- **feat: adiciona código base do sistema de chamados**  
  Inclusão de todo o restante do código fonte e arquivos necessários para rodar o sistema.

## Próximos passos
- Definir estrutura do banco de dados
- Configurar conexão com Postgres
- Criar rotas iniciais no Express
- Implementar autenticação JWT

## Diferenciais (se houver tempo extra)
- Histórico detalhado dos chamados
- Chat interno entre usuários
- Dashboard analítico

## Como executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/johnnyf-dev/sistema-chamados.git
