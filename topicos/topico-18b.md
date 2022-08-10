## [Tópico T18b] - Modelo Entidade Relacionamento (MER) - Exercício
###### *by Prof. Plinio Sa Leitao-Junior (INF/UFG)*

Considere os requisitos de dados a seguir, pertinentes ao **BD Multas de Trânsito**, conforme o controle do DETRAN sobre as infrações ocorridas no estado:

- Os veículos são identificados pela placa e também descritos por chassi, cor predominante, modelo, categoria e ano de fabricação.
- Cada veículo possui um único proprietário, que é identificado por seu CPF. Deve-se saber o nome, endereço, bairro, cidade estado, telefone (vários), sexo, data de nascimento e idade.
- Todo veículo possui um único modelo; por exemplo, COROLLA ALTIS, GOL MI, FUSCA 1500L, etc.:
  - cada modelo é codificado por um número de 6 dígitos.
- Similarmente ao modelo, uma categoria deve ser atribuída a cada veículo; por exemplo, AUTOMÓVEL, MOTOCICLETA, CAMINHÃO, etc.:
  - cada categoria é codificada por um número de 2 dígitos.
- Existem diversos tipos de infração, AVANÇO DE SINAL VERMELHO, PARADA SOBRE A FAIXA DE PEDESTRES, etc., cada identificada pelo código associado:
  - a cada tipo de infração é associado um valor que deverá ser cobrado na ocorrência de infração.
- Uma infração é identificada pelo veículo infrator, data/hora e tipo de infração. Também é importante conhecer o local, velocidade aferida (se possível) e agente de trânsito.
- Cada local é descrito pelo código, posição geográfica e velocidade permitida; um local é geralmente referenciado por seu código.
- Um agente de trânsito é conhecido através de sua matrícula, sendo também descrito pelo nome, data de contratação e tempo de serviço.

Construa o diagrama entidade-relacionamento pertinente ao **BD Multas de Trânsito**.

## Não há atividade para este tópico, excepcionalmente.
