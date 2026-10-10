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

<!-- validacao:inicio -->

## 🧪 Como validar

Teste de 7 dias. Resultados vão na [Bancada de Ideias](https://claude.ai/artifact/Y4H9MCxyvwwLDmhL812znj).

### P3 · Kies — cofre de chaves

**Em uma frase:** Guarda as chaves de API e senhas dos seus projetos e impede que elas vazem no GitHub.

- **Problema:** Dev iniciante sobe `.env` e keystore para o GitHub sem perceber (aconteceu nesta própria conta). Uma chave vazada pode gerar conta alta na nuvem.
- **Para quem:** Devs solo e iniciantes, quem faz projetos com IA e várias chaves de API.
- **Como funciona:** Um programa de terminal: você salva as chaves uma vez, ele cria o `.env` de cada projeto e bloqueia o commit se tiver segredo.
- **Como ganha dinheiro:** Open source grátis para uso local; R$ 15/mês para sincronizar entre computadores e alertar vazamentos.

| Teste | |
|---|---|
| Tipo | Landing + lista de espera |
| Página | https://validar-ideias.netlify.app/p3/ |
| Onde divulgar | Grupos de dev no Discord/Telegram, r/brdev, LinkedIn |
| Preço testado | R$ 15/mês |
| Meta em 7 dias | **25 inscrições em 7 dias** |

<!-- validacao:fim -->
