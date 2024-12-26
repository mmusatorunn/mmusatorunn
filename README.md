<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Otel Zaman Çizelgesi</title>
  <!-- Bootstrap 5 CSS bağlantısı -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .timeline {
      position: relative;
      padding: 20px 0;
    }
    .timeline::before {
      content: '';
      position: absolute;
      left: 50%;
      top: 0;
      bottom: 0;
      width: 4px;
      background: #e9ecef;
      transform: translateX(-50%);
    }
    .timeline-item {
      position: relative;
      margin-bottom: 30px;
    }
    .timeline-item::before {
      content: '';
      position: absolute;
      left: 50%;
      top: 0;
      width: 20px;
      height: 20px;
      background: #007bff;
      border-radius: 50%;
      transform: translateX(-50%);
    }
    .timeline-content {
      position: relative;
      padding: 15px;
      background: #f8f9fa;
      border-radius: 10px;
      max-width: 60%;
    }
    .timeline-content .date {
      font-size: 12px;
      color: #6c757d;
    }
    .timeline-item.right .timeline-content {
      left: 50%;
      margin-left: 30px;
    }
    .timeline-item.left .timeline-content {
      left: 0;
      margin-right: 30px;
    }
  </style>
</head>
<body>

<div class="container mt-5">
  <h2>Otel Zaman Çizelgesi</h2>
  <div class="timeline">
    <!-- Otel Giriş -->
    <div class="timeline-item left">
      <div class="timeline-content">
        <h5>Otel Girişi</h5>
        <p class="date">14 Aralık 2024 - 14:00</p>
        <p>Misafirler otele giriş yaptı. Odaya yerleşme işlemleri tamamlandı.</p>
      </div>
    </div>
    <!-- Yemek Servisi -->
    <div class="timeline-item right">
      <div class="timeline-content">
        <h5>Öğle Yemeği Servisi</h5>
        <p class="date">14 Aralık 2024 - 13:00</p>
        <p>Misafirlere açık büfe öğle yemeği servisi sunuldu.</p>
      </div>
    </div>
    <!-- Spa Ziyareti -->
    <div class="timeline-item left">
      <div class="timeline-content">
        <h5>Spa Ziyareti</h5>
        <p class="date">14 Aralık 2024 - 15:00</p>
        <p>Misafirler spa bölümünde rahatlama fırsatı buldu.</p>
      </div>
    </div>
    <!-- Akşam Yemeği -->
    <div class="timeline-item right">
      <div class="timeline-content">
        <h5>Akşam Yemeği</h5>
        <p class="date">14 Aralık 2024 - 19:00</p>
        <p>Günün finalinde akşam yemeği servisi yapıldı.</p>
      </div>
    </div>
    <!-- Oda Servisi -->
    <div class="timeline-item left">
      <div class="timeline-content">
        <h5>Oda Servisi</h5>
        <p class="date">14 Aralık 2024 - 21:00</p>
        <p>Misafirlere gece için oda servisi hizmeti sağlandı.</p>
      </div>
    </div>
  </div>
</div>

<!-- Bootstrap 5 JS bağlantısı -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
