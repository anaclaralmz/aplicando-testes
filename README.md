# Testes de Software com .NET 5: exemplos de utilização
Deverá haver um commit para cada teste implementado.

O seu repositório deverá ter no arquivo reaadme uma seção para cada tipo de testes. Nessa seção, você irá detalhar de forma clara objetiva a aplicação do testes e fornecer dois cenários de exemplo.

Na seção de cada teste, após as descrições, coloque um print do teste sendo executado.

Substituir o texto do barema por:

(De 0 a 3) - Implementação dos 3 tipos de testes apresentados no artigo (1 ponto para cada tipo de teste implementado)
(De 0 a 2) - Explicação clara e objetiva sobre a aplicação dos testes
(De 0 a 2) - Organização do arquivo readme, com imagens dos testes e coerência dos textos.
## Tecnologias e conceitos aprendidos
- .NET
- JetBrains Rider (IDE)
- xUnit
- Testes unitários
## Testes de unidade
- Iremos implementar testes de unidade para um método que transforma graus Fahrenheit para a escala de Celsius.
### Xunit testes
1. Criação de uma solução vazia, e, após, criação de um projeto de unit tests com Xunit:
![projeto](./assets/project-1.png)
![projeto](./assets/estrutura-1.png)
2. Criação do método de conversão de escalas te temperatura
3. Configuração de 6 testes unitários para testar o método criado anteriormente.
3. Testes rodados. Resultado: todos os testes passaram com sucesso.
![projeto](./assets/testes-1.png)