# Introdução

As apostas esportivas online ganharam espaço no Brasil nos últimos anos e passaram a movimentar valores relevantes no orçamento de muitas pessoas. Em levantamento nacional realizado em 2024, o DataSenado estimou que 16% dos brasileiros com 16 anos ou mais haviam feito apostas esportivas nos 30 dias anteriores à pesquisa. No mesmo ano, uma análise do Banco Central estimou cerca de 24 milhões de apostadores e uma média de R$ 20,8 bilhões enviados mensalmente às empresas de apostas entre janeiro e agosto de 2024 (DATASENADO, 2024; BANCO CENTRAL DO BRASIL, 2024). 

A prática de apostar não representa, por si só, um transtorno. O problema aparece quando há perda de controle, prioridade crescente dada ao jogo e continuidade mesmo diante de consequências negativas. A Organização Mundial da Saúde classifica o transtorno do jogo entre os transtornos decorrentes de comportamentos aditivos, e o Ministério da Saúde alerta para possíveis impactos financeiros, emocionais, familiares e profissionais associados ao uso problemático de apostas (WORLD HEALTH ORGANIZATION, 2024; BRASIL, 2026). 

Além do risco de perda financeira, existe uma dificuldade prática: quem utiliza mais de uma plataforma pode ter seus registros espalhados em diferentes contas e perder a noção do total gasto ao longo do mês. Sem uma visão consolidada, fica mais difícil perceber aumentos de frequência, comparar períodos e saber quanto as apostas estão comprometendo o orçamento disponível. 

O projeto propõe uma aplicação web voltada ao próprio usuário apostador, que poderá organizar manualmente suas movimentações, acompanhar resultados, definir um limite mensal, visualizar alertas e consultar a evolução dos gastos. A aplicação também reunirá orientações de uso, informações sobre jogo responsável e canais externos de ajuda, sem criar um fluxo interno de atendimento ou compartilhamento de dados com terceiros. 
 
A aplicação não terá recursos para indicar apostas, divulgar odds, recomendar casas de apostas ou estimular novas jogadas. O foco será exclusivamente o acompanhamento financeiro e a conscientização. Na primeira versão, todos os registros e configurações serão armazenados localmente no navegador do próprio usuário, sem autenticação, banco de dados remoto ou envio automático de informações para servidores externos.

## Problema

O problema central do projeto é a dificuldade de pessoas adultas que realizam apostas esportivas online acompanharem, de forma consolidada, quanto estão gastando e qual é o impacto desse comportamento em seu orçamento. A solução busca responder à seguinte questão: como oferecer uma visão simples dos gastos com apostas, permitindo que o usuário identifique aumentos, estabeleça limites, compare períodos e tome decisões com mais informação, sem incentivar a prática de apostar e mantendo seus registros financeiros armazenados localmente? 

## Objetivos

O objetivo geral é desenvolver uma aplicação web que ajude o usuário a acompanhar o impacto financeiro de suas apostas esportivas por meio do registro, da organização e da visualização das movimentações realizadas, mantendo os dados localmente no navegador. 

Como objetivos específicos, o projeto pretende permitir o cadastro e a organização das movimentações, calcular o resultado financeiro do período, apresentar indicadores em um painel, permitir a definição de limites mensais, emitir alertas de atenção, facilitar a comparação dos gastos ao longo do tempo e disponibilizar orientações de uso, informações sobre jogo responsável e canais externos de busca por ajuda especializada, preservando a privacidade dos registros financeiros.

## Justificativa

A escolha do tema se justifica pela dimensão que as apostas online alcançaram no país e pela dificuldade que parte dos usuários pode ter para perceber o impacto acumulado de pequenas movimentações. O Banco Central estimou que aproximadamente 24 milhões de pessoas realizaram transferências para empresas de apostas no período analisado em 2024. O DataSenado, em uma pesquisa com mais de 21 mil entrevistados, também identificou presença relevante das apostas esportivas na população brasileira (BANCO CENTRAL DO BRASIL, 2024; DATASENADO, 2024). 

O tema também envolve uma questão de saúde e de bem-estar financeiro. A Organização Mundial da Saúde aponta que os danos relacionados ao jogo podem ocorrer mesmo antes de um quadro clínico de transtorno e podem incluir dificuldade financeira, conflitos familiares e prejuízo à saúde mental. No Brasil, o Ministério da Saúde reforça que o transtorno do jogo pode estar relacionado à dificuldade de controlar o impulso de apostar mesmo diante de consequências negativas (WORLD HEALTH ORGANIZATION, 2024; BRASIL, 2026). 

Nesse contexto, uma ferramenta de acompanhamento pode funcionar como apoio à percepção do próprio comportamento. O projeto não pretende substituir atendimento psicológico, médico ou financeiro, nem garantir que o usuário deixe de apostar. A proposta é oferecer informações objetivas sobre valores, limites e evolução dos gastos, de modo que a pessoa consiga enxergar com mais clareza aquilo que muitas vezes fica disperso entre diferentes plataformas. Orientações de uso e canais externos de ajuda poderão ser apresentados de forma informativa, sem que a aplicação envie ou compartilhe os registros financeiros do usuário. 

## Cenário atual e proposta de melhoria 

As soluções disponíveis hoje costumam atuar em frentes diferentes. Ferramentas como BetBlocker e Gamban têm como foco principal bloquear ou restringir o acesso a sites e aplicativos de apostas, sendo úteis principalmente para quem deseja reduzir a exposição ou interromper o hábito (BETBLOCKER, 2026; GAMBAN, 2026). A proposta deste projeto segue outro caminho: concentrar os registros financeiros do próprio usuário, mesmo quando as apostas foram feitas em plataformas diferentes, e transformar esses dados em histórico, indicadores, limites, alertas e orientações. Assim, a melhoria pretendida não é criar mais um ambiente de apostas, mas uma ferramenta simples de controle financeiro voltada especificamente para esse contexto. Como limite tecnológico da primeira versão, os lançamentos serão feitos manualmente e todos os dados do sistema serão armazenados no próprio navegador, sem integração direta com casas de apostas, contas bancárias, banco de dados remoto ou área interna de atendimento. 

## Público-Alvo

O público-alvo é formado por pessoas maiores de 18 anos que realizam apostas esportivas online, de forma ocasional ou frequente, e querem acompanhar melhor os valores envolvidos nessa atividade. Esse mesmo perfil inclui pessoas que perceberam aumento nos gastos ou na frequência das apostas e procuram uma forma simples de monitorar ou reduzir esse comportamento. 

A solução considera usuários com diferentes níveis de familiaridade com tecnologia e finanças pessoais. Por isso, a interface deverá funcionar tanto em computador quanto em celular, utilizar linguagem direta e apresentar os principais dados sem exigir conhecimento técnico ou financeiro avançado. Profissionais ou instituições de apoio não constituem perfis de usuário da aplicação; quando necessário, poderão ser apresentados apenas como canais externos de orientação. 

Como os registros envolvem informações pessoais e financeiras, privacidade, discrição e facilidade de uso são pontos importantes. Os dados deverão permanecer armazenados localmente no navegador e não serão disponibilizados automaticamente a terceiros. A aplicação também deverá considerar acessibilidade, com boa legibilidade, navegação clara e elementos que possam ser utilizados por teclado e compreendidos sem depender apenas de cores. 
