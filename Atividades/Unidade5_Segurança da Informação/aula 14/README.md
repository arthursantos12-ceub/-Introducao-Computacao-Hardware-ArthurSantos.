# Ameaças e Vulnerabilidades

## Diferença entre ameaça, vulnerabilidade, risco e controle

- **Ameaça:** agente, evento ou situação com potencial para causar dano a um ativo, sistema ou informação.
- **Vulnerabilidade:** fraqueza técnica, humana ou processual que pode ser explorada por uma ameaça.
- **Risco:** possibilidade de uma ameaça explorar uma vulnerabilidade e causar impacto.
- **Controle:** medida usada para reduzir, evitar, transferir ou aceitar riscos de forma planejada.

## Vulnerabilidades técnicas

- Sistemas operacionais desatualizados.
- Falta de correções de segurança.
- Senhas fracas ou reutilizadas.
- Falta de autenticação em duas etapas.
- Configurações incorretas em redes, servidores e permissões.
- Uso de softwares piratas ou sem suporte.
- Falta de backup confiável.

## Vulnerabilidades humanas

- Clicar em links suspeitos.
- Abrir anexos desconhecidos.
- Informar senhas por telefone, e-mail ou mensagem.
- Usar a mesma senha em vários serviços.
- Compartilhar dados sensíveis em ferramentas de IA sem autorização.
- Conectar pendrives desconhecidos.
- Trabalhar em redes públicas sem proteção.

## Impactos potenciais em sistemas e organizações

As ameaças e vulnerabilidades podem causar vazamento de dados, perda financeira, paralisação de serviços, dano à imagem da instituição, multas legais, perda de confiança de clientes, interrupção de operações e sequestro de arquivos por ransomware.

## Boas práticas destacadas na aula

- Usar senhas fortes e gerenciadores de senhas.
- Ativar autenticação em duas etapas.
- Desconfiar de mensagens com urgência exagerada.
- Verificar remetentes, links e anexos antes de clicar.
- Manter sistemas, navegadores e aplicativos atualizados.
- Usar VPN e firewall quando necessário.
- Evitar Wi-Fi público para sistemas sensíveis.
- Não inserir dados sensíveis nem código-fonte em ferramentas de IA sem autorização.

## Definição de Segurança da Informação

De acordo com a ISO/IEC 27000:2018, Segurança da Informação é a preservação da confidencialidade, integridade e disponibilidade da informação. Em outras palavras, é o conjunto de práticas, controles, políticas e tecnologias usados para proteger dados e sistemas contra acessos indevidos, alterações não autorizadas, perdas, indisponibilidade e outros incidentes.

Na aula, a segurança da informação foi apresentada como uma forma de proteger ativos informacionais, garantir a continuidade do negócio e reduzir incidentes. Também foi destacado que o objetivo central é aplicar controles apropriados para proteger as informações contra ameaças acidentais ou intencionais.
## Medidas de mitigação aplicadas ou recomendadas

As medidas recomendadas para evitar ou reduzir ataques semelhantes são:

1. Aplicar atualizações de segurança com rapidez, especialmente correções críticas como a MS17-010.
2. Desativar protocolos antigos e inseguros, como SMBv1, quando não forem necessários.
3. Manter backups atualizados, testados e isolados da rede principal.
4. Utilizar antivírus, EDR, firewall e monitoramento de rede.
5. Segmentar redes para impedir propagação lateral de malware.
6. Treinar usuários sobre phishing, anexos suspeitos e engenharia social.
7. Criar plano de resposta a incidentes com papéis e procedimentos claros.
8. Fazer inventário de ativos e identificar sistemas antigos ou sem suporte.

## Relação com a aula

O caso mostra a relação direta entre ameaça, vulnerabilidade, risco e controle. A ameaça foi o ransomware WannaCry. A vulnerabilidade foi a falha no SMBv1 e a ausência de atualização em muitos ambientes. O risco se concretizou quando a ameaça explorou a vulnerabilidade. Os controles necessários envolvem atualização, backup, segmentação, conscientização e resposta a incidentes.
## Descrição do trabalho

Este repositório apresenta os conceitos fundamentais de segurança da informação, seus atributos principais, ameaças digitais comuns e um estudo de caso sobre o ataque ransomware WannaCry. O conteúdo foi organizado conforme a proposta da Aula 14.

## Arquivos principais

- `conceitos.md` - definição de segurança da informação e atributos principais.
- `ameacas.md` - ameaças, vulnerabilidades, riscos, impactos e boas práticas.
- `estudo_de_caso.md` - análise do ataque WannaCry, opção A do estudo de cenário.
- `reflexao_individual.md` - texto individual sobre o fator humano.
- `slides/apresentacao_aula14.pptx` - apresentação resumida do trabalho.
- `imagens/` - imagens dos slides da aula usadas no Markdown.
- `arquivos/` - PDF original da aula e materiais auxiliares.

# Reflexão Individual

## Por que o fator humano é considerado o elo mais frágil da segurança da informação?

O fator humano é considerado o elo mais frágil da segurança da informação porque, mesmo quando a organização possui boas ferramentas de proteção, as pessoas ainda podem tomar decisões que abrem caminho para ataques. Um sistema pode ter antivírus, firewall, criptografia e autenticação em duas etapas, mas basta um usuário clicar em um link falso, baixar um anexo malicioso ou informar sua senha em uma página falsa para que a segurança seja comprometida.

A engenharia social mostra muito bem esse problema. Em vez de atacar diretamente a tecnologia, o criminoso tenta manipular a pessoa. Ele pode criar uma mensagem com aparência de banco, escola, empresa ou serviço conhecido. Também pode usar medo, urgência ou curiosidade para fazer a vítima agir sem pensar. Frases como “sua conta será bloqueada”, “confirme seus dados agora” ou “abra este documento urgente” são exemplos de estratégias usadas para pressionar o usuário.

Outro ponto importante é que muitas falhas acontecem por hábitos comuns: usar senhas fracas, repetir a mesma senha em vários sites, deixar dispositivos desbloqueados, conectar pendrives desconhecidos, ignorar atualizações ou compartilhar informações sensíveis em locais inadequados. Essas atitudes parecem pequenas, mas podem gerar grandes consequências, como vazamento de dados, perda de arquivos, prejuízo financeiro e interrupção de serviços.

Por isso, a segurança da informação não depende apenas de tecnologia. Ela depende também de comportamento, atenção, treinamento e responsabilidade. A conscientização dos usuários é uma das medidas mais importantes para reduzir riscos. Quando as pessoas aprendem a desconfiar de mensagens suspeitas, criar senhas fortes, verificar links e proteger seus dispositivos, elas deixam de ser uma vulnerabilidade fácil e passam a fazer parte da proteção da organização.

Concluindo, o fator humano é frágil porque pessoas podem ser enganadas, agir com pressa ou cometer erros. Porém, com educação, boas práticas e cultura de segurança, esse ponto fraco pode ser transformado em uma defesa importante contra ameaças digitais.
