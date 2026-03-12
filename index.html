<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CarDoc — Receita Digital do Seu Carro</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      background: #F4F6F9;
      color: #1a1a1a;
      min-height: 100vh;
    }

    .screen { display: none; }
    .screen.active { display: block; }

    .app-wrap {
      max-width: 600px;
      margin: 0 auto;
      background: #fff;
      min-height: 100vh;
      box-shadow: 0 0 40px rgba(0,0,0,0.08);
    }

    .header {
      display: flex; align-items: center; gap: 12px;
      padding: 1.25rem 1.5rem;
      border-bottom: 1px solid #eee;
      background: #fff;
      position: sticky; top: 0; z-index: 10;
    }
    .logo-icon {
      width: 40px; height: 40px; border-radius: 12px;
      background: #1B4F72;
      display: flex; align-items: center; justify-content: center;
      font-size: 20px;
    }
    .logo-text { font-size: 20px; font-weight: 600; color: #1B4F72; }
    .logo-sub { font-size: 12px; color: #888; margin-top: 1px; }

    .form-wrap { padding: 1.25rem 1.5rem 2.5rem; }

    .section-title {
      font-size: 11px; font-weight: 600; letter-spacing: 0.08em;
      color: #999; text-transform: uppercase;
      margin: 1.5rem 0 0.75rem;
    }

    .field { margin-bottom: 1rem; }
    .field label {
      display: block; font-size: 13px; color: #555;
      margin-bottom: 5px; font-weight: 500;
    }
    .field input, .field select {
      width: 100%; padding: 10px 13px; font-size: 15px;
      border: 1.5px solid #e0e0e0;
      border-radius: 10px;
      background: #fff;
      color: #1a1a1a;
      outline: none;
      transition: border-color 0.15s, box-shadow 0.15s;
      -webkit-appearance: none;
    }
    .field input:focus, .field select:focus {
      border-color: #1B4F72;
      box-shadow: 0 0 0 3px rgba(27,79,114,0.1);
    }
    .field input::placeholder { color: #bbb; }

    .row { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; }

    .btn-primary {
      width: 100%; padding: 14px;
      background: #1B4F72; color: white;
      border: none; border-radius: 12px;
      font-size: 16px; font-weight: 600; cursor: pointer;
      margin-top: 1.75rem;
      transition: background 0.15s, transform 0.1s;
      letter-spacing: 0.01em;
    }
    .btn-primary:hover { background: #154060; }
    .btn-primary:active { transform: scale(0.98); }

    .btn-wpp {
      width: 100%; padding: 14px;
      background: #25D366; color: white;
      border: none; border-radius: 12px;
      font-size: 16px; font-weight: 600; cursor: pointer;
      margin-top: 0.75rem;
      display: flex; align-items: center; justify-content: center; gap: 10px;
      transition: background 0.15s, transform 0.1s;
    }
    .btn-wpp:hover { background: #1ebe5a; }
    .btn-wpp:active { transform: scale(0.98); }

    .btn-secondary {
      width: 100%; padding: 12px;
      background: transparent; color: #666;
      border: 1.5px solid #e0e0e0;
      border-radius: 12px;
      font-size: 15px; font-weight: 500; cursor: pointer;
      margin-top: 0.75rem;
      transition: background 0.15s;
    }
    .btn-secondary:hover { background: #f5f5f5; }

    .etiqueta {
      background: #fff;
      border: 1px solid #eee;
      border-radius: 16px;
      overflow: hidden;
      margin: 0 1.5rem 1rem;
    }

    .etiqueta-header {
      background: #1B4F72;
      padding: 1.25rem 1.5rem;
      display: flex; align-items: center; justify-content: space-between;
    }
    .etiqueta-header-left { color: white; }
    .etiqueta-header-left .emitido { font-size: 11px; opacity: 0.65; letter-spacing: 0.06em; text-transform: uppercase; }
    .etiqueta-header-left .titulo { font-size: 22px; font-weight: 700; margin-top: 2px; }
    .etiqueta-header-right {
      background: rgba(255,255,255,0.15);
      border-radius: 10px; padding: 10px 14px;
      text-align: center; color: white;
      backdrop-filter: blur(4px);
    }
    .etiqueta-header-right .placa-val { font-size: 20px; font-weight: 700; letter-spacing: 0.12em; }
    .etiqueta-header-right .placa-label { font-size: 10px; opacity: 0.65; text-transform: uppercase; letter-spacing: 0.06em; margin-top: 2px; }

    .etiqueta-body { padding: 1.25rem 1.5rem; }

    .info-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 14px; }
    .info-label { font-size: 11px; color: #999; text-transform: uppercase; letter-spacing: 0.06em; margin-bottom: 3px; }
    .info-value { font-size: 15px; font-weight: 600; color: #1a1a1a; }

    .proxima-card {
      background: #EAF2FB;
      border-radius: 12px;
      padding: 1rem 1.25rem;
      margin-top: 1rem;
      display: flex; align-items: center; gap: 14px;
    }
    .proxima-icon {
      width: 44px; height: 44px; border-radius: 12px;
      background: #1B4F72;
      display: flex; align-items: center; justify-content: center;
      font-size: 22px; flex-shrink: 0;
    }
    .proxima-info .label { font-size: 11px; color: #185FA5; text-transform: uppercase; letter-spacing: 0.06em; font-weight: 600; }
    .proxima-info .value { font-size: 17px; font-weight: 700; color: #0C447C; margin-top: 2px; }

    .obs-card {
      border: 1.5px solid #FEE2B3;
      background: #FFFBF2;
      border-radius: 10px;
      padding: 0.875rem 1rem;
      margin-top: 0.75rem;
      font-size: 14px; color: #7A5200;
      line-height: 1.5;
    }
    .obs-title { font-size: 11px; font-weight: 700; color: #7A5200; text-transform: uppercase; letter-spacing: 0.06em; margin-bottom: 4px; }

    .etiqueta-footer {
      border-top: 1px solid #eee;
      padding: 0.875rem 1.5rem;
      display: flex; align-items: center; justify-content: space-between;
      background: #FAFAFA;
    }
    .footer-oficina { font-size: 13px; color: #888; }
    .footer-badge {
      background: #1B4F72;
      color: white;
      font-size: 11px; font-weight: 700;
      padding: 5px 12px; border-radius: 20px;
      letter-spacing: 0.05em;
    }

    .action-wrap { padding: 0 1.5rem 2.5rem; }

    .success-msg {
      display: flex; align-items: center; gap: 8px;
      background: #F0FFF5;
      border: 1px solid #BBF7D0;
      border-radius: 10px;
      padding: 12px 1rem;
      margin: 0 1.5rem 1rem;
      font-size: 14px; color: #166534;
    }

    @media (max-width: 400px) {
      .row { grid-template-columns: 1fr; }
      .info-grid { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>
<div class="app-wrap">

  <!-- TELA: FORMULÁRIO -->
  <div id="screen-form" class="screen active">
    <div class="header">
      <div class="logo-icon">🚗</div>
      <div>
        <div class="logo-text">CarDoc</div>
        <div class="logo-sub">Receita digital do seu carro</div>
      </div>
    </div>

    <div class="form-wrap">
      <div class="section-title">Dados do veículo</div>
      <div class="row">
        <div class="field">
          <label>Placa</label>
          <input id="placa" type="text" placeholder="ABC-1234" maxlength="8" oninput="this.value=this.value.toUpperCase()" />
        </div>
        <div class="field">
          <label>KM atual</label>
          <input id="km" type="number" placeholder="Ex: 52400" />
        </div>
      </div>
      <div class="row">
        <div class="field">
          <label>Marca</label>
          <input id="marca" type="text" placeholder="Ex: Toyota" />
        </div>
        <div class="field">
          <label>Modelo</label>
          <input id="modelo" type="text" placeholder="Ex: Corolla" />
        </div>
      </div>

      <div class="section-title">Serviço realizado</div>
      <div class="field">
        <label>Tipo de óleo utilizado</label>
        <select id="oleo">
          <option value="">Selecione o óleo</option>
          <option>5W-30 Sintético</option>
          <option>5W-40 Sintético</option>
          <option>10W-40 Semissintético</option>
          <option>15W-40 Mineral</option>
          <option>0W-20 Sintético</option>
          <option>Outro</option>
        </select>
      </div>
      <div class="row">
        <div class="field">
          <label>Próxima troca (KM)</label>
          <input id="proxKm" type="number" placeholder="Ex: 57400" />
        </div>
        <div class="field">
          <label>Prazo (meses)</label>
          <input id="proxMeses" type="number" placeholder="Ex: 6" />
        </div>
      </div>
      <div class="field">
        <label>Observações do mecânico</label>
        <input id="obs" type="text" placeholder="Ex: Pastilha traseira com 30% de vida" />
      </div>

      <div class="section-title">Dados do cliente</div>
      <div class="field">
        <label>Nome do cliente</label>
        <input id="nomeCliente" type="text" placeholder="Ex: João Silva" />
      </div>
      <div class="field">
        <label>WhatsApp (com DDD)</label>
        <input id="whatsapp" type="tel" placeholder="Ex: 11999999999" />
      </div>

      <div class="section-title">Sua oficina</div>
      <div class="field">
        <label>Nome da oficina</label>
        <input id="oficina" type="text" placeholder="Ex: Auto Center Silva" />
      </div>

      <button class="btn-primary" onclick="gerarReceita()">Gerar Receita Digital 🚗</button>
    </div>
  </div>

  <!-- TELA: RECEITA -->
  <div id="screen-receita" class="screen">
    <div class="header">
      <div class="logo-icon">🚗</div>
      <div>
        <div class="logo-text">CarDoc</div>
        <div class="logo-sub">Receita gerada com sucesso</div>
      </div>
    </div>

    <div class="success-msg">
      ✅ Receita criada! Envie pelo WhatsApp para o cliente.
    </div>

    <div class="etiqueta">
      <div class="etiqueta-header">
        <div class="etiqueta-header-left">
          <div class="emitido" id="r-marca-modelo">Veículo</div>
          <div class="titulo">Receita Digital</div>
        </div>
        <div class="etiqueta-header-right">
          <div class="placa-val" id="r-placa">ABC-1234</div>
          <div class="placa-label">Placa</div>
        </div>
      </div>

      <div class="etiqueta-body">
        <div class="info-grid">
          <div>
            <div class="info-label">Data da troca</div>
            <div class="info-value" id="r-data">—</div>
          </div>
          <div>
            <div class="info-label">KM na troca</div>
            <div class="info-value" id="r-km">—</div>
          </div>
          <div>
            <div class="info-label">Óleo utilizado</div>
            <div class="info-value" id="r-oleo">—</div>
          </div>
          <div>
            <div class="info-label">Cliente</div>
            <div class="info-value" id="r-cliente">—</div>
          </div>
        </div>

        <div class="proxima-card">
          <div class="proxima-icon">🔔</div>
          <div class="proxima-info">
            <div class="label">Próxima troca recomendada</div>
            <div class="value" id="r-proxima">—</div>
          </div>
        </div>

        <div class="obs-card" id="r-obs-wrap" style="display:none;">
          <div class="obs-title">⚠️ Observação do mecânico</div>
          <span id="r-obs"></span>
        </div>
      </div>

      <div class="etiqueta-footer">
        <div class="footer-oficina" id="r-oficina">Oficina</div>
        <div class="footer-badge">CarDoc</div>
      </div>
    </div>

    <div class="action-wrap">
      <button class="btn-wpp" onclick="enviarWhatsApp()">
        <svg width="20" height="20" viewBox="0 0 24 24" fill="white">
          <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/>
        </svg>
        Enviar pelo WhatsApp
      </button>
      <button class="btn-secondary" onclick="novaReceita()">← Nova receita</button>
    </div>
  </div>

</div>

<script>
  function gerarReceita() {
    const placa = document.getElementById('placa').value.toUpperCase() || '—';
    const km = document.getElementById('km').value;
    const marca = document.getElementById('marca').value;
    const modelo = document.getElementById('modelo').value;
    const oleo = document.getElementById('oleo').value || '—';
    const proxKm = document.getElementById('proxKm').value;
    const proxMeses = document.getElementById('proxMeses').value;
    const obs = document.getElementById('obs').value;
    const nomeCliente = document.getElementById('nomeCliente').value || 'Cliente';
    const oficina = document.getElementById('oficina').value || 'Oficina';

    const hoje = new Date();
    const dataStr = hoje.toLocaleDateString('pt-BR');

    document.getElementById('r-placa').textContent = placa;
    document.getElementById('r-marca-modelo').textContent = [marca, modelo].filter(Boolean).join(' ') || 'Veículo';
    document.getElementById('r-data').textContent = dataStr;
    document.getElementById('r-km').textContent = km ? Number(km).toLocaleString('pt-BR') + ' km' : '—';
    document.getElementById('r-oleo').textContent = oleo;
    document.getElementById('r-cliente').textContent = nomeCliente;
    document.getElementById('r-oficina').textContent = oficina;

    let proxText = '';
    if (proxKm) proxText += Number(proxKm).toLocaleString('pt-BR') + ' km';
    if (proxKm && proxMeses) proxText += ' ou ';
    if (proxMeses) proxText += proxMeses + ' meses';
    document.getElementById('r-proxima').textContent = proxText || '—';

    if (obs) {
      document.getElementById('r-obs').textContent = obs;
      document.getElementById('r-obs-wrap').style.display = 'block';
    } else {
      document.getElementById('r-obs-wrap').style.display = 'none';
    }

    document.getElementById('screen-form').classList.remove('active');
    document.getElementById('screen-receita').classList.add('active');
    window.scrollTo(0, 0);
  }

  function enviarWhatsApp() {
    const whatsapp = document.getElementById('whatsapp').value.replace(/\D/g, '');
    const placa = document.getElementById('placa').value.toUpperCase();
    const km = document.getElementById('km').value;
    const marca = document.getElementById('marca').value;
    const modelo = document.getElementById('modelo').value;
    const oleo = document.getElementById('oleo').value;
    const proxKm = document.getElementById('proxKm').value;
    const proxMeses = document.getElementById('proxMeses').value;
    const obs = document.getElementById('obs').value;
    const nomeCliente = document.getElementById('nomeCliente').value || 'cliente';
    const oficina = document.getElementById('oficina').value || 'nossa oficina';
    const hoje = new Date().toLocaleDateString('pt-BR');

    let msg = `🚗 *CarDoc — Receita Digital*\n\n`;
    msg += `Olá, ${nomeCliente}! Aqui está a receita digital da troca de óleo do seu veículo.\n\n`;
    msg += `🔧 *Serviço realizado em ${hoje}*\n`;
    if (placa) msg += `Placa: *${placa}*\n`;
    if (marca || modelo) msg += `Veículo: *${[marca, modelo].filter(Boolean).join(' ')}*\n`;
    if (km) msg += `KM: *${Number(km).toLocaleString('pt-BR')} km*\n`;
    if (oleo) msg += `Óleo: *${oleo}*\n`;
    if (proxKm || proxMeses) {
      msg += `\n🔔 *Próxima troca recomendada:*\n`;
      if (proxKm) msg += `• KM: ${Number(proxKm).toLocaleString('pt-BR')} km\n`;
      if (proxMeses) msg += `• Prazo: ${proxMeses} meses\n`;
    }
    if (obs) msg += `\n⚠️ *Atenção:* ${obs}\n`;
    msg += `\n✅ Realizado por: *${oficina}*\n`;
    msg += `_Guarde esta mensagem — é o prontuário digital do seu carro!_ 🚗`;

    const numero = whatsapp ? `55${whatsapp}` : '';
    const url = `https://wa.me/${numero}?text=${encodeURIComponent(msg)}`;
    window.open(url, '_blank');
  }

  function novaReceita() {
    document.getElementById('screen-receita').classList.remove('active');
    document.getElementById('screen-form').classList.add('active');
    window.scrollTo(0, 0);
  }
</script>
</body>
</html>
