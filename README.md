<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Our Services</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
    }

    .services-section {
      text-align: center;
      padding: 60px 20px;
      background-color: #ffffff;
    }

    .services-section h2 {
      font-size: 36px;
      margin-bottom: 10px;
    }

    .services-section p {
      color: #555;
      font-size: 18px;
      margin-bottom: 40px;
    }

    .services-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
    }

    .service-box {
      background: #f0f0f0;
      border-radius: 12px;
      padding: 30px;
      width: 280px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .service-box:hover {
      transform: translateY(-8px);
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
    }

    .service-icon {
      font-size: 40px;
      margin-bottom: 15px;
      color: #007bff;
    }

    .service-title {
      font-size: 22px;
      margin-bottom: 10px;
      font-weight: bold;
    }

    .service-description {
      color: #666;
      font-size: 16px;
    }
  </style>
</head>
<body>

  <section class="services-section">
    <h2>Our Services</h2>
    <p>We provide high-quality solutions to help your business grow</p>

    <div class="services-container">
      <div class="service-box">
        <div class="service-icon">💻</div>
        <div class="service-title">Web Design</div>
        <div class="service-description">Modern, responsive, and SEO-friendly websites using WordPress & Elementor.</div>
      </div>

      <div class="service-box">
        <div class="service-icon">📊</div>
        <div class="service-title">Data Analysis</div>
        <div class="service-description">Clean, analyze, and visualize your business data with accuracy and clarity.</div>
      </div>

      <div class="service-box">
        <div class="service-icon">📧</div>
        <div class="service-title">Email Marketing</div>
        <div class="service-description">Grow your audience and convert leads through powerful email campaigns.</div>
      </div>
    </div>
  </section>

</body>
</html>
