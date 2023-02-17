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
