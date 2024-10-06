<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>HearkenHeart</title>
</head>
<body>
    <header>
        <h1>HearkenHeart</h1>
        <nav>
            <ul>
                <li><a href="#services">บริการ</a></li>
                <li><a href="#appointment">นัดหมาย</a></li>
                <li><a href="#about">เกี่ยวกับเรา</a></li>
                <li><a href="#contact">ติดต่อ</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <h2>คำปรึกษาที่คุณต้องการ</h2>
        <p>ให้คำปรึกษาออนไลน์ในทุกด้าน</p>
        <a href="#appointment" class="button">นัดหมายเลย</a>
    </section>

    <section id="services">
        <h2>บริการของเรา</h2>
        <div class="service-card">
            <h3>การให้คำปรึกษาเฉพาะด้าน</h3>
            <p>ให้คำปรึกษาในหลากหลายด้าน เช่น สุขภาพจิต การเงิน ฯลฯ</p>
        </div>
        <div class="service-card">
            <h3>การสนับสนุน 24/7</h3>
            <p>มีทีมงานพร้อมให้บริการตลอด 24 ชั่วโมง</p>
        </div>
    </section>

    <section id="appointment">
        <h2>นัดหมายการให้คำปรึกษา</h2>
        <form id="appointment-form">
            <label for="name">ชื่อ:</label>
            <input type="text" id="name" required>
            <label for="email">อีเมล:</label>
            <input type="email" id="email" required>
            <label for="date">วันที่:</label>
            <input type="date" id="date" required>
            <label for="time">เวลา:</label>
            <input type="time" id="time" required>
            <button type="submit">นัดหมาย</button>
        </form>
    </section>

    <section id="about">
        <h2>เกี่ยวกับเรา</h2>
        <p>HearkenHeart มุ่งมั่นที่จะให้คำปรึกษาที่มีคุณภาพและช่วยเหลือผู้คนในทุกด้าน</p>
    </section>

    <section id="contact">
        <h2>ช่องทางการติดต่อ</h2>
        <p>Email: example@hearkenheart.com</p>
        <p>โทร: 012-345-6789</p>
        <p>Line: <a href="https://line.me/R/ti/p/%40yourlineid">@yourlineid</a></p>
    </section>

    <footer>
        <p>&copy; 2024 HearkenHeart. สงวนลิขสิทธิ์.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
