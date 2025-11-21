# Sistema de Acompanhamento de Líderes

Um sistema web completo para acompanhar o desempenho de líderes em relação aos padrões de liderança cristã. Inclui avaliações, relatórios individuais com recomendações e análise comparativa.

## 🎯 Funcionalidades

- **Cadastro de Líderes**: Registre informações básicas dos líderes
- **Acompanhamento de Reuniões**: Registre presença e justificativas
- **Avaliação de Padrões**: Avalie os 17 padrões de liderança (escala 1-5)
- **Relatórios Individuais**: Gere relatórios personalizados com recomendações para melhoria
- **Relatório Geral**: Visualize comparativo de todos os líderes (confidencial)
- **Gráficos e Estatísticas**: Dashboard com presença e desempenho
- **Exportação**: Baixe relatórios em PDF ou dados em CSV
- **Armazenamento Local**: Todos os dados são salvos no navegador

## 📋 Padrões de Liderança

1. Ser salvo por Jesus
2. Ser batizado nas águas
3. Viver com integridade e santidade
4. Ser honesto
5. Fidelidade Conjugal/Pureza
6. Ser submisso à liderança
7. Ser comprometido e responsável
8. Estar no programa de Líderes
9. Participar do discipulado
10. Participar ativamente das reuniões
11. Respeitar seus líderes
12. Ser pronto a servir
13. Prática de oração em línguas
14. Meditação na Palavra de Deus
15. Tratar as pessoas com amor e respeito
16. Não falar mal dos outros
17. Estar disposto a prestar contas

## 🚀 Como Usar

### Localmente

```bash
# Instale as dependências (se necessário)
npm install

# Inicie o servidor de desenvolvimento
npm run dev

# Acesse em http://localhost:3000
```

### Online (Vercel)

Acesse: [acompanhamento-lideres.vercel.app](https://acompanhamento-lideres.vercel.app)

## 💾 Dados

Os dados são armazenados localmente no navegador usando `localStorage`. Nenhuma informação é enviada para servidores externos.

### Backup de Dados

Para fazer backup dos seus dados:
1. Abra o navegador (F12 → Console)
2. Execute: `copy(JSON.stringify({lideres: localStorage.getItem('lideres'), reunioes: localStorage.getItem('reunioes'), avaliacoes: localStorage.getItem('avaliacoes')}))`
3. Cole em um arquivo de texto para guardar

### Restaurar Dados

1. Abra o Console (F12)
2. Cole o código: `const dados = {seu_backup_aqui}; localStorage.setItem('lideres', dados.lideres); localStorage.setItem('reunioes', dados.reunioes); localStorage.setItem('avaliacoes', dados.avaliacoes);`

## 🛠️ Tecnologias

- **HTML5**: Estrutura
- **CSS3**: Estilo responsivo
- **JavaScript Vanilla**: Lógica da aplicação
- **Chart.js**: Gráficos
- **html2pdf.js**: Exportação em PDF

## 📱 Responsividade

A aplicação é totalmente responsiva e funciona em:
- Desktop
- Tablet
- Smartphone

## 🔒 Privacidade

- Nenhum dado é enviado para servidores
- Tudo é armazenado localmente no seu navegador
- Você tem controle total dos seus dados

## 📝 Licença

MIT

## 👨‍💼 Autor

Eduardo Argollo

## 📧 Suporte

Para dúvidas ou sugestões, entre em contato.

---

**Desenvolvido com ❤️ para liderança cristã**
