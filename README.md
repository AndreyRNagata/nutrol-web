# nutrol-web

Site estático do Nutrol, publicado na Vercel: página inicial, Política de Privacidade,
Termos de Uso e Excluir conta (URLs exigidas pela App Store e pelo Google Play).

- `/privacidade`, `/termos`, `/excluir-conta`: `cleanUrls` no `vercel.json` serve os `.html` sem extensão.
- Sem build: na Vercel, framework "Other", sem comando de build, saída na raiz.

Para ver localmente:

```bash
npx serve .
```
