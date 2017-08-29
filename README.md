# Microsoft Graph Samples

Este repositório tem como objetivo listar alguns exemplos de endpoints REST para obter dados da Microsoft Graph API

## Pessoas com quem trabalho
https://graph.microsoft.com/beta/me/people?$filter=personType%20eq%20'Person'%20and%20mailboxType%20eq%20'Mailbox'

## Obtem todos os Teams que participo
https://graph.microsoft.com/beta/me/joinedTeams

## Canais de um Team
https://graph.microsoft.com/beta/groups/ID-DO-TEAM/channels

## Membros de um time no Teams
https://graph.microsoft.com/beta/groups/ID-DO-TEAM/members

## Documentos de um time no Teams
https://graph.microsoft.com/beta/groups/ID-DO-TEAM/drive/list/items

## Obter a foto de um usuário pelo seu email
https://graph.microsoft.com/v1.0/users('usuario@email.com')/photo/$value

## Informações de um canal de um grupo do teams que faço parte
https://graph.microsoft.com/beta/groups/ID-DO-TEAM/channels/ID-DO-CANAL

## Documentos que estão em alta
https://graph.microsoft.com/beta/me/insights/trending

## Ultimos documentos que eu trabalhei
https://graph.microsoft.com/v1.0/me/drive/recent

## Meus documentos
https://graph.microsoft.com/v1.0/me/drive/root/children?$select=name

## Documentos compartilhados comigo
https://graph.microsoft.com/v1.0/me/drive/sharedWithMe

## Eventos no meu calendario do outlook em um determinado periodo
https://graph.microsoft.com/v1.0/me/calendarview?startdatetime=1017-04-30T19:00:00.0000000&enddatetime=2099-04-30T19:00:00.0000000

## Buscar usuário pelo inicio de seu display name
https://graph.microsoft.com/v1.0/users?$filter=(startswith('Fulano', displayName))

## Pessoas relacionadas a um tópico
https://graph.microsoft.com/beta/me/people/?$search="topic: topicoAqui"

## Url para um grupo no teams (link)
https://teams.microsoft.com/_#/conversations/Geral?threadId=19:{ID DO GRUPO}
