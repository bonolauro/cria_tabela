# Programa de Geração de Tabela de Roupas

Este programa Python cria uma tabela de roupas com 15000 linhas e a salva em um arquivo Excel na Área de Trabalho. Cada linha contém valores aleatórios para as colunas [Loja], [Item], [Tamanho], [Quantidade], e [Valor]. A coluna [Loja] intercala valores de 'Loja 1' a 'Loja 10', a coluna [Item] intercala entre 20 tipos de roupas diferentes, a coluna [Quantidade] contém valores inteiros aleatórios, a coluna [Tamanho] intercala entre os valores 'PP', 'P', 'M', 'G', 'GG', 'EGG', e a coluna [Valor] contém valores aleatórios em formato float.

## Requisitos

- Python 3.x
- Bibliotecas: pandas, openpyxl

## Instalação de Dependências

Instale as bibliotecas necessárias utilizando o seguinte comando:

```bash
pip install pandas openpyxl
```

## Execução do Programa

Execute o script `gerar_tabela_roupas.py` para gerar a tabela e salvar o arquivo Excel na Área de Trabalho.

```bash
python gerar_tabela_roupas.py
```

## Resultado

O arquivo Excel resultante será salvo na Área de Trabalho com o nome `tabela_roupas.xlsx`.

## Estrutura do Código

- `gerar_tabela_roupas.py`: Script principal que cria e salva a tabela.
- `README.md`: Documentação do programa.

## Autor

Lauro Bonometti

## Licença

Este projeto está sob a licença MIT - veja o arquivo [LICENSE.md](LICENSE.md) para detalhes.

---

Sinta-se à vontade para personalizar o README conforme necessário. Certifique-se de incluir seu nome como autor e ajustar a licença conforme apropriado para o seu uso.
