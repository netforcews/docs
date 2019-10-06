# Variaveis para usar nos filtros do sistema

## Variáveis de contexto

Variável | Descrição
------------ | -------------
@USUARIO     | ID / Handle do usuário logado no sistema
@GRUPOS      | Lista de IDs (separada por virgula, dos grupos de permissão do usuário logado
@MODULO      | ID do módulo selecionado no sistema
@REGISTROPAI | ID do registo pai (registro de origem) ao registro selecionado
@EMPRESA     | ID da empresa usuária selecionada no contexto do sistema

## Variáveis de datas e períodos

Variável | Descrição
------------ | -------------
@AGORA              | A data e hora atual do servidor no forma
@HOJEINI            | Data do dia de HOJE com a hora 00:00:00
@HOJEFIM            | Data do dia de HOJE com a hora 23:59:59
@HOJE               | Data do dia de HOJE (sem hora)
@U6DIAS             | Data de 6 dias atrás com hora 00:00:00
@U7DIAS             | Data de 7 dias atrás com hora 00:00:00
@U12DIAS            | Data de 12 dias atrás com hora 00:00:00
@U15DIAS            | Data de 15 dias atrás com hora 00:00:00
@U30DIAS            | Data de 30 dias atrás com hora 00:00:00
@P7DIAS             | Data de 7 dias a frente com hora 23:59:59
@P15DIAS            | Data de 15 dias a frente com hora 23:59:59
@P30DIAS            | Data de 30 dias a frente com hora 23:59:59
@SEMANAINI          | Data do primeiro dia da semana atual com hora 00:00:00
@SEMANAFIM          | Data do último dia da semana atual com hora 23:59:59
@PROXIMASEMANAINI   | Data do primeiro dia da próxima semana com hora 00:00:00
@PROXIMASEMANAFIM   | Data do último dia da próxima semana com hora 23:59:59
@QUINZENAINI        | Data do primeiro dia da quinzena atual com hora 00:00:00
@QUINZENAFIM        | Data do último dia da quinzena atual com hora 23:59:59
@MESINI             | Data do primeiro dia do mês atual com a hora 00:00:00
@MESFIM             | Data do último dia do mês atual com a hora 23:59:59
@MESANTERIORINI     | Data do primeiro dia do último mês com a hora 00:00:00
@MESANTERIORFIM     | Data do último dia do último mês com a hora 23:59:59
@2MESATRASINI       | Data do primeiro dia de 2 meses atrás com a hora 00:00:00
@2MESATRASFIM       | Data do último dia de 2 meses atrás com a hora 23:59:59
@3MESATRASINI       | Data do primeiro dia de 3 meses atrás com a hora 00:00:00
@3MESATRASFIM       | Data do último dia de 3 meses atrás com a hora 23:59:59
@4MESATRASINI       | Data do primeiro dia de 4 meses atrás com a hora 00:00:00
@4MESATRASFIM       | Data do último dia de 4 meses atrás com a hora 23:59:59
@5MESATRASINI       | Data do primeiro dia de 5 meses atrás com a hora 00:00:00
@5MESATRASFIM       | Data do último dia de 5 meses atrás com a hora 23:59:59
@6MESATRASINI       | Data do primeiro dia de 6 meses atrás com a hora 00:00:00
@6MESATRASFIM       | Data do último dia de 6 meses atrás com a hora 23:59:59
@PROXIMOMESINI      | Data do primeiro dia do próximo mês com a data 00:00:00
@PROXIMOMESFIM      | Data do último dia do próximo mês com a data 23:59:59
@ANOINI             | Data do primeiro dia do ano atual com a hora 00:00:00
@ANOFIM             | Data do último dia do ano atual com a hora 23:59:59
      
> ATENÇÃO: Todas as datas e horas são no formado do banco de dados(Y-m-d H:i:s)
