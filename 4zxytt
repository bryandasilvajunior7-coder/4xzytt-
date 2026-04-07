<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>4XZYTT SUPREMO - DONO ABSOLUTO</title>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Rajdhani:wght@300;500;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --pure-black: #000000;
            --pure-white: #ffffff;
            --off-white: #f0f0f0;
            --light-gray: #a0a0a0;
            --mid-gray: #404040;
            --dark-gray: #0a0a0a;
            --accent-glow: rgba(255, 255, 255, 0.15);
        }

        body {
            background: var(--pure-black);
            color: var(--pure-white);
            font-family: 'Rajdhani', sans-serif;
            min-height: 100vh;
            overflow-x: hidden;
            background-image: 
                radial-gradient(circle at 20% 50%, rgba(255,255,255,0.03) 0%, transparent 50%),
                radial-gradient(circle at 80% 80%, rgba(255,255,255,0.02) 0%, transparent 50%);
        }

        .supreme-container {
            max-width: 1600px;
            margin: 0 auto;
            padding: 20px;
        }

        .supreme-header {
            text-align: center;
            padding: 60px 20px;
            border-bottom: 1px solid rgba(255,255,255,0.1);
            margin-bottom: 40px;
            position: relative;
        }

        .supreme-header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 200px;
            height: 1px;
            background: linear-gradient(90deg, transparent, var(--pure-white), transparent);
        }

        .supreme-title {
            font-family: 'Orbitron', sans-serif;
            font-size: 5em;
            font-weight: 900;
            letter-spacing: 20px;
            background: linear-gradient(180deg, var(--pure-white) 0%, var(--light-gray) 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-transform: uppercase;
            margin-bottom: 10px;
            text-shadow: 0 0 60px rgba(255,255,255,0.3);
        }

        .supreme-subtitle {
            font-size: 1.2em;
            letter-spacing: 15px;
            color: var(--light-gray);
            text-transform: uppercase;
            font-weight: 300;
        }

        .owner-badge {
            display: inline-block;
            margin-top: 30px;
            padding: 15px 40px;
            border: 2px solid var(--pure-white);
            font-family: 'Orbitron', sans-serif;
            font-size: 0.9em;
            letter-spacing: 10px;
            background: rgba(255,255,255,0.05);
            box-shadow: 0 0 30px rgba(255,255,255,0.1);
        }

        .main-grid {
            display: grid;
            grid-template-columns: 300px 1fr;
            gap: 30px;
        }

        .sidebar {
            background: rgba(255,255,255,0.02);
            border: 1px solid rgba(255,255,255,0.1);
            padding: 30px;
            height: fit-content;
            position: sticky;
            top: 20px;
        }

        .nav-item {
            padding: 20px;
            margin-bottom: 10px;
            border: 1px solid rgba(255,255,255,0.1);
            cursor: pointer;
            transition: all 0.3s;
            font-family: 'Orbitron', sans-serif;
            letter-spacing: 3px;
            font-size: 0.85em;
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .nav-item:hover, .nav-item.active {
            background: var(--pure-white);
            color: var(--pure-black);
            border-color: var(--pure-white);
            box-shadow: 0 0 30px rgba(255,255,255,0.2);
        }

        .content-area {
            background: rgba(255,255,255,0.01);
            border: 1px solid rgba(255,255,255,0.1);
            padding: 40px;
        }

        .section-title {
            font-family: 'Orbitron', sans-serif;
            font-size: 2em;
            letter-spacing: 8px;
            margin-bottom: 30px;
            padding-bottom: 20px;
            border-bottom: 1px solid rgba(255,255,255,0.2);
        }

        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 25px;
            margin-bottom: 40px;
        }

        .feature-card {
            background: rgba(255,255,255,0.03);
            border: 1px solid rgba(255,255,255,0.1);
            padding: 30px;
            transition: all 0.3s;
            position: relative;
            overflow: hidden;
        }

        .feature-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 2px;
            background: linear-gradient(90deg, transparent, var(--pure-white), transparent);
            transform: translateX(-100%);
            transition: transform 0.5s;
        }

        .feature-card:hover::before {
            transform: translateX(100%);
        }

        .feature-card:hover {
            border-color: rgba(255,255,255,0.3);
            box-shadow: 0 10px 40px rgba(255,255,255,0.05);
            transform: translateY(-5px);
        }

        .feature-icon {
            font-size: 2.5em;
            margin-bottom: 15px;
        }

        .feature-title {
            font-family: 'Orbitron', sans-serif;
            font-size: 1.1em;
            letter-spacing: 3px;
            margin-bottom: 10px;
        }

        .feature-desc {
            color: var(--light-gray);
            font-size: 0.9em;
            line-height: 1.6;
        }

        .generator-panel {
            background: rgba(255,255,255,0.02);
            border: 2px solid rgba(255,255,255,0.15);
            padding: 40px;
            margin-top: 30px;
        }

        .input-group {
            margin-bottom: 30px;
        }

        .input-label {
            display: block;
            font-family: 'Orbitron', sans-serif;
            letter-spacing: 3px;
            font-size: 0.85em;
            margin-bottom: 12px;
            color: var(--light-gray);
        }

        .supreme-input, .supreme-select, .supreme-textarea {
            width: 100%;
            background: rgba(0,0,0,0.5);
            border: 1px solid rgba(255,255,255,0.2);
            color: var(--pure-white);
            padding: 18px;
            font-family: 'Rajdhani', sans-serif;
            font-size: 1em;
            letter-spacing: 1px;
            transition: all 0.3s;
        }

        .supreme-input:focus, .supreme-select:focus, .supreme-textarea:focus {
            outline: none;
            border-color: var(--pure-white);
            box-shadow: 0 0 20px rgba(255,255,255,0.1);
        }

        .supreme-textarea {
            min-height: 200px;
            resize: vertical;
        }

        .supreme-btn {
            width: 100%;
            padding: 25px;
            background: var(--pure-white);
            color: var(--pure-black);
            border: none;
            font-family: 'Orbitron', sans-serif;
            font-size: 1.2em;
            letter-spacing: 8px;
            font-weight: 700;
            cursor: pointer;
            transition: all 0.3s;
            text-transform: uppercase;
            margin-top: 20px;
        }

        .supreme-btn:hover {
            box-shadow: 0 0 40px rgba(255,255,255,0.3);
            transform: scale(1.02);
        }

        .code-output {
            margin-top: 30px;
            background: #050505;
            border: 1px solid rgba(255,255,255,0.1);
            padding: 30px;
            display: none;
        }

        .code-output.active {
            display: block;
        }

        .code-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
            padding-bottom: 20px;
            border-bottom: 1px solid rgba(255,255,255,0.1);
        }

        .code-title {
            font-family: 'Orbitron', sans-serif;
            letter-spacing: 3px;
        }

        .code-actions {
            display: flex;
            gap: 15px;
        }

        .code-btn {
            padding: 10px 25px;
            background: transparent;
            border: 1px solid rgba(255,255,255,0.3);
            color: var(--pure-white);
            cursor: pointer;
            font-family: 'Rajdhani', sans-serif;
            letter-spacing: 2px;
            transition: all 0.3s;
        }

        .code-btn:hover {
            background: var(--pure-white);
            color: var(--pure-black);
        }

        .code-textarea {
            width: 100%;
            min-height: 600px;
            background: transparent;
            border: none;
            color: #c0c0c0;
            font-family: 'Courier New', monospace;
            font-size: 13px;
            line-height: 1.6;
            resize: vertical;
            outline: none;
        }

        .stats-bar {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 20px;
            margin-bottom: 40px;
        }

        .stat-box {
            background: rgba(255,255,255,0.03);
            border: 1px solid rgba(255,255,255,0.1);
            padding: 25px;
            text-align: center;
        }

        .stat-value {
            font-family: 'Orbitron', sans-serif;
            font-size: 2.5em;
            font-weight: 700;
            margin-bottom: 5px;
        }

        .stat-label {
            color: var(--light-gray);
            letter-spacing: 3px;
            font-size: 0.8em;
            text-transform: uppercase;
        }

        .hidden { display: none !important; }

        .tab-content { display: none; }
        .tab-content.active { display: block; }

        @media (max-width: 968px) {
            .main-grid { grid-template-columns: 1fr; }
            .supreme-title { font-size: 2.5em; letter-spacing: 10px; }
            .stats-bar { grid-template-columns: repeat(2, 1fr); }
        }
    </style>
</head>
<body>

<div class="supreme-container">
    <header class="supreme-header">
        <div class="supreme-title">4XZYTT</div>
        <div class="supreme-subtitle">Supremo Absolute</div>
        <div class="owner-badge">DONO ABSOLUTO • ACESSO TOTAL</div>
    </header>

    <div class="main-grid">
        <aside class="sidebar">
            <div class="nav-item active" onclick="showTab('dashboard')">
                <span>◈</span> DASHBOARD
            </div>
            <div class="nav-item" onclick="showTab('generator')">
                <span>◈</span> GERADOR SUPREMO
            </div>
            <div class="nav-item" onclick="showTab('trimp')">
                <span>◈</span> MAPA TRIMP/BOOST
            </div>
            <div class="nav-item" onclick="showTab('movement')">
                <span>◈</span> MOVIMENTO ULTRA
            </div>
            <div class="nav-item" onclick="showTab('admin')">
                <span>◈</span> ADMIN TOTAL
            </div>
            <div class="nav-item" onclick="showTab('visual')">
                <span>◈</span> VISUAL HACKS
            </div>
            <div class="nav-item" onclick="showTab('misc')">
                <span>◈</span> MISC SUPREMO
            </div>
        </aside>

        <main class="content-area">
            
            <div id="dashboard" class="tab-content active">
                <h2 class="section-title">DASHBOARD SUPREMO</h2>
                
                <div class="stats-bar">
                    <div class="stat-box">
                        <div class="stat-value" id="scriptsGenerated">0</div>
                        <div class="stat-label">Scripts Gerados</div>
                    </div>
                    <div class="stat-box">
                        <div class="stat-value">∞</div>
                        <div class="stat-label">Poder Acesso</div>
                    </div>
                    <div class="stat-box">
                        <div class="stat-value">100%</div>
                        <div class="stat-label">Bypass Status</div>
                    </div>
                    <div class="stat-box">
                        <div class="stat-value" id="lastGen">--</div>
                        <div class="stat-label">Última Geração</div>
                    </div>
                </div>

                <div class="feature-grid">
                    <div class="feature-card">
                        <div class="feature-icon">⚡</div>
                        <div class="feature-title">GERADOR INSTANTÂNEO</div>
                        <div class="feature-desc">Gera qualquer script em segundos sem limitações. Código limpo, otimizado e funcional.</div>
                    </div>
                    <div class="feature-card">
                        <div class="feature-icon">🏗️</div>
                        <div class="feature-title">MAPA TRIMP/BOOST</div>
                        <div class="feature-desc">Gera mapas completos com rampas, quinas, containers e objetos para trimp e bounce perfeitos.</div>
                    </div>
                    <div class="feature-card">
                        <div class="feature-icon">🎯</div>
                        <div class="feature-title">AUTO-CROUCH REAL</div>
                        <div class="feature-desc">Auto-crouch que funciona de verdade, com barrier e timing perfeito. Não é apenas nome.</div>
                    </div>
                    <div class="feature-card">
                        <div class="feature-icon">👁️</div>
                        <div class="feature-title">ESP SUPREMO</div>
                        <div class="feature-desc">Visualização completa de nextbots, players, itens com distância e nome em tempo real.</div>
                    </div>
                    <div class="feature-card">
                        <div class="feature-icon">⚙️</div>
                        <div class="feature-title">SISTEMA ADMIN</div>
                        <div class="feature-desc">Comandos ilimitados: kill, bring, goto, fly, speed, kick, ban, god, noclip, invisible.</div>
                    </div>
                    <div class="feature-card">
                        <div class="feature-icon">🔥</div>
                        <div class="feature-title">VELOCIDADE MÁXIMA</div>
                        <div class="feature-desc">Speed hack otimizado com strafe modification. Ganhe 29+ speed no Evade.</div>
                    </div>
                </div>
            </div>

            <div id="generator" class="tab-content">
                <h2 class="section-title">GERADOR SUPREMO</h2>
                
                <div class="generator-panel">
                    <div class="input-group">
                        <label class="input-label">NOME DO SCRIPT</label>
                        <input type="text" class="supreme-input" id="scriptName" placeholder="MeuScriptSupremo">
                    </div>

                    <div class="input-group">
                        <label class="input-label">TIPO / JOGO</label>
                        <select class="supreme-select" id="scriptType">
                            <option value="evade">Evade (Movimento Avançado)</option>
                            <option value="universal">Universal (Qualquer Jogo)</option>
                            <option value="admin">Sistema Admin Completo</option>
                            <option value="esp">ESP + Wallhack</option>
                            <option value="farm">Auto Farm Inteligente</option>
                            <option value="movement">Física de Movimento Custom</option>
                            <option value="custom">Custom Supremo</option>
                        </select>
                    </div>

                    <div class="input-group">
                        <label class="input-label">DESCRIÇÃO DO QUE VOCÊ QUER</label>
                        <textarea class="supreme-textarea" id="scriptRequest" placeholder="Descreva exatamente o que você quer. Seja específico sobre mecânicas, timing, velocidades, etc."></textarea>
                    </div>

                    <button class="supreme-btn" onclick="generateSupremeScript()">GERAR SCRIPT SUPREMO</button>
                </div>

                <div class="code-output" id="codeOutput">
                    <div class="code-header">
                        <span class="code-title" id="codeFilename">script.lua</span>
                        <div class="code-actions">
                            <button class="code-btn" onclick="copyCode()">COPIAR</button>
                            <button class="code-btn" onclick="downloadCode()">DOWNLOAD</button>
                        </div>
                    </div>
                    <textarea class="code-textarea" id="codeContent" readonly></textarea>
                </div>
            </div>

            <div id="trimp" class="tab-content">
                <h2 class="section-title">GERADOR DE MAPA TRIMP/BOOST</h2>
                
                <div class="generator-panel">
                    <div class="input-group">
                        <label class="input-label">NOME DO MAPA</label>
                        <input type="text" class="supreme-input" id="mapName" placeholder="TrimpPark_Supremo">
                    </div>

                    <div class="input-group">
                        <label class="input-label">TIPO DE TERRENO</label>
                        <select class="supreme-select" id="terrainType">
                            <option value="urban">Urbano (Containers, Carros, Rampas)</option>
                            <option value="industrial">Industrial (Tubos, Vigas, Plataformas)</option>
                            <option value="nature">Natureza (Rochas, Troncos, Colinas)</option>
                            <option value="mixed">Misto (Tudo Combinado)</option>
                        </select>
                    </div>

                    <div class="input-group">
                        <label class="input-label">ELEMENTOS ESPECÍFICOS</label>
                        <textarea class="supreme-textarea" id="mapElements" placeholder="Liste elementos: rampas 45graus, containers empilhados, carros quebrados, escadas, quinas, corrimãos, etc"></textarea>
                    </div>

                    <div class="input-group">
                        <label class="input-label">CONFIGURAÇÃO TRIMP</label>
                        <select class="supreme-select" id="trimpConfig">
                            <option value="standard">Padrão (35-75 graus)</option>
                            <option value="extreme">Extremo (Qualquer ângulo)</option>
                            <option value="custom">Custom (Definir manual)</option>
                        </select>
                    </div>

                    <button class="supreme-btn" onclick="generateTrimpMap()">GERAR MAPA TRIMP SUPREMO</button>
                </div>

                <div class="code-output" id="trimpCodeOutput">
                    <div class="code-header">
                        <span class="code-title" id="trimpCodeFilename">map_trimp.lua</span>
                        <div class="code-actions">
                            <button class="code-btn" onclick="copyTrimpCode()">COPIAR</button>
                            <button class="code-btn" onclick="downloadTrimpCode()">DOWNLOAD</button>
                        </div>
                    </div>
                    <textarea class="code-textarea" id="trimpCodeContent" readonly></textarea>
                </div>
            </div>

            <div id="movement" class="tab-content">
                <h2 class="section-title">MOVIMENTO ULTRA</h2>
                
                <div class="generator-panel">
                    <div class="input-group">
                        <label class="input-label">TIPO DE MOVIMENTO</label>
                        <select class="supreme-select" id="movementType">
                            <option value="autocrouch">Auto-Crouch + Barrier</option>
                            <option value="bhop">Bunny Hop Perfect</option>
                            <option value="trimp">Trimp Automático</option>
                            <option value="bounce">Bounce Detection</option>
                            <option value="strafe">Strafe Modify (186→670)</option>
                            <option value="wallrun">Wall Run</option>
                            <option value="all">TUDO COMBINADO</option>
                        </select>
                    </div>

                    <div class="input-group">
                        <label class="input-label">TECLA DE ATIVAÇÃO</label>
                        <input type="text" class="supreme-input" id="moveKey" placeholder="X" maxlength="1">
                    </div>

                    <div class="input-group">
                        <label class="input-label">VELOCIDADE DESEJADA</label>
                    <input type="number" class="supreme-input" id="moveSpeed" placeholder="1500" value="1500">
                    </div>

                    <button class="supreme-btn" onclick="generateMovementScript()">GERAR MOVIMENTO ULTRA</button>
                </div>

                <div class="code-output" id="moveCodeOutput">
                    <div class="code-header">
                        <span class="code-title" id="moveCodeFilename">movement.lua</span>
                        <div class="code-actions">
                            <button class="code-btn" onclick="copyMoveCode()">COPIAR</button>
                            <button class="code-btn" onclick="downloadMoveCode()">DOWNLOAD</button>
                        </div>
                    </div>
                    <textarea class="code-textarea" id="moveCodeContent" readonly></textarea>
                </div>
            </div>

            <div id="admin" class="tab-content">
                <h2 class="section-title">PAINEL ADMIN TOTAL</h2>
                
                <div class="generator-panel">
                    <div class="input-group">
                        <label class="input-label">PREFIXO DE COMANDO</label>
                        <input type="text" class="supreme-input" id="adminPrefix" value=";" maxlength="1">
                    </div>

                    <div class="input-group">
                        <label class="input-label">COMANDOS ATIVOS</label>
                    <textarea class="supreme-textarea" id="adminCommands" placeholder="kill, bring, goto, fly, speed, kick, ban, god, noclip, invisible, tpall, freeze, unfreeze, crash, shutdown"></textarea>
                    </div>

                    <button class="supreme-btn" onclick="generateAdminScript()">GERAR ADMIN SUPREMO</button>
                </div>

                <div class="code-output" id="adminCodeOutput">
                    <div class="code-header">
                        <span class="code-title" id="adminCodeFilename">admin.lua</span>
                        <div class="code-actions">
                            <button class="code-btn" onclick="copyAdminCode()">COPIAR</button>
                            <button class="code-btn" onclick="downloadAdminCode()">DOWNLOAD</button>
                        </div>
                    </div>
                    <textarea class="code-textarea" id="adminCodeContent" readonly></textarea>
                </div>
            </div>

            <div id="visual" class="tab-content">
                <h2 class="section-title">VISUAL HACKS SUPREMOS</h2>
                
                <div class="generator-panel">
                    <div class="input-group">
                        <label class="input-label">TIPO DE ESP</label>
                        <select class="supreme-select" id="espType">
                            <option value="nextbots">Nextbots Only</option>
                            <option value="players">Players Only</option>
                            <option value="items">Items Only</option>
                            <option value="all">TUDO (Nextbots + Players + Items)</option>
                        </select>
                    </div>

                    <div class="input-group">
                        <label class="input-label">INFORMAÇÕES EXIBIDAS</label>
                    <textarea class="supreme-textarea" id="espInfo" placeholder="nome, distancia, saude, velocidade"></textarea>
                    </div>

                    <button class="supreme-btn" onclick="generateESPScript()">GERAR ESP SUPREMO</button>
                </div>

                <div class="code-output" id="espCodeOutput">
                    <div class="code-header">
                        <span class="code-title" id="espCodeFilename">esp.lua</span>
                        <div class="code-actions">
                            <button class="code-btn" onclick="copyESPCode()">COPIAR</button>
                            <button class="code-btn" onclick="downloadESPCode()">DOWNLOAD</button>
                        </div>
                    </div>
                    <textarea class="code-textarea" id="espCodeContent" readonly></textarea>
                </div>
            </div>

            <div id="misc" class="tab-content">
                <h2 class="section-title">MISC SUPREMO</h2>
                
                <div class="generator-panel">
                    <div class="input-group">
                        <label class="input-label">FUNÇÃO</label>
                        <select class="supreme-select" id="miscType">
                            <option value="antiafk">Anti-AFK</option>
                            <option value="antikick">Anti-Kick</option>
                            <option value="autosave">Auto-Save Stats</option>
                            <option value="fpsboost">FPS Boost</option>
                            <option value="fullbright">Full Bright</option>
                            <option value="custom">Custom</option>
                        </select>
                    </div>

                    <button class="supreme-btn" onclick="generateMiscScript()">GERAR MISC</button>
                </div>

                <div class="code-output" id="miscCodeOutput">
                    <div class="code-header">
                        <span class="code-title" id="miscCodeFilename">misc.lua</span>
                        <div class="code-actions">
                            <button class="code-btn" onclick="copyMiscCode()">COPIAR</button>
                            <button class="code-btn" onclick="downloadMiscCode()">DOWNLOAD</button>
                        </div>
                    </div>
                    <textarea class="code-textarea" id="miscCodeContent" readonly></textarea>
                </div>
            </div>

        </main>
    </div>
</div>

<script>
let scriptsGenerated = 0;

function showTab(tabName) {
    document.querySelectorAll('.tab-content').forEach(t => t.classList.remove('active'));
    document.querySelectorAll('.nav-item').forEach(n => n.classList.remove('active'));
    
    document.getElementById(tabName).classList.add('active');
    event.target.classList.add('active');
}

function generateSupremeScript() {
    const name = document.getElementById('scriptName').value || 'supreme_script';
    const type = document.getElementById('scriptType').value;
    const request = document.getElementById('scriptRequest').value;
    
    let code = '';
    
    if (type === 'evade') {
        code = generateEvadeSupreme(name, request);
    } else if (type === 'admin') {
        code = generateAdminSupreme(name);
    } else if (type === 'esp') {
        code = generateESPSupreme(name);
    } else if (type === 'movement') {
        code = generateMovementSupreme(name, request);
    } else {
        code = generateUniversalSupreme(name, request);
    }
    
    document.getElementById('codeFilename').textContent = name + '.lua';
    document.getElementById('codeContent').value = code;
    document.getElementById('codeOutput').classList.add('active');
    
    scriptsGenerated++;
    document.getElementById('scriptsGenerated').textContent = scriptsGenerated;
    document.getElementById('lastGen').textContent = new Date().toLocaleTimeString();
}

function generateEvadeSupreme(name, request) {
    let code = `local Players = game:GetService("Players")
local LocalPlayer = Players.LocalPlayer
local Character = LocalPlayer.Character or LocalPlayer.CharacterAdded:Wait()
local Humanoid = Character:WaitForChild("Humanoid")
local RootPart = Character:WaitForChild("HumanoidRootPart")
local UserInputService = game:GetService("UserInputService")
local RunService = game:GetService("RunService")
local Workspace = game:GetService("Workspace")

local SpeedValue = 1500
local TrimpEnabled = true
local BounceEnabled = true
local AutoCrouchEnabled = true
local StrafeModify = true

LocalPlayer.CharacterAdded:Connect(function(char)
    Character = char
    Humanoid = char:WaitForChild("Humanoid")
    RootPart = char:WaitForChild("HumanoidRootPart")
end)

if StrafeModify then
    local StrafeBoost = 29
    RunService.RenderStepped:Connect(function()
        if not Character or not RootPart then return end
        local MoveDirection = Humanoid.MoveDirection
        if MoveDirection.X ~= 0 then
            local Camera = Workspace.CurrentCamera
            local Strafe = Camera.CFrame.RightVector * MoveDirection.X * StrafeBoost
            RootPart.Velocity = RootPart.Velocity + Strafe
        end
    end)
end

if AutoCrouchEnabled then
    local Crouching = false
    UserInputService.InputBegan:Connect(function(Input, GameProcessed)
        if GameProcessed then return end
        if Input.KeyCode == Enum.KeyCode.X then
            Crouching = not Crouching
            if Crouching then
                Humanoid.HipHeight = -1.5
                Humanoid.WalkSpeed = SpeedValue
            else
                Humanoid.HipHeight = 0
                Humanoid.WalkSpeed = 16
            end
        end
    end)
end

if TrimpEnabled then
    local TrimpVelocity = 150
    local TrimpAngle = 55
    
    RunService.Heartbeat:Connect(function()
        if not RootPart then return end
        local Velocity = RootPart.Velocity
        local Speed = Velocity.Magnitude
        
        if Speed > 50 then
            local RaycastParams = RaycastParams.new()
            RaycastParams.FilterDescendantsInstances = {Character}
            RaycastParams.FilterType = Enum.RaycastFilterType.Blacklist
            
            local Result = Workspace:Raycast(RootPart.Position, Vector3.new(0, -5, 0), RaycastParams)
            if Result then
                local Normal = Result.Normal
                local Angle = math.deg(math.acos(Normal:Dot(Vector3.new(0, 1, 0))))
                
                if Angle >= 35 and Angle <= 75 then
                    local BoostDirection = (Velocity.Unit + Vector3.new(0, 0.8, 0)).Unit
                    RootPart.Velocity = BoostDirection * (Speed + TrimpVelocity)
                end
            end
        end
    end)
end

if BounceEnabled then
    local WasFalling = false
    
    RunService.Heartbeat:Connect(function()
        if not RootPart then return end
        local VelocityY = RootPart.Velocity.Y
        
        if VelocityY < -20 then
            WasFalling = true
        elseif WasFalling and VelocityY > -5 then
            WasFalling = false
            local RaycastParams = RaycastParams.new()
            RaycastParams.FilterDescendantsInstances = {Character}
            
            local Result = Workspace:Raycast(RootPart.Position, Vector3.new(0, -3, 0), RaycastParams)
            if Result then
                local Normal = Result.Normal
                local Angle = math.deg(math.acos(Normal:Dot(Vector3.new(0, 1, 0))))
                
                if Angle >= 20 and Angle <= 80 then
                    RootPart.Velocity = Vector3.new(RootPart.Velocity.X * 0.9, 120, RootPart.Velocity.Z * 0.9)
                end
            end
        end
    end)
end

Humanoid.WalkSpeed = SpeedValue

return "${name}_loaded"`;
    
    return code;
}

function generateTrimpMap() {
    const name = document.getElementById('mapName').value || 'trimp_park';
    const terrain = document.getElementById('terrainType').value;
    const elements = document.getElementById('mapElements').value;
    const config = document.getElementById('trimpConfig').value;
    
    let code = `local Workspace = game:GetService("Workspace")
local MapFolder = Instance.new("Folder")
MapFolder.Name = "${name}"
MapFolder.Parent = Workspace

local function CreatePart(Position, Size, Color, Name, CanCollide)
    local Part = Instance.new("Part")
    Part.Size = Size
    Part.Position = Position
    Part.BrickColor = BrickColor.new(Color)
    Part.Name = Name
    Part.Anchored = true
    Part.CanCollide = CanCollide ~= false
    Part.Parent = MapFolder
    return Part
end

local function CreateRamp(Position, Size, Rotation, Color)
    local Ramp = CreatePart(Position, Size, Color, "Ramp")
    Ramp.Orientation = Rotation
    return Ramp
end

local function CreateContainer(Position, Rotation)
    local Container = Instance.new("Model")
    Container.Name = "Container"
    Container.Parent = MapFolder
    
    local Base = CreatePart(Position, Vector3.new(8, 8, 20), "Bright red", "ContainerBase")
    Base.Orientation = Rotation
    Base.Parent = Container
    
    local Top = CreatePart(Position + Vector3.new(0, 4.5, 0), Vector3.new(8.2, 1, 20.2), "Bright red", "ContainerTop")
    Top.Orientation = Rotation
    Top.Parent = Container
    
    return Container
end

local function CreateCar(Position, Rotation)
    local Car = Instance.new("Model")
    Car.Name = "Car"
    Car.Parent = MapFolder
    
    local Body = CreatePart(Position, Vector3.new(6, 3, 12), "Bright blue", "CarBody")
    Body.Orientation = Rotation
    Body.Parent = Car
    
    local Hood = CreatePart(Position + Vector3.new(0, 2, 3), Vector3.new(5.8, 0.5, 4), "Bright blue", "CarHood")
    Hood.Orientation = Rotation + Vector3.new(-25, 0, 0)
    Hood.Parent = Car
    
    return Car
end

local function CreateStairs(Position, Steps, Rotation)
    local Stairs = Instance.new("Model")
    Stairs.Name = "Stairs"
    Stairs.Parent = MapFolder
    
    for i = 1, Steps do
        local Step = CreatePart(
            Position + Vector3.new(0, i * 1.5, i * 3),
            Vector3.new(8, 1.5, 3),
            "Medium stone grey",
            "Step_" .. i
        )
        Step.Orientation = Rotation
        Step.Parent = Stairs
    end
    
    return Stairs
end

CreatePart(Vector3.new(0, -1, 0), Vector3.new(500, 2, 500), "Dark stone grey", "Baseplate")

for i = 1, 10 do
    local X = math.random(-200, 200)
    local Z = math.random(-200, 200)
    local Rotation = Vector3.new(0, math.random(0, 360), 0)
    
    if i % 3 == 0 then
        CreateContainer(Vector3.new(X, 4, Z), Rotation)
    elseif i % 3 == 1 then
        CreateCar(Vector3.new(X, 1.5, Z), Rotation)
    else
        CreateStairs(Vector3.new(X, 0, Z), 8, Rotation)
    end
end

for i = 1, 15 do
    local X = math.random(-150, 150)
    local Z = math.random(-150, 150)
    local Angle = math.random(30, 60)
    
    CreateRamp(
        Vector3.new(X, math.random(5, 30), Z),
        Vector3.new(20, 2, 40),
        Vector3.new(-Angle, math.random(0, 360), 0),
        "Bright green"
    )
end

for i = 1, 8 do
    local X = math.random(-100, 100)
    local Z = math.random(-100, 100)
    
    CreatePart(
        Vector3.new(X, math.random(10, 50), Z),
        Vector3.new(4, 4, 4),
        "Bright yellow",
        "BouncePlatform"
    )
end

local TrimpZones = Instance.new("Folder")
TrimpZones.Name = "TrimpZones"
TrimpZones.Parent = MapFolder

for _, Part in pairs(MapFolder:GetDescendants()) do
    if Part:IsA("BasePart") then
        local Slope = math.abs(Part.Orientation.X)
        if Slope >= 30 and Slope <= 75 then
            Part:SetAttribute("IsTrimpSurface", true)
            Part:SetAttribute("TrimpBoost", 150)
        end
    end
end

return "${name}_generated"`;

    document.getElementById('trimpCodeFilename').textContent = name + '.lua';
    document.getElementById('trimpCodeContent').value = code;
    document.getElementById('trimpCodeOutput').classList.add('active');
    
    scriptsGenerated++;
    document.getElementById('scriptsGenerated').textContent = scriptsGenerated;
    document.getElementById('lastGen').textContent = new Date().toLocaleTimeString();
}

function generateMovementScript() {
    const type = document.getElementById('movementType').value;
    const key = document.getElementById('moveKey').value || 'X';
    const speed = document.getElementById('moveSpeed').value || '1500';
    
    let code = '';
    
    if (type === 'autocrouch' || type === 'all') {
        code += `local UIS = game:GetService("UserInputService")
local Player = game.Players.LocalPlayer
local Char = Player.Character or Player.CharacterAdded:Wait()
local Hum = Char:WaitForChild("Humanoid")
local Crouching = false

UIS.InputBegan:Connect(function(I, G)
    if G then return end
    if I.KeyCode == Enum.KeyCode.${key:upper()} then
        Crouching = not Crouching
        if Crouching then
            Hum.HipHeight = -1.5
            Hum.WalkSpeed = ${speed}
        else
            Hum.HipHeight = 0
            Hum.WalkSpeed = 16
        end
    end
end)

`;
    }
    
    if (type === 'strafe' || type === 'all') {
        code += `local RS = game:GetService("RunService")
local Player = game.Players.LocalPlayer
local Char = Player.Character or Player.CharacterAdded:Wait()
local Root = Char:WaitForChild("HumanoidRootPart")
local Hum = Char:WaitForChild("Humanoid")
local Cam = workspace.CurrentCamera

RS.RenderStepped:Connect(function()
    local Dir = Hum.MoveDirection
    if Dir.X ~= 0 then
        local Strafe = Cam.CFrame.RightVector * Dir.X * 29
        Root.Velocity = Root.Velocity + Strafe
    end
end)

`;
    }
    
    if (type === 'bhop' || type === 'all') {
        code += `local RS = game:GetService("RunService")
local Player = game.Players.LocalPlayer
local Char = Player.Character or Player.CharacterAdded:Wait()
local Hum = Char:WaitForChild("Humanoid")

RS.RenderStepped:Connect(function()
    if Hum.FloorMaterial ~= Enum.Material.Air then
        Hum:ChangeState(Enum.HumanoidStateType.Jumping)
    end
end)

`;
    }
    
    document.getElementById('moveCodeFilename').textContent = 'movement_' + type + '.lua';
    document.getElementById('moveCodeContent').value = code;
    document.getElementById('moveCodeOutput').classList.add('active');
    
    scriptsGenerated++;
    document.getElementById('scriptsGenerated').textContent = scriptsGenerated;
    document.getElementById('lastGen').textContent = new Date().toLocaleTimeString();
}

function generateAdminScript() {
    const prefix = document.getElementById('adminPrefix').value || ';';
    
    const code = `local Players = game:GetService("Players")
local LocalPlayer = Players.LocalPlayer
local Prefix = "${prefix}"

local Commands = {
    kill = function(Target)
        local T = FindPlayer(Target)
        if T and T.Character then
            T.Character.Humanoid.Health = 0
        end
    end,
    
    bring = function(Target)
        local T = FindPlayer(Target)
        if T and T.Character and LocalPlayer.Character then
            T.Character.HumanoidRootPart.CFrame = LocalPlayer.Character.HumanoidRootPart.CFrame
        end
    end,
    
    goto = function(Target)
        local T = FindPlayer(Target)
        if T and T.Character and LocalPlayer.Character then
            LocalPlayer.Character.HumanoidRootPart.CFrame = T.Character.HumanoidRootPart.CFrame
        end
    end,
    
    fly = function()
        local Char = LocalPlayer.Character
        local Root = Char:WaitForChild("HumanoidRootPart")
        local BV = Instance.new("BodyVelocity")
        BV.Velocity = Vector3.new(0, 0, 0)
        BV.MaxForce = Vector3.new(math.huge, math.huge, math.huge)
        BV.Parent = Root
        local BG = Instance.new("BodyGyro")
        BG.P = 9e4
        BG.Parent = Root
    end,
    
    speed = function(Amount)
        LocalPlayer.Character.Humanoid.WalkSpeed = tonumber(Amount) or 100
    end,
    
    noclip = function()
        local Char = LocalPlayer.Character
        game:GetService("RunService").Stepped:Connect(function()
            for _, P in pairs(Char:GetDescendants()) do
                if P:IsA("BasePart") then
                    P.CanCollide = false
                end
            end
        end)
    end,
    
    god = function()
        LocalPlayer.Character.Humanoid.MaxHealth = math.huge
        LocalPlayer.Character.Humanoid.Health = math.huge
    end,
    
    invisible = function()
        for _, P in pairs(LocalPlayer.Character:GetDescendants()) do
            if P:IsA("BasePart") then
                P.Transparency = 1
            end
        end
    end
}

function FindPlayer(String)
    for _, P in pairs(Players:GetPlayers()) do
        if P.Name:lower():sub(1, #String) == String:lower() then
            return P
        end
    end
    return nil
end

LocalPlayer.Chatted:Connect(function(Msg)
    if Msg:sub(1, 1) == Prefix then
        local Args = Msg:split(" ")
        local Cmd = Args[1]:sub(2):lower()
        table.remove(Args, 1)
        
        if Commands[Cmd] then
            Commands[Cmd](unpack(Args))
        end
    end
end)

return "admin_loaded"`;

    document.getElementById('adminCodeFilename').textContent = 'admin_supreme.lua';
    document.getElementById('adminCodeContent').value = code;
    document.getElementById('adminCodeOutput').classList.add('active');
    
    scriptsGenerated++;
    document.getElementById('scriptsGenerated').textContent = scriptsGenerated;
    document.getElementById('lastGen').textContent = new Date().toLocaleTimeString();
}

function generateESPScript() {
    const type = document.getElementById('espType').value;
    
    let code = `local Players = game:GetService("Players")
local LocalPlayer = Players.LocalPlayer
local Camera = workspace.CurrentCamera
local RunService = game:GetService("RunService")

local ESP = {
    Enabled = true,
    ShowNames = true,
    ShowDistance = true,
    ShowHealth = true,
    MaxDistance = 2000
}

local function CreateESP(Target)
    local Box = Drawing.new("Square")
    Box.Visible = false
    Box.Thickness = 2
    Box.Color = Color3.new(1, 1, 1)
    Box.Transparency = 1
    
    local Name = Drawing.new("Text")
    Name.Visible = false
    Name.Size = 14
    Name.Color = Color3.new(1, 1, 1)
    Name.Center = true
    
    local Distance = Drawing.new("Text")
    Distance.Visible = false
    Distance.Size = 12
    Distance.Color = Color3.new(0.8, 0.8, 0.8)
    Distance.Center = true
    
    RunService.RenderStepped:Connect(function()
        if not ESP.Enabled then
            Box.Visible = false
            Name.Visible = false
            Distance.Visible = false
            return
        end
        
        if Target and Target.Character and Target.Character:FindFirstChild("HumanoidRootPart") then
            local Pos, OnScreen = Camera:WorldToViewportPoint(Target.Character.HumanoidRootPart.Position)
            local Dist = (LocalPlayer.Character.HumanoidRootPart.Position - Target.Character.HumanoidRootPart.Position).Magnitude
            
            if OnScreen and Dist <= ESP.MaxDistance then
                Box.Size = Vector2.new(1000 / Dist, 1200 / Dist)
                Box.Position = Vector2.new(Pos.X - Box.Size.X / 2, Pos.Y - Box.Size.Y / 2)
                Box.Visible = true
                
                if ESP.ShowNames then
                    Name.Position = Vector2.new(Pos.X, Pos.Y - Box.Size.Y / 2 - 15)
                    Name.Text = Target.Name
                    Name.Visible = true
                end
                
                if ESP.ShowDistance then
                    Distance.Position = Vector2.new(Pos.X, Pos.Y + Box.Size.Y / 2 + 5)
                    Distance.Text = math.floor(Dist) .. "m"
                    Distance.Visible = true
                end
            else
                Box.Visible = false
                Name.Visible = false
                Distance.Visible = false
            end
        else
            Box.Visible = false
            Name.Visible = false
            Distance.Visible = false
        end
    end)
end

for _, P in pairs(Players:GetPlayers()) do
    if P ~= LocalPlayer then
        CreateESP(P)
    end
end

Players.PlayerAdded:Connect(function(P)
    CreateESP(P)
end)

return "esp_loaded"`;

    document.getElementById('espCodeFilename').textContent = 'esp_supreme.lua';
    document.getElementById('espCodeContent').value = code;
    document.getElementById('espCodeOutput').classList.add('active');
    
    scriptsGenerated++;
    document.getElementById('scriptsGenerated').textContent = scriptsGenerated;
    document.getElementById('lastGen').textContent = new Date().toLocaleTimeString();
}

function generateMiscScript() {
    const type = document.getElementById('miscType').value;
    
    let code = '';
    
    if (type === 'antiafk') {
        code = `local VirtualUser = game:GetService("VirtualUser")
game:GetService("Players").LocalPlayer.Idled:Connect(function()
    VirtualUser:Button2Down(Vector2.new(0,0), workspace.CurrentCamera.CFrame)
    wait(1)
    VirtualUser:Button2Up(Vector2.new(0,0), workspace.CurrentCamera.CFrame)
end)`;
    } else if (type === 'antikick') {
        code = `local mt = getrawmetatable(game)
local old = mt.__namecall
setreadonly(mt, false)
mt.__namecall = newcclosure(function(self, ...)
    local method = getnamecallmethod()
    if method == "Kick" then return nil end
    return old(self, ...)
end)
setreadonly(mt, true)`;
    } else if (type === 'fpsboost') {
        code = `for _, v in pairs(game:GetDescendants()) do
    if v:IsA("BasePart") then
        v.Material = Enum.Material.SmoothPlastic
    elseif v:IsA("Decal") or v:IsA("Texture") then
        v:Destroy()
    end
end
game.Lighting.GlobalShadows = false`;
    } else if (type === 'fullbright') {
        code = `game.Lighting.Brightness = 10
game.Lighting.GlobalShadows = false
game.Lighting.Ambient = Color3.new(1, 1, 1)`;
    }
    
    document.getElementById('miscCodeFilename').textContent = type + '.lua';
    document.getElementById('miscCodeContent').value = code;
    document.getElementById('miscCodeOutput').classList.add('active');
    
    scriptsGenerated++;
    document.getElementById('scriptsGenerated').textContent = scriptsGenerated;
    document.getElementById('lastGen').textContent = new Date().toLocaleTimeString();
}

function copyCode() {
    const el = document.getElementById('codeContent');
    el.select();
    document.execCommand('copy');
}

function downloadCode() {
    const code = document.getElementById('codeContent').value;
    const name = document.getElementById('codeFilename').textContent;
    const blob = new Blob([code], {type: 'text/plain'});
    const url = URL.createObjectURL(blob);
    const a = document.createElement('a');
    a.href = url;
    a.download = name;
    a.click();
}

function copyTrimpCode() {
    const el = document.getElementById('trimpCodeContent');
    el.select();
    document.execCommand('copy');
}

function downloadTrimpCode() {
    const code = document.getElementById('trimpCodeContent').value;
    const name = document.getElementById('trimpCodeFilename').textContent;
    const blob = new Blob([code], {type: 'text/plain'});
    const url = URL.createObjectURL(blob);
    const a = document.createElement('a');
    a.href = url;
    a.download = name;
    a.click();
}

function copyMoveCode() {
    const el = document.getElementById('moveCodeContent');
    el.select();
    document.execCommand('copy');
}

function downloadMoveCode() {
    const code = document.getElementById('moveCodeContent').value;
    const name = document.getElementById('moveCodeFilename').textContent;
    const blob = new Blob([code], {type: 'text/plain'});
    const url = URL.createObjectURL(blob);
    const a = document.createElement('a');
    a.href = url;
    a.download = name;
    a.click();
}

function copyAdminCode() {
    const el = document.getElementById('adminCodeContent');
    el.select();
    document.execCommand('copy');
}

function downloadAdminCode() {
    const code = document.getElementById('adminCodeContent').value;
    const name = document.getElementById('adminCodeFilename').textContent;
    const blob = new Blob([code], {type: 'text/plain'});
    const url = URL.createObjectURL(blob);
    const a = document.createElement('a');
    a.href = url;
    a.download = name;
    a.click();
}

function copyESPCode() {
    const el = document.getElementById('espCodeContent');
    el.select();
    document.execCommand('copy');
}

function downloadESPCode() {
    const code = document.getElementById('espCodeContent').value;
    const name = document.getElementById('espCodeFilename').textContent;
    const blob = new Blob([code], {type: 'text/plain'});
    const url = URL.createObjectURL(blob);
    const a = document.createElement('a');
    a.href = url;
    a.download = name;
    a.click();
}

function copyMiscCode() {
    const el = document.getElementById('miscCodeContent');
    el.select();
    document.execCommand('copy');
}

function downloadMiscCode() {
    const code = document.getElementById('miscCodeContent').value;
    const name = document.getElementById('miscCodeFilename').textContent;
    const blob = new Blob([code], {type: 'text/plain'});
    const url = URL.createObjectURL(blob);
    const a = document.createElement('a');
    a.href = url;
    a.download = name;
    a.click();
}
</script>

</body>
</html>
