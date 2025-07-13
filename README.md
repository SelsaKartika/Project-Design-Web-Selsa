# Project-Design-Web-Selsa

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recipe Platform - Kuliner Indonesia</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f8f9fa;
        }
        
        .container {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        h1 {
            color: #e74c3c;
            border-bottom: 3px solid #e74c3c;
            padding-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        h2 {
            color: #2c3e50;
            margin-top: 30px;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        h3 {
            color: #34495e;
            margin-top: 20px;
        }
        
        .badge {
            background: #e74c3c;
            color: white;
            padding: 4px 8px;
            border-radius: 4px;
            font-size: 0.8em;
            font-weight: bold;
        }
        
        .stats {
            background: #ecf0f1;
            padding: 15px;
            border-radius: 8px;
            margin: 15px 0;
        }
        
        .stats ul {
            margin: 0;
            padding-left: 20px;
        }
        
        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        
        .feature-card {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            border-left: 4px solid #e74c3c;
        }
        
        .feature-card h4 {
            margin-top: 0;
            color: #2c3e50;
        }
        
        .code-block {
            background: #2c3e50;
            color: #ecf0f1;
            padding: 20px;
            border-radius: 8px;
            overflow-x: auto;
            margin: 15px 0;
        }
        
        .code-block pre {
            margin: 0;
            white-space: pre-wrap;
        }
        
        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 15px 0;
        }
        
        .tech-item {
            background: #3498db;
            color: white;
            padding: 5px 10px;
            border-radius: 15px;
            font-size: 0.9em;
        }
        
        .contact-info {
            background: #e8f5e8;
            padding: 20px;
            border-radius: 8px;
            margin-top: 20px;
        }
        
        .footer {
            text-align: center;
            margin-top: 30px;
            padding-top: 20px;
            border-top: 1px solid #ddd;
            color: #666;
            font-style: italic;
        }
        
        a {
            color: #e74c3c;
            text-decoration: none;
        }
        
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🍳 Recipe Platform - Kuliner Indonesia</h1>
        
        <h2>🌟 Tentang Proyek Ini</h2>
        <p>Proyek ini adalah platform resep berbasis web yang terinspirasi dari aplikasi kuliner populer <strong>Yummy</strong>. Tujuan kami adalah menciptakan platform yang sederhana, intuitif, dan menarik secara visual untuk membantu para pecinta kuliner Indonesia menemukan, berbagi, dan menguasai resep masakan.</p>
        
        <h2>💡 Inspirasi</h2>
        <p>Inspirasi kami berasal dari aplikasi <strong>Yummy</strong> yang telah meraih kesuksesan luar biasa:</p>
        <div class="stats">
            <ul>
                <li>1 juta unduhan di toko aplikasi</li>
                <li>Rating 4.5 bintang dari pengguna</li>
                <li>Presentasi resep yang sederhana dan mudah dipahami</li>
                <li>Gambar berkualitas tinggi dan konten video yang menarik</li>
            </ul>
        </div>
        
        <h2>✨ Fitur Utama</h2>
        
        <h3>🚀 Fitur Saat Ini</h3>
        <div class="feature-grid">
            <div class="feature-card">
                <h4>📋 Penemuan Resep</h4>
                <p>Jelajahi resep berdasarkan kategori (bahan, jenis masakan)</p>
            </div>
            <div class="feature-card">
                <h4>🎥 Pembelajaran Visual</h4>
                <p>Gambar berkualitas tinggi dan tutorial video untuk setiap resep</p>
            </div>
            <div class="feature-card">
                <h4>👩‍🍳 Panduan Langkah-demi-Langkah</h4>
                <p>Instruksi visual yang jelas membuat memasak menjadi mudah diakses</p>
            </div>
            <div class="feature-card">
                <h4>🔍 Pencarian Lanjutan</h4>
                <p>Fungsi pencarian detail untuk akses resep yang mudah</p>
            </div>
            <div class="feature-card">
                <h4>💬 Interaksi Pengguna</h4>
                <p>Sistem komentar dan saran resep</p>
            </div>
            <div class="feature-card">
                <h4>👨‍🍳 Konten Chef Terkenal</h4>
                <p>Resep unggulan dari koki terkenal dan influencer kuliner</p>
            </div>
        </div>
        
        <h3>🔮 Fitur yang Direncanakan</h3>
        <div class="feature-grid">
            <div class="feature-card">
                <h4>🛒 Generator Daftar Belanja</h4>
                <p>Otomatis membuat daftar belanja dari resep</p>
            </div>
            <div class="feature-card">
                <h4>❤️ Resep Favorit</h4>
                <p>Simpan dan atur resep favorit</p>
            </div>
            <div class="feature-card">
                <h4>📚 Koleksi Resep</h4>
                <p>Buat koleksi resep kustom</p>
            </div>
            <div class="feature-card">
                <h4>⏱️ Timer Memasak</h4>
                <p>Timer built-in untuk langkah-langkah memasak</p>
            </div>
        </div>
        
        <h2>🎯 Misi</h2>
        <p>Mendukung para pecinta kuliner dan membantu meningkatkan kemampuan memasak di kalangan masyarakat Indonesia dengan menyediakan platform kuliner yang mudah diakses, komprehensif, dan menarik.</p>
        
        <h2>🚀 Memulai</h2>
        
        <h3>📋 Prasyarat</h3>
        <ul>
            <li>Node.js (v14 atau lebih tinggi)</li>
            <li>npm atau yarn</li>
            <li>Browser web modern</li>
        </ul>
        
        <h3>⚙️ Instalasi</h3>
        <div class="code-block">
            <pre># Clone repository
git clone https://github.com/yourusername/recipe-platform.git

# Masuk ke direktori proyek
cd recipe-platform

# Install dependencies
npm install

# Jalankan development server
npm start</pre>
        </div>
        
        <h2>🛠️ Tech Stack</h2>
        <div class="tech-stack">
            <span class="tech-item">Frontend: React/Vue/Angular</span>
            <span class="tech-item">Backend: Node.js/Python/PHP</span>
            <span class="tech-item">Database: MySQL/PostgreSQL/MongoDB</span>
            <span class="tech-item">Media: CloudStorage</span>
        </div>
        
        <h2>🤝 Kontribusi</h2>
        <p>Kami menyambut kontribusi dari komunitas! Silakan baca <a href="CONTRIBUTING.md">Panduan Kontribusi</a> sebelum mengirim pull request.</p>
        
        <h2>📄 Lisensi</h2>
        <p>Proyek ini dilisensikan di bawah <a href="LICENSE">MIT License</a>.</p>
        
        <div class="contact-info">
            <h2>📞 Kontak</h2>
            <p>Untuk pertanyaan atau saran, silakan hubungi:</p>
            <ul>
                <li>📧 Email: <a href="mailto:your-email@example.com">your-email@example.com</a></li>
                <li>🐙 GitHub Issues: <a href="#">Repository Issues Page</a></li>
            </ul>
        </div>
        
        <div class="footer">
            <p>🍽️ <em>Terinspirasi oleh Yummy App - Membuat memasak mudah diakses dan menyenangkan untuk semua</em></p>
        </div>
    </div>
</body>
</html>
