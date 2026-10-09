# PrimeSystemPDV 1.0.13 — Production / Stable

**Versão:** 1.0.13  
**Ambiente:** Production  
**Canal:** Stable  
**Schema:** 15  
**Instalador:** `PrimeSystemPDV_1.0.13_Setup.exe`  
**Tamanho:** 58.028.939 bytes  
**SHA-256:** `85d83c2bbbc8cd67b076c7058173d03e8222adeedb7eaf00e9fdb2cc9f21d06a`  
**Atualização obrigatória:** não  
**Versão mínima:** 1.0.3

## Alterações da versão

- Código automático de clientes não é mais consumido ao abrir ou cancelar o cadastro e reutiliza o menor código livre.
- Mensagens de WhatsApp, status e e-mail passam a usar os textos padrão configuráveis com variáveis da O.S. e da empresa.
- Assuntos de e-mail configuráveis passam a ser aplicados no envio ao cliente.
- Despesas/Saídas do Caixa passam a exibir o usuário autenticado corretamente.
- Tela de permissões recebeu destino mais claro entre perfil e usuário específico.
- Mensagens da integração Prime Folha foram ajustadas para uso comercial, sem rótulos internos de BETA/STAGING/Fase.
- Central de Aparelhos e Pagamentos da Equipe receberam limpeza visual sem alterar a arquitetura financeira.

## Integridade

Confirme o hash do instalador antes de distribuir:

```powershell
(Get-FileHash .\PrimeSystemPDV_1.0.13_Setup.exe -Algorithm SHA256).Hash.ToLowerInvariant()
```

Resultado esperado:

```text
85d83c2bbbc8cd67b076c7058173d03e8222adeedb7eaf00e9fdb2cc9f21d06a
```

## Publicação

A publicação comercial só estará completa após anexar o instalador à GitHub Release `v1.0.13-stable`, conferir a integridade do download e cadastrar o link no catálogo **Production/Stable** do Portal Cliente SousaHub. Não substituir o registro do instalador PILOTO até confirmar o funcionamento do link Stable. Licenças de Staging não ativam instaladores Production.

As informações de versão, integridade e alterações acima foram transcritas do manifesto gerado junto ao instalador em 09/10/2026.
