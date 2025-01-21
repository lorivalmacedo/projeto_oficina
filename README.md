# Projeto de Banco de Dados de Oficina mecânica

	- Contexto: Levantamento de requisitos
	- Projeto Conceitual: Modelo das entidades e relacionamentos
	- Projeto Lógico: Modelo relacional

# Modelando OFICINA:
### Ordem de serviço
    - A ordem de serviço é criada com o orçamento feito para o cliente
    - A oficina pode realizar mais de uma ordem de serviço para o mesmo cliente
    - Um único mecânico cria a OS
    - Uma ordem de serviço é para um único carro

### Clientes
    - O cliente pode ser Pessoa Jurídica ou Pessoa Física
    - Um cliente pode ter mais de um carro
    
### Mecânico
    - Um mecânico pode estar em mais de uma OS

## Entidades: 
- Ordem de serviço, Clientes, Mecânicos

## Software usado para modelagem
**MySQL Workbench**
