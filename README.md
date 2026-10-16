# ORYX Backup — GitHub Pages

Este repositório contém **somente páginas públicas informativas** para o consentimento OAuth da integração privada ORYX Backup. **Não publicar** `rclone.conf`, tokens, senhas, arquivos `.pgcustom`, certificados com chaves privadas, manifestos sensíveis ou backups reais.

## Configuração do GitHub Pages

1. Acessar **Settings → Pages → Build and deployment** neste repositório.
2. Selecionar **Deploy from a branch**, branch **main**, diretório **/(root)** e salvar.
3. Conferir, após a publicação, os dois links:
   - Página inicial: https://gamereverson.github.io/
   - Política de Privacidade: https://gamereverson.github.io/privacidade.html
4. Criar uma propriedade no [Google Search Console](https://search.google.com/search-console) por prefixo de URL e seguir a comprovação solicitada pela interface. Não presumir aprovação automática do domínio `github.io`; ele pode ser bloqueado como domínio multi-inquilino.
5. Somente **se o Google aceitar a verificação de domínio e exigir estes endereços**, preencher os campos de Branding do projeto Google Cloud **ORYX Backup**. Nunca utilizar um domínio alheio ou afirmar propriedade de `github.io`.
6. Confirmar que o único escopo OAuth do Drive é `https://www.googleapis.com/auth/drive.file` antes de qualquer mudança de Testing para In production.
7. Após publicação OAuth legítima, autorizar novamente o rclone e comprovar leitura/restauração dos snapshots existentes. Não divulgar os segredos ou tokens.

> A política publicada descreve a fase atual de testes com dados fictícios. Atualizar antes de usar dados de clientes reais. O backup real do Supabase, a validação de Auth/Storage/Edge e a restauração isolada continuam **em HOLD**, sob aprovação operacional específica.

Publicar estas páginas **não publica o SaaS ORYX nem o conteúdo do Google Drive**.
