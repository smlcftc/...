<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Korkuteli İlçe Sağlık Müdürlüğü Teşkilat Şeması</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f9;
        }
        h1 {
            color: white;
            background-color: red;
            padding: 15px;
            display: inline-block;
            border-radius: 5px;
            border: 2px solid black;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
        }
        .button-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 20px;
        }
        .button {
            background-color: red;
            color: white;
            padding: 15px 20px;
            margin: 10px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            font-size: 14px;
            width: 200px;
            height: 70px;
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
            transition: all 0.2s ease-in-out;
        }
        .button:hover {
            animation: shake 0.3s;
            animation-iteration-count: 1;
            transform: scale(1.05);
        }
        @keyframes shake {
            0% { transform: translateX(0); }
            25% { transform: translateX(-5px); }
            50% { transform: translateX(5px); }
            75% { transform: translateX(-5px); }
            100% { transform: translateX(0); }
        }
        .modal {
            display: none;
            position: fixed;
            z-index: 1;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            overflow: auto;
            background-color: rgba(0, 0, 0, 0.5);
            padding-top: 50px;
        }
        .modal-content {
            background-color: white;
            margin: auto;
            padding: 20px;
            border: 1px solid #888;
            width: 50%;
            border-radius: 10px;
            text-align: left;
        }
        .close {
            color: #aaa;
            float: right;
            font-size: 28px;
            font-weight: bold;
        }
        .close:hover, .close:focus {
            color: black;
            text-decoration: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>Korkuteli İlçe Sağlık Müdürlüğü Teşkilat Şeması</h1>
    <div class="button-container">
        <button class="button" onclick="showModal('Çevre Sağlığı Birimi', ['Şaban KARACA', 'İnci TANLAK'])">Çevre Sağlığı Birimi</button>
        <button class="button" onclick="showModal('Mali Hizmetler Birimi', ['Bülent KURT'])">Mali Hizmetler Birimi</button>
        <button class="button" onclick="showModal('Sağlıklı Beslenme ve Hareketli Hayat Birimi', [])">Sağlıklı Beslenme ve Hareketli Hayat Birimi</button>
        <button class="button" onclick="showModal('Disiplin İşlemleri Birimi', ['Emine ÖZTÜRK AKINCI', 'Ebe'])">Disiplin İşlemleri Birimi</button>
        <button class="button" onclick="showModal('İlaç ve Eczacılık Birimi', [])">İlaç ve Eczacılık Birimi</button>
        <button class="button" onclick="showModal('Ağız ve Diş Sağlığı Birimi', [])">Ağız ve Diş Sağlığı Birimi</button>
        <button class="button" onclick="showModal('Ayakta Teşhis ve Tedavi Yapılan Özel Sağlık Kuruluşları Birimi', [])">Ayakta Teşhis ve Tedavi Yapılan Özel Sağlık Kuruluşları Birimi</button>
        <button class="button" onclick="showModal('İnsan Kaynakları Birimi', ['Ramazan AKINCI','Emine DEMİRKAYA'])">İnsan Kaynakları Birimi</button>
        <button class="button" onclick="showModal('Bilgi İşlem Birimi', ['İsmail ÇİFTÇİ', 'Bilgisayar İşletmeni'])">Bilgi İşlem Birimi</button>
        <button class="button" onclick="showModal('Kanser Birimi', [])">Kanser Birimi</button>
        <button class="button" onclick="showModal('Ruh Sağlığı Birimi', [])">Ruh Sağlığı Birimi</button>
        <button class="button" onclick="showModal('Hasta Hakları ve Tıbbi Sosyal Hizmetler Birimi', [])">Hasta Hakları ve Tıbbi Sosyal Hizmetler Birimi</button>
        <button class="button" onclick="showModal('Kronik Hastalıklar ve Yaşlı Sağlığı Birimi', [])">Kronik Hastalıklar ve Yaşlı Sağlığı Birimi</button>
        <button class="button" onclick="showModal('Tütün ve Madde Bağımlılığı ile Mücadele Birimi', [])">Tütün ve Madde Bağımlılığı ile Mücadele Birimi</button>
        <button class="button" onclick="showModal('Kadın ve Üreme Sağlığı Birimi', [])">Kadın ve Üreme Sağlığı Birimi</button>
        <button class="button" onclick="showModal('Çocuk ve Ergen Sağlığı Birimi', [])">Çocuk ve Ergen Sağlığı Birimi</button>
        <button class="button" onclick="showModal('Aşı ile Önlenebilir Hastalıklar ve Bağışıklama Birimi', [])">Aşı ile Önlenebilir Hastalıklar ve Bağışıklama Birimi</button>
        <button class="button" onclick="showModal('Bulaşıcı Hastalıklar ve Erken Uyarı Birimi', [])">Bulaşıcı Hastalıklar ve Erken Uyarı Birimi</button>
        <button class="button" onclick="showModal('Tüberküloz Birimi', [])">Tüberküloz Birimi</button>
        <button class="button" onclick="showModal('Zoonotik ve Vektörel Hastalıklar Birimi', [])">Zoonotik ve Vektörel Hastalıklar Birimi</button>
        <button class="button" onclick="showModal('Çalışan Sağlığı Birimi', [])">Çalışan Sağlığı Birimi</button>
        <button class="button" onclick="showModal('Aile Hekimliği Uygulama ve Geliştirme Birimi', [])">Aile Hekimliği Uygulama ve Geliştirme Birimi</button>
        <button class="button" onclick="showModal('Aile Hekimliği Eğitim ve İzleme Birimi', [])">Aile Hekimliği Eğitim ve İzleme Birimi</button>
        <button class="button" onclick="showModal('Göç Sağlığı Birimi', [])">Göç Sağlığı Birimi</button>
        <button class="button" onclick="showModal('Toplum Sağlığı Hizmetleri ve Eğitim Birimi', [])">Toplum Sağlığı Hizmetleri ve Eğitim Birimi</button>
    </div>

    <div id="modal" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal()">&times;</span>
            <h2 id="unit-name"></h2>
            <ul id="personnel-list"></ul>
        </div>
    </div>

    <script>
        function showModal(unitName, personnel) {
            document.getElementById('unit-name').innerText = unitName;
            const list = document.getElementById('personnel-list');
            list.innerHTML = ''; // Önceki içerikleri temizle
            if (personnel.length > 0) {
                personnel.forEach(person => {
                    const li = document.createElement('li');
                    li.innerText = person;
                    list.appendChild(li);
                });
            } else {
                const li = document.createElement('li');
                li.innerText = 'Personel bilgisi mevcut değil.';
                list.appendChild(li);
            }
            document.getElementById('modal').style.display = 'block';
        }

        function closeModal() {
            document.getElementById('modal').style.display = 'none';
        }
    </script>
</body>
</html>
