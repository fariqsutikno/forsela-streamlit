Struktur Halaman yang Diusulkan:

    Tren Studi Lanjut:
        Apakah ada peningkatan angka penerimaan jumlah lulusan yang studi lanjut setiap angkatan?
        Bagaimana tren setiap angkatan pada memilih kategori kampus (negeri, swasta)?
        Apakah ada peningkatan angka penerimaan jumlah lulusan di masing-masing kategori kampus pada setiap angkatan?
        Bagaimana tren tahun masuk perguruan tinggi pada setiap angkatan? apakah banyak yang mengambil gap year? atau tidak?
        Bagaimana tren ranah kuliah (umum atau agama) yang diambil pada setiap angkatan?
        Bagaimana tren peningkatan penerimaan berdasarkan jalur masuk (snbp, snbt, mandiri) pada setiap angkatan?

    Profil Alumni:
        Apa saja jenjang yang diambil oleh kebanyakan alumni? sarjana kah atau diploma?
        Berapa banyak alumni yang mendapatkan beasiswa? dan siapa saja?
        Apa ranah yang banyak diambil pada lintas angkatan?
        Apa kebanyakan jalur masuk yang ditempuh oleh alumni pada lintas angkatan?
        Universitas mana yang terdapat banyak alumni di sana?
        Prodi apa yang terdapat banyak alumni di sana?

    Filter Data Alumni:
        Filter data alumni untuk mengetahui nama-nama berdasarkan saringan yang dipilih



st.caption('Lumbung Data Alumni MAS Al Irsyad (2021 - 2024)')

st.header('Sekilas Tentang Portal')
st.header('Disclaimer Akurasi Data')

home_page = st.Page("dashboard.py", title="Profil Data Sebaran Alumni", icon=":material/dashboard:")
profile_page = st.Page("pages/Profile.py", title="Profil Data Sebaran Alumni", icon=":material/dashboard:")

pg = st.navigation({
    "": [home_page], 
    "Persebaran Alumni": [profile_page],
})

pg.run()
