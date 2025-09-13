# Paleta de Cores ARIA

Projeto simples em HTML/CSS com uma paleta de cores harmoniosa e elementos semânticos, incluindo dicas de acessibilidade (ARIA). Ideal para usar como base ou inspiração em pequenos sites e protótipos.

## ✨ Destaques
- Paleta harmoniosa: primária (azul), secundária (teal) e acento (coral)
- Modo claro/escuro com toggle e persistência em `localStorage`
- Estrutura semântica: `header`, `section`, `aside`, `footer`
- Componentes prontos: botões (primário, secundário, contorno) e links
- Variáveis CSS centralizadas em `:root` para fácil personalização
- Navegação com `aria-label` e foco em contraste legível

## 🧪 Visualizar
- Demo (GitHub Pages): https://matheussiqueirahub.github.io/paleta_de_cores_aria/
- Local: abra o arquivo `index.html` diretamente no navegador.

### Modo escuro
- Use o botão no topo (🌙/☀️) para alternar entre claro e escuro.
- A preferência fica salva e respeita o `prefers-color-scheme` do sistema.

> Dica: use uma extensão como “Live Server” (VS Code) para recarregar automaticamente ao salvar.

## 🎨 Paleta de cores (padrão)
- Primária: `#3A7BD5`
- Primária 700: `#2C5FA8`
- Secundária: `#2EC4B6`
- Secundária 700: `#219E92`
- Acento: `#FF6B6B`
- Fundo: `#F7FAFF`
- Superfície: `#FFFFFF`
- Texto: `#1F2A44`
- Texto secundário: `#5B6477`
- Borda: `#E2E8F0`

Para ajustar, edite as variáveis no bloco `:root` em `index.html`.

## 📁 Estrutura
- `index.html`: página com layout, componentes e estilos embutidos
- `README.md`: este guia

## 🔎 Acessibilidade
- Navegação principal com `aria-label="principal"`
- Contraste pensado para leitura confortável em fundo claro
- Utilize o acento com moderação para manter legibilidade

## 🚀 Como começar
1. Clone o repositório
   ```bash
   git clone https://github.com/matheussiqueirahub/paleta_de_cores_aria.git
   cd paleta_de_cores_aria
   ```
2. Abra `index.html` no navegador
3. Personalize as cores no seletor `:root`

## ✅ Checklist de qualidade
- [x] HTML semântico básico
- [x] Paleta consistente via CSS vars
- [x] Componentes interativos (botões/links)
- [x] Dicas ARIA na navegação
- [x] Modo escuro com toggle e persistência

---
Se quiser, posso incluir um screenshot em `docs/preview.png` assim que o Pages estiver online (ou gerar via ação do GitHub). 

---
Se quiser, posso gerar uma variação em “modo escuro” e alternância automática no mesmo arquivo.
