# 💡 Ideia: Kies — cofre de chaves

> Este repositório é uma **ideia em validação**. Mapa completo de todas as ideias: [IDEIAS.md no repo `dev`](https://github.com/cantsixsix/dev/blob/claude/serene-bardeen-1tjfw2/IDEIAS.md).
>
> Estágios: 💡 ideia · 🧪 protótipo · 🚀 no ar · ✅ validada · 🗄️ arquivada.
> Regra: antes de escrever mais código, rodar o **teste** de uma variação. Sem reação em 2 semanas → 🗄️.

## P3 · Kies — cofre de chaves — `kies` 💡

- **P3.a CLI de `.env`** — guarda chaves por projeto e injeta no `.env` local (resolveria o problema de chaves vazadas que você mesmo teve). *Teste:* usar nos seus próprios repos por 2 semanas.
- **P3.b Scanner de segredos** — avisa antes do commit se tem keystore/`.env`/chave de API. *Teste:* hook de pre-commit open source.
- **P3.c Cofre de senhas pessoal** — gerenciador de senhas simples. *Teste:* pesquisa: por que não usam Bitwarden?
- **P3.d Rotação de chaves** — lembrete/automação para trocar chaves de API periodicamente.

Por que agora: chaves e keystores já vazaram em repos públicos desta conta (`dev`, `mistico`, `voxel`). P3.a e P3.b resolveriam o seu próprio problema primeiro — melhor primeiro cliente possível.
