# PROJETO-2023
O projeto é um autômato de manivela

Composto por 4 partes que funcionam individualmente

Para abrir as pastas dos sub-assemblies no assembly geral...
Antes de abrir, ir em Options -> From Search Folders -> "+" -> /pasta/do/projeto...
(Digite 3 pontos no final da pasta sem colocar "/")

## R1

- [X] Montagem 
- [X] Simulação Individual

## R2 
- [X] Montagem
- [X] Simulação Individual
A montagem foi refeita com constraints locais
Foi adicionada uma peça de encaixe para o eixo secundário
Joints -> Revolute onde se deve, Slider no foguinho

## R3
- [X] Montagem
- [X] "Simulação Individual" (Mais ou menos)

A montagem foi refeita com constraints "meio soltas" ex: "Fit"
Os parafusos foram removidos e substituídos por "bastões universais"
Joints -> Não usar dois Revolutes em um único Motion Body, prefira o Contact 3D

OBS:O render com contact 3d das bevel-gears é muito longo...
## R4 
- [X] Montagem -> Apenas reoganizar para caber na mesa
- [X] Simulação Individual

Os problemas da simulação são:
	- [] Contact 3d entre o braço e o tronco leva muito tempo no solve
	- [] Contact 3d entre o braço e o tronco não encaixa corretamente
	- [] [BUG] Por algum motivo, na segunda "hélice" da engrenagem o personagem cai mais que o esperado