[About You.html](https://github.com/user-attachments/files/24336104/About.You.html)
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>11.11.2025</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #9a4903d2;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        /* Kontainer utama kartu */
        .card-slider {
            width: 400px;
            background-color: #c18e5e;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.292);
            overflow: hidden; 
            display: flex;
            flex-direction: column; 
            
            /* 👇 SESUAI PERMINTAAN ANDA: margin: 8px; 👇 */
            margin: 8px; 
        }

        /* Area tempat slide akan muncul */
        .slider-content {
            padding: 30px;
            min-height: 250px; 
            text-align: center;
        }

        /* Masing-masing slide */
        .slide {
            display: none; 
            animation: fadeIn 0.5s;
        }

        /* Slide yang sedang aktif */
        .slide.active {
            display: block; 
        }

        /* Styling konten di dalam slide */
        .slide h2 {
            color: #111112;
            margin-top: 0;
        }

        .slide p {
            color: #0c0c0c;
            font-size: 17px;
            line-height: 1.7;
        }
        
        /* Kontainer untuk tombol navigasi */
        .navigation {
            display: flex;
            justify-content: space-between;
            padding: 20px;
            background-color: #f8d5b9;
            border-top: 2px solid #000000;
        }

        /* Styling tombol */
        .nav-btn {
            padding: 10px 20px;
            border: none;
            border-radius: 6px;
            background-color: #ad6322;
            color: rgb(0, 0, 0);
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .nav-btn:hover {
            background-color: #693803;
        }

        .nav-btn:disabled {
            background-color: #6b635d;
            cursor: not-allowed;
        }

        /* Animasi fade-in */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        .slide-image {
            display: block;    /* Ini penting */
            max-width: 80%;
            height: auto;
            margin: 15px auto; /* INI YANG MEMBUAT KE TENGAH */
            border-radius: 8px;
        }
        .slide-video {
            display: block;
            max-width: 100%;
            height: auto;
            margin: 15px auto; /* Ini yang bikin ke tengah */
            border-radius: 8px;
        }

    </style>
</head>
<body>

    <div class="card-slider">

        <div class="slider-content">

            <div class="slide active"> 
                <h2>About You</h2>
                <p>Mungkin buka web ini lebih baik daripada kamu scroll tiktok. Semoga kamu benar benar membacanya. Enjoy your time. Silakan klik 'Selanjutnya'.</p>
            </div>

            <div class="slide">
                <h2>Halaman 2</h2>
                <p>disini sebenernya aku cuma mau pamer kalo aku lagi latian ngoding aja sii. Dan aku suka banget proses bikin ini. Gatau mulai bikin ini dari kapan, yang jelas lebih dari sebulan

                    <h3>- _ -</h3>
                </p>
            </div>

            <div class="slide">
                <h2>Halaman 3</h2>
                <p>Teruntuk kamu yang kemarin habis kehilangan kunci, semoga kamu baca ini dalam keadaan yang baik baik aja. aku tau kalo kehilangan kunci juga nguras energi yang cukup banyak buat kamu. tapi santai aja kamu dikelilingi orang orang baik.

                </p>
                </div>

            <div class="slide">
                <h2>Halaman 4</h2>
                <p>diisi apa yahh</p>
            </div>

            <div class="slide">
                <h2>Halaman 5</h2>
                
                <img class="slide-image" { display: block;   
                        max-width: 80%;
                         height: auto;
                       margin: 15px auto;
                        border-radius: 8px;
        }
                     src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM3NqZzNqY3o0cDBuZXhwc2N5NWs2aXk2aWtvdGkwaW1tYjZqemtkdCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3oEhn680y9Gf3eB1n2/giphy.gif" 
                     alt="GIF perayaan">
                
                <p>Sudah setengah jalan!</p>
            </div>

            <div class="slide">
                <h2>Halaman 6</h2>
                <img src="images/WhatsApp Image 2025-11-08 at 02.11.26 (1).jpeg" alt="pemandangan gunung" width="234px" height="312px">
                
                <p>Penatian yang lama sii buat bisa muncak ke beser. iya emang deket, cuma gatau kenapa bisa selama itu nunggu nya.</p>
            </div>

            <div class="slide">
                <h2>Halaman 7</h2>
                <video class="slide-video" 
                       controls 
                       src="images/WhatsApp Video 2025-11-04 at 10.24.502.mp4">
                       
                </video>
                <p>lagii nonton apa tuu?? ohh iya lagi nonton maruko.ternyata asikk juga yaa nonton kartun kayak gituu, sebelumnya aku mikir kalo nonton kayak gitu pasti ngebosenin. tapi mungkin dulu aku yang kurang bisa menikmati, dan pas itu aku coba nonton dan memahami maruko. asik sii, ternyata itu yang dirasain ponakanku pas lagi nonton hello jadoo. mirip ga sii maruko sama jadoo?? kemarin pas di konrtrakan aku pernah nonton maruko lagi dan diketawain sama dimass. Ini video di paparazi in sama dapi</p>
            </div>

            <div class="slide">
                <h2>Halaman 8</h2>
                
                <img src="images/WhatsApp Image 2025-11-11 at 00.27.06.jpeg" alt="jahra" width="234px" height="312px">
                
                <p>Tonton Sampai Akhir.</p>
            </div>

            <div class="slide">
                <h2>Halaman 9</h2>                
                <p>Satu halaman lagi sebelum penutup.</p>
            </div>

            <div class="slide">
                <h2>Tentang Demis</h2>
                <img src="images/WhatsApp Image 2025-11-30 at 02.40.56.jpeg" alt="demis" width="234px" height="312">
                <p>Selamatt demiss</p>
                <p style="margin-top: 20px; font-style: italic;">- 30 November 2025</p>
            </div>

            <div class="slide">
                <h2>Halaman 11</h2>
                <p>telah membaca!</p>
                <img src="images/WhatsApp Image 2025-12-18 at 21.44.07 (2).jpeg" alt="fieldtrip" width="180px" height="320">
                <p style="margin-top: 20px; font-style: italic;">18 Desember 2025</p>
            </div>
            <div class="slide">
                <h2>Halaman 12</h2>
                <p>Terimakasih sudah meluangkan waktunya untuk membaca dan meresapi setiap kata sederhana yang aku susun dalam bentuk website ini. semoga kamu senang melihatnya. jumpa lagi di keseruan berikutnya</p>
                <p style="margin-top: 20px; font-style: italic;">- Dari Fajar Firmansyah</p>
            </div>
        </div>

        <div class="navigation">
            <button class="nav-btn" id="prevBtn">Sebelumnya</button>
            <button class="nav-btn" id="nextBtn">Selanjutnya</button>
        </div>

    </div>

    <script>
        const slides = document.querySelectorAll('.slide');
        const prevBtn = document.getElementById('prevBtn');
        const nextBtn = document.getElementById('nextBtn');
        
        let currentSlide = 0; 
        const totalSlides = slides.length; // Otomatis menghitung jadi 10

        function showSlide(index) {
            slides.forEach(slide => {
                slide.classList.remove('active');
            });
            slides[index].classList.add('active');
            
            prevBtn.disabled = (currentSlide === 0);
            nextBtn.disabled = (currentSlide === totalSlides - 1);
        }

        nextBtn.addEventListener('click', () => {
            if (currentSlide < totalSlides - 1) {
                currentSlide++; 
                showSlide(currentSlide);
            }
        });

        prevBtn.addEventListener('click', () => {
            if (currentSlide > 0) {
                currentSlide--; 
                showSlide(currentSlide);
            }
        });

        showSlide(currentSlide);
    </script>

</body>
</html>
