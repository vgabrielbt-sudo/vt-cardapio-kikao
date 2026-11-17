# VT Cardápio — Kikão (demonstração)

Demonstração estática de cardápio digital, pensada para apresentar a centralização dos canais de atendimento e o fluxo de montagem de pedidos.

## Publicar na Vercel
1. Importe este repositório na Vercel.
2. Framework Preset: **Other**.
3. Build Command: deixe vazio.
4. Output Directory: `.`
5. Deploy.

## Antes de apresentar como projeto oficial
- Esta versão é uma demonstração. Os produtos, descrições, imagens e preços são ilustrativos.
- Confirme com o estabelecimento a marca, cardápio, preços, fotos, endereço e canais oficiais.
- No fim de `index.html`, edite o objeto `CONFIG`:
  - `whatsapp`: número oficial com código do país e DDD, somente dígitos (ex.: 55 + DDD + número).
  - `deliveryUrl`: reservado para o link do delivery próprio; atualizar o botão quando o link oficial for fornecido.
- O botão do iFood está direcionado ao site geral do iFood nesta demonstração; substituir pelo link correto da loja.
- O link de localização usa uma busca por “Kikão Lajeado RS”; confirmar o endereço oficial.

## Recursos incluídos
- Layout responsivo, priorizando celular.
- Filtros por categoria.
- Carrinho com quantidades e total.
- Resumo de pedido com nome e observações.
- Atalho de WhatsApp configurável.
- Links de acesso aos canais externos.

Feito para a VT Sites.