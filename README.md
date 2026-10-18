# CENTRAL COD

Plataforma de operações de vendas com pagamento na entrega (COD).

## Estado

- Repositório inicializado.
- Dashboard de homologação anterior foi publicado separadamente na Vercel; **ainda não está conectado a este repositório**.
- Esquema inicial de leads, conversas, mensagens e pedidos foi preparado no Supabase; **não representa integração funcional com o frontend**.
- Integrações WhatsApp, Logzz, Hyppe e Meta Ads: pendentes.

## Princípios

- Modo manual deve funcionar independentemente de IA.
- Modos desligado, manual, assistido e automático devem ser aplicados pelo backend, não só pela interface.
- Nenhum pedido, mensagem ou anúncio deve ser enviado em testes sem autorização explícita.
- Toda fase requer testes automatizados, validação manual e evidência de deploy.
- Segredos apenas em variáveis de ambiente, nunca no Git.

## Ordem de entrega

1. Projeto web, autenticação e integração segura com Supabase.
2. Dashboard e CRM manual de leads e pedidos.
3. Controles operacionais e auditoria.
4. WhatsApp e transferência para atendimento humano.
5. Vendedores IA e supervisor.
6. Integrações Logzz/Hyppe, webhooks e idempotência.
7. Recuperação, pós-venda e financeiro real.
8. Mineração, criativos, Meta Ads e gerente IA.

## Ações do proprietário

- Importar este repositório para a Vercel e configurar o deploy Git.
- Informar o provedor de WhatsApp e confirmar acesso ao WhatsApp Business.
- Fornecer documentação oficial ou acesso autorizado às APIs Logzz e Hyppe.
- Autorizar Meta Ads quando chegar a fase de campanhas.
- Definir administradores, regras de aprovação e dados comerciais.

Não inserir credenciais ou senhas em issues, commits ou mensagens de chat.
