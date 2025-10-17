# Página Bloqueada — PJC/MT

Página institucional que comunica o **bloqueio de acesso a um domínio por ordem judicial**, por tempo indeterminado.
Layout **responsivo**, tipografia fluida e identidade visual da **Polícia Judiciária Civil de Mato Grosso**.

> **Descrição curta (SEO):** Página institucional da Polícia Judiciária Civil de Mato Grosso que comunica o bloqueio de acesso a um domínio por ordem judicial, por tempo indeterminado. Layout responsivo, identidade visual oficial e destaque para o status “Página Bloqueada”.

---

## ✨ Destaques

* HTML e CSS **puros** (sem frameworks).
* **Mobile-first** com `clamp()` para fontes e espaçamentos.
* Moldura com `quadro_fundo.svg` e frames decorativos.
* Header (logo + títulos) **sempre centralizado**.
* Bloco central valorizado (efeito “glass” opcional).
* Acessibilidade básica e boa legibilidade sobre o background.

---

## 📁 Estrutura

```
/
├─ index.html
├─ css/
│  └─ style.css
└─ assets/
   ├─ bg-pjc.png
   ├─ pjc_logo.svg
   ├─ quadro_fundo.svg
   ├─ frame1.svg
   ├─ frame2.svg
   ├─ fonts/
   │  └─ rajdhani-medium.ttf
   └─ (favicons gerados)
```

---

## 🚀 Como executar localmente

### Opção 1 — Live Server (VS Code)

1. Instale a extensão **Live Server**.
2. Abra a pasta do projeto no VS Code.
3. Clique em “Go Live” (ou botão direto no status bar).

### Opção 2 — Servidor simples (Python)

```bash
# na raiz do projeto
python3 -m http.server 5500
# abra http://localhost:5500 no navegador
```

---

## 🧩 Personalização rápida

### Textos

Edite no `index.html`:

```html
<p>O ACESSO A ESTE DOMÍNIO FOI</p>
<p>BLOQUEADO POR ORDEM JUDICIAL</p>
<p>POR TEMPO INDETERMINADO</p>
```

### Cores e escalas

Ajuste variáveis no `:root` do `css/style.css`:

```css
:root{
  --brand: #eca625;
  --text: #ffffff;
  --container-w: min(1100px, 100% - 2rem);
}
```

### Moldura no mobile

Para remover/mostrar moldura em telas pequenas, veja o breakpoint `@media (max-width: 520px)` no CSS.

---

## 📱 Responsividade

Breakpoints principais:

* `1200px`, `992px`, `768px`, `520px`
  O layout é fluido; fontes e paddings usam `clamp()` para manter proporções.


## 🛠️ Desenvolvimento

* Sem build tooling. Apenas HTML/CSS estático.
* SVGs preferidos para ícones (nítidos em qualquer DPI).

---

## 📌 Roadmap (opcional)

* [ ] Adicionar versão “alto contraste”.
* [ ] Internacionalização (pt-BR / en-US).
* [ ] Testes de acessibilidade (Lighthouse/axe).

---

## 📜 Licença

Defina a licença conforme a política da instituição (uso governamental).

---

## 👤 Créditos

Desenvolvimento: **Jackson Luiz Domingos Silva**
Design e ajustes responsivos: colaboração com **Everton Kunz**
