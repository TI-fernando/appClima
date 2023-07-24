# Aplicativo de Previsão do Tempo

Este é um aplicativo simples de previsão do tempo desenvolvido em HTML, CSS e JavaScript. Ele permite que os usuários obtenham informações climáticas em tempo real para uma determinada localização.

## Como funciona?

1. **Digite Sua Localização:** Insira o nome da cidade ou localização para a qual deseja obter a previsão do tempo na caixa de pesquisa.

2. **Clique no Botão de Busca:** Após inserir a localização, clique no ícone de busca ou pressione a tecla "Enter" para buscar as informações climáticas correspondentes.

3. **Exibição da Previsão:** O aplicativo fará uma requisição à API do OpenWeatherMap para obter os dados climáticos para a localização inserida. Se a localização for válida, o aplicativo exibirá as seguintes informações:

   - Ícone representando a condição climática (ex: sol, chuva, neve, etc.).
   - Temperatura atual em graus Celsius.
   - Descrição da condição climática (ex: ensolarado, chuvoso, nevando, etc.).
   - Umidade relativa do ar em porcentagem.
   - Velocidade do vento em quilômetros por hora.

4. **Localização Inválida:** Se a localização inserida não for encontrada na API, o aplicativo exibirá uma mensagem de erro informando que a localização é inválida.

## Recursos Utilizados

- **HTML e CSS:** A estrutura do aplicativo foi criada utilizando HTML para a marcação dos elementos e CSS para a estilização visual.

- **Fontes Personalizadas:** O aplicativo utiliza as fontes Poppins e Roboto do Google Fonts para melhorar a tipografia.

- **Biblioteca FontAwesome:** O ícone de localização e o ícone de busca são fornecidos pela biblioteca FontAwesome.

- **API do OpenWeatherMap:** Para obter os dados climáticos em tempo real, o aplicativo faz uma requisição à API do OpenWeatherMap, que fornece informações detalhadas sobre as condições climáticas de uma localização específica.

## Nota Importante
Este aplicativo é apenas um exemplo educacional e não foi implementado com recursos de segurança ou tratamento de erros robustos. Ele não é recomendado para uso em produção sem uma revisão apropriada.

Autor
Este aplicativo foi desenvolvido pelo Canal ASMR Programming e modificado por mim do meu modo. Sinta-se à vontade para alterações.

Aviso: As informações climáticas fornecidas por este aplicativo são baseadas na API do OpenWeatherMap e podem não estar totalmente atualizadas ou precisas em tempo real. Certifique-se de verificar fontes confiáveis para obter informações meteorológicas críticas.

## Configuração da Chave da API

Para utilizar corretamente o aplicativo, é necessário obter uma chave de acesso à API do OpenWeatherMap. Siga os seguintes passos:

1. Acesse o site do OpenWeatherMap (https://openweathermap.org) e crie uma conta gratuita.

2. Após criar a conta, acesse o painel de controle do OpenWeatherMap e obtenha sua chave de API.

3. No código JavaScript (index.js), substitua a string `"Sua Chave Aqui"` pela sua chave de API.

```javascript
const APIKey = "Sua Chave Aqui";
