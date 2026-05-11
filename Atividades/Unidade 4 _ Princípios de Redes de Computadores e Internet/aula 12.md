# Aula 12 - Internet: História, Conceitos, Protocolos e Navegadores

## Descrição do trabalho
Este material apresenta uma análise prática de protocolos utilizando o Inspetor do Navegador (F12), na aba Network/Rede. O site analisado foi o portal da UFRN e o status code escolhido foi **200 OK - Sucesso**.

## Objetivo
Compreender como o navegador realiza requisições para um servidor e como o servidor responde com arquivos e códigos de status.

## Conteúdo produzido
O PDF contém:

1. Breve história da Internet.
2. Conceitos fundamentais: Internet, Web, cliente-servidor e IP.
3. Protocolos: TCP/IP, HTTP/HTTPS, DNS e FTP.
4. Navegadores e motores de renderização.
5. Exercício prático com o Inspetor do Navegador.
6. Análise de Request, Response e Status Code.
7. Conclusão e reflexão individual.

## Análise prática realizada

- **Ferramenta utilizada:** Inspetor do Navegador (F12), aba Network/Rede.
- **Site analisado:** https://www.ufrn.br
- **Requisição escolhida:** arquivo CSS `slick-theme.css`
- **Request Method:** GET
- **Status Code:** 200 OK
- **Response:** o servidor enviou o arquivo CSS solicitado, com Content-Type `text/css`.

## Organização dos arquivos

```text
Aula12_Analise_Protocolos/
├── README.md
├── analise_protocolos_status_200_ok.pdf
└── imagens/
    ├── 01_print_network_status_200.png
    ├── 02_detalhe_request_response.png
    ├── 03_lista_requisicoes_network.png
    └── 04_status_200_destacado.png
```

## Como anexar no GitHub
Envie a pasta `Aula12_Analise_Protocolos` para a pasta da Aula 12 no repositório da disciplina. O arquivo principal para avaliação é o PDF `analise_protocolos_status_200_ok.pdf`.
