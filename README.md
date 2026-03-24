# 🏋️ FitPro — Personal Trainer App

> Web App completo para gerenciamento de personal trainers em **português brasileiro**.

---

## ✅ Funcionalidades Implementadas

### 🔐 Login
- Tela de login com email e senha
- Animações suaves de entrada/saída
- Toggle para mostrar/esconder senha

### 📊 Dashboard
- Cards com métricas: total de alunos, treinos ativos, receita do mês, pagamentos pendentes
- Gráfico de barras: receita mensal (Chart.js)
- Gráfico de rosca: distribuição de objetivos dos alunos
- Lista de próximas sessões agendadas
- Feed de atividades recentes

### 👥 Alunos
- Grid de cards com foto, nome, status, nível, objetivo, plano e próxima sessão
- Filtros por busca, status (ativo/inativo) e nível
- Cadastro de novo aluno (nome, email, telefone, nascimento, objetivo, nível, plano, anamnese)
- **Perfil completo do aluno** com:
  - Medidas corporais (peso, altura, IMC, % gordura) com tendência
  - Treinos vinculados
  - Histórico de pagamentos
  - Botão de chat direto
- Ação de marcar aluno como inativo

### 🏋️ Treinos
- Lista de planos de treino com acordeão expansível
- Visualização de exercícios: nome, grupo muscular, séries, repetições, carga
- Criação de novo treino com builder de exercícios dinâmico
- Vinculação de treino a aluno específico
- Duplicar e excluir treinos
- Filtros por aluno e por nome

### 💰 Pagamentos
- Cards financeiros: recebido, pendente, atrasado, total do mês
- Tabela completa de cobranças com aluno, plano, valor, vencimento e status
- Filtro por status (pago, pendente, atrasado)
- Marcar pagamento como pago com 1 clique
- Criar nova cobrança (aluno, plano, valor, vencimento, status)
- Preenchimento automático do valor ao selecionar o plano

### 💬 Chat / Mensagens
- Lista lateral de conversas com foto, último status e hora
- Indicador de aluno online (ponto verde)
- Contador de mensagens não lidas
- Interface de chat estilo WhatsApp
- Envio de mensagens com Enter ou botão
- Respostas automáticas simuladas para demonstração
- Scroll automático para última mensagem

### 🎥 Biblioteca de Vídeos
- Grid responsivo de cards de exercícios
- Filtro por categorias: Peito, Costas, Pernas, Ombros, Braços, Core, Cardio
- Thumbnails do YouTube automáticas
- Player integrado com YouTube embed em modal
- Badges de dificuldade (Iniciante, Intermediário, Avançado)
- Adicionar e remover vídeos da biblioteca

---

## 🗂️ Estrutura de Arquivos

```
index.html           → Estrutura HTML principal (SPA)
css/
  style.css          → Estilos completos (tema escuro premium)
js/
  app.js             → Lógica JavaScript, dados mockados, interatividade
```

---

## 🚀 Como Acessar

| Rota | Descrição |
|------|-----------|
| `/` | Tela de Login |
| Dashboard | Visão geral após login |
| Alunos | Gestão de alunos |
| Treinos | Planos de treino |
| Pagamentos | Financeiro |
| Mensagens | Chat |
| Vídeos | Biblioteca de exercícios |

> **Login de demonstração:** qualquer email + qualquer senha

---

## 🎨 Design

| Elemento | Valor |
|----------|-------|
| Fundo principal | `#0F0F0F` |
| Fundo secundário | `#1A1A1A` |
| Cor de destaque | `#00FF7F` (verde neon) |
| Cor de ação | `#FF6B00` (laranja) |
| Cor de info | `#4D9FFF` (azul) |
| Fonte | Inter (Google Fonts) |
| Ícones | Font Awesome 6 |
| Gráficos | Chart.js |

---

## 📊 Dados Mockados

- **12 alunos** com perfis completos
- **5 treinos** com exercícios detalhados
- **12 pagamentos** em diferentes estados
- **5 conversas** de chat com histórico real
- **12 vídeos** de exercícios (YouTube)

---

## 🔮 Próximas Melhorias Recomendadas

- [ ] Integração com backend (API REST ou Firebase)
- [ ] Persistência de dados (localStorage ou banco de dados)
- [ ] Autenticação real (JWT, Firebase Auth)
- [ ] Upload de fotos de alunos
- [ ] Agendamento com calendário interativo
- [ ] Notificações push para pagamentos em atraso
- [ ] App mobile (React Native ou PWA)
- [ ] Relatórios e exportação em PDF
- [ ] Integração com gateway de pagamento (PagSeguro, Stripe)
- [ ] Planos alimentares / fichas de nutrição
- [ ] Galeria de fotos de evolução do aluno
