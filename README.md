📦 FiveM Admin Menu – OX Lib + OX Inventory

Um sistema administrativo simples e funcional desenvolvido para servidores FiveM, utilizando ox_lib, ox_inventory e recursos nativos.
O objetivo é oferecer um menu leve, odular e de fácil manutenção, com foco em ações rápidas de administração. m<img width="359" height="439" alt="Captura de ecrã 2025-11-20 110033" src="https://github.com/user-attachments/assets/bfc86563-f343-490f-891f-dabc74712797" />


✨ Funcionalidades
🧍 Player Actions

Ferramentas administrativas focadas em jogadores: <img width="365" height="163" alt="Captura de ecrã 2025-11-20 110006" src="https://github.com/user-attachments/assets/6e148508-9aa2-4405-af7d-0daa4918bebb" />
 

Reviver jogador

Teleportar até o jogador

Trazer jogador até você

Ativar/Desativar spectate

Dar arma

Dar item (com input de ID)

Kick

Ban

Menu de retorno a qualquer momento

🚗 Vehicle Actions

Ações relacionadas a veículos:

Spawn de veículos Deletar veículo próximo <img width="344" height="314" alt="Captura de ecrã 2025-11-20 105913" src="https://github.com/user-attachments/assets/fdf8838d-91a1-4e49-9203-a0a137ef38d0" />


Deletar veículo próximo

Opção de voltar ao menu principal

🛠️ Utility Actions

Ferramentas úteis para administração geral:

Reviver o próprio administrador

Ativar/Desativar noclip

Teleportar para a marcação (TPM)

Voltar ao menu principal

🎒 Integração com OX Inventory

Totalmente integrado com o ox_inventory:
Ao dar um item para um jogador, o item é adicionado diretamente ao inventário dele usando:

exports.ox_inventory:AddItem(itemName, count)


Os administradores podem dar itens rapidamente informando:

ID do jogador

Nome do item

Quantidade

🧩 Estrutura Modular

O script foi desenvolvido de forma organizada e modular:

Menus criados usando ox_lib.registerContext

Separação entre Client e Server

Funções reutilizáveis (reviver, spectate, noclip, spawn de veículos, etc.)

Sistema de permissões personalizável

📚 Requisitos

ox_lib

ox_inventory

FiveM (build atualizada)

OneSync ativado (para espectador e teleporte adequado)

🎯 Objetivo do Projeto

Fornecer um menu administrativo simples, funcional e altamente personalizável, que possa ser facilmente adaptado a qualquer servidor FiveM, seja RP, PvP ou servidores privados.
