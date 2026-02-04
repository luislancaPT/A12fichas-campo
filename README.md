# 📋 Fichas de Campo - Neuroarquitectura

**App PWA para recolha de dados em campo que funciona 100% offline**

## ✅ Funcionalidades

- ✅ Funciona **offline** após primeira visita
- ✅ Guarda dados **localmente** no iPad/tablet
- ✅ Múltiplas fichas para diferentes espaços
- ✅ Continuar trabalho em momentos diferentes
- ✅ Exportar quando tiver rede (JSON, CSV, copiar para Sheets)
- ✅ Backup e restauro de dados
- ✅ Indicador de fichas pendentes de exportar

---

## 🚀 Como Hospedar GRATUITAMENTE (GitHub Pages)

### Passo 1: Criar conta GitHub (se não tiver)
1. Vá a https://github.com
2. Clique em "Sign up"
3. Crie uma conta gratuita

### Passo 2: Criar repositório
1. Clique no "+" no canto superior direito
2. Selecione "New repository"
3. Nome: `fichas-campo` (ou outro nome)
4. Marque "Public"
5. Clique "Create repository"

### Passo 3: Fazer upload dos ficheiros
1. Na página do repositório, clique "uploading an existing file"
2. Arraste TODOS estes ficheiros:
   - `index.html`
   - `sw.js`
   - `manifest.json`
   - `icon-192.png`
   - `icon-512.png`
3. Clique "Commit changes"

### Passo 4: Ativar GitHub Pages
1. Vá a "Settings" (configurações do repositório)
2. No menu lateral, clique "Pages"
3. Em "Source", selecione "Deploy from a branch"
4. Em "Branch", selecione "main" e "/ (root)"
5. Clique "Save"

### Passo 5: Aguardar (1-2 minutos)
- O GitHub vai publicar o seu site
- O URL será: `https://SEU-USUARIO.github.io/fichas-campo/`

---

## 📱 Como Usar no iPad

### Primeira vez (precisa de rede):
1. Abra o Safari no iPad
2. Vá ao URL: `https://seu-usuario.github.io/fichas-campo/`
3. Aguarde carregar completamente
4. Toque no ícone de partilha (quadrado com seta para cima)
5. Deslize para baixo e toque em **"Adicionar ao Ecrã Principal"**
6. Dê um nome e toque "Adicionar"

### Usar offline:
1. Toque no ícone no ecrã principal
2. A app funciona mesmo sem internet!
3. Todos os dados são guardados localmente

### Exportar dados (quando tiver rede):
1. Vá ao separador 💾 ou toque em "📤 Exportar"
2. Opções:
   - **Copiar para Google Sheets**: Copia dados em formato tabela
   - **JSON**: Ficheiro de backup completo
   - **CSV**: Ficheiro para Excel/Google Sheets

---

## 🔄 Fluxo de Trabalho Recomendado

1. **No início do dia (com rede)**:
   - Abra a app e confirme que está tudo OK

2. **No campo (sem rede)**:
   - Crie fichas para cada espaço
   - Preencha os dados
   - A app guarda automaticamente

3. **No fim do dia (com rede)**:
   - Vá a "📤 Exportar"
   - Exporte JSON como backup
   - Copie para Google Sheets se quiser
   - As fichas ficam marcadas como "exportadas" ✓

---

## 📊 Importar para Google Sheets

1. Na app, toque "📋 Copiar Tudo"
2. Toque na caixa de texto
3. Selecione tudo (toque longo → "Selecionar tudo")
4. Copie
5. Abra Google Sheets
6. Cole na célula A1
7. Os dados aparecem organizados em colunas!

---

## 💾 Backup e Restauro

### Fazer backup:
1. Exportar → JSON (backup)
2. Guarde o ficheiro no iCloud/Google Drive

### Restaurar:
1. Exportar → Importar Backup
2. Selecione o ficheiro JSON
3. As fichas são adicionadas

---

## ⚠️ Notas Importantes

- Os dados ficam guardados **no browser** (localStorage)
- Se limpar os dados do Safari, **perde as fichas**
- Faça backups regulares!
- A app funciona melhor no **Safari** no iPad

---

## 📁 Ficheiros Incluídos

| Ficheiro | Descrição |
|----------|-----------|
| `index.html` | App principal |
| `sw.js` | Service Worker (permite offline) |
| `manifest.json` | Configuração PWA |
| `icon-192.png` | Ícone pequeno |
| `icon-512.png` | Ícone grande |

---

## 🆘 Problemas Comuns

**A app não funciona offline:**
- Certifique-se que abriu via Safari (não Chrome)
- Visite a página pelo menos uma vez com rede
- Adicione ao ecrã principal

**Perdi os dados:**
- Verifique se tem backup JSON
- Use "Importar Backup" para restaurar

**Não consigo adicionar ao ecrã:**
- Tem de usar Safari
- O botão está em Partilhar → Adicionar ao Ecrã Principal

---

Desenvolvido para o Máster de Neuroarquitectura - Universidad de Alicante
