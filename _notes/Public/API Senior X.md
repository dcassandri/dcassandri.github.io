---
title : API Senior X
notetype : feed
date : 26-09-2021
---

# Api que devolve usuários associados a um papel

API: https://platform.senior.com.br/t/senior.com.br/bridge/1.0/rest/platform/authorization/queries/listRoleAssignedUsers

Método: POST

Payload:

```json
{"role":"HCM - Analista de GP - Coop0002","blockedUsers":false,"pagination":{"pageNumber":0,"pageSize":10}}
```

Response:

```json

{"users":[{"name":"greice_goncalves","fullName":"HMG Greice Elis Goncalves","email":"greice_goncalves@sicredi.com.br","assigned":true},{"name":"katrym_bez","fullName":"katrym  bez - Senior","email":"emailxyz@emailxyz.com.br","assigned":true}],"listInformation":{"totalElements":2,"totalPages":1}}

```