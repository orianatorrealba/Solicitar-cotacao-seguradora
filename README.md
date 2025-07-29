Projeto de Testes no Postman com JavaScript
Olá! Este projeto tem como objetivo demonstrar como realizar testes automatizados em uma API usando o Postman, com scripts em JavaScript. Utilizamos diversas técnicas de teste para garantir a qualidade e a confiabilidade do seu serviço.

Técnicas de Teste Utilizadas
Testes de Classe: Verificação de diferentes categorias de respostas, como sucesso, erro de cliente e erro de servidor.
Valor Limite: Testes com valores extremos para validar limites de entrada e saída.
Tabela de Decisão: Testes baseados em diferentes combinações de condições para cobrir cenários variados.
Análise Combinatória: Combinação de múltiplos fatores para testar várias configurações possíveis.
Como usar
Importar o projeto no Postman:
Importe o arquivo
.json
do seu projeto no Postman.

Configurar variáveis:
Ajuste as variáveis de ambiente conforme necessário para seu ambiente de teste.

Executar os testes:
Execute as coleções e observe os resultados na aba de testes do Postman.

Exemplo de Script de Teste
// Teste de Valor Limite
pm.test("Verifica limite superior de idade", function () {
    var idade = pm.response.json().idade;
    pm.expect(idade).to.be.at.most(120);
});
Contribuição
Se desejar contribuir, sinta-se à vontade para fazer um fork e enviar pull requests. Sua colaboração é bem-vinda!

Contato
Para dúvidas ou sugestões, entre em contato comigo. 😊

Se precisar de um arquivo
.json
de exemplo ou de mais detalhes, posso ajudar também!
