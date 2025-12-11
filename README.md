# Documentação do Módulo de Conexão

## Descrição
Este projeto implementa um padrão de conexão segura com o banco de dados, utilizando **Design Patterns** para evitar *hardcoding*.

## O que foi feito
- [x] Criação do repositório
- [x] Implementação da conexão
- [x] Resolução de conflito de Merge
- [x] Separação de configuração

## Exemplo de Uso
Abaixo, o código padrão utilizado pelo Arquiteto:

```python
# Constante de configuração
DB_HOST = "192.168.0.1"

def conectar_banco():
    """Conecta usando a constante definida"""
    return f"Conectado ao {DB_HOST}"
