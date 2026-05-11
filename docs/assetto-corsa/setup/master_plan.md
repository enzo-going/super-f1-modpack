# Plano mestre — Assetto Corsa Super F1

## Objetivo

Transformar o Assetto Corsa na base principal do projeto Super F1, usando mods organizados por camadas e presets.

O objetivo não é acumular mods aleatórios, mas montar experiências coerentes de Fórmula 1 moderna e histórica.

## Camadas do projeto

| Camada | Função | Status |
|---|---|---|
| Content Manager | Launcher e gerenciador principal | Validado |
| Custom Shaders Patch | Base técnica, gráfica e física estendida | Validado |
| Pure / Weather FX | Clima, iluminação e atmosfera | Planejado |
| PPFilter | Ajuste visual final | Planejado |
| HUD / Apps | Interface, delta, mapa, pneus, telemetria | Planejado |
| Carros F1 modernos | Fórmula híbrida moderna | Planejado |
| Carros F1 históricos | Eras Senna, Schumacher e clássicos | Planejado |
| Pistas F1 | Pistas atuais, antigas e removidas | Planejado |
| Presets | Pacotes jogáveis por era/temporada | Planejado |
| Launcher Python | Interface própria do projeto | Futuro |

## Filosofia

Cada mod precisa ter função clara dentro do ecossistema.

Um carro, pista, filtro gráfico ou app só deve entrar se contribuir para uma experiência coerente.

## Presets prioritários

### Preset 1 — F1 2020

Objetivo: recriar uma experiência inspirada na temporada 2020.

Componentes desejados:

- carro base de alta qualidade
- skin pack da temporada
- capacetes, macacões e luvas
- pistas compatíveis
- HUD adequado
- configuração gráfica limpa
- preset salvo no Content Manager

### Preset 2 — Modern Dominance

Objetivo: carros modernos de alto desempenho, incluindo eras como Mercedes W11/Hamilton e Red Bull dominante.

### Preset 3 — Schumacher Era

Objetivo: experiência histórica focada na era Ferrari/Schumacher.

### Preset 4 — Senna Era

Objetivo: experiência histórica focada em Senna/McLaren e F1 clássica.

## Ordem de instalação

1. Validar base técnica
2. Instalar melhoria gráfica
3. Testar estabilidade
4. Instalar primeiro carro F1 moderno
5. Testar carro em pista padrão
6. Instalar skin pack
7. Instalar primeira pista adicional
8. Criar primeiro preset
9. Documentar tudo
10. Só então expandir para novos pacotes

## Regras

- Um mod por vez
- Teste após cada instalação
- Sem torrent
- Sem Google Drive aleatório
- Sem executáveis suspeitos
- Sem mod pago redistribuído ilegalmente
- Sem instalar pacotes em massa
- Sempre registrar fonte, versão, função e resultado

---

## Estratégia free-first

Nesta fase, o projeto prioriza mods gratuitos, seguros e de alto nível.

O objetivo é montar uma base forte antes de considerar conteúdo pago.

## Stack gratuita inicial

| Camada | Mod/Ferramenta | Status |
|---|---|---|
| Launcher | Content Manager Lite | Validado |
| Base técnica | Custom Shaders Patch recommended | Validado |
| Clima/atmosfera | Sol | Próximo alvo |
| PPFilter | C13 AEGIS Lite ou SKY | Planejado |
| HUD | F1 2020 HUD simples | Planejado |
| Carros | Mods gratuitos confiáveis primeiro; pagos só depois se fizer sentido | Planejado |
| Pistas | Pistas gratuitas confiáveis via OverTake e fontes reputadas | Planejado |

## Critério de entrada

Um mod gratuito só entra se cumprir:

1. fonte confiável;
2. compatibilidade com Assetto Corsa + CSP;
3. função clara no projeto;
4. ausência de executável suspeito;
5. possibilidade de remoção/restauração;
6. teste individual após instalação.

## Ordem free-first

1. Sol
2. PPFilter gratuito
3. teste visual
4. HUD simples estilo F1
5. primeiro carro F1 gratuito ou altamente confiável
6. primeira pista extra
7. preset inicial

---

## Revisão técnica — Sol em espera

Sol foi inicialmente considerado como primeira camada gratuita de clima/atmosfera.

Após validação, o projeto manterá Sol em espera porque a instalação atual usa CSP 0.2.11, e há relatos de incompatibilidade entre Sol 2.2.9 e CSP 0.2.10/0.2.11.

Decisão atual:

| Item | Decisão |
|---|---|
| CSP atual | Manter 0.2.11 |
| Sol | Não instalar agora |
| Próxima camada visual | PPFilter gratuito compatível com CSP |
| Motivo | Evitar downgrade/troca de CSP antes de consolidar a base |

## Próximo alvo gráfico

Prioridade atual:

1. PPFilter gratuito
2. Teste visual
3. Só depois decidir sobre clima avançado
