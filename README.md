# Repositório Provas Antigas Vestibulares

Este repositório contém uma coleção organizada de provas antigas de diversos vestibulares (Estaduais, Federais e Privadas), estruturadas para facilitar o acesso via API.

## Estrutura do Repositório

- `api_vestibulares.json`: Arquivo principal contendo o mapeamento de todas as provas disponíveis.
- `provas/`: Diretório contendo os arquivos PDF das provas, organizados por categoria, instituição e ano.

## Como usar a API

Você pode consumir os dados diretamente do arquivo `api_vestibulares.json`. Cada entrada no JSON fornece o caminho relativo para o arquivo PDF correspondente.

### Exemplo de Estrutura JSON

```json
{
  "categorias": {
    "Estadual": {
      "UEMA": {
        "2024": [
          {
            "nome_arquivo": "UEMA 2024.pdf",
            "caminho_relativo": "provas/Estadual/UEMA/2024/UEMA 2024.pdf",
            "tipo": "prova_completa"
          }
        ]
      }
    }
  }
}
```

## Contribuição

Sinta-se à vontade para abrir Pull Requests para adicionar novas provas ou corrigir informações.

---
*Este repositório foi gerado automaticamente para fins educacionais.*
