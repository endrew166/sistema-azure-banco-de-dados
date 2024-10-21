# Exemplo de Uso de Mesclar vs Atribuir

## Mesclar

Quando utilizamos a opção de **mesclar** em ferramentas de manipulação de dados (Power BI, Excel), estamos preservando a integridade relacional dos dados entre duas tabelas. Por exemplo, na tabela abaixo, temos uma relação entre gerentes e seus respectivos colaboradores:

| Gerente       | Colaborador      |
| ------------- | ---------------- |
| John Smith    | Amanda Teixeira  |
| Franklin Wong | Joyce English    |
| John Smith    | Ramesh Narayan   |

Ao mesclar com outra tabela que possui detalhes adicionais dos colaboradores, preservamos essas relações e garantimos que os dados fiquem completos e consistentes.

## Atribuir

Se utilizássemos **atribuir**, poderíamos sobrescrever ou duplicar dados sem respeitar essas associações. Isso poderia resultar em uma perda de contexto, como no caso de duplicar entradas para "John Smith" ao atribuir novas informações sem manter a relação com os colaboradores.

Portanto, **mesclar** é a escolha correta para preservar a integridade dos dados e suas associações.
