# README - Sistema de Gestão de Frequência Enterprise

<div align="center">

![Status](https://img.shields.io/badge/Status-Ativo-success)
![Versão](https://img.shields.io/badge/Versão-1.0-blue)
![Licença](https://img.shields.io/badge/Licença-Proprietária-red)
![Desenvolvedor](https://img.shields.io/badge/Dev-Carlos%20Piquet-purple)

**Sistema Profissional de Gestão de Frequência e Presença**

Desenvolvido por **Carlos Antonio de Oliveira Piquet**

</div>

---

## 📋 Sobre o Projeto

Sistema enterprise de gestão de frequência desenvolvido com tecnologias modernas e design profissional. Oferece controle completo de presença, estatísticas avançadas e exportação de relatórios em múltiplos formatos.

### 🎯 Principais Características

- ✨ Interface moderna com glassmorphism e gradientes
- 📊 Dashboard com estatísticas em tempo real
- 📥 Importação inteligente de Excel com detecção automática de colunas
- 📤 Exportação para PDF e Excel
- ⚙️ Configuração flexível de campos visíveis
- 🎨 Tema claro/escuro
- 💾 Armazenamento local automático
- 📱 Design responsivo

---

## 👨‍💻 Autor e Direitos Autorais

**Desenvolvedor:** Carlos Antonio de Oliveira Piquet  
**E-mail:** carlospiquet.projetos@gmail.com  
**Copyright © 2025** - Todos os direitos reservados

### 🔒 Licença

Este software é **proprietário** e protegido por direitos autorais. O uso está sujeito aos termos da licença. Consulte os arquivos:
- `LICENSE.md` - Licença completa
- `TERMOS_DE_USO.md` - Termos de uso e política de privacidade

**Legislação aplicável:**
- Lei nº 9.609/98 (Lei do Software)
- Lei nº 9.610/98 (Lei de Direitos Autorais)
- Lei nº 13.709/18 (LGPD)

---

## 🚀 Tecnologias Utilizadas

### Frontend
- **HTML5** - Estrutura semântica
- **CSS3** - Tailwind CSS 3.x
- **JavaScript ES6+** - Vanilla JS com padrões modernos

### Bibliotecas
- **jsPDF 2.5.1** - Geração de PDFs
- **jsPDF-AutoTable 3.8.2** - Tabelas em PDF
- **SheetJS (XLSX) 0.18.5** - Manipulação de Excel
- **Chart.js 4.4.0** - Gráficos e estatísticas
- **Animate.css** - Animações
- **Font Awesome 6** - Ícones

### Padrões de Design
- **MVC Architecture** - Model-View-Controller
- **Observer Pattern** - Reatividade
- **Module Pattern** - Encapsulamento
- **Debouncing** - Performance

---

## 📦 Estrutura do Projeto

```
presença/
├── index.html              # Aplicação principal (single-file)
├── LICENSE.md              # Licença de uso
├── TERMOS_DE_USO.md       # Termos de uso e privacidade
├── README.md              # Este arquivo
└── exemplo_alunos.md      # Exemplo de dados
```

---

## 🔧 Instalação e Uso

### Requisitos
- Navegador moderno (Chrome, Firefox, Edge, Safari)
- JavaScript habilitado
- Conexão com internet (para CDNs das bibliotecas)

### Como Usar

1. **Abra o arquivo `index.html`** no navegador
2. **Importe uma planilha Excel** com dados dos alunos
3. **Configure as colunas visíveis** (botão ⚙️ Colunas)
4. **Adicione eventos** de frequência
5. **Registre presença/falta** para cada aluno
6. **Exporte relatórios** em PDF ou Excel

### Formato da Planilha Excel

**Colunas obrigatórias:**
- Nome

**Colunas opcionais (detectadas automaticamente):**
- CPF
- Matrícula
- Data de Admissão
- Turma
- Nome do Pai
- Nome da Mãe
- Endereço
- Telefone
- E-mail
- Data de Nascimento
- *Qualquer outra coluna personalizada*

---

## 📊 Funcionalidades

### 1. Gestão de Alunos
- ➕ Adicionar aluno manualmente
- ✏️ Editar dados do aluno
- 🗑️ Remover aluno
- 📥 Importação em massa via Excel

### 2. Gestão de Eventos
- 📅 Criar eventos com data, horário e local
- ✏️ Editar eventos
- 🗑️ Remover eventos
- 📋 Lista de eventos recentes

### 3. Controle de Frequência
- ✅ Marcar presença
- ❌ Marcar falta
- 📝 Adicionar observações
- 📊 Cálculo automático de estatísticas

### 4. Relatórios e Exportação
- 📄 Exportar para PDF (relatório completo)
- 📊 Exportar para Excel (formato editável)
- 📈 Visualização de estatísticas
- 📉 Gráficos de desempenho

### 5. Configurações
- ⚙️ Selecionar colunas visíveis
- 🎨 Alternar tema claro/escuro
- 🔄 Resetar todo o sistema
- 💾 Auto-save a cada 30 segundos

---

## 🎨 Interface

### Design System
- **Cores primárias:** Gradientes roxo/azul
- **Efeitos:** Glassmorphism, sombras suaves
- **Tipografia:** Inter (Google Fonts)
- **Animações:** Transições suaves
- **Responsividade:** Mobile-first

### Componentes
- 🎴 Cards com glassmorphism
- 🔘 Botões com gradientes
- 📋 Tabelas responsivas com scroll
- 🔔 Notificações toast
- 🗨️ Modais de confirmação
- 📊 Dashboard de estatísticas

---

## 💾 Armazenamento de Dados

### LocalStorage
Todos os dados são armazenados **localmente** no navegador:
- ✅ Privacidade total (sem envio para servidores)
- ✅ Acesso offline
- ✅ Auto-save automático
- ⚠️ Limitado ao navegador/dispositivo

### Backup Recomendado
- Exporte regularmente para Excel/PDF
- Não dependa apenas do LocalStorage
- Limpar cache do navegador apaga os dados

---

## 🛡️ Segurança e Privacidade

### Conformidade LGPD
- 🔒 Dados armazenados localmente
- 🚫 Nenhum dado enviado para servidores
- 👤 Usuário é controlador dos dados
- ✅ Transparência total no processamento

### Responsabilidades do Usuário
- Obter consentimento dos titulares de dados
- Proteger acesso ao dispositivo
- Fazer backups regulares
- Cumprir legislação educacional

---

## 📞 Suporte e Contato

### Canais de Suporte

**📧 E-mail:** carlospiquet.projetos@gmail.com  
**📋 Assunto sugerido:** [Suporte] Sistema de Frequência Enterprise

### Tempo de Resposta
- Dúvidas gerais: até 72h úteis
- Bugs críticos: prioridade alta
- Solicitações de recursos: análise sob demanda

### Serviços Disponíveis
- ✅ Suporte básico (gratuito)
- 💼 Customizações (sob orçamento)
- 🎓 Treinamento (consulte valores)
- 🔧 Manutenção (planos disponíveis)

---

## 🔄 Atualizações

### Versão Atual: 1.0 (26/10/2025)

**Recursos implementados:**
- ✅ Sistema completo de gestão de frequência
- ✅ Importação inteligente de Excel
- ✅ Exportação PDF/Excel
- ✅ Dashboard de estatísticas
- ✅ Campos personalizados flexíveis
- ✅ Interface enterprise moderna

### Roadmap Futuro
- 🔮 Sincronização em nuvem (opcional)
- 🔮 Geração de certificados
- 🔮 Relatórios avançados
- 🔮 Integração com APIs externas
- 🔮 App mobile nativo

---

## ⚠️ Avisos Importantes

### Uso Legal
Este software é protegido por direitos autorais. O uso não autorizado pode resultar em:
- ⚖️ Ações legais civis
- 🚨 Responsabilização criminal
- 💰 Indenizações por danos

### Isenção de Garantias
O software é fornecido "como está", sem garantias de:
- Funcionamento ininterrupto
- Ausência de erros
- Adequação a todos os propósitos

### Limitação de Responsabilidade
O desenvolvedor não se responsabiliza por:
- Perda de dados
- Danos diretos ou indiretos
- Violações da LGPD pelo usuário
- Uso inadequado do sistema

---

## 📜 Citação e Créditos

Ao utilizar ou referenciar este sistema, cite:

```
Sistema de Gestão de Frequência Enterprise
Desenvolvedor: Carlos Antonio de Oliveira Piquet
E-mail: carlospiquet.projetos@gmail.com
Ano: 2025
Licença: Proprietária
```

---

## 🤝 Licenciamento Comercial

Para usar este sistema comercialmente, entre em contato:

**📧 E-mail:** carlospiquet.projetos@gmail.com  
**📋 Assunto:** [Licenciamento Comercial] Sistema de Frequência

**Opções disponíveis:**
- 🏢 Licença empresarial
- 🎓 Licença educacional
- 🏛️ Licença governamental
- 💼 White-label customizado

---

## 📚 Documentação Adicional

Para documentação completa:
- `LICENSE.md` - Licença de uso detalhada
- `TERMOS_DE_USO.md` - Termos e política de privacidade
- `exemplo_alunos.md` - Modelo de planilha Excel

---

## 🌟 Agradecimentos

Obrigado por escolher o **Sistema de Gestão de Frequência Enterprise**.

Este projeto foi desenvolvido com dedicação e expertise técnica, aplicando as melhores práticas de desenvolvimento de software e design de interface.

---

<div align="center">

**Sistema de Gestão de Frequência Enterprise**

Desenvolvido por **Carlos Antonio de Oliveira Piquet**

© 2025 - Todos os direitos reservados

📧 carlospiquet.projetos@gmail.com

---

*"Transformando dados em conhecimento, frequência em sucesso."*

</div>
