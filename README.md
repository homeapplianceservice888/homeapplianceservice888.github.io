<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Home Appliance Service</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">

  <style>
    :root {
      --bg: #000000;
      --gold: #d1a766;
      --gold-soft: #e3c792;
      --text: #f7f2e7;
      --muted: #a48a63;
    }
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      min-height: 100vh;
      background: radial-gradient(circle at top, #151515 0, #000 45%, #000 100%);
      color: var(--text);
      font-family: Inter, system-ui, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 24px 12px;
    }

    .card {
      width: 100%;
      max-width: 480px;
      background: #000;
      border-radius: 18px;
      border: 1px solid rgba(209,167,102,0.85);
      padding: 34px 24px 30px;
      text-align: center;
      box-shadow: 0 26px 70px rgba(0,0,0,0.9);
    }

    h1 {
      font-family: "Playfair Display", serif;
      font-size: 24px;
      letter-spacing: 0.22em;
      text-transform: uppercase;
      color: var(--gold-soft);
      margin-bottom: 22px;
    }

    .services {
      font-size: 13px;
      letter-spacing: 0.18em;
      text-transform: uppercase;
      color: var(--gold-soft);
      margin-bottom: 18px;
    }

    .rule-line {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 12px;
      margin-bottom: 22px;
      color: var(--gold-soft);
    }
    .rule-line span {
      flex: 1;
      height: 1px;
      background: linear-gradient(90deg, transparent, var(--gold-soft));
    }
    .rule-line span:last-child {
      background: linear-gradient(90deg, var(--gold-soft), transparent);
    }

    .phone {
      font-size: 18px;
      margin-bottom: 10px;
      color: var(--gold);
    }

    .email {
      font-size: 14px;
      color: var(--muted);
      margin-bottom: 30px;
    }

    .btn-main {
      padding: 13px 40px;
      border-radius: 999px;
      border: none;
      background: linear-gradient(135deg, #d6ad69, #b78645);
      color: #1b1308;
      font-size: 18px;
      cursor: pointer;
      box-shadow: 0 10px 30px rgba(0,0,0,0.7);
    }
  </style>
</head>

<body>

  <div class="card">
    <h1>HOME APPLIANCE SERVICE</h1>

    <p class="services">
      Washers Dryers Ovens Refrigerators Dishwashers Microwave
    </p>

    <div class="rule-line">
      <span></span><div>✧</div><span></span>
    </div>

    <p class="phone">call/text (253) 213-1651</p>
    <p class="email">homeapplianceservice888@gmail.com</p>

    <!-- ПРОСТОЙ РАБОЧИЙ ЗАПРОС НА ПОЧТУ -->
    <a
      class="btn-main"
      href="mailto:homeapplianceservice888@gmail.com?subject=Schedule%20request&body=Hello,%0D%0A%0D%0AMy name:%20_____%0D%0APhone:%20_____%0D%0AAddress:%20_____%0D%0ADate:%20_____%0D%0ATime%20window%20(8-12,%2012-4,%204-8):%20_____%0D%0AAppliance(s)%20(Washer,%20Dryer,%20Oven,%20Refrigerator,%20Dishwasher,%20Microwave):%20_____%0D%0A%0D%0AThank%20you."
    >
      Make Schedule
    </a>
  </div>

</body>
</html>
