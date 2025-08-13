# 🚗 Controle de KM Rodado - Sistema de Gestão de Quilometragem

![Controle de KM Rodado Screenshot](https://kmrodado.netlify.app/assets/screenshot.png) <!-- Exemplo de screenshot, substituir pela imagem real -->

## 🌟 Visão Geral

O **Controle de KM Rodado** é uma aplicação web robusta e intuitiva, projetada para simplificar o registro e a gestão de quilometragem percorrida. Ideal para profissionais que precisam controlar despesas de viagem, frotas de veículos ou qualquer necessidade de monitoramento de KM, este sistema oferece uma solução completa com funcionalidades avançadas e uma interface de usuário moderna e responsiva.

Desenvolvido com as tecnologias web mais recentes, o projeto foca em usabilidade, performance e um design minimalista que garante uma experiência agradável em qualquer dispositivo.

## ✨ Funcionalidades Principais

Este sistema oferece um conjunto abrangente de recursos para gerenciar seus registros de quilometragem de forma eficiente:

### 📝 Registro e Cálculo Automático

- **Registro Detalhado**: Insira informações essenciais como data, hora, nome do condutor, empresa associada, quilometragem inicial e final.
- **Cálculo Inteligente**: O sistema calcula automaticamente a quilometragem rodada e o valor total a ser ressarcido, com base em um valor configurável por KM.

### ✏️ Edição de Registros (NOVO!)

- **Flexibilidade Total**: Edite qualquer registro existente após o lançamento, permitindo correções e atualizações de forma simples e rápida.
- **Interface Intuitiva**: Um modal de edição elegante e fácil de usar garante que suas modificações sejam feitas sem complicação.
- **Validação em Tempo Real**: Os dados são validados durante a edição para garantir a integridade das informações.

### 🔄 Atualização de Valores em Massa (NOVO!)

- **Recálculo Global**: Altere o valor por KM e, com um único clique, recalcule o valor total de todos os registros existentes, adaptando-se rapidamente a novas políticas ou custos.
- **Confirmação Segura**: Uma confirmação explícita é solicitada antes de aplicar as alterações em massa, prevenindo modificações acidentais.

### 💾 Armazenamento e Persistência de Dados

- **Armazenamento Local**: Todos os seus dados são salvos diretamente no `localStorage` do seu navegador, garantindo que suas informações permaneçam acessíveis mesmo após fechar e reabrir o navegador.

### 📊 Filtragem e Exportação Versátil

- **Filtros Inteligentes**: Organize e visualize seus dados com filtros por empresa e por mês, facilitando a análise e a busca por informações específicas.
- **Exportação Multi-Formato**: Exporte seus registros em diversos formatos populares, incluindo:
    - **JSON**: Para integração com outras aplicações ou backup de dados.
    - **Excel (.xlsx)**: Para análises detalhadas em planilhas.
    - **PDF**: Para relatórios impressos ou compartilhamento fácil.
    - **TXT**: Para compatibilidade simples com outros sistemas.
- **Importação de Dados**: Carregue registros a partir de um arquivo JSON, facilitando a migração ou a restauração de dados.

### 🗑️ Gerenciamento de Dados

- **Remoção Individual**: Exclua registros específicos com uma confirmação de segurança.
- **Limpeza Completa**: Opção para apagar todos os dados, ideal para reiniciar o controle ou para fins de privacidade.

## 🎨 Design e Experiência do Usuário (UX)

O projeto foi cuidadosamente desenhado para oferecer uma experiência de usuário superior:

- **Design Minimalista e Profissional**: Uma estética limpa e moderna, com uma paleta de cores sofisticada e tipografia otimizada para legibilidade.
- **Bootstrap 5.3.3**: Utiliza a versão mais recente do framework Bootstrap para garantir responsividade, componentes UI atualizados e um visual coeso.
- **Ícones Bootstrap Icons**: Integração de ícones vetoriais para uma interface mais intuitiva e visualmente atraente.
- **Sistema de Feedback Avançado**: Notificações `toast` elegantes fornecem feedback em tempo real para todas as ações do usuário (sucesso, erro, aviso).
- **Melhorias de Usabilidade**: Preenchimento automático de data e hora, limpeza de campos após o registro, e micro-interações (como `hover states` e animações suaves) que aprimoram a fluidez da interação.
- **Responsividade Total**: A aplicação se adapta perfeitamente a diferentes tamanhos de tela, proporcionando uma experiência consistente em desktops, tablets e smartphones.

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e acessível da aplicação.
- **CSS3**: Estilização personalizada com foco em um tema escuro moderno e minimalista.
- **JavaScript (ES6+)**: Lógica de negócio, manipulação do DOM e interatividade.
- **Bootstrap 5.3.3**: Framework front-end para componentes UI e responsividade.
- **Bootstrap Icons**: Biblioteca de ícones.
- **XLSX.js**: Biblioteca para manipulação e exportação de dados para Excel.
- **jsPDF**: Biblioteca para geração de documentos PDF.

## 🚀 Como Usar

Para começar a usar o sistema de Controle de KM Rodado, siga os passos abaixo:

### 💻 Execução Local

1. **Clone o Repositório**: Baixe o código-fonte para o seu computador:
   ```bash
   git clone https://github.com/seu-usuario/km-rodado.git
   ```
2. **Navegue até o Diretório**: Entre na pasta do projeto:
   ```bash
   cd km-rodado
   ```
3. **Abra no Navegador**: Simplesmente abra o arquivo `index_melhorado.html` em seu navegador web preferido. Não é necessário um servidor web para execução local.

### 🌐 Versão Online (Live Demo)

Você pode acessar uma versão demo do sistema online através do seguinte link:

[**Acessar Live Demo**](https://kmrodado.netlify.app/)

### Guia Rápido de Uso

1. **Configuração Inicial**: Defina o valor por KM (padrão: R$ 1,50). Data e hora são preenchidas automaticamente.

2. **Adicionar Registro**: Preencha todos os campos obrigatórios e clique em "Adicionar Registro". Os campos são limpos automaticamente.

3. **Editar Registro (NOVO!)**: Clique no botão "Editar" (ícone de lápis) na linha desejada. Modifique os dados no modal que abrir e clique em "Salvar Alterações".

4. **Atualizar Valores em Massa (NOVO!)**: Altere o "Valor por KM (R$)" no topo da página. Clique no botão "Atualizar Valores" ao lado do campo. Confirme a atualização e todos os valores dos registros serão recalculados.

5. **Filtrar e Exportar**: Use os filtros por empresa ou mês. Exporte em diversos formatos conforme necessário e importe dados de arquivos JSON.

## 📄 Arquivos do Projeto

- `index.html`: O arquivo principal da aplicação web.
- `README_github.md`: Este arquivo de documentação.

## 🎉 Conclusão

Esta versão do sistema de Controle de KM Rodado representa um avanço significativo em termos de funcionalidade e experiência do usuário. Com a adição de recursos de edição e atualização em massa, juntamente com um design moderno e responsivo, o sistema está pronto para atender às suas necessidades de gestão de quilometragem de forma eficiente e profissional.

Sinta-se à vontade para explorar o código, contribuir com melhorias ou adaptar o projeto às suas necessidades específicas. Se tiver alguma dúvida ou sugestão, entre em contato!

--- 

Desenvolvido com ❤️ por Erick de Lima Souza.

