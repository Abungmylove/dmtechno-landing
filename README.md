<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dmtechno | Lifestyle Kreatif Ramah Lingkungan</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
        }
        
        .nature-gradient {
            background: linear-gradient(135deg, #84cc16 0%, #22d3ee 100%);
        }
        
        .product-card:hover {
            transform: translateY(-5px);
            transition: all 0.3s ease;
        }
        
        .eco-badge {
            position: absolute;
            top: -10px;
            right: -10px;
            background-color: #ef4444;
            color: white;
            border-radius: 50%;
            width: 50px;
            height: 50px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        .floating-cta {
            animation: float 3s ease-in-out infinite;
        }
        
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav class="bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4">
            <div class="flex justify-between items-center">
                <div class="flex items-center">
                    <div class="flex-shrink-0 flex items-center">
                        <img src="https://placehold.co/160x60?text=Dmtechno&font=Montserrat" alt="Logo Dmtechno dengan tipografi modern warna hijau dan biru" class="h-10">
                    </div>
                </div>
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#produk" class="text-gray-600 hover:text-green-600 font-medium">Produk</a>
                    <a href="#tentang" class="text-gray-600 hover:text-green-600 font-medium">Tentang Kami</a>
                    <a href="#testimoni" class="text-gray-600 hover:text-green-600 font-medium">Testimoni</a>
                    <a href="#kontak" class="text-gray-600 hover:text-green-600 font-medium">Kontak</a>
                </div>
                <div class="hidden md:block">
                    <button class="bg-green-600 hover:bg-green-700 text-white px-6 py-2 rounded-full text-sm font-medium transition duration-300">
                        Belanja Sekarang
                    </button>
                </div>
                <div class="md:hidden">
                    <button type="button" class="text-gray-500 hover:text-gray-600 focus:outline-none">
                        <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                        </svg>
                    </button>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="nature-gradient text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20 md:py-28">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <h1 class="text-3xl md:text-5xl font-bold mb-4 leading-tight">Lifestyle Kreatif untuk Masa Depan yang Lebih Hijau</h1>
                    <p class="text-lg md:text-xl mb-8 opacity-90">Produk berkualitas dengan desain minimalis dan bahan ramah lingkungan yang membuat perbedaan</p>
                    <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4">
                        <button class="bg-white text-green-600 hover:bg-gray-100 px-6 py-3 rounded-full font-bold text-lg transition duration-300 flex items-center justify-center">
                            Jelajahi Koleksi
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 ml-2" viewBox="0 0 20 20" fill="currentColor">
                                <path fill-rule="evenodd" d="M10.293 5.293a1 1 0 011.414 0l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414-1.414L12.586 11H5a1 1 0 110-2h7.586l-2.293-2.293a1 1 0 010-1.414z" clip-rule="evenodd" />
                            </svg>
                        </button>
                        <button class="bg-transparent border-2 border-white hover:bg-white hover:text-green-600 px-6 py-3 rounded-full font-bold text-lg transition duration-300">
                            Video Produk
                        </button>
                    </div>
                    <div class="mt-8 flex items-center">
                        <div class="flex -space-x-2">
                            <img src="https://placehold.co/40x40" alt="Foto pelanggan tersenyum memegang produk tote bag Dmtechno" class="w-10 h-10 rounded-full border-2 border-white">
                            <img src="https://placehold.co/40x40" alt="Foto pelanggan tersenyum memegang produk tumbler Dmtechno" class="w-10 h-10 rounded-full border-2 border-white">
                            <img src="https://placehold.co/40x40" alt="Foto pelanggan tersenyum memegang produk notebook Dmtechno" class="w-10 h-10 rounded-full border-2 border-white">
                        </div>
                        <div class="ml-4">
                            <p class="text-sm opacity-80">Digunakan dan dipercaya oleh <span class="font-bold">5.000+</span> pelanggan</p>
                        </div>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center">
                    <div class="relative">
                        <img src="https://placehold.co/600x600?text=Produk+Dmtechno" alt="Tiga produk utama Dmtechno terdiri dari tote bag katun organik, tumbler stainless steel, dan notebook kertas daur ulang disusun minimalis" class="rounded-lg shadow-2xl max-w-full h-auto">
                        <div class="eco-badge">Eco</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Promo Banner -->
    <section class="bg-white py-6">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-green-50 border border-green-100 rounded-lg px-6 py-4 flex flex-col md:flex-row items-center justify-between">
                <div class="flex items-center mb-4 md:mb-0">
                    <div class="bg-green-100 p-2 rounded-full mr-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-green-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 10h18M7 15h1m4 0h1m-7 4h12a3 3 0 003-3V8a3 3 0 00-3-3H6a3 3 0 00-3 3v8a3 3 0 003 3z" />
                        </svg>
                    </div>
                    <div>
                        <h3 class="font-bold text-lg text-gray-900">Spesial Launching!</h3>
                        <p class="text-gray-600">Diskon 20% untuk pembelian pertama + gratis ongkir hingga Rp 20.000</p>
                    </div>
                </div>
                <button class="bg-green-600 hover:bg-green-700 text-white px-6 py-2 rounded-full text-sm font-medium transition duration-300 whitespace-nowrap">
                    Dapatkan Promo
                </button>
            </div>
        </div>
    </section>

    <!-- Produk Section -->
    <section id="produk" class="py-16 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb30–12">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Koleksi Produk Kami</h2>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto">Desain minimalis dengan komitmen ramah lingkungan</p>
            </div>
            
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8 mt-12">
                <!-- Tote Bag -->
                <div class="product-card bg-white rounded-xl shadow-md overflow-hidden transition duration-300">
                    <div class="relative">
                        <img src="https://placehold.co/600x500?text=Tote+Bag" alt="Tote bag katun organik warna natural dengan logo kecil Dmtechno" class="w-full h-64 object-cover">
                        <div class="absolute top-4 left-4 bg-green-100 text-green-800 text-xs px-2 py-1 rounded-full">Bahan Organik</div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-gray-900 mb-2">Tote Bag Minimalis</h3>
                        <p class="text-gray-600 mb-4">Tas serbaguna dari katun organik dengan desain sederhana yang elegan</p>
                        <div class="flex justify-between items-center">
                            <span class="text-lg font-bold text-gray-900">Rp 89.000</span>
                            <button class="bg-green-600 hover:bg-green-700 text-white px-4 py-2 rounded-full text-sm font-medium transition duration-300">
                                + Keranjang
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Tumbler -->
                <div class="product-card bg-white rounded-xl shadow-md overflow-hidden transition duration-300">
                    <div class="relative">
                        <img src="https://placehold.co/600x500?text=Tumbler" alt="Tumbler stainless steel dengan lapisan tembaga dan logo Dmtechno yang subtle" class="w-full h-64 object-cover">
                        <div class="absolute top-4 left-4 bg-blue-100 text-blue-800 text-xs px-2 py-1 rounded-full">Stainless Steel</div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-gray-900 mb-2">Tumbler Ramah Lingkungan</h3>
                        <p class="text-gray-600 mb-4">Thermos berkualitas tinggi yang menjaga suhu hingga 12 jam</p>
                        <div class="flex justify-between items-center">
                            <div>
                                <span class="text-lg font-bold text-gray-900">Rp 159.000</span>
                                <span class="text-sm text-gray-500 line-through ml-2">Rp 199.000</span>
                            </div>
                            <button class="bg-green-600 hover:bg-green-700 text-white px-4 py-2 rounded-full text-sm font-medium transition duration-300">
                                + Keranjang
                            </button>
                        </div>
                    </div>
                </div>
                
                <!-- Notebook -->
                <div class="product-card bg-white rounded-xl shadow-md overflow-hidden transition duration-300">
                    <div class="relative">
                        <img src="https://placehold.co/600x500?text=Notebook" alt="Notebook dengan sampul kayu daur ulang dan kertas ramah lingkungan" class="w-full h-64 object-cover">
                        <div class="absolute top-4 left-4 bg-yellow-100 text-yellow-800 text-xs px-2 py-1 rounded-full">Daur Ulang</div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-gray-900 mb-2">Notebook Eco</h3>
                        <p class="text-gray-600 mb-4">Buku catatan dengan kertas daur ulang dan sampul kayu yang unik</p>
                        <div class="flex justify-between items-center">
                            <span class="text-lg font-bold text-gray-900">Rp 65.000</span>
                            <button class="bg-green-600 hover:bg-green-700 text-white px-4 py-2 rounded-full text-sm font-medium transition duration-300">
                                + Keranjang
                            </button>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <button class="inline-flex items-center text-green-600 hover:text-green-800 font-medium">
                    Lihat Semua Produk
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 ml-1" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M12.293 5.293a1 1 0 011.414 0l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-2.293-2.293a1 1 0 010-1.414z" clip-rule="evenodd" />
                    </svg>
                </button>
            </div>
        </div>
    </section>

    <!-- Tentang Kami -->
    <section id="tentang" class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <img src="https://placehold.co/600x400?text=Dmtechno+Team" alt="Tim Dmtechno sedang bekerja di workshop produksi yang terang dan bersih" class="rounded-lg shadow-md w-full">
                </div>
                <div class="md:w-1/2 md:pl-12">
                    <h2 class="text-3xl font-bold text-gray-900 mb-6">Tentang Dmtechno</h2>
                    <p class="text-gray-600 mb-4">Dmtechno lahir dari passion untuk menciptakan produk lifestyle yang tidak hanya indah tetapi juga bertanggung jawab terhadap lingkungan. Kami percaya bahwa gaya hidup minimalis dan keberlanjutan adalah masa depan.</p>
                    <p class="text-gray-600 mb-6">Setiap produk kami dibuat dengan bahan-bahan pilihan yang ramah lingkungan dan diproduksi secara etis oleh tangan-tangan terampil di Indonesia.</p>
                    <div class="grid grid-cols-2 gap-4 mt-6">
                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-green-600 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                            </svg>
                            <span class="text-gray-700">Bahan Ramah Lingkungan</span>
                        </div>
                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-green-600 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                            </svg>
                            <span class="text-gray-700">Desain Minimalis</span>
                        </div>
                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-green-600 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                            </svg>
                            <span class="text-gray-700">Produksi Lokal</span>
                        </div>
                        <div class="flex items-center">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-green-600 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                            </svg>
                            <span class="text-gray-700">Garansi Kualitas</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimoni -->
    <section id="testimoni" class="py-16 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Kata Pelanggan Kami</h2>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto">Apa yang mereka katakan tentang pengalaman menggunakan produk Dmtechno</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded-xl shadow-sm">
                    <div class="flex items-center mb-4">
                        <img src="https://placehold.co/60x60" alt="Foto profil Arini, pelanggan Dmtechno dari Jakarta" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="font-bold text-gray-900">Arini S.</h4>
                            <div class="flex">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-yellow-400" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-yellow-400" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-yellow-400" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-yellow-400" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-yellow-400" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 italic">"Tote bag-nya sangat kuat dan nyaman dipakai! Desainnya simpel tapi sangat stylish. Sudah beli 3 warna berbeda!"</p>
                </div>
                
                <div class="bg-white p-6 rounded-xl shadow-sm">
                    <div class="flex items-center mb-4">
                        <img src="https://placehold.co/60x60" alt="Foto profil Rendra, pelanggan Dmtechno dari Bandung" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="font-bold text-gray-900">Rendra K.</h4>
                            <div class="flex">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-yellow-400" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-yellow-400" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                                </svg>
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-yellow-400" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8
