<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gizlilik Politikası / Privacy Policy - Converter: Audio Video Visual</title>
    <style>
        :root {
            --primary: #4f46e5;
            --primary-hover: #4338ca;
            --bg-color: #f8fafc;
            --card-bg: #ffffff;
            --text-main: #1e293b;
            --text-muted: #64748b;
            --border-color: #e2e8f0;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 0 20px;
        }

        .card {
            background-color: var(--card-bg);
            border-radius: 12px;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
            padding: 40px;
            margin-bottom: 30px;
            border: 1px solid var(--border-color);
        }

        .lang-switch {
            display: flex;
            justify-content: flex-end;
            gap: 10px;
            margin-bottom: 20px;
        }

        .lang-btn {
            background-color: #e2e8f0;
            border: none;
            padding: 8px 16px;
            border-radius: 6px;
            cursor: pointer;
            font-weight: 600;
            color: var(--text-muted);
            transition: all 0.2s;
        }

        .lang-btn.active, .lang-btn:hover {
            background-color: var(--primary);
            color: white;
        }

        h1 {
            font-size: 24px;
            color: var(--text-main);
            margin-top: 0;
            border-bottom: 2px solid var(--border-color);
            padding-bottom: 15px;
        }

        h2 {
            font-size: 18px;
            color: var(--primary);
            margin-top: 25px;
        }

        p, li {
            color: var(--text-muted);
            font-size: 15px;
        }

        ul {
            padding-left: 20px;
        }

        li {
            margin-bottom: 8px;
        }

        .update-date {
            font-size: 13px;
            color: var(--text-muted);
            font-style: italic;
            margin-bottom: 25px;
        }

        .section {
            display: none;
        }

        .section.active {
            display: block;
        }

        .contact-box {
            background-color: #f1f5f9;
            padding: 15px 20px;
            border-radius: 8px;
            margin-top: 20px;
            border-left: 4px solid var(--primary);
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="lang-switch">
            <button class="lang-btn active" onclick="setLanguage('tr')">Türkçe</button>
            <button class="lang-btn" onclick="setLanguage('en')">English</button>
        </div>

        <div class="card">
            <!-- TÜRKÇE İÇERİK -->
            <div id="tr" class="section active">
                <h1>GİZLİLİK POLİTİKASI</h1>
                <div class="update-date">Son Güncelleme Tarihi: 4 Mart 2026</div>

                <p>"Converter: Audio Video Visual" ("Uygulama") olarak, kullanıcılarımızın gizliliğine büyük önem veriyoruz. Bu Gizlilik Politikası, uygulamamızı kullandığınızda verilerinizin nasıl işlendiğini açıklamak amacıyla hazırlanmıştır.</p>

                <h2>1. Toplanan Veriler ve Veri İşleme Süreci</h2>
                <p>Uygulamamız, kullanıcıların cihazlarındaki medya dosyalarını (görsel, ses ve video) dönüştürmesi amacıyla geliştirilmiştir.</p>
                <ul>
                    <li><strong>Yerel İşleme:</strong> Görsel dönüşümleri (Android Bitmap ve görüntü işleme kütüphaneleri) ve ses/video dönüşümleri (FFmpeg tabanlı sistem) tamamen cihazınız üzerinde yerel olarak gerçekleştirilir.</li>
                    <li><strong>Kişisel Veri Toplanmama İlkesi:</strong> Uygulamamız sunucularına hiçbir şekilde kişisel veri, fotoğraf, ses kaydı, video veya hassas dosya yüklemez, depolamaz veya üçüncü taraflarla paylaşmaz.</li>
                    <li><strong>Dosya Erişimi:</strong> Android Storage Access Framework (Sistem Dosya Seçicisi) aracılığıyla yalnızca sizin seçtiğiniz dosyalara ve çıktıların kaydedileceği klasörlere erişim sağlanır.</li>
                </ul>

                <h2>2. Uygulama İçi Özellikler ve İzinler</h2>
                <ul>
                    <li><strong>Depolama ve Dosya Yönetimi:</strong> Dönüştürülen dosyaların cihazınıza kaydedilmesi, paylaşılması veya açılması için depolama izinleri kullanılır. Bu veriler yalnızca sizin kontrolünüzdedir.</li>
                    <li><strong>Dönüştürme Geçmişi:</strong> Uygulama içerisinde tutulan geçmiş kayıtları sadece sizin cihazınızda yerel olarak saklanır.</li>
                </ul>

                <h2>3. Reklamlar ve Üçüncü Taraf Hizmetler</h2>
                <p>Uygulamamızda, hizmetlerimizi sürdürebilmek amacıyla üçüncü taraf reklam ağları (örneğin Google AdMob) kullanılabilir. Bu reklam sağlayıcıları, reklam sunmak ve ilgi alanınıza göre özelleştirilmiş reklamlar göstermek amacıyla cihaz tanımlayıcıları, çerezler veya benzer teknolojiler kullanabilir. Bu süreçte kişisel medya dosyalarınız (görsel, ses ve videolarınız) asla reklam sağlayıcılarıyla paylaşılmaz.</p>

                <h2>4. Çocukların Gizliliği</h2>
                <p>Uygulamamız 13 yaş altı çocuklardan bilerek kişisel veri toplamaz. Yerel işlem yapısı sayesinde çocukların gizliliği maksimum düzeyde korunur.</p>

                <h2>5. Değişiklikler</h2>
                <p>Bu Gizlilik Politikası zaman zaman güncellenebilir. Yapılan değişiklikler bu sayfada yayınlanacaktır.</p>

                <h2>6. İletişim</h2>
                <div class="contact-box">
                    <p>Gizlilik Politikamız ile ilgili her türlü soru ve öneriniz için bizimle iletişime geçebilirsiniz:</p>
                    <p><strong>E-posta:</strong> sonnurornek61@gmail.com</p>
                </div>
            </div>

            <!-- İNGİLİZCE İÇERİK -->
            <div id="en" class="section">
                <h1>PRIVACY POLICY</h1>
                <div class="update-date">Last Update: March 4, 2026</div>

                <p>As "Converter: Audio Video Visual" ("Application"), we attach great importance to the privacy of our users. This Privacy Policy is prepared to explain how your data is processed when you use our application.</p>

                <h2>1. Collected Data and Data Processing</h2>
                <p>Our application is designed to allow users to convert media files (image, audio, and video) directly on their devices.</p>
                <ul>
                    <li><strong>Local Processing:</strong> Image conversions (Android Bitmap and image processing libraries) and audio/video conversions (FFmpeg-based system) are performed entirely locally on your device.</li>
                    <li><strong>No Personal Data Collection Policy:</strong> Our application does not upload, store, or share personal data, photos, audio recordings, videos, or sensitive files to external servers in any way.</li>
                    <li><strong>File Access:</strong> Access is granted only to the files you select and the folders where outputs are saved through the Android Storage Access Framework (System File Picker).</li>
                </ul>

                <h2>2. In-App Features and Permissions</h2>
                <ul>
                    <li><strong>Storage and File Management:</strong> Storage permissions are used to save, share, or open converted files on your device. This data is entirely under your control.</li>
                    <li><strong>Conversion History:</strong> History records kept within the application are stored locally only on your device.</li>
                </ul>

                <h2>3. Ads and Third-Party Services</h2>
                <p>Our application may use third-party advertising networks (such as Google AdMob) to support our services. These ad providers may use device identifiers, cookies, or similar technologies to serve ads and display personalized advertisements based on your interests. During this process, your personal media files (images, audio, and videos) are never shared with advertising providers.</p>

                <h2>4. Children's Privacy</h2>
                <p>Our application does not knowingly collect personal data from children under the age of 13. Thanks to its local processing architecture, children's privacy is protected to the maximum degree.</p>

                <h2>5. Changes</h2>
                <p>This Privacy Policy may be updated from time to time. Changes will be posted on this page.</p>

                <h2>6. Contact Us</h2>
                <div class="contact-box">
                    <p>If you have any questions or suggestions regarding our Privacy Policy, you can contact us:</p>
                    <p><strong>Email:</strong> sonnurornek61@gmail.com</p>
                </div>
            </div>
        </div>
    </div>

    <script>
        function setLanguage(lang) {
            document.querySelectorAll('.section').forEach(el => el.classList.remove('active'));
            document.querySelectorAll('.lang-btn').forEach(el => el.classList.remove('active'));
            
            document.getElementById(lang).classList.add('active');
            event.currentTarget.classList.add('active');
        }
    </script>
</body>
</html>
