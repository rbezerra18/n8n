# URSO - Message Buffer (Slack -> Redis)

Este workflow foi desenvolvido para automatizar processos relacionados a **URSO - Message Buffer (Slack -> Redis)**. O fluxo manipula bancos de dados vetoriais/em memória para recuperar conhecimentos ou gerenciar sessões e contexto de memória (RAG ou Memory). É acionado automaticamente a partir de integrações externas.

## 🚀 Como Funciona

Este fluxo de trabalho opera baseado nos seguintes componentes (nós) do n8n:

### 📥 Gatilhos (Triggers)
- Slack

### ⚙️ Ações e Processamento
- Code, Redis

## 🔒 Segurança e Dados Sensíveis
Todas as chaves reais de API e credenciais (credentials) foram devidamente tratadas no arquivo `.json` exportado para garantir a segurança dos dados originais. O arquivo pode ser importado com segurança e você deve configurar suas próprias credenciais em sua instância n8n.

## 🛠 Como utilizar
1. Abra o n8n.
2. Na tela de workflows, selecione `Import from File` (Importar de um arquivo).
3. Selecione o arquivo json associado a este workflow.
4. Ajuste as credenciais necessárias em todos os nós sinalizados.
5. Salve e ative (se desejar).
