# 🔐 Política de Segurança

Este repositório contém configurações pessoais para ambientes Bash. Embora seja voltado ao uso individual, boas práticas de segurança são aplicadas e documentadas abaixo.

---

## 🔏 Commits Assinados (GPG)

Todos os commits deste repositório são assinados com GPG:

- 🆔 Chave pública: `9FD1479F341442C2`
- 🔐 Assinatura está ativada localmente
- ✅ GitHub exibe `Verified` ao lado dos commits válidos

---

## 🛡️ Hook de Segurança (Pre-commit)

Este repositório possui um hook de pre-commit com validação customizada:

- 🚫 Bloqueia commits contendo o domínio corporativo
- ✅ Protege contra vazamento de e-mails corporativos em arquivos públicos
- 📄 Local: `.git/hooks/pre-commit`

---

## ⚠️ Escopo

Este repositório é **pessoal**, mas segue princípios corporativos de segurança:

- Histórico autenticado
- Validações anti-leak
- Estrutura padronizada por ambiente

---

## 📫 Relatar Problemas

Este repositório é mantido por [@rtsantanna](https://github.com/rtsantanna).  
Em caso de sugestões ou problemas de segurança, abra um _issue_ ou envie um _pull request_.

---

## 📝 Licença

Este repositório está sob a Licença MIT.  
Consulte o arquivo [LICENSE](./LICENSE) para mais informações.
