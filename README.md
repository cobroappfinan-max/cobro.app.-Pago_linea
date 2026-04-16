<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Comprobante NexiPlus</title>

<style>

body{
  margin:0;
  background:#000000;
  font-family: Arial, Helvetica, sans-serif;
  color:#fff;
}

/* CONTENEDOR */
.container{
  max-width:420px;
  margin:auto;
  padding:20px;
}

/* HEADER */
.header{
  display:flex;
  align-items:center;
  gap:10px;
  margin-bottom:25px;
}

.logo{
  width:40px;
  height:40px;
  border-radius:50%;
  background:linear-gradient(45deg,#1e90ff,#00bfff);
  display:flex;
  align-items:center;
  justify-content:center;
  font-weight:bold;
}

.title{
  font-size:22px;
  font-weight:bold;
}

.title span{
  color:#4da6ff;
}

/* FILAS */
.row{
  display:flex;
  justify-content:space-between;
  padding:14px 0;
  border-bottom:1px solid rgba(255,255,255,0.1);
  font-size:14px;
}

.label{
  color:#aaa;
}

.value{
  color:#fff;
  text-align:right;
  max-width:55%;
}

/* FECHAS */
.date-row{
  display:flex;
  justify-content:space-between;
  margin-top:20px;
  font-size:14px;
}

.status{
  text-align:center;
  margin-top:40px;
  font-size:16px;
  color:#ccc;
}

</style>

</head>

<body>

<div class="container">

  <!-- HEADER -->
  <div class="header">
    <div class="logo">C</div>
    <div class="title">Credito<span>Industrial</span></div>
  </div>

  <!-- DATOS -->
  <div class="row">
    <div class="label">Nombre</div>
    <div class="value">Maria Angeles Diaz</div>
  </div>

  <div class="row">
    <div class="label">Documento</div>
    <div class="value">22792336</div>
  </div>

  <div class="row">
    <div class="label">Valor</div>
    <div class="value">$40.000,00</div>
  </div>

  <div class="row">
    <div class="label">Banco</div>
    <div class="value">BANCO DE LA PROVINCIA DE CORDOBA S.A.</div>
  </div>

  <div class="row">
    <div class="label">Número de cuenta</div>
    <div class="value">****3430</div>
  </div>

  <!-- FECHAS -->
  <div class="date-row">
    <div class="label">Solicitado</div>
    <div class="value">2026 11 02</div>
  </div>

  <div class="date-row">
    <div class="label">Depositado</div>
    <div class="value">2026 14 02</div>
  </div>

  <!-- ESTADO -->
  <div class="status">
    Depositado (Abonado)
  </div>

</div>

</body>
</html>
