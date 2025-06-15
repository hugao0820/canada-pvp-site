<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Canada PvP - Comandos</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    function copiarComando(comando) {
      navigator.clipboard.writeText(comando);
      alert(`Comando "${comando}" copiado!`);
    }
  </script>
</head>
<body class="bg-gray-900 text-white font-sans">
  <div class="max-w-4xl mx-auto py-10 px-6">
    <div class="text-center mb-10">
      <img src="logo.png" alt="Logo Canada PvP" class="mx-auto w-40 mb-4">
      <h1 class="text-5xl font-bold text-cyan-400">🇨🇦 Canada PvP</h1>
      <p class="text-gray-300 mt-2">Lista completa de comandos disponíveis no servidor!</p>
    </div>

    <section class="mb-10">
      <h2 class="text-3xl font-semibold text-blue-300 mb-4">⚙️ Comandos Gerais</h2>
      <ul class="space-y-2 text-lg">
        <li class="flex justify-between items-center"><span><code class="bg-gray-800 px-2 py-1 rounded">/dailyreward</code> — Recebe seu prêmio diário!</span><button onclick="copiarComando('/dailyreward')" class="bg-gray-700 px-3 py-1 rounded hover:bg-gray-600">Copiar</button></li>
        <li class="flex justify-between items-center"><span><code class="bg-gray-800 px-2 py-1 rounded">/fps</code> — Exibe a taxa de FPS atual do seu jogo.</span><button onclick="copiarComando('/fps')" class="bg-gray-700 px-3 py-1 rounded hover:bg-gray-600">Copiar</button></li>
        <li class="flex justify-between items-center"><span><code class="bg-gray-800 px-2 py-1 rounded">/id</code> — Mostra o seu ID no servidor.</span><button onclick="copiarComando('/id')" class="bg-gray-700 px-3 py-1 rounded hover:bg-gray-600">Copiar</button></li>
        <li class="flex justify-between items-center"><span><code class="bg-gray-800 px-2 py-1 rounded">/leaderboard</code> — Veja o ranking de jogadores.</span><button onclick="copiarComando('/leaderboard')" class="bg-gray-700 px-3 py-1 rounded hover:bg-gray-600">Copiar</button></li>
        <li class="flex justify-between items-center"><span><code class="bg-gray-800 px-2 py-1 rounded">/neige</code> — Ativa/desativa o clima de neve.</span><button onclick="copiarComando('/neige')" class="bg-gray-700 px-3 py-1 rounded hover:bg-gray-600">Copiar</button></li>
        <li class="flex justify-between items-center"><span><code class="bg-gray-800 px-2 py-1 rounded">/deathcam</code> — Ativa/desativa a câmera de morte.</span><button onclick="copiarComando('/deathcam')" class="bg-gray-700 px-3 py-1 rounded hover:bg-gray-600">Copiar</button></li>
        <li class="flex justify-between items-center"><span><code class="bg-gray-800 px-2 py-1 rounded">/vip</code> — Informações sobre o sistema VIP.</span><button onclick="copiarComando('/vip')" class="bg-gray-700 px-3 py-1 rounded hover:bg-gray-600">Copiar</button></li>
      </ul>
    </section>

    <section class="mb-10">
      <h2 class="text-3xl font-semibold text-red-400 mb-4">💥 Comandos de PvP e Ações Especiais</h2>
      <ul class="space-y-2 text-lg">
        <li class="flex justify-between items-center"><span><code class="bg-gray-800 px-2 py-1 rounded">/Deadlog</code> — Exibe os logs de morte.</span><button onclick="copiarComando('/Deadlog')" class="bg-gray-700 px-3 py-1 rounded hover:bg-gray-600">Copiar</button></li>
        <li class="flex justify-between items-center"><span><code class="bg-gray-800 px-2 py-1 rounded">/r</code> — Revive veículo ou personagem.</span><button onclick="copiarComando('/r')" class="bg-gray-700 px-3 py-1 rounded hover:bg-gray-600">Copiar</button></li>
        <li class="flex justify-between items-center"><span><code class="bg-gray-800 px-2 py-1 rounded">/steal</code> — Roubando itens de outros jogadores.</span><button onclick="copiarComando('/steal')" class="bg-gray-700 px-3 py-1 rounded hover:bg-gray-600">Copiar</button></li>
        <li class="flex justify-between items-center"><span><code class="bg-gray-800 px-2 py-1 rounded">/carry</code> — Carrega outro jogador.</span><button onclick="copiarComando('/carry')" class="bg-gray-700 px-3 py-1 rounded hover:bg-gray-600">Copiar</button></li>
        <li class="flex justify-between items-center"><span><code class="bg-gray-800 px-2 py-1 rounded">/squad</code> — Gerencia sua equipe de PvP.</span><button onclick="copiarComando('/squad')" class="bg-gray-700 px-3 py-1 rounded hover:bg-gray-600">Copiar</button></li>
        <li class="flex justify-between items-center"><span><code class="bg-gray-800 px-2 py-1 rounded">/crew</code> — Gerencia sua gangue ou crew.</span><button onclick="copiarComando('/crew')" class="bg-gray-700 px-3 py-1 rounded hover:bg-gray-600">Copiar</button></li>
      </ul>
    </section>

    <section class="mb-10">
      <h2 class="text-3xl font-semibold text-yellow-300 mb-4">🔧 Comandos de Interação</h2>
      <ul class="space-y-2 text-lg">
        <li class="flex justify-between items-center"><span><code class="bg-gray-800 px-2 py-1 rounded">/report</code> — Relatar jogador.</span><button onclick="copiarComando('/report')" class="bg-gray-700 px-3 py-1 rounded hover:bg-gray-600">Copiar</button></li>
        <li class="flex justify-between items-center"><span><code class="bg-gray-800 px-2 py-1 rounded">/damage</code> — Estatísticas de dano.</span><button onclick="copiarComando('/damage')" class="bg-gray-700 px-3 py-1 rounded hover:bg-gray-600">Copiar</button></li>
      </ul>
    </section>

    <section class="bg-gray-800 p-6 rounded-lg">
      <h2 class="text-2xl font-semibold text-green-400 mb-3">📜 Dicas do Servidor</h2>
      <p class="mb-2 text-base">🎁 <strong>Recompensa Diária:</strong> Use <code class="bg-gray-700 px-1 py-0.5 rounded">/dailyreward</code> todo dia para garantir seus prêmios!</p>
      <p class="text-base">⚔️ <strong>Ações PvP:</strong> A ação nunca para no <strong>Canada PvP</strong>! Use <code class="bg-gray-700 px-1 py-0.5 rounded">/steal</code> e <code class="bg-gray-700 px-1 py-0.5 rounded">/carry</code> para interagir com outros jogadores!</p>
    </section>

    <footer class="text-center text-sm text-gray-500 mt-12">
      © 2025 Canada PvP Server. Todos os direitos reservados.
    </footer>
  </div>
</body>
</html>
