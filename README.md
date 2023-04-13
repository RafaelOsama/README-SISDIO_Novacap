![Logo da novacap](https://assets.infra.grancursosonline.com.br/projeto/novacap-companhia-urbanizadora-da-nova-capital-do-brasil.png)

[Acessando o site](#acessando-o-site) |
[Painel principal](#painel-principal) |
[Emissão](#emissão) |
[Relatórios](#relatórios) |
[Administração](#administração) |
[Tecnologias](#tecnologias-utilizadas-no-sisdionovacap)


# Acessando o site
O usuário deverá estar previamente autorizado para acessar o _SISDIO_.
**O login e a senha são os mesmos utilizados para o acesso à rede corporativa.**

*Ultimas update*

- [x] Acessando o site.
- [x] Painel principal.
- [x] Emissão.
- [x] Relatórios.
- [x] Administração.


## login
![image](https://user-images.githubusercontent.com/104030715/231474727-011e3796-09ca-4375-bf0b-595f65cd7d10.png)

<br>

_Preencha os campos com o login e senha. Clique em Autorizar acesso para acessar o sistema._

<br>

# Painel Principal

_Após realizar o login, o sistema apresentará a seguinte tela:_
![image](https://user-images.githubusercontent.com/104030715/231475634-e5eeb9bd-2761-4f67-ab6a-0fa56768c354.png)_Após realizar o login, o sistema apresentará a seguinte tela:_


# Emissão
_O sistema apresentará a tela para gerar uma nova emissão de diário de obra:_

![image](https://user-images.githubusercontent.com/104030715/231477578-f231d0c4-747c-4471-be80-e5a3ae88a970.png)

_É possível filtrar a ordem da sequencia da lista de DIOs clicando sobre o parâmetro desejado, por exemplo, filtrar por orgão, assim o sistema tornará a lista em ordem alfabética descrente por orgão._

## Retorno
![image](https://user-images.githubusercontent.com/104030715/231478625-9a47155f-74f1-4ede-ab13-acb135b2404b.png)
Informe o Número DIO e depois em Pesquisar.

Os demais dados serão inseridos automaticamente, com os dados do DIO informado.


*Marque a opção:*

* Cancelar DIO (Em caso de Cancelamento, Escolha um motivo)
* DIO Ocioso
* DIO Excepcional

**E MAIS:**

* Retorno KM/Hora
* Recebimento
* Liberação
* Gestor/Supervisor/Motorista
* Observação


## lista de Retornos

_Na lista de retornos é possível visualizar:_

* Nº do DIO
* Data de Retorno
* Contrato
* Equipamento
* Trab. (Horas Trabalhadas/ Horas Paradas)
* Responsável pelo DIO
* Emissor do DIO
* Retorno do DIO

### Fechar Retorno para Faturamento
![image](https://user-images.githubusercontent.com/104030715/231482063-3da271ae-0043-473b-8587-968eb14f6ac4.png)

### Ações:



* Cancelar o retorno (Para cancelar o retorno, clique no ícone CANCELAR)
* Arquivar o retorno (Para arquivar o retorno, clique no ícone ARQUIVAR)
* Alterar o retorno (Para alterar o retorno, clique no ícone ALTERAR)
* Excluir o retorno (Para excluir o retorno, clique no ícone EXCLUIR)
* Faturar o retorno (Para faturar o retorno, clique no ícone FATURAR)

# Relatórios



_É possível gerar relatórios por meio de:_

* Valores Brutos por beneficiarios
* Valores Brutos por beneficiarios (Conferência)
* Valores Brutos por Prefixo/Placa/Série.
* Valores Totais por benefiario
* Listagem de Equipamentos por Classificação
* Listagem de Equipamentos por Classificação
* Listagem de Equipamentos Desligados da Empresa
* Listagem de Equipamentos Ativos/ Inativos.
* Diário de Operações Sem Retorno
* Diário de Operações Com Retorno
* Diário de Operações Com tempo de Retorno
* Retorno Cancelados

<br>

## Dashboard
<br>


_Acessando este item na parte superior da tela e mostrado uma painel de controle com todos o dados de forma resumida e simplificada._
<br>

![image](https://user-images.githubusercontent.com/104030715/231492998-0e351e80-32c0-40fd-8cae-3e486bd462ac.png)

# Administração

![image](https://user-images.githubusercontent.com/104030715/231494981-04698871-aa62-424c-971f-882da0c05f41.png)

### Usuario

_Cadastro do usuario_

![image](https://user-images.githubusercontent.com/104030715/231495910-8d371166-3f4a-498b-85f1-19defb81ca5b.png)

<br>

**Na lista de usuários é possível visualizar:**

* Matrícula
* Nome do usuário
* Login
* Função exercida pelo usuário
* Órgão
* Perfil
* Situação
* Ações

## Funcionarios

_Cadastro de funcionarios_

![image](https://user-images.githubusercontent.com/104030715/231496968-1960502c-27f6-4f37-bd3d-dc43f9789051.png)

_Na lista de usuários é possível visualizar:_

* Matrícula
* Nome do usuário
* Função
* Órgão
* Ação

<br>

-----------------------------------------------------------
# Tecnologias utilizadas no SISDIO/Novacap

* PHP | v7.3.1

* Codeigniter | v3.11

* SQLserver | ano 2005

-------------------------------------------------------------
# Clonar, organizar e instalar para iniciar localmente

1. >Run git clone
2. >Run composer install
3. >Run cp .env.example .env
4. >Run php artisan key:generate
5. >Run php artisan migrate, before set conf to database
6. >Run php artisan db:seed
7. >Run php artisan serve
8. >Go to link localhost:8000

------------------------------------------------------------

_**COLABORADORES**_ | _**GITHUB PAGE**_
-------------- | ----------------
**Darciso Maia Filho** |	https://github.com/Darciso
**Rafael Alencar do Amaral** | https://github.com/RafaelOsama
**Rute Miliana**	| https://github.com/rutemiliana
**Cristian Barbosa**	| https://github.com/djchristiandf
---------------------------------------------------------------
