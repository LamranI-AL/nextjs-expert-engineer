# 🚀 Guide de Démarrage Rapide

## 📦 Publication NPM

### 1. Configuration Initiale

```bash
# 1. Se connecter à NPM
npm login

# 2. Vérifier la configuration
npm whoami
npm run validate

# 3. Publication automatisée
./scripts/release.sh
```

### 2. Publication Manuelle

```bash
# Mettre à jour la version
npm version patch  # ou minor/major

# Publier
npm publish --access public
```

## 🤖 Intégration Claude Code

### Installation pour Utilisateurs

#### Méthode 1: NPM (Recommandée)
```bash
npm install -g nextjs-expert-engineer

# Dans votre projet Next.js
cd mon-projet-nextjs
nextjs-expert-engineer init
```

#### Méthode 2: Claude Code Direct
```bash
# Installation directe
claude-code install nextjs-expert-engineer

# Utilisation immédiate
/audit Mon projet Next.js
/advanced-audit Analyse complète
```

#### Méthode 3: Configuration Manuelle
```bash
# Dans votre projet
mkdir -p .claude/agents
mkdir -p .claude/commands

# Copier les fichiers de l'agent
cp .claude/agents/nextjs-expert-engineer.md votre-projet/.claude/agents/
cp .claude/commands/*.md votre-projet/.claude/commands/
```

### Configuration Projet

```json
// .claude/config.json
{
  "agents": ["nextjs-expert-engineer"],
  "nextjs-expert": {
    "auditLevel": "advanced",
    "autoDetect": true,
    "frameworks": ["tailwind", "prisma"]
  }
}
```

## 🎯 Utilisation Immédiate

### Commandes de Base

```bash
# Aide générale
"Help me implement Server Actions with validation"

# Audit standard
/audit Mon app Next.js a des problèmes de performance

# Audit avancé
/advanced-audit Analyse sécurité et performance pour production
```

### Cas d'Usage Courants

```bash
# Migration
"Help me migrate from Pages Router to App Router"

# Optimisation
"Optimize my dashboard for Core Web Vitals"

# Sécurité
"Review my authentication implementation"

# Architecture
"Help me structure my Next.js 15 app with best practices"
```

## 📚 Documentation Rapide

- **Installation**: `npm install -g nextjs-expert-engineer`
- **Init Projet**: `nextjs-expert-engineer init`
- **Audit**: `/audit` ou `/advanced-audit`
- **Configuration**: `.claude/config.json`

## 🔗 Liens Utiles

- **NPM**: `https://npmjs.com/package/nextjs-expert-engineer`
- **Docs**: Voir README.md et docs/
- **Support**: GitHub Issues

---

**Prêt en 2 minutes ! 🚀**