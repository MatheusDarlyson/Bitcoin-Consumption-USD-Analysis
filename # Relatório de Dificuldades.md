# Relatório de Dificuldades

## 1. Montagem da string de consulta da URL API

**Dificuldade:**  
Durante o desenvolvimento, uma das primeiras dificuldades encontradas foi a correta montagem da string de consulta para a API de câmbio do Banco Central. A API exige parâmetros específicos como a data de consulta, o formato de retorno e os campos que devem ser extraídos. Inicialmente, houve dificuldades em montar a URL no formato correto para que a requisição fosse bem-sucedida, resultando em erros como "InvalidSchema".

**Solução:**  
Para solucionar essa questão, foi necessário um entendimento mais detalhado da documentação oficial da API, que explicava a estrutura dos parâmetros. Além disso, o uso de inteligência artificial (IA) ajudou a fornecer exemplos práticos e funcionais, facilitando a montagem correta da URL. Essa abordagem permitiu compreender os detalhes da API e garantir a sintaxe correta dos parâmetros.

## 2. Extração de dados de JSON para CSV

**Dificuldade:**  
Após obter os dados da API, a conversão do formato JSON para CSV apresentou desafios. A estrutura do JSON exigia a correta normalização dos dados para que eles fossem transformados em um DataFrame manipulável pelo Pandas. Além disso, houve dificuldades com o correto mapeamento das chaves do JSON para garantir que os dados desejados fossem extraídos.

**Solução:**  
A solução envolveu o uso de ferramentas como a biblioteca Pandas e a função `pd.json_normalize()` para normalizar os dados JSON. A análise detalhada da estrutura dos dados retornados pela API foi crucial para identificar a chave correta (`'value'`) onde as cotações estavam localizadas. Novamente, a IA contribuiu com exemplos de código e insights sobre a estrutura do JSON, facilitando a extração eficiente e a exportação para CSV.

## Justificativa

Para ambas as dificuldades, a resolução foi alcançada através de:

- **Entendimento da Documentação:** Estudo detalhado da documentação da API para entender os parâmetros exigidos e como estruturar as consultas corretamente.
- **Pesquisa e Uso de IA:** O uso de ferramentas de inteligência artificial para fornecer suporte técnico, exemplos de código e explicações práticas foi fundamental para superar os desafios relacionados à URL e ao formato dos dados.

Essa abordagem combinada garantiu a coleta correta dos dados e sua posterior manipulação em formato CSV, de maneira eficiente e precisa.
