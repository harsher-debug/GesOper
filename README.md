# GesOper — demonstração revisada

Site estático em português, sem build. Abra index.html ou publique a pasta na Vercel.

## Revisão solicitada
- Logo oficial e favicon originais baixados do site GesOper, sem recoloração ou redesenho.
- Paleta azul-marinho e ocre coordenada à marca.
- Composição inspirada no Linea / 8B: fotografia ampla na abertura, navegação arredondada, tipografia Host Grotesk, faixas claras e escuras e animações sutis.
- Removidos painel fictício, métricas numéricas e numeração de cards/etapas. O algarismo do nome oficial 4Sup foi preservado.
- Duas imagens institucionais geradas pela ferramenta nativa image_gen, identificadas como ilustrativas. Prompts completos em IMAGE-PROMPTS.md.
- Fonte e imagens locais, sem dependências remotas para renderização.

## Publicar na Vercel
Importe o repositório da pasta na Vercel. Framework: Other. Sem comando de build ou instalação. Output Directory: ponto (.). O vercel.json já configura a saída.

Alternativa com Node.js instalado, nesta pasta:

```powershell
npx vercel login
npx vercel --prod
```

A publicação ainda depende do login do proprietário. Não foi feita implantação nem alteração no domínio oficial.

## Apresentação
Abra a página inicial, apresente a identidade preservada e a organização do conteúdo. Explore os filtros e os detalhes dos módulos, depois segmentos e implantação. Finalize no contato.

O formulário valida os campos e prepara uma mensagem no aplicativo de e-mail do visitante. Não há backend de leads nem envio automático. O site é uma demonstração e está marcado noindex.

## Validação
JavaScript sem erros de sintaxe. Recursos locais com HTTP 200. Filtro Pessoas, modal e menu móvel verificados. Largura conferida em desktop (1280) e celular (390), sem rolagem horizontal. Links internos resolvidos e imagens sem erro de carregamento. Nenhum e-mail real enviado.

## Arquivos
index.html, style.css, app.js, assets/, robots.txt e vercel.json compõem o site. A pasta reference contém materiais de referência e backup da primeira versão, excluídos da publicação. A referência Linea serviu de modelo visual; não foram importados textos, avaliações ou funcionalidades do aplicativo de legendagem.
