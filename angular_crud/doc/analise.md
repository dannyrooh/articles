# Objetivo

Criar uma artigo para angular 19, no formato hands-on, que servirá como base para uma video aula para ser colocado no canal da empresa.
O artigo será para o nivel básico, abordando os setuintes assuntos:

- componentização
- formulário
- http utilizando json-server
- mvc

## Tarefa

    Criar um dashboard para gerar o CIS (CLIENT INFORMATION SHEET), as informações serão agrupadas da seguinte forma, apóa o input dos dados;

|Cooporate Information | "dados da coorporação ou dados da empresa" |
|--|--|
|Full Name of Corporate Institution | string  |
|Registration Number |string|
|Date of Registration | date |
|Domicile / Jurisdiction |string|
|Postal Address |string|
|Registration Address |string|
|Physical Address (If different from Registration Address) |string|
|Business Telephone Number |string|
|Corporate Officers and Titles |string|

|DETAILS OF SIGNATORY TO CONTRACT – CORPORATE AND INDIVIDUAL | "dados do gestor" |
|--|--|
|First Name |string|
|Last Name |string|
|Date and Place of Birth |date|
|Nationality |string|
|Passport Number |string|
|Date of Issue of the Passport |date|
|Expiry Date of the Passport |date|
|Title Within the Corporation/Company |string|
|Mobile Phone Number |string|
|Home Address |string|
|Do you speak English? |boolean|
|If not, what language do you speak? |string|
|Translator’s Name |string|
|Translator’s Address |string|
|Translator’s Phone Number/s |string|
|Translator’s Skype ID: |string|
|Translator’s E-mail Address |string|

|Details of Bank Account – Where Funds Are Held | "dados bancários" |
|--|--|
|Bank Name |string|
|Bank Address |string|
|Bank Swift Code |string|
|Iban Number |string|
|Account Number |string|
|Account Signatory Name and Title |string|
|Bank Officer Name and Title |string|
|Bank Officer Phone Number |string|
|Bank Officer Facsimile Number |string|
|Bank Officer E-Mail Address |string|


|Upload de Anexos | "imagens em pdf, png ou jpeg" |
|--|--|
| company logo |binary|
| profile photo |binary|
| passaport |binary|
| certification registration |binary|