# 📤 Instruções para Subir Conteúdo para GitHub

## 🚀 **Passos para Subir o Conteúdo de Inglês**

### **1. Preparar o Repositório Local**

```bash
# Navegar para a pasta do projeto
cd /Users/imac/planode-estudos

# Inicializar git (se ainda não foi feito)
git init

# Adicionar o repositório remoto
git remote add origin https://github.com/pimenta1402/planode-estudos.git

# Verificar se o remote foi adicionado
git remote -v
```

### **2. Adicionar e Commitar os Arquivos**

```bash
# Adicionar todos os arquivos da pasta Inglês
git add Ingles/

# Verificar o status
git status

# Fazer commit com mensagem descritiva
git commit -m "📚 Adicionar plano de estudos completo de Inglês 2º EM

- Plano de estudo estruturado com cronograma de 2 semanas
- 5 provas simuladas com 50 questões no total
- Explicações detalhadas para cada resposta
- Foco na ementa: Present Perfect, Future Forms, Question Tags, First Conditional
- Sistema de pontuação e dicas de estudo
- README completo com instruções de uso"
```

### **3. Subir para o GitHub**

```bash
# Fazer push para o repositório remoto
git push -u origin main

# Se der erro de branch, use:
git branch -M main
git push -u origin main
```

### **4. Verificar no GitHub**

1. Acesse: https://github.com/pimenta1402/planode-estudos
2. Verifique se a pasta `Ingles/` foi criada
3. Confirme se todos os arquivos estão presentes:
   - `README.md`
   - `PLANO_DE_ESTUDO_INGLES.md`
   - `PROVA_1_PRESENT_PERFECT_FUTURE.md`
   - `PROVA_2_QUESTION_TAGS_CONDITIONALS.md`
   - `PROVA_3_MIXED_GRAMMAR.md`
   - `PROVA_4_ADVANCED_GRAMMAR.md`
   - `PROVA_5_COMPREHENSIVE_REVIEW.md`

## 📁 **Estrutura de Arquivos no GitHub**

```
planode-estudos/
├── Ingles/
│   ├── README.md
│   ├── PLANO_DE_ESTUDO_INGLES.md
│   ├── PROVA_1_PRESENT_PERFECT_FUTURE.md
│   ├── PROVA_2_QUESTION_TAGS_CONDITIONALS.md
│   ├── PROVA_3_MIXED_GRAMMAR.md
│   ├── PROVA_4_ADVANCED_GRAMMAR.md
│   ├── PROVA_5_COMPREHENSIVE_REVIEW.md
│   └── INSTRUCOES_GITHUB_INGLES.md
├── LPL/
└── README.md
```

## 🔧 **Comandos Alternativos (se necessário)**

### **Se houver conflitos:**
```bash
# Puxar mudanças do repositório remoto
git pull origin main

# Resolver conflitos manualmente
# Depois fazer commit novamente
git add .
git commit -m "Resolve conflicts"
git push origin main
```

### **Se quiser forçar o push:**
```bash
git push -f origin main
```

### **Para atualizar o README principal:**
```bash
# Editar o README.md principal para incluir a seção de Inglês
# Depois fazer commit
git add README.md
git commit -m "📝 Atualizar README principal com seção de Inglês"
git push origin main
```

## ✅ **Checklist de Verificação**

- [ ] Pasta `Ingles/` criada no repositório
- [ ] Todos os 7 arquivos .md enviados
- [ ] README.md da pasta Inglês visível
- [ ] Estrutura de pastas organizada
- [ ] Links funcionando corretamente
- [ ] Conteúdo formatado corretamente

## 🎯 **Próximos Passos**

1. **Testar os links** no GitHub
2. **Verificar a formatação** Markdown
3. **Atualizar o README principal** se necessário
4. **Compartilhar o link** do repositório
5. **Começar os estudos** seguindo o plano!

---

**Tudo pronto para subir! 🚀📚**
