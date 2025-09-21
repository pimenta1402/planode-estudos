# 🚀 Instruções para Conectar com GitHub

## ✅ **Status Atual**
- ✅ Repositório Git local inicializado
- ✅ Todos os arquivos commitados
- ✅ README.md criado

## 📋 **Próximos Passos**

### 1. **Criar Repositório no GitHub**
1. Acesse [github.com](https://github.com)
2. Faça login na sua conta **pimenta1402**
3. Clique em **"New repository"** (botão verde)
4. Nome do repositório: `plano-estudos-lpl`
5. Descrição: `Plano de Estudos LPL - Língua Portuguesa e Literatura com exercícios e provas`
6. Marque como **Public**
7. **NÃO** marque "Add a README file" (já temos um)
8. Clique em **"Create repository"**

### 2. **Conectar Repositório Local com GitHub**
Execute os seguintes comandos no terminal (PowerShell):

```bash
# Adicionar o repositório remoto
git remote add origin https://github.com/pimenta1402/plano-estudos-lpl.git

# Renomear branch principal para main (se necessário)
git branch -M main

# Fazer push do conteúdo
git push -u origin main
```

### 3. **Verificar Upload**
- Acesse: https://github.com/pimenta1402/plano-estudos-lpl
- Verifique se todos os arquivos foram enviados
- Confirme se o README.md está sendo exibido

## 📁 **Estrutura do Repositório**

```
plano-estudos-lpl/
├── README.md
├── INSTRUCOES_GITHUB.md
└── LPL/
    ├── PLANO_DE_ESTUDO_LPL.md
    ├── PROVA_1_GRAMATICA_SUBSTANTIVO_ADJETIVO.md
    ├── PROVA_2_LITERATURA_REALISMO_NATURALISMO.md
    ├── PROVA_3_MISTA_GRAMATICA_LITERATURA.md
    └── [materiais PDF...]
```

## 🔄 **Comandos Git Úteis**

```bash
# Ver status dos arquivos
git status

# Adicionar arquivos modificados
git add .

# Fazer commit
git commit -m "Descrição da alteração"

# Enviar para GitHub
git push

# Baixar atualizações
git pull
```

## 🎯 **Objetivo Alcançado**
- ✅ Repositório local configurado
- ✅ Conteúdo organizado e commitado
- ✅ README.md profissional criado
- ✅ Instruções para upload no GitHub

---

**Pronto! Siga as instruções acima para conectar com sua conta GitHub pimenta1402.**
