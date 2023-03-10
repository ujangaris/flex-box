# Flex-Box

## Flex-direction

     adalah sebuah property CSS yang digunakan untuk menentukan arah tata letak (layout direction) dari kontainer
     fleksibel (flex container) dan orientasi dari item flex (flex item) di dalamnya.
     Dengan menggunakan flex-direction, Anda dapat mengatur apakah kontainer fleksibel dan item fleks harus ditata
     secara horizontal atau vertikal, serta urutan tampilan item flex dari kiri ke kanan atau sebaliknya.

     Nilai yang dapat digunakan pada properti flex-direction adalah:

     1. row (default): Tata letak secara horizontal dimana item flex ditampilkan dari kiri ke kanan.
     2. row-reverse: Tata letak secara horizontal dimana item flex ditampilkan dari kanan ke kiri.
     3. column: Tata letak secara vertikal dimana item flex ditampilkan dari atas ke bawah.
     4. column-reverse: Tata letak secara vertikal dimana item flex ditampilkan dari bawah ke atas.

    Todo :
    1. flex-direction/index.html
        - flex-direction-row
        - flex-direction-reverse
        - flex-direction-column
        - flex-direction-column-reverse
    2. flex-direction/style.css
        - flex-direction row atau default
        - flex-direction reverse
        - flex-direction column
        - flex-direction column-reverse

## Flex-wrap

     adalah sebuah property CSS yang digunakan untuk mengatur bagaimana item flex (flex items) ditata dalam kontainer fleksibel (flex container) jika melebihi ukuran kontainer tersebut. Dengan menggunakan flex-wrap, Anda dapat menentukan apakah item flex akan dipindahkan ke baris atau kolom berikutnya jika kontainer fleksibel tidak cukup lebar atau tinggi untuk menampung semua item flex.

    Nilai yang dapat digunakan pada properti flex-wrap adalah:

    1.  nowrap (default): Item flex tidak akan dipindahkan ke baris atau kolom berikutnya.
        Item flex akan tetap ditampilkan dalam satu baris atau kolom, meskipun lebar atau tinggi
        kontainer fleksibel tidak mencukupi.
    2.  wrap: Item flex akan dipindahkan ke baris atau kolom berikutnya jika lebar atau tinggi kontainer
        fleksibel tidak mencukupi untuk menampung semua item flex. Baris atau kolom yang baru akan
        dimulai di bawah atau di samping baris atau kolom sebelumnya.

    3.  wrap-reverse: Item flex akan dipindahkan ke baris atau kolom berikutnya jika lebar atau tinggi
        kontainer fleksibel tidak mencukupi untuk menampung semua item flex. Baris atau kolom yang baru
        akan dimulai di atas atau di sebelah kiri baris atau kolom sebelumnya.

    Todo :
    1. flex-wrap/index.html
        - Tanpa Flex Wrap
        - Dengan Flex Wrap
        - Dengan Flex Wrap reverse
    2. flex-wrap/style.css
        - Tanpa Flex Wrap
        - Dengan Flex Wrap
        - Dengan Flex Wrap reverse

## Justify Content

    adalah salah satu properti dalam CSS yang digunakan untuk mengatur posisi konten
    dalam sebuah kontainer secara horizontal. Properti ini biasanya digunakan untuk mengatur letak
    dan jarak antar konten dalam sebuah flex container.

    Beberapa nilai yang dapat digunakan untuk properti justify-content antara lain:

    1.  flex-start: Konten diletakkan di awal kontainer (sebelah kiri).
    2.  flex-end: Konten diletakkan di akhir kontainer (sebelah kanan).
    3.  center: Konten diletakkan di tengah-tengah kontainer.
    4.  space-between: Konten diletakkan dengan jarak sama antara satu sama lain.
    6.  space-around: Konten diletakkan dengan jarak sama di sekelilingnya.

    Todo :
    1. justify-content/index.html
        - Justify Content Start
        - Justify Content Center
        - Justify Content Space Between
        - Justify Content Space Around
        - Justify Content Flex End
    2. justify-content/style.css
        - Justify Content Start
        - Justify Content Center
        - Justify Content Space Between
        - Justify Content Space Around
        - Justify Content Flex End

## Align Items

    adalah salah satu properti dalam CSS yang digunakan untuk mengatur posisi konten dalam sebuah kontainer secara vertikal.
    Properti ini biasanya digunakan untuk mengatur letak dan jarak antar konten dalam sebuah flex container.

    Beberapa nilai yang dapat digunakan untuk properti align-items antara lain:

    1.  flex-start: Konten diletakkan di atas kontainer.
    2.  flex-end: Konten diletakkan di bawah kontainer.
    3.  center: Konten diletakkan di tengah-tengah kontainer.
    4.  baseline: Konten diletakkan pada garis dasar teks dalam kontainer.
    5.  stretch: Konten ditarik untuk mengisi seluruh ruang di dalam kontainer.

    Todo :
    1. align-items/index.html
        - Align Items Flex Start
        - Align Items Flex End
        - Align Items Center
        - Align Items Baseline
            baseline akan berdungsi jika elemen didalamnnya ada ukuran
            contoh class satu & class tiga
        - Align Items Stretch
            jika heightnya dimatiin akan panjang kebawah
    2. align-items/style.css
        - Align Items Flex Start
        - Align Items Flex End
        - Align Items Center
        - Align Items Baseline
            baseline akan berdungsi jika elemen didalamnnya ada ukuran
        - Align Items Stretch
            jika heightnya dimatiin akan panjang kebawah
