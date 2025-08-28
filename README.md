# CCB - Sistema de Gerenciamento de Ferramentas

Um sistema web moderno e responsivo para gerenciamento de ferramentas da CCB (Companhia de Construção e Beneficiamento).

## 🚀 Características

- **Dashboard Interativo**: Visualização rápida de estatísticas e status das ferramentas
- **Gerenciamento Completo**: Cadastro, edição, exclusão e consulta de ferramentas
- **Filtros Avançados**: Busca por status, categoria e texto livre
- **Relatórios**: Geração de relatórios de uso, manutenção e inventário
- **Design Responsivo**: Interface adaptável para desktop, tablet e mobile
- **Persistência de Dados**: Armazenamento local no navegador
- **Interface Moderna**: Design temático da CCB com cores profissionais

## 📋 Funcionalidades

### Dashboard
- Estatísticas em tempo real
- Contadores de ferramentas por status
- Ações rápidas para operações comuns

### Gerenciamento de Ferramentas
- **Cadastro**: Adicionar novas ferramentas com informações completas
- **Edição**: Modificar dados existentes
- **Exclusão**: Remover ferramentas com confirmação
- **Filtros**: Buscar por status, categoria e texto
- **Tabela Responsiva**: Visualização organizada dos dados

### Relatórios
- **Relatório de Uso**: Estatísticas de utilização das ferramentas
- **Relatório de Manutenção**: Controle de manutenções
- **Relatório de Inventário**: Lista completa de todas as ferramentas

### Configurações
- Personalização de dados da empresa
- Configurações de backup

## 🎨 Design e Interface

### Cores da CCB
- **Azul Principal**: #1e3a8a (identidade da empresa)
- **Laranja Secundário**: #f59e0b (destaque)
- **Verde Sucesso**: #10b981
- **Vermelho Perigo**: #ef4444
- **Amarelo Aviso**: #f59e0b

### Tipografia
- **Fonte Principal**: Inter (Google Fonts)
- **Hierarquia Clara**: Títulos, subtítulos e texto
- **Legibilidade**: Contraste otimizado

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilos modernos com CSS Grid e Flexbox
- **JavaScript ES6+**: Funcionalidades interativas
- **Font Awesome**: Ícones profissionais
- **Google Fonts**: Tipografia otimizada

## 📱 Responsividade

O sistema é totalmente responsivo e funciona em:
- **Desktop**: Layout completo com todas as funcionalidades
- **Tablet**: Adaptação para telas médias
- **Mobile**: Interface otimizada para smartphones

## 🚀 Como Usar

### 1. Instalação
1. Baixe todos os arquivos do projeto
2. Abra o arquivo `index.html` em qualquer navegador moderno
3. O sistema estará pronto para uso

### 2. Primeiro Uso
- O sistema vem com dados de exemplo
- Você pode começar a usar imediatamente
- Todos os dados são salvos automaticamente no navegador

### 3. Navegação
- **Início**: Dashboard com estatísticas
- **Ferramentas**: Gerenciamento completo
- **Relatórios**: Geração de relatórios
- **Configurações**: Configurações do sistema

### 4. Operações Básicas

#### Adicionar Ferramenta
1. Clique em "Nova Ferramenta" no dashboard ou na seção de ferramentas
2. Preencha os campos obrigatórios:
   - Código (único)
   - Nome
   - Categoria
   - Status
   - Localização
   - Data de aquisição
3. Clique em "Adicionar"

#### Editar Ferramenta
1. Na tabela de ferramentas, clique no ícone de editar (lápis)
2. Modifique os dados desejados
3. Clique em "Salvar"

#### Excluir Ferramenta
1. Na tabela de ferramentas, clique no ícone de excluir (lixeira)
2. Confirme a exclusão no modal

#### Filtrar Ferramentas
- Use os filtros na seção de ferramentas
- Filtre por status, categoria ou texto livre
- Os filtros funcionam em conjunto

### 5. Atalhos de Teclado
- **Ctrl/Cmd + N**: Nova ferramenta
- **Ctrl/Cmd + F**: Focar na busca
- **ESC**: Fechar modais

## 📊 Estrutura de Dados

### Ferramenta
```javascript
{
  id: 1,
  code: "F001",
  name: "Furadeira Elétrica Bosch",
  category: "eletrica",
  status: "disponivel",
  location: "Almoxarifado A",
  purchaseDate: "2023-01-15",
  lastMaintenance: "2024-01-10",
  description: "Furadeira elétrica profissional 1100W"
}
```

### Categorias Disponíveis
- **Elétrica**: Ferramentas elétricas
- **Manual**: Ferramentas manuais
- **Hidráulica**: Equipamentos hidráulicos
- **Pneumática**: Equipamentos pneumáticos

### Status Disponíveis
- **Disponível**: Pronta para uso
- **Em Uso**: Atualmente sendo utilizada
- **Em Manutenção**: Em processo de manutenção
- **Inativo**: Temporariamente indisponível

## 💾 Persistência de Dados

- Os dados são salvos automaticamente no localStorage do navegador
- Não há necessidade de configuração de banco de dados
- Os dados persistem entre sessões
- Backup automático a cada alteração

## 📈 Relatórios Disponíveis

### Relatório de Uso
- Total de ferramentas
- Distribuição por status
- Distribuição por categoria
- Data de geração

### Relatório de Manutenção
- Ferramentas em manutenção
- Data da última manutenção
- Lista detalhada

### Relatório de Inventário
- Lista completa de todas as ferramentas
- Informações detalhadas
- Formato JSON para importação

## 🔧 Personalização

### Cores
As cores podem ser personalizadas editando as variáveis CSS no arquivo `styles.css`:

```css
:root {
  --primary-color: #1e3a8a;
  --secondary-color: #f59e0b;
  --accent-color: #10b981;
  /* ... outras cores */
}
```

### Dados da Empresa
- Edite o nome da empresa nas configurações
- Personalize informações específicas

## 🚨 Notificações

O sistema exibe notificações para:
- ✅ Operações bem-sucedidas
- ❌ Erros e validações
- ⚠️ Avisos e informações

## 📱 Compatibilidade

### Navegadores Suportados
- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

### Dispositivos
- Desktop (Windows, macOS, Linux)
- Tablet (iOS, Android)
- Mobile (iOS, Android)

## 🔒 Segurança

- Validação de dados em tempo real
- Confirmação para operações críticas
- Sanitização de entrada de dados
- Armazenamento local seguro

## 📞 Suporte

Para dúvidas ou sugestões:
- Verifique a documentação
- Teste em diferentes navegadores
- Verifique a compatibilidade do dispositivo

## 🎯 Próximas Funcionalidades

- [ ] Sistema de usuários e permissões
- [ ] Backup em nuvem
- [ ] Integração com banco de dados
- [ ] API REST
- [ ] Aplicativo mobile
- [ ] QR Code para identificação
- [ ] Histórico de uso detalhado
- [ ] Agendamento de manutenção
- [ ] Notificações por email
- [ ] Dashboard avançado com gráficos

## 📄 Licença

Este projeto foi desenvolvido especificamente para a CCB - Companhia de Construção e Beneficiamento.

---

**Desenvolvido com ❤️ para a CCB**
