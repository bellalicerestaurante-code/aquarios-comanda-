# Comanda Aquarius - Versão 1 (Protótipo)
**Conteúdo:** projeto React + Vite pronto para deploy no Vercel.

## Instruções rápidas para subir no Vercel
1. Baixe e extraia o arquivo `comanda_aquarius_v1.zip`.
2. (Opcional) Ajuste `package.json` se necessário.
3. No Vercel, crie um novo projeto e faça upload do diretório do projeto ou conecte a um repositório Git.
4. O Vercel detecta Vite automaticamente. Use os comandos:
   - Build command: `npm run build`
   - Output directory: `dist`
5. Deploy concluído → acesse `https://<seu-projeto>.vercel.app` (pode renomear para `comanda-aquarius` se disponível).

## O que está incluído
- Mesas 1/2/3 (botões lado a lado)
- Cardápio organizado em categorias (Porções, Batidas, Refrigerantes, Cervejas, Águas)
- Itens fictícios com preços em R$
- Adicionar/remover/editar quantidade de itens
- Mesa aberta/fechada (verde/cinza)
- Fechar mesa → 10% embutido automaticamente
- Recibo centralizado com título "Comanda Aquarius" e total em negrito
- Botão "Imprimir/Salvar PDF" (usa janela de impressão do navegador)
- Textos em pt-BR
