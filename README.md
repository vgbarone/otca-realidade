<H1> OTCA - Onde Tem Crime Ambiental (REALIDADE)</H1>

<H2>Sobre o Projeto</H2>

OTCA (Onde Tem Crime Ambiental) é um chatbot projetado para facilitar o acesso à informação sobre legislação ambiental brasileira <del>e permitir a denúncia de crimes ambientais. Este chatbot foi desenvolvido para ser executado em HTML responsivo, garantindo que seja acessível em qualquer dispositivo, seja um celular antigo ou um computador moderno.</del>

<b>Essa versão é um chatbot que tira dúvidas sobre a Lei de Crimes Ambientais.Python pra rodar no Colab.</b>

<H2>Metodologia</H2>

<H3>O desenvolvimento deste projeto envolveu o uso de <del>várias</del> plataformas e tecnologias:</H3>

<B>Google Colab:</B> Utilizado para desenvolvimento inicial e testes de scripts.

<B>AI Studio e Gemini da Google:</B> Empregado para gerar código, tirar dúvidas, analisar logs e sistematizar os principais artigos da Lei de Crimes Ambientais nº 9.605, de 12 de fevereiro de 1998. Os dados foram então exportados para um arquivo JSON (lei_crimes_ambientais.json).

<del><B>CodePen:</B> Usado para prototipação rápida do frontend do chatbot.</del>

<del><B>PythonAnywhere:</B> Tentativa de hospedagem da aplicação.</del>

<H2>Tecnologias Utilizadas</H2>

<del><B>Flask:</B> Framework escolhido para o servidor backend do chatbot.</del>

<B>google-generativeai:</B> API usada para enriquecer e detalhar as respostas do chatbot.

<del><B>gspread e oauth2client:</B> Ferramentas para integração com Google Sheets, usadas para coletar e gerenciar denúncias.</del>

<del><B>google-auth e secrets:</B> Usados para a autenticação segura e gerenciamento de configurações sensíveis.</del>

<H2>Estrutura do Código</H2>

O código em Python consulta o arquivo lei_crimes_ambientais.json e usa a API google-generativeai para aprimorar e adicionar informações detalhadas nas respostas.

<H2>Objetivos</H2>

<del>Além de</del> <b>esclarecer dúvidas sobre a Lei de Crimes Ambientais</b>, <del>o chatbot foi projetado para receber denúncias, capturar coordenadas geográficas e, inicialmente para testes, alimentar um Google Sheets. Esse Sheets, por sua vez, deveria alimentar um dashboard com um mapa no Google Data Studio.</del>

<H2>Desafios e Realizações</H2>

<b>O projeto encontrou obstáculos técnicos, mas consegui viabilizar o chatbot para python que está nesse diretório (ele funciona). No outro repositório, <b><a href="https://github.com/vgbarone/otca-expectativa">otca-expectativa</a></b>, vocês podem ver todo o esforço de 48 hs que, infelizmente, não deu resultado.</b>
