# ALL Vistorias — como publicar e usar

Aplicativo web instalável (PWA) para vistorias de campo. **Não depende do Claude nem de servidor próprio**: depois de publicado, funciona no celular, inclusive sem internet. Os dados ficam no próprio aparelho.

## 1. Publicar (uma vez, ~5 minutos, grátis)
O celular só libera câmera e GPS em endereço seguro (https), por isso a pasta precisa ficar hospedada. Escolha uma opção:

- **Netlify Drop (mais simples):** acesse app.netlify.com/drop, arraste a pasta `app-vistoria` inteira e anote o endereço gerado (ex.: `https://all-vistorias.netlify.app`).
- **GitHub Pages ou Cloudflare Pages:** suba o conteúdo da pasta em um repositório e ative o Pages.
- **Domínio da ALL:** copie a pasta para o servidor do site (ex.: `vistoria.allengenharia.com.br`).

## 2. Instalar no celular
- **Android (Chrome):** abra o endereço → menu ⋮ → *Instalar app*.
- **iPhone (Safari):** abra o endereço → Compartilhar → *Adicionar à Tela de Início*.
Abra uma vez com internet; depois disso funciona offline. Permita **Câmera/Fotos** e **Localização** quando pedir.

## 3. Primeiro uso
1. **Ajustes:** confira empresa, responsável técnico (preencha o **CREA**), seu nome e, se quiser, o PIN do painel.
2. **Obras → + Obra → + Nova vistoria.**
3. Aba **Fotos → Tirar foto:** cada foto guarda data/hora e GPS do momento do registro (também gravados na imagem). Escreva a descrição de cada foto.
4. **Constatações:** achados com gravidade, recomendação e fotos relacionadas. **Conclusão:** parecer e recomendações.
5. **Emitir:** Memorial de Vistoria Técnica, Memorial Fotográfico e **Relatório Consolidado** (os dois em um único documento, sem repetir capa e cabeçalho) em **Word e PDF**, com logo, cores, cabeçalho e rodapé da ALL. Use "Compartilhar" para enviar por WhatsApp/e-mail.

## 4. Painel administrativo (aba Painel)
Indicadores, filtros por obra, local, situação e período, agrupamento por obra ou por local visitado, registro de emissões (número VT/MF, revisão, formato, data, emissor) e exportação em CSV. Emissão oficial gera numeração sequencial (VT-001/2026) e controla revisões; sem marcar "oficial" sai um rascunho com marca d'água, sem registro.

## 5. Vários celulares / equipe
Cada aparelho guarda seus próprios dados. Para consolidar: em **Ajustes → Exportar tudo**, envie o arquivo `.json` ao administrador e, no aparelho dele, **Importar backup** (os dados são mesclados, nada é apagado). Faça backup periodicamente: se o app for desinstalado ou os dados do navegador forem limpos, o conteúdo local se perde.

## Limitações conhecidas
- A numeração é por aparelho; ao consolidar vários celulares, números podem coincidir. Se isso for um problema, o ideal é uma emissão centralizada pelo administrador ou a futura ligação a um banco em nuvem.
- O PIN do painel é uma barreira simples, não criptografia.
- Fotos importadas da galeria usam a data do arquivo e ficam sem GPS.
