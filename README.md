# AYB-KE-RETMEN-
Aybüke Öğretmenimiz, 2017 yılında henüz 22 yaşındayken Batman'ın Kozluk ilçesinde PKK'lı teröristlerin haince düzenlediği bir silahlı saldırı sonucu şehit düşmüştü. O temiz sesiyle söylediği "Mağusa Limanı" türküsü ve "Beni öldürende yoktur din iman" sözleri hepimizin hafızasına kazındı.
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

        /* Navigasyon / Üst Menü */
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

        /* Ana Giriş Alanı (Hero Section) */
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('https://images.unsplash.com/photo-1511671782779-c97d3d27a1d4?q=80&w=1200') no-repeat center center/cover;
            height: 60vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            padding: 20px;
        }

        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            font-weight: 700;
        }

        .hero p {
            font-size: 1.2rem;
            color: #ddd;
            font-style: italic;
            max-width: 600px;
        }

        /* İçerik Konteyneri */
        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 0 20px;
        }

        /* Kart Yapısı */
        .card {
            background: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            margin-bottom: 30px;
            border-left: 5px solid #e63946;
        }

        .card h3 {
            color: #1a1a1a;
            margin-bottom: 15px;
            font-size: 1.6rem;
            border-bottom: 2px solid #f0f0f0;
            padding-bottom: 8px;
        }

        .card p {
            color: #555;
            font-size: 1.05rem;
            margin-bottom: 15px;
            text-align: justify;
        }

        /* Türkü Bölümü Gece Modu Esintili */
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
        }

        /* Anı Defteri Formu */
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

        /* Alt Bilgi (Footer) */
        footer {
            background-color: #1a1a1a;
            color: #888;
            text-align: center;
            padding: 20px;
            margin-top: 60px;
            font-size: 0.9rem;
        }
