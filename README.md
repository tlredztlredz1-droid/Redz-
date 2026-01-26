-- Verifica o ID do lugar (PlaceId) e define a world correta
if game.PlaceId == 2753915549 then
    World1 = true
elseif game.PlaceId == 4442272183 then
    World2 = true
elseif game.PlaceId == 7449423635 then
    World3 = true
else
    game:GetService("Players").LocalPlayer:Kick("Do not Support, redz waid ...")
end

-- Carrega a biblioteca
local redzlib = loadstring(game:HttpGet("https://raw.githubusercontent.com/tbao143/Library-ui/refs/heads/main/Redzhubui"))()

-- Cria a janela com as configurações
local Window = redzlib:MakeWindow({
    Title = "redz Hub : Blox Fruits",
    SubTitle = "by redz9999",
    SaveFolder = "testando | redz lib v5.lua",
    Theme = "Dark"
})

-- Adiciona botão de minimizar com estilo
Window:AddMinimizeButton({
    Button = {
        Image = "rbxassetid://133032272724948",
        BackgroundTransparency = 0
    },
    Corner = {
        CornerRadius = UDim.new(0, 5)
    }
})

-- Adiciona abas
local Tab0 = Window:MakeTab({"Discord", "rbxassetid://86641106722992"})
local Tab1 = Window:MakeTab({"farm", "home"})
local Tab2 = Window:MakeTab({"envento", "waves"})
local Tab3 = Window:MakeTab({"Itens", "swords"})
local Tab4 = Window:MakeTab({"Um", "gem"})
local Tab5 = Window:MakeTab({"Um", "cherry"})
local Tab6 = Window:MakeTab({"Um", "rbxassetid://123469286761895"})
local Tab7 = Window:MakeTab({"Um", "rbxassetid://4483345998"})
local Tab8 = Window:MakeTab({"Um", "settings"})

-- Fim do carregamento da biblioteca redz


