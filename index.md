---
layout: default
---

# O quê é XP Mod?

XP Mod é um complemento para o HideNSeek.<br>
Os jogadores ganham pontos de XP por quão bem eles jogam.

## Primeira vez jogando?

Ao jogar pela primeira vez, você recebe 1000 de XP!<br>
Você ganha XP baseado na sua jogabilidade, e poderá comprar mais upgrades nos menus.

### Comandos
``` sourcepawn
!xp, !cm, !mm, !store Abre o menu principal do XP Mod
!hide Esconde / Mostra o rastro dos jogadores
```
## Modos de jogo

* ### Com Bloco

Mapas onde são criados "spots" que utilizam blocos com diversas finalidades. Ex: Ganhar arma; recuperar vida; escorregar.<br>
* ### No Block

Em todos os mapas com final `_noblock` Exemplo: `hns_devblocks_v4_noblock`<br>
Os UPGRADES são desativados para não desbalancear o modo.<br>
Você ganhará xp extra por sobreviver de TERRORISTA<br>

#### Todos os terroristas receberão:
* 2 Flashbangs
* 1 Frost Nade

### O quê mais muda no No Block?

|  | TR's | CT's |
|:----------------|:----------------|:----------------|
| 20% Redução no dano de queda | ✓ | ✓ |
| Regeneração de vida | ✕ | ✓ |
| Imune a facadas por 3 segundos | ✓ | ✕ |

* * *

## Como ganho XP?

| Em Mapas | Com Bloco | No Block |
|:----------------|:----------------|:----------------|
| Ações     | XP    | XP    |
| Matar     | +65 XP | +45 XP |
| Matar com `HE` | +20 XP | 0 XP |
| Matar de `HS`    | +50 XP | 0 XP |
| Suicídio      | -25 XP | -35 XP |
| Sobreviver de TR | +10 XP | +60 XP |
| Ganhar o Round | +15 XP | +50 XP |
| Jogar no servidor | +5 XP | +10 XP |

Com esses pontos de XP, você pode comprar upgrades. <br>
Para obter a lista desses upgrades, digite !xp e visualize os outros menus.

* * *

## Menu de Granadas

> A habilidade `Granadas` no XP Mod é apenas para terroristas.<br>
> A habilidade `Granadas` contém HE Grenade, 2 Flashbangs e uma Frost Nade.<br>
> Estas são as `Granadas` que você receberá no começo de cada round.

|  | HE Grenade | Flashbang #1 | Flashbang #2 | Frost Nade |
|:-------------|:-------------|:------------------|:-------------|:------------------|
| Intervalos de chance | 12.5% | 25% | 25% | 25% |
| Nível máximo | 8 | 4 | 4 | 4 |
| Chance máxima | 100% | 100% | 100% | 100% |

## Menu de Vida Extra

> A habilidade de `Vida Extra` é a quantidade de `Vida` a mais que você receberá em cada round.

| Time | Terrorista | CT's |
|:-------------|:-------------|:------------------|
| Intervalos de vida | 10 HP | 10 HP |
| Nível máximo | 10 | 5 |
| Vida máxima | 200 HP | 150 HP |

## Menu de Colete Extra

> A habilidade de `Colete Extra` é a quantidade de `Colete` a mais que você receberá.

| Time | Terrorista | CT's |
|:-------------|:-------------|:------------------|
| Intervalos de colete | 25 AP | 25 AP |
| Nível máximo | 8 | 6 |
| Colete máximo | 200 AP | 150 AP |

### Por que comprar colete?
> Colete é um item importantíssimo para os `CT's`, como os terroristas podem comprar HE.

## Menu de Respawn

> A habilidade `Respawn` é chance de reviver após morrer.

| Time | Terrorista | CT's |
|:-------------|:-------------|:------------------|
| Intervalos de chance | 15% | 25% |
| Nível máximo | 3 | 4 |
| Chance máxima | 45% | 100% |

> Digite !reviveme viver (dependendo da porcentagem que tiver adquirido).

## Menu de Dano de queda

> A habilidade de `dano de queda` reduz a quantidade de dano causado pela queda.

| Time | Terrorista | CT's |
|:-------------|:-------------|:------------------|
| Intervalos de redução | 10% | 10% |
| Nível máximo | 8 | 8 |
| Redução máxima | 80% | 80% |

#### Donate
* [Steam Trade Offer](https://steamcommunity.com/tradeoffer/new/?partner=86976147&token=P6xfDcHF)

#### TO-DO
``` sourcepawn
+ Adicionar
- Remover
* Modificar

+ Site para vender VIP por skins de CS:GO.

+ Fazer !rank e um !top10 para recompensar os melhores jogadores com XP EXTRA!
+ Fazer com que players que não possuam vip possam comprar `Skins e Rastros` com XP

+ new g_xptotal[ MAXPLAYERS + 1 ]; (TOP 10)
+ new g_pFirstPlayed[ MAXPLAYERS + 1 ]; (site)
+ new g_pLastSeen[ MAXPLAYERS + 1 ]; (site)
+ new g_pTotalTimePlayed[ MAXPLAYERS + 1 ]; (site)

:TALVEZ:
+ Menu de Habilidade
+ Anti-Flash ( % por flash tacada )
+ Dano Extra

* Como estou salvando o xp
```

##### Updates recentes
``` sourcepawn 
UPDATE > 1.7.4: 
+ Player Skins (models) para os jogadores
+ Rastros (trais) para os jogadores
```
