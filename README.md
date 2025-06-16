# Gerador de Currículos

Este Gerador de Currículos é uma aplicação web que permite aos utilizadores criar currículos personalizados, inserindo informações pessoais e profissionais, e gerar um PDF estilizado com essas informações. A aplicação inclui funcionalidades interativas, como pré-visualização de foto de perfil e validação de campos obrigatórios.

## Funcionalidades principais:

  * **Formulário Interativo:** O utilizador pode preencher diversas secções do currículo:
      * Informações Pessoais (campos obrigatórios): Nome, Profissão, Email, Telefone, CEP, Endereço, Cidade, Estado, Nacionalidade, Idade, Gênero, Relacionamento.
      * Experiência Profissional (opcional): Permite descrever a experiência de trabalho anterior.
      * Formação Acadêmica (opcional): Informações sobre a educação do utilizador.
      * Idiomas (opcional): Idiomas que o utilizador fala.
      * Cursos (opcional): Cursos ou formações adicionais.
      * Habilidades (opcional): Competências técnicas ou pessoais.
      * Projetos (opcional): Projetos que o utilizador tenha realizado.
  * **Upload de Foto de Perfil:** O utilizador pode fazer upload de uma foto de perfil, que é pré-visualizada em tempo real. A imagem é processada e convertida para um formato base64, garantindo a sua incorporação no currículo gerado e no PDF.
  * **Geração de Currículo:** Após preencher o formulário, o currículo é gerado dentro da página, permitindo ao utilizador visualizar todas as informações inseridas com um layout bonito e organizado. O currículo exibe a foto de perfil do utilizador, seguida pelas Informações Pessoais e demais seções opcionais como Experiência Profissional, Formação Acadêmica, etc.
  * **Download em PDF:** Após gerar o currículo, o utilizador pode clicar no botão "Baixar Currículo em PDF". O PDF gerado mantém o layout e os estilos do currículo visualizado na página, incluindo a foto de perfil e todas as informações inseridas. O botão de download está estilizado com uma cor vermelha elegante.
  * **Validação de Campos:** Apenas os campos das "Informações Pessoais" são obrigatórios, garantindo que o currículo contenha as informações essenciais. Seções adicionais, como experiência profissional e habilidades, são opcionais, dando flexibilidade ao utilizador.
  * **Busca Automática de Endereço pelo CEP:** O campo CEP (código postal) permite que o utilizador insira o seu CEP, e a aplicação faz uma busca automática do endereço, preenchendo automaticamente os campos de "Endereço", "Cidade" e "Estado", utilizando a API do ViaCEP.

## Principais Benefícios:

  * **Interface Simples e Responsiva:** A aplicação é fácil de usar, adaptando-se bem tanto em dispositivos móveis quanto em desktops.
  * **Personalização Completa:** O utilizador pode ajustar as informações do currículo conforme suas necessidades e exportá-lo em PDF com um layout elegante.
  * **Foto de Perfil:** A inclusão de uma foto de perfil personaliza ainda mais o currículo.
  * **Automatização:** O preenchimento automático do endereço através do CEP simplifica o processo de criação.

Este Gerador de Currículos combina facilidade de uso, flexibilidade e funcionalidades avançadas, permitindo ao utilizador criar e exportar um currículo profissional em poucos minutos.
