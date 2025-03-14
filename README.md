# DNC Weather
Este projeto é uma aplicação web que permite ao usuário inserir informações como nome, e-mail, CEP, latitude e longitude, e exibir informações sobre o endereço e a previsão do tempo para a localidade fornecida.

## Funcionalidades:
- **Formulário de Entrada**: O usuário pode inserir seu primeiro nome, e-mail, CEP, latitude e longitude.
- **Busca de Endereço pelo CEP**: Ao inserir o CEP, a aplicação exibe detalhes como logradouro, bairro, localidade, etc.
- **Previsão do Tempo**: A aplicação busca a previsão do tempo para a latitude e longitude fornecidas, exibindo dados como temperatura, umidade, etc.

## Tecnologias Utilizadas:
- **HTML**: Estrutura da página e formulários.
- **CSS**: Estilos para a página, incluindo design responsivo e layout moderno.
- **JavaScript**: Para fazer chamadas de API e interagir com os dados do CEP e da previsão do tempo.

### Layout:
- **Cabeçalho**:
  - Exibe o título da aplicação e links de navegação.
  - Responsivo: No mobile, o cabeçalho se ajusta para um tamanho compacto, ocultando os links e adaptando o título.
  
- **Formulário**:
  - O formulário de entrada é bem destacado com um fundo branco e bordas arredondadas, com inputs e botão em azul.
  - No layout responsivo, o formulário se adapta para dispositivos móveis, com tamanhos de fonte reduzidos e entradas em largura total.
  
- **Exibição de CEP e Previsão do Tempo**:
  - As seções de exibição de dados (CEP e previsão) possuem fundos azuis com textos em branco e detalhes em cinza claro.
  - As informações de previsão e endereço são exibidas de forma centralizada e clara, com ajustes para telas menores.

### Responsividade:
A página é totalmente responsiva, com adaptações específicas para dispositivos móveis (telas com largura inferior a 768px). Alguns ajustes incluem:

- Tamanhos de fontes e botões reduzidos.
- Ajustes no layout das seções de conteúdo, tornando o formulário e as informações mais acessíveis.
- Ocultação de alguns elementos de navegação no cabeçalho para uma melhor experiência mobile.

## APIs:
- **API de CEP**: A aplicação usa uma API de consulta de CEP para exibir os dados do endereço correspondente.
- **API de Previsão do Tempo**: A aplicação faz uma chamada para uma API de previsão do tempo para obter informações climáticas com base na latitude e longitude fornecidas.

## Contribuições:
Se você deseja contribuir para este projeto, sinta-se à vontade para abrir uma **pull request** ou relatar **problemas** no repositório.

## Contato:
Caso tenha dúvidas ou sugestões, entre em contato através de renaldopetlim@gmail.com.

Link do SITE: https://dnc-weather-api-consumer.netlify.app/


### Responsividade Desktop:
<img src="/readme/responsividade-desktop.png" width="720px">

### Responsividade Mobile:
<img src="/readme/responsividade-mobile.jpg" width="480px">