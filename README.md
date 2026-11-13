# 📚 Central de Procedimentos SGP

Base de conhecimento operacional e tutoriais em vídeo para o sistema SGP.

## 🚀 Visão Geral
Aplicação web moderna, leve e responsiva com foco em produtividade, privacidade e conformidade com a LGPD:
- **Zero Dependências:** Construído em HTML5, CSS3 moderno e Vanilla JavaScript.
- **Privacidade Total:** Armazenamento isolado no navegador do usuário via `localStorage`.
- **Validação de Segurança & LGPD:** Pop-up obrigatório antes de salvar qualquer novo procedimento garantindo que foi gravado em base de testes e sem dados sensíveis.
- **Player de Vídeo Embutido (16:9):** Pré-visualização integrada de vídeos Loom, YouTube e Google Drive.
- **Busca Global Instantânea:** Insensível a acentos, com suporte a múltiplos termos e atalho `Ctrl+K`.
- **Ações Rápidas:** Botões padronizados para assistir e copiar link com feedback instantâneo.
- **Smart Merge JSON:** Importação e exportação de backups sem duplicação de links.

---

## 📁 Estrutura do Projeto
- `index.html`: Aplicação web completa com layout em barra lateral, busca e player de vídeo.
- `vercel.json`: Configurações de rotas limpas e segurança para deploy.

---

## 🛠️ Como Executar Localmente
Basta abrir o arquivo `index.html` em qualquer navegador web moderno:
```bash
# Windows
start index.html
```

---

## 🌐 Deploy na Vercel ou GitHub Pages
1. Importe este repositório na **Vercel** como projeto estático.
2. Cada colaborador que acessar o link terá seu próprio espaço de trabalho privado e isolado.
3. Para carregar ou restaurar procedimentos, basta utilizar o botão **"Importar JSON"** com seu arquivo local de backup.
