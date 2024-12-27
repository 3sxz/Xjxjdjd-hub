# Xjxjdjd-hub print("Selecione um script para executar:")
print("1 - Infinite Yield")
print("2 - MM2 Script (GUI e Auto Farm Candy)")

local escolha = tonumber(io.read())

if escolha == 1 then
    print("Executando Script 1...")
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
elseif escolha == 2 then
    print("Executando Script 2...")
    -- MM2 Script GUI
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Au0yX/Community/main/XhubMM2"))()

    -- Auto Farm Candy
    loadstring(game:HttpGet("https://raw.githubusercontent.com/vexroxd/My-Script-/refs/heads/main/MM2-Candy-Farm"))()
else
    print("Opção inválida!")
end
