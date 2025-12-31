# 🚀 NextJS Expert Engineer Agent

[![npm version](https://badge.fury.io/js/%40claude-agents%2Fnextjs-expert-engineer.svg)](https://badge.fury.io/js/%40claude-agents%2Fnextjs-expert-engineer)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Next.js](https://img.shields.io/badge/Next.js-15+-black?logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5+-blue?logo=typescript)](https://www.typescriptlang.org/)

Expert Next.js development agent with comprehensive audit capabilities for Next.js 15+ applications. Provides professional development assistance, security auditing, performance optimization, and code quality analysis.

## ✨ Features

### 🔍 **Advanced Audit Capabilities**
- **Standard Audit** (`/audit`): Security, Performance, and Code Quality analysis
- **Advanced Audit** (`/advanced-audit`): Comprehensive professional audit with deep analysis
- **Next.js 15+ Compliance**: Latest features and best practices validation
- **Production Readiness**: Deployment strategies and monitoring recommendations

### 🛡️ **Security Analysis**
- Taint APIs implementation
- CSRF protection patterns
- Input validation with Zod schemas
- Authentication security (NextAuth.js v5, Auth.js)
- OWASP Top 10 compliance

### ⚡ **Performance Optimization**
- Partial Prerendering (PPR) analysis
- Advanced caching strategies
- Bundle optimization
- Core Web Vitals optimization
- Image and font loading optimization

### 🏗️ **Code Quality Review**
- SOLID principles compliance
- Component architecture analysis
- TypeScript optimization
- Testing setup recommendations
- Accessibility (WCAG 2.1) validation

## 🚀 Installation

### NPM Installation
```bash
npm install @claude-agents/nextjs-expert-engineer
```

### Yarn Installation
```bash
yarn add @claude-agents/nextjs-expert-engineer
```

### Claude Code Integration
```bash
# Install directly in Claude Code
claude-code install nextjs-expert-engineer
```

## 📖 Usage

### Basic Development Assistance
```
I need to implement a dashboard with server components and proper caching
```

### Standard Audit
```
/audit My Next.js app has performance issues with slow page loads
```

### Advanced Audit
```
/advanced-audit Comprehensive analysis of my e-commerce Next.js application with user authentication and payment processing
```

### Specific Feature Implementation
```
Help me implement Server Actions for form handling with proper validation and error handling
```

## 🎯 Audit Capabilities

### Security Audit
- **Vulnerability Detection**: XSS, CSRF, injection attacks
- **Data Protection**: Sensitive data exposure, secure storage
- **Authentication**: Session management, token security
- **Input Validation**: Server Actions validation, sanitization
- **Environment Security**: Secrets management, configuration

### Performance Audit
- **Core Web Vitals**: LCP, FID, CLS optimization
- **Rendering Strategy**: SSR vs CSR analysis
- **Caching Analysis**: Strategy optimization
- **Bundle Analysis**: Size optimization opportunities
- **Database Queries**: N+1 problem detection

### Code Quality Audit
- **Architecture Review**: Component structure, modularization
- **TypeScript Usage**: Type safety, configuration
- **Best Practices**: Next.js 15+ conventions
- **Testing Strategy**: Coverage and approaches
- **Maintenance**: Code duplication, refactoring opportunities

## 🔧 Configuration

### Project Integration

1. **Add to your Next.js project**:
```json
// .claude/agents.json
{
  "agents": [
    "@claude-agents/nextjs-expert-engineer"
  ]
}
```

2. **Custom Configuration** (Optional):
```json
// .claude/config/nextjs-expert.json
{
  "auditLevel": "advanced",
  "focusAreas": ["security", "performance", "accessibility"],
  "nextjsVersion": "15+",
  "typescript": true,
  "frameworks": ["tailwind", "shadcn", "prisma"]
}
```

### Environment Setup

```bash
# Required for full functionality
export NEXT_PUBLIC_APP_ENV=development
export CLAUDE_AGENT_LEVEL=expert
```

## 📚 Knowledge Base (2025)

### Latest Next.js Features
- **App Router**: Stable with enhanced nested layouts
- **Server Actions**: Production-ready with improved security
- **Partial Prerendering (PPR)**: Available with Turbopack
- **React 19**: Server Components, Concurrent Rendering, use() hook
- **Turbopack**: Development and build optimizations

### Supported Integrations
- **Databases**: Prisma, Drizzle, MongoDB, PostgreSQL
- **Authentication**: NextAuth.js v5, Auth.js, Clerk, Supabase Auth
- **Styling**: Tailwind CSS, Styled Components, CSS Modules
- **State Management**: Zustand, Redux Toolkit, Valtio
- **Testing**: Vitest, Playwright, Jest, Testing Library

## 🛠️ Development

### Local Development
```bash
git clone https://github.com/claude-agents/nextjs-expert-engineer.git
cd nextjs-expert-engineer
npm install
npm run validate
```

### Contributing
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit changes: `git commit -m 'Add amazing feature'`
4. Push to branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📝 Examples

### Server Actions Implementation
```typescript
// Request: "Implement secure Server Actions for user profile update"

// Generated solution includes:
// - Input validation with Zod
// - Error handling
// - Revalidation strategies
// - Security best practices
```

### Performance Optimization
```typescript
// Request: "/audit Performance issues with dashboard loading"

// Analysis includes:
// - Bundle size analysis
// - Rendering strategy review
// - Caching optimization
// - Database query optimization
```

## 🤝 Support

- **Documentation**: [Full Documentation](https://nextjs-expert-agent.dev/docs)
- **Issues**: [GitHub Issues](https://github.com/claude-agents/nextjs-expert-engineer/issues)
- **Discord**: [Community Discord](https://discord.gg/nextjs-expert)
- **Email**: support@nextjs-expert.dev

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Next.js team for the amazing framework
- Claude Code team for the agent infrastructure
- Community contributors and feedback

---

**Made with ❤️ for the Next.js community**