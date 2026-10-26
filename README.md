# Comercial Agro Bardin

Link do relatório de Produção e Venda da Agro Bardin para o celular.

O `index.html` traz o relatório **criptografado** (AES-256-GCM, com chave derivada da senha da equipe por PBKDF2-SHA256, 600 mil iterações). Sem a senha, nenhum dado da empresa pode ser lido. O arquivo é gerado pelo botão **Gerar link do celular**, na versão do administrador do app.

Para atualizar: gere um novo `index.html` na versão do administrador, com a mesma senha, e envie para este repositório (Add file → Upload files → Commit changes).
