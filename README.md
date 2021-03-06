# EvosuiteEvaluation

## Abaixo segue a lista de projetos e suas respectivas classes avaliadas 
Alguns rótulo foram definidos para facilitar o ponto de vista. Foram eles:
#### COMPREENSÍVEL:
Este rótulo se refere ao quão compreensível (para o avaliador) foram os testes gerados pela ferramenta Evosuite.
#### IMPORTANTE PARA O CONTEXTO:
Este rótulo se refere ao quão importante (do ponto de vista do avaliador) um teste gerado pela ferramenta Evosuite, é, para a classe testada.
#### DE FÁCIL CRIAÇÃO:
Este rótulo informa se gerar o mesmo código de um determinado teste gerado pela ferramenta Evosuite, de forma manual, é fácil (do ponto de vista do avaliador).

* [Jsonld-java](https://github.com/ronysilvati/jsonld-java)
  * [JsonLdUrl_ESTest](https://github.com/ronysilvati/jsonld-java/blob/master/core/src/test/evosuite/com/github/jsonldjava/utils/JsonLdUrl_ESTest.java)
  * [JsonLdUtils_ESTest](https://github.com/ronysilvati/jsonld-java/blob/master/core/src/test/evosuite/com/github/jsonldjava/core/JsonLdUtils_ESTest.java)
  * [RemoteDocument_ESTest](https://github.com/ronysilvati/jsonld-java/blob/master/core/src/test/evosuite/com/github/jsonldjava/core/RemoteDocument_ESTest.java)
  * [UniqueNamer_ESTest](https://github.com/ronysilvati/jsonld-java/blob/master/core/src/test/evosuite/com/github/jsonldjava/core/UniqueNamer_ESTest.java)
* [jackson-datatype-money](https://github.com/ronysilvati/jackson-datatype-money)
  * [MoneyModule_ESTest](https://github.com/ronysilvati/jackson-datatype-money/blob/master/evosuite/best-tests/org/zalando/jackson/datatype/money/MoneyModule_ESTest.java)
  * [MonetaryAmountSerializer_ESTest.java](https://github.com/ronysilvati/jackson-datatype-money/blob/master/evosuite/best-tests/org/zalando/jackson/datatype/money/MonetaryAmountSerializer_ESTest.java)
  * [DecimalAmountWriter_ESTest](https://github.com/ronysilvati/jackson-datatype-money/blob/master/evosuite/best-tests/org/zalando/jackson/datatype/money/DecimalAmountWriter_ESTest.java)
  * [CurrencyUnitSerializer_ESTest](https://github.com/ronysilvati/jackson-datatype-money/blob/master/evosuite/best-tests/org/zalando/jackson/datatype/money/CurrencyUnitSerializer_ESTest.java)
* [checkstyle](https://github.com/ronysilvati/checkstyle)
  * [ParameterNameCheck_ESTest](https://github.com/ronysilvati/checkstyle/blob/master/evosuite/best-tests/com/puppycrawl/tools/checkstyle/checks/naming/ParameterNameCheck_ESTest.java)
  * [MethodDefHandler_ESTest](https://github.com/ronysilvati/checkstyle/blob/master/evosuite/best-tests/com/puppycrawl/tools/checkstyle/checks/indentation/MethodDefHandler_ESTest.java)
  * [CommentsIndentationCheck_ESTest](https://github.com/ronysilvati/checkstyle/blob/master/evosuite/best-tests/com/puppycrawl/tools/checkstyle/checks/indentation/CommentsIndentationCheck_ESTest.java)
* [mybatis-3](https://github.com/ronysilvati/mybatis-3)
  * [DataSourceException_ESTest](https://github.com/ronysilvati/mybatis-3/blob/master/evosuite-tests/org/apache/ibatis/datasource/DataSourceException_ESTest.java)
  * [ResultMapException_ESTest](https://github.com/ronysilvati/mybatis-3/blob/master/evosuite-tests/org/apache/ibatis/executor/result/ResultMapException_ESTest.java)
  * [LogException_ESTest](https://github.com/ronysilvati/mybatis-3/blob/master/evosuite-tests/org/apache/ibatis/logging/LogException_ESTest.java)
  * [GenericTokenParser_ESTest](https://github.com/ronysilvati/mybatis-3/blob/master/evosuite-tests/org/apache/ibatis/parsing/GenericTokenParser_ESTest.java)
* [fastjson](https://github.com/ronysilvati/fastjson)
  * [BeanContext_ESTest](https://github.com/ronysilvati/fastjson/blob/master/evosuite-tests/com/alibaba/fastjson/serializer/BeanContext_ESTest.java)
  * [ToStringSerializer_ESTest](https://github.com/ronysilvati/fastjson/blob/master/evosuite-tests/com/alibaba/fastjson/serializer/ToStringSerializer_ESTest.java)
