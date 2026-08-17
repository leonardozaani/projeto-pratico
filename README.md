# Sistema de Gestão de Veículos para Concessionárias

Sistema desenvolvido para auxiliar concessionárias no **controle e gerenciamento dos veículos que entram e saem do pátio**, permitindo registrar movimentações, consultar informações e acompanhar o histórico dos veículos.

## Sobre o Projeto

O sistema tem como objetivo facilitar o controle do fluxo de veículos dentro da concessionária mantendo um registro organizado das entradas e saídas.

A aplicação pode ser utilizada para controlar veículos de clientes, veículos disponíveis para venda, veículos em manutenção, test-drive e outras movimentações internas.

## Objetivos

* Registrar a entrada de veículos na concessionária.
* Registrar a saída de veículos.
* Manter o histórico de movimentações.
* Consultar veículos que estão atualmente no pátio.
* Identificar o responsável pela entrada ou saída.
* Facilitar o controle e a organização dos veículos.
* Reduzir erros no controle manual das movimentações.

## Funcionalidades

### Cadastro de Veículos

Permite cadastrar informações dos veículos, como:

* Placa;
* Marca;
* Modelo;
* Ano;
* Cor;
* Quilometragem;
* Proprietário;
* Observações.

### Entrada de Veículos

Ao registrar a entrada, o sistema armazena:

* Data e horário;
* Veículo;
* Quilometragem;
* Motivo da entrada;
* Responsável pelo registro;
* Observações.

### Saída de Veículos

O sistema permite registrar a saída de um veículo, armazenando:

* Data e horário da saída;
* Veículo;
* Quilometragem de saída;
* Motivo da saída;
* Responsável;
* Observações.

### Consulta

É possível consultar:

* Veículos atualmente no pátio;
* Veículos que já saíram;
* Histórico de movimentações;
* Entradas e saídas por período;
* Veículos por placa ou modelo.

## Tecnologias

Exemplo de tecnologias que podem ser utilizadas no projeto:

* **HTML5**
* **CSS3**
* **JavaScript**
* **Node.js**
* **Express**
* **PostgreSQL**
* **Git**
* **GitHub**

## Como Executar

### 1. Clonar o repositório

```bash
git clone https://github.com/SEU-USUARIO/sistema-concessionaria.git
```

### 2. Entrar no diretório

```bash
cd sistema-concessionaria
```

### 3. Instalar as dependências

```bash
npm install
```

### 4. Configurar o banco de dados

Configure as informações de conexão com o banco de dados no arquivo `.env`.

Exemplo:

```env
DB_HOST=localhost
DB_PORT=5432
DB_NAME=concessionaria
DB_USER=postgres
DB_PASSWORD=sua_senha
```

### 5. Executar o projeto

```bash
npm start
```

O sistema estará disponível no endereço configurado pela aplicação.

```

## Exemplo de Registro

| Placa    | Veículo        | Entrada | Saída | Status   |
| -------- | -------------- | ------- | ----- | -------- |
| ABC-1D23 | Toyota Corolla | 08:30   | —     | No pátio |
| DEF-4E56 | Honda Civic    | 09:15   | 14:20 | Saiu     |
| GHI-7J89 | VW T-Cross     | 10:00   | —     | No pátio |

## Segurança

O sistema deve possuir mecanismos para garantir a segurança das informações, incluindo:

* Autenticação de usuários;
* Controle de acesso;
* Registro dos responsáveis pelas movimentações;
* Validação dos dados cadastrados;
* Proteção das informações armazenadas.

## Possíveis Melhorias Futuras

* Dashboard com indicadores da concessionária;
* Leitura automática de placas (LPR);
* Controle de usuários e permissões;
* Geração de relatórios;
* Exportação para Excel/PDF;
* Integração com câmeras de segurança;
* Notificações de entrada e saída;
* Registro de test-drives;
* Integração com sistemas de estoque;
* Histórico completo por veículo.

## Desenvolvimento

Projeto desenvolvido com o objetivo de aplicar conceitos de **desenvolvimento de sistemas, banco de dados, versionamento de código e controle de movimentação de veículos**.

---

⭐ **Projeto de Sistema de Gestão de Veículos para Concessionárias**
