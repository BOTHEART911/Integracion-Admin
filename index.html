<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <title>REGISTRO DE VOTACIÓN / REFERIDOS</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <link rel="icon" href="https://res.cloudinary.com/dqqeavica/image/upload/v1759166341/WhatsApp_mljaqm.webp">

  <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11"></script>

  <style>
    :root{
      --primary:#007BFF;
      --primary-2:#0056b3;
      --ok:#16a34a;
      --error:#dc2626;
      --scrim:rgba(0,0,0,.35);
    }

    html,body{
      margin:0; padding:0; height:100%; width:100%;
      overflow-x:hidden;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      color:#111;
      background:#f3f4f6;
    }

    /* Contenedor general: ancho cómodo para ambos */
    .container{ max-width: 1000px; margin: 0 auto; padding: 16px; }

    /* Cards */
    .card{
      background: rgba(255,255,255,.96);
      border: 2px solid #ddd;
      border-radius: 10px;
      box-shadow: 0 8px 18px rgba(0,0,0,.12);
      margin: 16px auto;
      padding: 16px 16px 12px 16px;
      box-sizing:border-box;
    }

    h1,h2{ margin: 8px 0 12px; text-align:center; }
    h1{
      color:var(--primary);
      text-shadow: 0 2px 2px #031732;
      font-size:1.6rem;
    }
    h2{
      color:var(--primary);
      font-size:1.3rem;
    }

    p.helper{ color:#555; font-size:.95rem; text-align:center; margin:8px 0 16px; }

    label{ display:block; font-weight:700; margin: 10px 0 6px; color:var(--primary); }

    input, button{
      width:100%; padding:12px; box-sizing:border-box;
      border:1.5px solid #ccc; border-radius:8px; background:#fff;
      outline:none; transition: border-color .2s ease, transform .08s ease;
      font-size:16px;
    }
    input:focus{ border-color:var(--primary); }

    button{
      cursor:pointer; border:2px solid var(--primary);
      background:#fff; color:#000; font-weight:700;
    }
    button:hover{ background:var(--primary-2); color:#fff; border-color:var(--primary-2); }
    .btn-primary{ background:var(--primary); color:#fff; }

    .btn-row{ display:flex; gap:12px; }
    .btn-row > *{ flex:1; }
    @media (max-width: 700px){ .btn-row{ flex-direction:column; } }

    .btn-col{
      display:flex;
      flex-direction:column;
      gap:10px;
      margin-top:12px;
    }

    .muted{ color:#666; font-size:.9rem; }
    .center{ text-align:center; }
    .hidden{ display:none !important; }

    .btn-with-icon{
      display:flex;
      align-items:center;
      justify-content:center;
      gap:10px;
    }
    .btn-with-icon img{
      width:22px;
      height:22px;
      object-fit:contain;
      border-radius:4px;
      background:#fff;
    }

    /* Loader centrado (overlay) */
    .loader{
      position:fixed; inset:0;
      display:flex; align-items:center; justify-content:center;
      background:rgba(0,0,0,.35);
      z-index:9999; backdrop-filter: blur(2px);
      opacity:1; transition: opacity .12s ease;
      will-change: opacity;
    }
    .loader.hidden{
      display:flex !important;
      opacity:0; pointer-events:none;
    }

    /* Spinner tipo iOS (12 barras) */
    .spinner-ios{ position:relative; width:64px; height:64px; }
    .spinner-ios i{
      position:absolute; left:50%; top:50%;
      width:6px; height:18px; margin:-9px 0 0 -3px;
      background:#fff; border-radius:3px;
      opacity:.2;
      animation:iosFade 1.2s linear infinite;
      transform-origin: center center;
    }
    @keyframes iosFade{
      0%, 39%, 100% { opacity:.2; }
      40% { opacity:1; }
    }
    .spinner-ios i:nth-child(1)  { transform: rotate(  0deg) translateY(-24px); animation-delay:-1.1s; }
    .spinner-ios i:nth-child(2)  { transform: rotate( 30deg) translateY(-24px); animation-delay:-1.0s; }
    .spinner-ios i:nth-child(3)  { transform: rotate( 60deg) translateY(-24px); animation-delay:-0.9s; }
    .spinner-ios i:nth-child(4)  { transform: rotate( 90deg) translateY(-24px); animation-delay:-0.8s; }
    .spinner-ios i:nth-child(5)  { transform: rotate(120deg) translateY(-24px); animation-delay:-0.7s; }
    .spinner-ios i:nth-child(6)  { transform: rotate(150deg) translateY(-24px); animation-delay:-0.6s; }
    .spinner-ios i:nth-child(7)  { transform: rotate(180deg) translateY(-24px); animation-delay:-0.5s; }
    .spinner-ios i:nth-child(8)  { transform: rotate(210deg) translateY(-24px); animation-delay:-0.4s; }
    .spinner-ios i:nth-child(9)  { transform: rotate(240deg) translateY(-24px); animation-delay:-0.3s; }
    .spinner-ios i:nth-child(10) { transform: rotate(270deg) translateY(-24px); animation-delay:-0.2s; }
    .spinner-ios i:nth-child(11) { transform: rotate(300deg) translateY(-24px); animation-delay:-0.1s; }
    .spinner-ios i:nth-child(12) { transform: rotate(330deg) translateY(-24px); animation-delay: 0s; }

    /* Secciones */
    .section-title{
      margin: 18px auto 8px;
      max-width: 1000px;
      padding: 0 16px;
      color:#111;
      font-weight:800;
      font-size: 1.05rem;
    }
    .divider{
      max-width: 1000px;
      margin: 10px auto 0;
      padding: 0 16px;
    }
    .divider hr{
      border:none;
      border-top: 2px dashed rgba(0,0,0,.15);
      margin: 14px 0;
    }

    /* Vistas (solo aplica para Referidos) */
    .view{
      display:none;
      opacity:0;
      transform:translateY(8px);
      transition:opacity .25s ease, transform .25s ease;
      box-sizing:border-box;
      padding:0;
    }
    .view.active{
      display:block;
      opacity:1;
      transform:translateY(0);
    }
  </style>
</head>

<body>
  <!-- Loader único (para ambas apps) -->
  <div id="loader" class="loader hidden" aria-live="polite" aria-busy="true">
    <div class="spinner-ios" role="status" aria-label="Cargando">
      <i></i><i></i><i></i><i></i><i></i><i></i>
      <i></i><i></i><i></i><i></i><i></i><i></i>
    </div>
  </div>

  <div class="container">

    <!-- ===================== ARRIBA: REGISTRO DE VOTACIÓN (index2) ===================== -->
    <section class="card" aria-label="Registro de Votación">
      <h1 style="color:var(--primary); text-shadow: 0 2px 2px #031732;">REGISTRO DE VOTACIÓN</h1>
      <p class="helper"><b>Ingresa el número de documento que aparece en el certificado electoral</b></p>

      <label for="documento-voto">Documento</label>
      <input
        id="documento-voto"
        type="tel"
        inputmode="numeric"
        placeholder="Sin puntos ni espacios"
        autocomplete="off"
        required
      />

      <div class="btn-row" style="margin-top:14px;">
        <button id="btn-guardar-voto" class="btn-primary">Guardar</button>
      </div>
    </section>

    <div class="divider"><hr></div>

    <!-- ===================== ABAJO: REFERIDOS (index1) ===================== -->
    <section id="view-login" class="view active" aria-label="Referidos">
      <div class="card">
        <h1>REFERIDOS</h1>
        <p class="helper">
          Ingresa tu Documento para registrar o consultar tus referidos.
        </p>

        <label>Documento</label>
        <input id="doc-login" type="tel" inputmode="numeric" placeholder="Sin puntos ni espacios">

        <div class="btn-col">
          <button class="btn-primary" id="btn-registrar">Registrar</button>
          <button id="btn-validar">Validar</button>
          <button id="btn-compartir" class="btn-with-icon">
            <img src="https://res.cloudinary.com/dqqeavica/image/upload/v1759166341/WhatsApp_mljaqm.webp" alt="" aria-hidden="true">
            <span>Comparte</span>
          </button>
        </div>
      </div>

      <div id="registro-card" class="card hidden">
        <h2>Nuevo Registro</h2>
        <p class="helper">
          Completa la información para crear tu registro de referidos.
        </p>

        <label>Nombre Completo</label>
        <input id="reg-nombre" type="text" placeholder="Ingresa tu Nombre completo">

        <label>Whatsapp</label>
        <input id="reg-telefono" type="tel" inputmode="numeric" placeholder="10 dígitos">

        <label>N° Referido</label>
        <input id="reg-referencia" type="tel" inputmode="numeric" placeholder="N° de Referido">

        <div class="btn-col">
          <button class="btn-primary" id="btn-guardar-registro">Guardar</button>
          <button id="btn-reg-atras">Atrás</button>
        </div>

        <p class="center muted">
          Revisa la información antes de guardar.
        </p>
      </div>
    </section>

  </div>

  <script>
    /* =====================================================================================
       LOADER ÚNICO (compartido)
    ===================================================================================== */
    const loader = document.getElementById('loader');
    let loadingCount = 0;
    let loaderTimer = null;

    function startLoading(){
      loadingCount++;
      if (loadingCount === 1){
        loaderTimer = setTimeout(()=> {
          loader.classList.remove('hidden');
          loaderTimer = null;
        }, 120);
      }
    }

    function stopLoading(){
      if (loadingCount === 0) return;
      loadingCount--;
      if (loadingCount === 0){
        if (loaderTimer){
          clearTimeout(loaderTimer);
          loaderTimer = null;
        }
        loader.classList.add('hidden');
      }
    }

    /* =====================================================================================
       SONIDOS (unificados) + Patch SweetAlert2
       - Se respeta el comportamiento de index2 (sonar por icon)
       - Se respeta el comportamiento de index1 (soundTag: 'login')
    ===================================================================================== */
    const SOUNDS = {
      // Index2
      info: 'https://res.cloudinary.com/dqqeavica/video/upload/v1759011578/Default_notification_pkp4wr.mp3',
      success: 'https://res.cloudinary.com/dqqeavica/video/upload/v1759011577/Pay_success_t5aawh.mp3',
      error: 'https://res.cloudinary.com/dqqeavica/video/upload/v1759011578/Low_battery_d5qua1.mp3',
      warning: 'https://res.cloudinary.com/dqqeavica/video/upload/v1759011578/Low_battery_d5qua1.mp3',
      question: 'https://res.cloudinary.com/dqqeavica/video/upload/v1759011577/Pay_fail_ls2aif.mp3',

      // Index1 extra
      login: 'https://res.cloudinary.com/dqqeavica/video/upload/v1759011577/Siri_star_g1owy4.mp3'
    };

    function playSoundOnce(url){
      try{
        const a = new Audio(url);
        a.preload = 'auto';
        a.play().catch(()=>{});
      }catch(e){}
    }

    // Patch SweetAlert2 (una sola vez)
    if (window.Swal && typeof Swal.fire === 'function'){
      const __fire = Swal.fire.bind(Swal);
      Swal.fire = function(options = {}, ...rest){
        try{
          const icon = options.icon || options.type;
          if (icon && SOUNDS[icon]) playSoundOnce(SOUNDS[icon]);
          if (options && options.soundTag === 'login' && SOUNDS.login) playSoundOnce(SOUNDS.login);
        }catch(e){}
        return __fire(options, ...rest);
      };
    }

    /* =====================================================================================
       APP 1: REGISTRO DE VOTACIÓN (index2) - SIN CAMBIAR ENDPOINT
    ===================================================================================== */
    const API_BASE_VOTO = 'https://script.google.com/macros/s/AKfycbynqDDTonOjq3wJaeeOdTkj59AfA2DFLSlGv9veiPNeFipSjKjA0nXgtwDf2u1FQQTn/exec';

    async function apiGetVoto(action, params = {}){
      startLoading();
      try{
        const url = new URL(API_BASE_VOTO);
        url.search = new URLSearchParams({ action, ...params }).toString();
        const r = await fetch(url.toString(), { method:'GET' });
        const j = await r.json();
        if(!j.ok) throw new Error(j.error || 'Error');
        return j.data;
      } finally {
        stopLoading();
      }
    }

    function resetFormVoto(){
      const doc = document.getElementById('documento-voto');
      if(doc) doc.value = '';
      try{ doc && doc.focus(); }catch(_){}
    }

    function validarDocumentoVoto(v){
      const documento = String(v||'').trim();
      if(!documento){
        Swal.fire({ icon:'warning', title:'Documento requerido', text:'Ingresa el documento.' });
        return null;
      }
      if(!/^\d{6,10}$/.test(documento)){
        Swal.fire({ icon:'warning', title:'Documento inválido', text:'Debe tener de 6 a 10 dígitos (sin puntos ni espacios).' });
        return null;
      }
      return documento;
    }

    document.getElementById('btn-guardar-voto').addEventListener('click', async ()=> {
      const documento = validarDocumentoVoto(document.getElementById('documento-voto').value);
      if(!documento) return;

      try{
        const res = await apiGetVoto('registrarVoto', { documento });

        // status posibles: NOT_FOUND | DUPLICATE | OK
        if(res?.status === 'NOT_FOUND'){
          await Swal.fire({
            icon:'info',
            title:'DOCUMENTO INEXISTENTE',
            text:'Usa la estrategia de registro con el grupo.'
          });
          return;
        }

        if(res?.status === 'DUPLICATE'){
          await Swal.fire({
            icon:'info',
            title:'YA REGISTRADO',
            text:'Este documento ya registró su voto.'
          });
          resetFormVoto();
          return;
        }

        await Swal.fire({
          icon:'success',
          title:'VOTO REGISTRADO',
          timer: 2000,
          showConfirmButton: false
        });

        resetFormVoto();
      }catch(e){
        Swal.fire({ icon:'error', title:'Error', text: e.message });
      }
    });

    document.getElementById('documento-voto').addEventListener('keydown', (e)=> {
      if(e.key === 'Enter'){
        e.preventDefault();
        document.getElementById('btn-guardar-voto').click();
      }
    });

    resetFormVoto();

    /* =====================================================================================
       APP 2: REFERIDOS (index1) - SIN CAMBIAR ENDPOINT
       (Se conserva la lógica; se renombran funciones internas para no chocar con las de Voto)
    ===================================================================================== */
    const API_BASE_REFERIDOS = 'https://script.google.com/macros/s/AKfycby1qmaPhvKbUOYDSAzIco9YPTnV-PRSer5PmR2zWrxMVC1hsUxEjmhAKv-fTcYrgvSh/exec';

    function concatRef(){
      var out = '';
      var i;
      for (i = 0; i < arguments.length; i = i + 1){
        out = out + String(arguments[i]);
      }
      return out;
    }

    async function apiGetReferidos(action, params){
      startLoading();
      try{
        var url = new URL(API_BASE_REFERIDOS);
        var sp = new URLSearchParams();
        sp.set('action', action);
        if (params){
          var keys = Object.keys(params);
          var i;
          for (i = 0; i < keys.length; i = i + 1){
            var key = keys[i];
            sp.set(key, params[key]);
          }
        }
        url.search = sp.toString();
        var r = await fetch(url.toString(), { method: 'GET' });
        var j = await r.json();
        if (!j.ok) throw new Error(j.error || 'Error');
        return j.data;
      } finally {
        stopLoading();
      }
    }

    async function apiPostReferidos(action, body){
      startLoading();
      try{
        var url = concatRef(API_BASE_REFERIDOS, '?action=', encodeURIComponent(action));
        var r = await fetch(url, {
          method: 'POST',
          headers: { 'Content-Type': 'text/plain;charset=utf-8' },
          body: JSON.stringify(body || {})
        });
        var j = await r.json();
        if (!j.ok) throw new Error(j.error || 'Error');
        return j.data;
      } finally {
        stopLoading();
      }
    }

    function showViewRef(id){
      var views = document.querySelectorAll('.view');
      var i;
      for (i = 0; i < views.length; i = i + 1){
        views[i].classList.remove('active');
      }
      var el = document.getElementById(id);
      if (el){
        el.classList.add('active');
        window.scrollTo({ top: 0, behavior: 'smooth' });
      }
    }

    var docLogin = document.getElementById('doc-login');
    var btnRegistrar = document.getElementById('btn-registrar');
    var btnValidar = document.getElementById('btn-validar');
    var btnCompartir = document.getElementById('btn-compartir');

    var regCard = document.getElementById('registro-card');
    var btnGuardarRegistro = document.getElementById('btn-guardar-registro');
    var btnRegAtras = document.getElementById('btn-reg-atras');

    btnRegistrar.addEventListener('click', async function(){
      var documento = String(docLogin.value || '').trim();
      if (!documento){
        Swal.fire({
          icon: 'question',
          title: 'Documento requerido',
          text: 'Ingresa un Documento para continuar.',
          soundTag: 'login'
        });
        return;
      }
      var docRegex = /^(?:[0-9]{6,9}|1[0-9]{9})$/;
      if (!docRegex.test(documento)){
        Swal.fire({
          icon: 'warning',
          title: 'Documento inválido',
          text: 'El Documento debe tener de 6 a 10 dígitos sin puntos ni espacios.',
          soundTag: 'login'
        });
        return;
      }

      try{
        var res = await apiGetReferidos('validarDocumento', { documento: documento });
        if (res && res.existe){
          Swal.fire({
            icon: 'info',
            title: 'Documento ya existe',
            text: 'Este Documento ya se encuentra registrado.',
            soundTag: 'login'
          });
          return;
        }
        regCard.classList.remove('hidden');
        Swal.fire({
          icon: 'info',
          title: 'Nuevo Registro',
          text: 'Completa tu registro para continuar.',
          soundTag: 'login'
        });
      } catch (e){
        Swal.fire({
          icon: 'error',
          title: 'Error',
          text: e.message
        });
      }
    });

    btnRegAtras.addEventListener('click', function(e){
      e.preventDefault();
      regCard.classList.add('hidden');
    });

    btnGuardarRegistro.addEventListener('click', async function(){
      var documentoBase = String(docLogin.value || '').trim();
      var formData = {
        nombre: String(document.getElementById('reg-nombre').value || '').trim(),
        documento: documentoBase,
        telefono: String(document.getElementById('reg-telefono').value || '').trim(),
        referencia: String(document.getElementById('reg-referencia').value || '').trim()
      };

      var documentoRegex = /^(?:[0-9]{6,9}|1[0-9]{9})$/;
      var telefonoRegex = /^[0-9]{10}$/;
      var referenciaRegex = /^[0-9]{1,3}$/;

      if (!formData.nombre || !formData.documento || !formData.telefono || !formData.referencia){
        Swal.fire({
          icon: 'warning',
          title: 'Faltan campos requeridos',
          text: 'Completa Nombre, Documento (en la parte superior), Whatsapp y N° Referido.'
        });
        return;
      }

      var partesNombre = formData.nombre.split(/\s+/).filter(function(p){ return p; });
      if (partesNombre.length < 2){
        Swal.fire({
          icon: 'warning',
          title: 'Nombre incompleto',
          text: 'Ingresa tu nombre completo (mínimo nombre y apellido).'
        });
        return;
      }

      if (!documentoRegex.test(formData.documento)){
        Swal.fire({
          icon: 'warning',
          title: 'Documento inválido',
          text: 'Revisa el número de documento en la parte superior.'
        });
        return;
      }

      if (!telefonoRegex.test(formData.telefono)){
        Swal.fire({
          icon: 'warning',
          title: 'Whatsapp inválido',
          text: 'Debe tener exactamente 10 dígitos.'
        });
        return;
      }

      if (!referenciaRegex.test(formData.referencia)){
        Swal.fire({
          icon: 'warning',
          title: 'N° Referido inválido',
          text: 'Debe tener de 1 a 3 dígitos.'
        });
        return;
      }

      var resumenHtml = concatRef(
        '<b>Nombre:</b> ', formData.nombre, '<br>',
        '<b>N° Documento:</b> ', formData.documento, '<br>',
        '<b>Whatsapp:</b> ', formData.telefono, '<br>',
        '<b>N° Referido:</b> ', formData.referencia, '<br>'
      );

      var rs = await Swal.fire({
        icon: 'info',
        title: 'Resumen de Registro',
        html: resumenHtml,
        showCancelButton: true,
        confirmButtonText: 'Confirmar',
        cancelButtonText: 'Editar',
        width: '80%'
      });

      if (!rs.isConfirmed) return;

      try{
        var r = await apiPostReferidos('guardarContactoEnServidor', formData);
        if (r && r.success){
          await Swal.fire({
            icon: 'success',
            title: 'Registro exitoso',
            timer: 1800,
            showConfirmButton: false
          });
          regCard.classList.add('hidden');
          docLogin.value = '';
          document.getElementById('reg-nombre').value = '';
          document.getElementById('reg-telefono').value = '';
          document.getElementById('reg-referencia').value = '';
          showViewRef('view-login');
        } else {
          Swal.fire({
            icon: 'error',
            title: 'Error al guardar',
            html: r && r.message ? r.message : 'Error desconocido'
          });
        }
      } catch (e){
        Swal.fire({
          icon: 'error',
          title: 'Error',
          text: e.message
        });
      }
    });

    btnValidar.addEventListener('click', async function(){
      var documento = String(docLogin.value || '').trim();
      if (!documento){
        Swal.fire({
          icon: 'question',
          title: 'Documento requerido',
          text: 'Ingresa un Documento para validar.',
          soundTag: 'login'
        });
        return;
      }

      var docRegex = /^(?:[0-9]{6,9}|1[0-9]{9})$/;
      if (!docRegex.test(documento)){
        Swal.fire({
          icon: 'warning',
          title: 'Documento inválido',
          text: 'El Documento debe tener de 6 a 10 dígitos sin puntos ni espacios.',
          soundTag: 'login'
        });
        return;
      }

      try{
        var r = await apiGetReferidos('validarlider', { documento: documento });
        if (!r || !r.existe){
          await Swal.fire({
            icon: 'info',
            title: 'Toma la opción Registrar',
            text: 'Haz clic en el botón Registrar.'
          });
          return;
        }

        var titulo = concatRef(
          'Tienes ',
          r.totalReferidos || '0',
          ' Referidos ',
          r.nombreCorto || ''
        );

        await Swal.fire({
          icon: 'success',
          title: titulo,
          html: r.htmlReferidos || '',
          confirmButtonText: 'Cerrar'
        });
      } catch (e){
        Swal.fire({
          icon: 'error',
          title: 'Error',
          text: e.message
        });
      }
    });

    btnCompartir.addEventListener('click', function(){
      Swal.fire({
        icon: 'info',
        title: 'Compartir',
        text: 'Se abrirá WhatsApp para compartir la App.',
        soundTag: 'login'
      });

      var url = 'https://botheart911.github.io/af-listado/';
      var txt = concatRef(
        'Regístrate para apoyar con tus referidos. ',
        url
      );
      if (navigator.clipboard && navigator.clipboard.writeText){
        navigator.clipboard.writeText(txt).catch(function(){});
      }
      var enc = encodeURIComponent(txt);
      var ua = navigator.userAgent || '';
      var esMovil = /android|iphone|ipad|mobile/i.test(ua);
      var hrefMovil = concatRef('whatsapp://send?text=', enc);
      var hrefWeb = concatRef('https://api.whatsapp.com/send?text=', enc);
      window.open(esMovil ? hrefMovil : hrefWeb, '_blank');
    });

    showViewRef('view-login');
  </script>
</body>
</html>
