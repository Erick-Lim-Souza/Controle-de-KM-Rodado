📊 Controle de KM Rodado
https://img.shields.io/badge/status-active-brightgreen https://img.shields.io/badge/license-MIT-blue

Um sistema profissional para registro e controle de quilometragem rodada por condutores, com cálculo automático de valores baseado no KM percorrido.

✨ Funcionalidades
Registro completo de viagens/deslocamentos

Cálculo automático de KM rodado e valor devido

Filtros avançados por empresa e período

Exportação de dados em múltiplos formatos:

📄 Excel (XLSX)

📊 JSON

📑 PDF

📝 TXT

Importação de dados via JSON

Interface moderna e responsiva

Armazenamento local (persistência de dados)

Notificações toast interativas

Totalizadores automáticos

🚀 Como Usar
Preencha os dados do deslocamento:

Data e hora

Nome do condutor

Empresa contratante

KM inicial e final

Defina o valor por KM no campo superior

Adicione o registro com o botão ou atalho Ctrl+Enter

Gerencie seus registros:

Edite com um clique

Remova itens indesejados

Filtre por empresa ou mês

Exporte seus dados quando necessário

🛠️ Tecnologias Utilizadas
https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white

https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white

https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black

https://img.shields.io/badge/-Bootstrap-7952B3?logo=bootstrap&logoColor=white

https://img.shields.io/badge/-Bootstrap_Icons-7952B3?logo=bootstrap&logoColor=white

https://img.shields.io/badge/-SheetJS-217346?logo=excel&logoColor=white

https://img.shields.io/badge/-jsPDF-black?logo=adobe-acrobat-reader&logoColor=white

📦 Instalação
Nenhuma instalação necessária! O sistema roda diretamente no navegador:

html
<!-- Simplesmente abra o arquivo index.html no seu navegador -->
Ou acesse online (se disponível):

bash
https://exemplo.com/controle-km-rodado
📸 Screenshots
https://via.placeholder.com/800x500/1e293b/ffffff?text=Controle+de+KM+Rodado
Interface principal do sistema

https://via.placeholder.com/600x400/1e293b/ffffff?text=Edi%C3%A7%C3%A3o+de+Registro
Modal para edição de registros

🌟 Destaques do Código
Armazenamento local com localStorage

Cálculos automáticos em tempo real

Responsividade para todos os dispositivos

Animações suaves e feedback visual

Validação de dados robusta

javascript
// Exemplo de função principal
function adicionarRegistro() {
  const kmRodado = kmFinal - kmInicial;
  const valor = kmRodado * valorPorKm;
  
  registros.push({ 
    data, hora, condutor, empresa, 
    kmInicial, kmFinal, kmRodado, valor 
  });
  
  salvarLocalStorage();
  renderizarTabela();
}
📈 Roadmap
Autenticação de usuários

Sincronização com nuvem

Relatórios gráficos

Multiplataforma (PWA)

Notificações por e-mail

🤝 Contribuição
Contribuições são bem-vindas! Siga estes passos:

Faça um fork do projeto

Crie sua branch (git checkout -b feature/AmazingFeature)

Commit suas mudanças (git commit -m 'Add some AmazingFeature')

Push para a branch (git push origin feature/AmazingFeature)

Abra um Pull Request

📜 Licença
Distribuído sob a licença MIT. Veja LICENSE para mais informações.

👨‍💻 Autor
Erick de Lima Souza

🌐 GitHub: Erick-Lim-Souza

💼 LinkedIn

🎓 Perfil DIO.me

📚 Perfil Alura

📧 Email: erick.devzone@gmail.com

🙏 Agradecimentos
Comunidade de desenvolvedores

Bibliotecas open source utilizadas

Feedback dos usuários

Desenvolvido com 💚 e dedicação ao aprendizado de tecnologias web modernas. 💪🏾
