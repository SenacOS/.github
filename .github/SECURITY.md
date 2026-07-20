# 🔒 Política de Segurança

A SenacOS leva a segurança dos seus projetos a sério. Agradecemos a colaboração da comunidade em identificar e reportar vulnerabilidades de forma responsável.

## Versões Suportadas

Como a maioria dos projetos da SenacOS está em desenvolvimento ativo, geralmente apenas a branch principal (`main` ou `develop`, conforme o repositório) recebe correções de segurança.

| Versão / Branch       | Suportada          |
| ---------------------- | ------------------ |
| `main` / `develop`     | ✅ Sim              |
| Versões antigas / tags | ❌ Não              |

Repositórios específicos podem detalhar exceções a essa regra em seu próprio README.

## Reportando uma Vulnerabilidade

**Não abra uma Issue pública para relatar vulnerabilidades de segurança.** Isso evita que a falha seja explorada antes de ser corrigida.

Em vez disso:

Envie um relato privado através da aba **[Security Advisories](https://github.com/SenacOS/.github/security/advisories/new)** do repositório afetado (ou deste repositório, caso não tenha certeza de onde reportar). Esse é atualmente o **único canal oficial** para relatos de segurança da SenacOS — não há outro meio de contato disponível para esse fim.

Ao reportar, inclua o máximo de informações possível:

- Descrição da vulnerabilidade e seu impacto potencial.
- Passos para reproduzir o problema (proof of concept, se possível).
- Versão, branch ou commit afetado.
- Qualquer sugestão de mitigação ou correção, se já tiver alguma ideia.

## O que Esperar

- **Confirmação de recebimento:** faremos o possível para confirmar o recebimento do seu relato em até alguns dias úteis.
- **Análise:** a equipe mantenedora vai avaliar a severidade e validar a vulnerabilidade.
- **Correção:** vulnerabilidades confirmadas serão corrigidas com prioridade, seguindo o fluxo normal de PRs, mas com revisão acelerada.
- **Divulgação:** após a correção, poderemos publicar um aviso de segurança (Security Advisory) descrevendo o problema e a solução, dando o devido crédito a quem reportou — a menos que você prefira permanecer anônimo.

## Escopo

Esta política cobre os repositórios sob a organização [SenacOS](https://github.com/SenacOS). Vulnerabilidades em dependências de terceiros devem ser reportadas diretamente aos mantenedores dessas dependências, mas fique à vontade para nos avisar também, caso afete algum projeto nosso diretamente.

## Boas Práticas para Quem Reporta

- Aja de boa-fé: evite acessar, modificar ou destruir dados que não sejam seus durante a investigação.
- Não explore a vulnerabilidade além do necessário para comprová-la.
- Dê tempo razoável para que a correção seja aplicada antes de divulgar publicamente o problema.

---

Obrigado por ajudar a manter a SenacOS e sua comunidade seguras! 🙏
