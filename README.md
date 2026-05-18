<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Şehit Öğretmen Aybüke Yalçın Anısına</title>
    <style>
        /* Genel Ayarlar */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f7f9fa;
            color: #333;
            line-height: 1.6;
        }

        /* Üst Başlık (Header) */
        header {
            background-color: #1a1a1a;
            color: white;
            padding: 20px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.2);
        }

        header h1 {
            font-size: 1.5rem;
            letter-spacing: 1px;
            color: #e63946;
        }

        /* Ana Giriş Alanı (Hero) */
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('https://images.unsplash.com/photo-1511671782779-c97d3d27a1d4?q=80&w=1200') no-repeat center center/cover;
            height: 50vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            padding: 20px;
        }

        .hero h2 {
            font-size: 2.3rem;
            margin-bottom: 10px;
            font-weight: 700;
        }

        .hero p {
            font-size: 1.1rem;
            color: #ddd;
            font-style: italic;
            max-width: 600px;
        }

        /* İçerik Kutusu */
        .container {
            max-width: 800px;
            margin: 30px auto;
            padding: 0 20px;
        }

        /* Bilgi Kartları */
        .card {
            background: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            margin-bottom: 25px;
            border-left: 5px solid #e63946;
        }

        .card h3 {
            color: #1a1a1a;
            margin-bottom: 15px;
            font-size: 1.5rem;
            border-bottom: 2px solid #f0f0f0;
            padding-bottom: 8px;
        }

        .card p {
            color: #555;
            font-size: 1.05rem;
            margin-bottom: 15px;
            text-align: justify;
        }

        /* Türkü Kartı */
        .lyrics-card {
            background: #2b2d42;
            color: #edf2f4;
            border-left: 5px solid #8d99ae;
        }

        .lyrics-card h3 {
            color: #edf2f4;
            border-bottom: 2px solid #3d405b;
        }

        .lyrics {
            font-style: italic;
            text-align: center;
            line-height: 2;
            color: #f4f4f9;
            background: rgba(255,255,255,0.05);
            padding: 20px;
            border-radius: 8px;
            font-size: 1.1rem;
        }

        /* Form Yapısı */
        .form-group {
            margin-bottom: 15px;
        }

        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
            color: #444;
        }

        .form-control {
            width: 100%;
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 8px;
            font-size: 1rem;
            outline: none;
            transition: 0.3s;
        }

        .form-control:focus {
            border-color: #e63946;
        }

        .btn {
            background-color: #e63946;
            color: white;
            padding: 12px 25px;
            border: none;
            border-radius: 8px;
            font-size: 1rem;
            cursor: pointer;
            width: 100%;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn:hover {
            background-color: #cb2d3e;
        }

        /* Alt Bilgi */
        footer {
            background-color: #1a1a1a;
            color: #888;
            text-align: center;
            padding: 20px;
            margin-top: 50px;
            font-size: 0.9rem;
        }

        footer span {
            color: #e63946;
        }
    </style>
</head>
<body>

    <header>
        <h1>ŞENAY AYBÜKE YALÇIN</h1>
    </header>

    <section class="hero">
        <h2>Unutmayacağız...</h2>
        <p>"Beni öldürende yoktur din iman..." Geride kalan hüzünlü bir türkü, hiç solmayacak bir öğretmen aşkı.</p>
    </section>

    <div class="container">

        <div class="card">
            <h3>İdealist Bir Ömür</h3>
            <p>Şenay Aybüke Yalçın, 1994 yılında Çorum'da dünyaya geldi. Müziğe ve öğretmenlik mesleğine olan büyük aşkıyla Necmettin Erbakan Üniversitesi Müzik Öğretmenliği bölümünden mezun oldu.</p>
            <p>2016 yılında hayalini kurduğu mesleğe adım atarak Batman'ın Kozluk ilçesine müzik öğretmeni olarak atandı. Atandığı gün attığı "Öğretmen oldum ben" mesajı, onun mesleğine olan inancının ve sevincinin en temiz kanıtıydı. Okulunda kısa sürede tüm öğrencilerinin sevgilisi oldu, onlara müziği sevdirdi.</p>
        </div>

        <div class="card">
            <h3>9 Haziran 2017</h3>
            <p>Henüz ilk öğretmenlik yılının sonunda, büyük bir heyecanla öğrencilerine karnelerini dağıttı. Yaz tatili için memleketine dönmek üzere arkadaşlarıyla yola çıktığı sırada, Kozluk ilçe merkezinde hain terör örgütü PKK mensupları tarafından düzenlenen silahlı saldırıda kurşunların hedefi oldu.</p>
            <p>Henüz 22 yaşında, ömrünün ve hayallerinin baharında şehitlik mertebesine ulaştı. Aybüke Öğretmen, sadece öğrencilerinin değil, tüm Türkiye'nin kalbinde ölümsüz bir simge haline geldi.</p>
        </div>

        <div class="card lyrics-card">
            <h3>Hafızalara Kazınan Ses: Mağusa Limanı</h3>
            <p>Ondan geriye, o güler yüzüyle seslendirdiği ve adeta kendi kaderini fısıldadığı hüzünlü Mağusa Limanı türküsü kaldı:</p>
            <div class="lyrics">
                Mağusa limanı limandır liman<br>
                Beni öldürende yoktur din iman<br>
                <br>
                Uyan alim uyan uyanmaz oldun<br>
                Yedi bıçak yarasına dayanmaz oldun
            </div>
        </div>

        <div class="card">
            <h3>Anı Defterine Not Bırakın</h3>
            <p>Aybüke Öğretmenimiz için hislerinizi, dualarınızı ve mesajlarınızı aşağıdaki alandan paylaşabilirsiniz.</p>
            <form onsubmit="alert('Mesajınız (Temsili olarak) anı defterine eklendi.'); return false;">
                <div class="form-group">
                    <label>Adınız Soyadınız</label>
                    <input type="text" class="form-control" placeholder="Adınızı yazın" required>
                </div>
                <div class="form-group">
                    <label>Mesajınız</label>
                    <textarea class="form-control" rows="4" placeholder="Aybüke Öğretmenimiz için duygularınızı yazın..." required></textarea>
                </div>
                <button type="submit" class="btn">Anı Defterine Gönder</button>
            </form>
        </div>

    </div>

    <footer>
        <p>Bu site Şehit Şenay Aybüke Yalçın'ın aziz anısına saygıyla hazırlanmıştır. <span>Vatan sağ olsun.</span></p>
    </footer>

</body>
    </html>
    
