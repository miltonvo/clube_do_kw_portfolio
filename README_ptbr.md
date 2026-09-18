<div align="right">
  <!-- Idiomas: -->
  <a title="English" href="README.md">🇺🇸 English</a>
</div>

# Clube do KW ☀️⚡

**Clube do KW** é um sistema completo de gestão para empresas de energia fotovoltaica, oferecendo controle de clientes consumidores, distribuidoras, análise financeira, gestão de equipes e monitoramento de instalações solares com dashboard em tempo real.

---

## Funcionalidades ✨

- **Gestão de Consumidores** 👥: Cadastro completo e acompanhamento de clientes fotovoltaicos
- **Controle de Distribuidoras** 🏢: Gerenciamento de parcerias com distribuidoras de energia
- **Dashboard Analítico** 📊: Métricas em tempo real de produção e consumo de energia
- **Sistema Financeiro** 💰: Controle de faturas, economia gerada e ROI dos sistemas
- **Gestão de Equipes** 👷: Controle de cargos e permissões para instaladores e técnicos
- **Relatórios Detalhados** 📈: Análises de performance e economia de energia

---

## Tecnologias Utilizadas 🛠️

### Backend

- **Django 5.0 + REST Framework** 🐍: API robusta e escalável com Python
- **PostgreSQL** 🐘: Banco de dados relacional para dados estruturados
- **Redis + Celery** 🔄: Processamento de tarefas em background e cache
- **Django Channels** 🌐: WebSocket para atualizações em tempo real

### Frontend

- **Vue 3 + Composition API** ⚡: Framework JavaScript reativo e moderno
- **TypeScript** 📘: Tipagem estática para maior segurança do código
- **Vuetify 3** 🎨: Biblioteca de componentes Material Design
- **Pinia** 🍍: Gerenciamento de estado intuitivo e performático

### Infraestrutura

- **Docker + Docker Compose** 🐳: Containerização para desenvolvimento e produção
- **GitHub Actions** 🚀: CI/CD automatizado com deploy contínuo
- **Nginx** 🌐: Servidor web de alta performance
- **Gunicorn + Daphne** 🦄: Servidores ASGI/WSGI para Django

---

## Fluxo do Sistema 💼

### Gestão de Energia Solar

1. **Cadastro de Consumidores**: Registro de clientes com sistemas fotovoltaicos
2. **Análise de Consumo**: Monitoramento de produção e economia de energia
3. **Integração com Distribuidoras**: Gestão de créditos e compensação energética
4. **Relatórios de Performance**: Dashboards com métricas de eficiência
5. **Manutenção Preventiva**: Alertas e agendamento de manutenções

### Sistema Financeiro

- **Análise de ROI**: Cálculo de retorno sobre investimento
- **Economia Gerada**: Acompanhamento mensal de economia na conta de luz
- **Gestão de Faturas**: Controle de pagamentos e créditos energéticos
- **Projeções Financeiras**: Estimativas de economia futura

---

## Arquitetura 🏗️

### Estrutura do Backend

- **apps/financeiro**: Sistema completo de gestão financeira e faturas
- **apps/dashboard**: Métricas e análises de produção energética
- **apps/pages**: Páginas informativas e central de ajuda
- **apps/websocket**: Comunicação em tempo real para atualizações
- **authentication**: Sistema de autenticação e controle de acesso
- **tasks**: Processamento assíncrono com Celery

### Estrutura do Frontend

- **@core**: Componentes e utilitários fundamentais
- **@layouts**: Templates e estruturas de página
- **composables**: Lógica reutilizável com Composition API
- **pages**: Rotas e páginas da aplicação
- **stores**: Gerenciamento de estado com Pinia
- **types**: Definições TypeScript para type-safety

### Segurança & Performance

- **Autenticação JWT**: Tokens seguros com refresh automático
- **Rate Limiting**: Proteção contra abuso de API
- **Cache Redis**: Otimização de consultas frequentes
- **Lazy Loading**: Carregamento sob demanda de componentes

---

## Autores 👥

- **@miltonvo** 👨‍💻: Desenvolvedor principal e arquiteto do sistema

---

## Demonstração 📺

| ![Dashboard](assets/1.png) | ![Dashboard 2](assets/2.png) | ![Financeiro](assets/3.png) |
|:------------------------:|:------------------------:|:------------------------:|
| Dashboard Principal | Dashboard Analytics | Sistema Financeiro |

| ![Consumidores](assets/4.png) | ![Edição de Consumidores](assets/5.png) | ![Painel Admin](assets/6.png) |
|:------------------------:|:------------------------:|:------------------------:|
| Gestão de Consumidores | Edição de Consumidores | Painel Administrativo |

| ![Cargos](assets/7.png) | ![Distribuidoras](assets/8.png) | ![Login](assets/9.png) |
|:------------------------:|:------------------------:|:------------------------:|
| Gestão de Cargos | Distribuidoras | Tela de Login |

🔗 **Veja o sistema em ação** ⬇️


---

📄 Case completo no site da MV Dev Solutions: [https://mvdevsolutions.com.br/projetos/clube-do-kw](https://mvdevsolutions.com.br/projetos/clube-do-kw)
