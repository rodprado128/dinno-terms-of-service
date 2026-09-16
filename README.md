# Dinno App — Termos de Serviço

Página única e estática com os termos de serviço do **Dinno App**, o aplicativo
de mesada gamificada.

**Publicada em:** <https://rodprado128.github.io/dinno-terms-of-service/>

## Como funciona

HTML + CSS puro, um arquivo só (`index.html`), com o CSS embutido no `<style>`.
Sem framework, sem build, sem JavaScript e **sem nenhuma requisição externa** —
nem fonte de CDN, para a página carregar em qualquer conexão e não depender de
terceiro nenhum.

```
index.html      a página inteira (conteúdo + estilo)
assets/         logo, favicons e o cartão de compartilhamento
robots.txt      libera a indexação e aponta o sitemap
sitemap.xml     a única URL deste site
```

As cores são os tokens reais do app (`app/globals.css`, tema claro). Aqui o
acento é o dourado do Starcoin (`#7a5a00`), porque o documento fala de dinheiro
e de moeda virtual; a política de privacidade usa o roxo da marca. São duas
páginas irmãs, não iguais.

## Publicar de novo

O GitHub Pages serve a raiz da branch `main`. Publicar é empurrar:

```bash
git add -A
git commit -m "..."
git push
```

O Pages reconstrói sozinho em um ou dois minutos.

## Valores do controlador

Os dois campos que nasceram como marcador — razão social/CNPJ e e-mail de
contato — **já estão preenchidos**: Rodrigo Prado da Silva e
<rodrigo@forjadev.app.br>. O destaque amarelo de "falta preencher" saiu junto,
porque destacar um dado real como se fosse pendência confunde quem lê. Se algum
deles mudar, procure pelo valor no `index.html`.

## O que estes termos prometem

Só o que o app faz hoje. Em particular:

- **o Starcoin é moeda virtual interna**, sem valor monetário direto fora do app;
- **o Dinno App não movimenta dinheiro**: o saque é um registro, e o pagamento
  real acontece fora, entre responsável e criança;
- **a assinatura paga ainda não foi lançada** — o item 4 descreve o que valerá
  quando for, e precisa ser revisto antes da primeira cobrança.

Qualquer texto novo aqui tem de continuar respeitando isso.

## Aviso

O conteúdo é um rascunho técnico escrito a partir do funcionamento real do
produto. **Não substitui revisão jurídica**, especialmente por envolver dados de
criança e cobrança futura por assinatura.

## Relacionado

- [Política de Privacidade](https://rodprado128.github.io/dinno-privacy-policy/)
- [Site do Dinno](https://dinnoapp.forjadev.app.br/)
