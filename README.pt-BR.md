[🇺🇸 English](README.md) · 🇧🇷 Português

# clone-tabnews

Projeto pessoal de estudo: recriar o [TabNews](https://www.tabnews.com.br) do zero acompanhando o curso [curso.dev](https://curso.dev).

## Contexto

O [TabNews](https://github.com/filipedeschamps/tabnews.com.br) é uma comunidade de código aberto criada por Filipe Deschamps e colaboradores, e o [curso.dev](https://curso.dev), do Filipe Deschamps, ensina a construí-lo passo a passo. **Todo o crédito pela ideia, pelo produto e pelo curso é deles.** Este repositório é apenas o meu código escrito durante o curso; não tem vínculo com o TabNews nem com o curso.dev.

> **Status: fase inicial.** Por enquanto existem só a configuração inicial do Next.js e uma página provisória.

## O que tem aqui

| Caminho | Conteúdo |
| --- | --- |
| `package.json` | Next.js 15, React 18 e React DOM 18; script `dev` (`next dev`) |
| `pages/index.js` | Arquivo da página inicial, ainda vazio |
| `pages/products/index.js` | Página provisória que mostra "Produtos — Página de produtos em desenvolvimento." |
| `.gitignore` | Existe, mas ainda está vazio |
| `LICENSE` | MIT |

## Como rodar

Requisitos: Node.js 18.18 ou mais recente e npm.

```bash
npm install
npm run dev
```

Depois abra <http://localhost:3000/products>.

Observação: `pages/index.js` está vazio, então a página inicial (`/`) mostra um erro do Next.js até exportar um componente React. O `npm test` é o placeholder padrão do npm e só termina com erro.

## O que aprendi / próximos passos

- Montar um projeto Next.js manualmente (`npm init`, instalar `next`, `react` e `react-dom`) e entender como a pasta `pages/` vira rotas.
- Próximo: criar o componente da página inicial em `pages/index.js`.
- Próximo: preencher o `.gitignore` (no mínimo `node_modules/` e `.next/`) antes de novos commits.
- Próximo: seguir os módulos do curso e fazer commits menores e mais frequentes.

## Feedback e contribuições são bem-vindos

É um repositório de estudo, então feedback é muito bem-vindo. Abra uma issue com sugestões, dúvidas ou correções, ou mande um pull request pequeno (por exemplo, ajustes de configuração ou documentação mais clara). Se você procura o projeto de verdade, contribua com o próprio [TabNews](https://github.com/filipedeschamps/tabnews.com.br).

## Licença

[MIT](LICENSE) © Yago Macambira
