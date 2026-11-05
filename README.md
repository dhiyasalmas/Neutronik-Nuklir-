# Kamus-Neutronik-Nuklir-

*Dhiya Salma Salsabila*
Catatan selama kuliah dan baca paper yang di jadikan satu serta bantuan AI dalam merapihkannya dan menerjemahkan beberapa bagian

## **Reaksi Nuklir**
Dalam teras reaktor nuklir, populasi dan distribusi neutron sangat penting dan di tentukan dengan reaksi nuklir yang terjadi, dalam analisis reaktor nuklir ada 3 jenis reaksi yang penting :
1. Reaksi Fisi Nuklir ialah reaksi pembelahan inti atom berat menjadi inti-inti atom yang lebih ringan. reaksi ini bersifat eksoterm dengan menghasilkan energi dalam jumlah relatif besar. 

    Persamaan umum dari suatu reaksi fisi nuklir adalah sebagai berikut :

    $$\vphantom{1}_0^1n + \vphantom{X}_{Z1}^{A1}X \rightarrow \vphantom{Y}_{Z2}^{A2}Y + \vphantom{Z}_{Z3}^{A3}Z + \text{neutron} + \text{energi}$$

    Beberapa contoh reaksi fisi U235 adalah sebagai berikut :

    $$\vphantom{1}_0^1n + \vphantom{U}_{92}^{235}U \rightarrow \vphantom{X}_{54}^{140}Xe + \vphantom{S}_{38}^{94}Sr + 2\vphantom{1}_0^1n + 200\text{ MeV}$$

    $$\vphantom{1}_0^1n + \vphantom{U}_{92}^{235}U \rightarrow \vphantom{C}_{55}^{140}Cs + \vphantom{R}_{37}^{93}Rb + 3\vphantom{1}_0^1n + 200\text{ MeV}$$

    $$\vphantom{1}_0^1n + \vphantom{U}_{92}^{235}U \rightarrow \vphantom{B}_{56}^{141}Ba + \vphantom{K}_{36}^{92}Kr + 3\vphantom{1}_0^1n + 200\text{ MeV}$$

2. Reaksi penangkapan neutron, disebut juga reaksi penangkapan radiatif karena menghasilkan radiasi gamma ketika inti atom metastabil hasil reaksi bertransformasi menjadi inti atom lain yang stabil dengan melepaskan sebagaian energi dalam bentu radiasi gamma.

    Berikut adalah tulisan ulang dari teks dan persamaan pada gambar:

    Persamaan umum dari reaksi penangkapan neutron adalah sebagai berikut :

    $${}_{0}^{1}n + {}_{Z}^{A}X \rightarrow \left( {}_{Z}^{A+1}X \right)^{*} \rightarrow {}_{Z}^{A+1}X + {}_{0}^{0}\gamma \qquad $$

    Contoh reaksi penangkapan neutron adalah sebagai berikut :

    $${}_{0}^{1}n + {}_{1}^{1}H \rightarrow \left( {}_{1}^{2}H \right)^{*} \rightarrow {}_{1}^{2}H + {}_{0}^{0}\gamma \qquad$$

3. Reaksi hamburan neutron, terjadi saat neutron datang menabrak inti atom tetapi tidak terjadi transformasi/perubahan nuklir setelah terjadi tumbukkan. Neutron hanya terhambur tetapi energi dan keadaan neutron bisa saja berubah.

    Reaksi hamburan neutron dibedakan menjadi 2 jenis :
    - Reaksi hamburan elastik, terjadi bila energi pada neutron dan inti atom tidak berubah setelah mengalami tumbukan.

    Persamaan umumnya adalah sebagai berikut :

    $${}_{0}^{1}n + {}_{Z}^{A}X \rightarrow {}_{Z}^{A}X + {}_{0}^{1}n$$
    - Reaksi hamburan inelastik, terjadi bila energi atau keadaan neutron dan inti atom mengalami perubahan setelah mengalami tumbukan.

    Persamaan umumnya adalah sebagai berikut :

    $${}_{0}^{1}n + {}_{Z}^{A}X \rightarrow \left( {}_{Z}^{A}X \right)^{*} + {}_{0}^{1}n \rightarrow {}_{Z}^{A}X + {}_{0}^{1}n + {}_{0}^{0}\gamma \qquad $$

> Dalam reaktor nuklir, neutron menjadi sangat penting karena dapat menyebabkan reaksi fisi. Dengan mengetahui perilaku neutron maka dapat menentukan seberapa sering reaksi fisi terjadi. Hal ini juga sebanding dengan energi yang dihasilkan.

## **Penampang Lintang (Cross Section)**

Penampang lintang menyatakan ukuran efektif peluang terjadinya interaksi neutron dengan inti. Besarnya bergantung pada jenis reaksi dan energi neutron.

### Penampang lintang mikroskopik

Penampang lintang mikroskopik untuk nuklida $i$ dan reaksi $x$ ditulis $\sigma_{x,i}$. Satuannya luas, biasanya barn atau $\mathrm{cm}^{2}$, dengan konversi:

$$1\ \mathrm{barn}=10^{-24}\ \mathrm{cm}^{2}.$$

Laju reaksi per satuan volume untuk neutron dengan fluks skalar $\phi$ adalah:

$$R_{x,i}=N_i\sigma_{x,i}\phi.$$

Dengan:

- $R_{x,i}$: laju reaksi per volume pada nuklida $i$ untuk reaksi $x$; satuan $\mathrm{cm}^{-3}\,\mathrm{s}^{-1}$.
- $N_i$: densitas atom nuklida $i$; satuan atom $\mathrm{cm}^{-3}$.
- $\sigma_{x,i}$: penampang lintang mikroskopik; satuan $\mathrm{cm}^{2}$.
- $\phi$: fluks neutron; satuan $\mathrm{cm}^{-2}\,\mathrm{s}^{-1}$.

Karena itu, laju reaksi per satu atom target adalah $\sigma_{x,i}\phi$ dengan satuan $\mathrm{s}^{-1}$.

Jenis reaksi yang umum dibahas meliputi:

- Fisi, dengan penampang lintang $\sigma_f$.
- Absorpsi, dengan penampang lintang $\sigma_a$.
- Hamburan, dengan penampang lintang $\sigma_s$.
- Tangkapan, dengan penampang lintang $\sigma_\gamma$ atau $\sigma_c$.

### Penampang lintang makroskopik

Untuk campuran nuklida, penampang lintang makroskopik reaksi $x$ adalah:

$$\Sigma_x=\sum_i N_i\sigma_{x,i},\qquad R_x=\Sigma_x\phi.$$

Dengan:

- $\Sigma_x$: penampang lintang makroskopik reaksi $x$; satuan $\mathrm{cm}^{-1}$.
- $N_i$: densitas atom nuklida $i$; satuan atom $\mathrm{cm}^{-3}$.
- $\sigma_{x,i}$: penampang lintang mikroskopik nuklida $i$; satuan $\mathrm{cm}^{2}$.
- $R_x$: laju reaksi total per volume; satuan reaksi $\mathrm{cm}^{-3}\,\mathrm{s}^{-1}$.
- $\phi$: fluks neutron; satuan $\mathrm{cm}^{-2}\,\mathrm{s}^{-1}$.

# <center><b> Analisis Neutronik </b></center>

Analisis neutronik bertujuan untuk memetakan distribusi fluks neutron (posisi, energi, arah, dan waktu) di dalam teras reaktor. Pemetaan ini esensial untuk memprediksi daya reaktor, tingkat kekritisan ($k_{eff}$), dan efektivitas batang kendali. Terdapat dua hierarki utama dalam perhitungannya: Teori Transport dan Teori Difusi.

Tingkat kekritisan dalam analisis neutronik dapat disebut juga faktor multiplikasi $(k)$ ialah gambaran keadaan reaktor yang di rumuskan sebagai:
$$ k = \frac{Populasi \ neutron \ pada \ suatu \ generasi}{Populasi \ neutron \ pada \ generasi \ sebelumnya}$$
Berdasarkan nilai faktor multiplikasi kita dapat mengetahui keadaan teras reaktor :
- $k>1$, superkritis dimana populasi neutron terus bertambah
- $k=1$, kritis dimana populasi neutron konstan
- $k<1$, subkritis dimana populasi neutron terus berkurang

**Nah ini bagian yang bikin kalian pengen resign dari nuklir hahahahaha**

## <center><b>  Persamaan Transport Neutron </b></center>
Dalam teori transport neutron di anggap sebagai partikel titik, dimana keadaan gerak neutron pada setiap saat dapat di tentukan secara presisi baik posisi dan kecepatannya.

Transport neutron memiliki prinsip dasar
$$ \begin{aligned}
&laju \ perubahan \ kerapatan \ neutron = \\
& laju \ pembangkit \ (Q) - laju \ kehilangan \ akibat \ aliran \ (L) \\
& - laju \ kehilangan \ akibat \ tumbukan \ (R)
\end{aligned}$$

- Keadaan gerak neutron secara spesifik di deskripsikan oleh 6 variabel:
    - Vektor posisi $(r)$, menentukan lokasi neutron dalam ruang tiga dimensi dalam koordinat kartesius $(x,y,z)$
    - Energi kinetik $(E)$, menentukan energi neutron yang berhubungan langsung dengan besarnya kecepatan
    - Arah gerak $(\Omega)$, vektor yang menentukan arah pergerakkan neutron dalam sudut polar $(\theta)$ dan sudut azimut $(\varphi)$

- Fungsi fungsi dasar teori transport neutron
1. Kerapatan sudut neutron (Neutron angular density), ialah jumlah neutron persatuan volume di sekitar titik r persatuan energi disekitar E dan persatuan sudut di sekitar arah $\Omega$ pada waktu t. Secara matematis jumlah neutron dalam elemen ruang
    $$ n(r,E,\Omega,t) drdEd\Omega$$
    Dengan integrasi kerapatan sudut neutron ke seluruh arah sudut di dapatkan
    $$ n(r,E,t) = \int_{4\pi} n(r,E,\Omega,t) d\Omega $$
2. Fluks sudut neutron (Neutron angular flux), mempresentasikan total panjang lintasan yang ditempuh persatuan waktu oleh neutron dalam satuan volume di sekitar r dengan energi E dan arah $\Omega$. Hal ini dapat di definisikan sebagai produk dari kerapatan sudut neutron dan besarnya kecepatan neutron.
    $$ \phi (r,E,\Omega,t) = v \ n \ (r,E,\Omega,t)$$
    Dengan mengintegrasikan fluks sudut ke segala arah maka di dapat
    $$ \phi(r,E,t) = \int_{4\pi} \phi(r,E,\Omega,t) d\Omega $$
3. Arus neutron (Neutron current), laju aliran neutron yang melewati suatu permukaan, misalkan n adalah sebuah vektor yang tegak lurus terhadap elemen permukaan dS di titik r. Maka jumlah neutron yang bergerak ke arah $\Omega$ dengan energi E yang melewati dS persatuan waktu dapat dirumuskan :
    $$ n (r,E,\Omega) v |\Omega.n|dS $$
    untuk menghitung aliran total maka didefinisikan arus parsial
     - arus parsial positif
        $$ J_n^+ dS = \int_{(\Omega,n)>0} n (r,E,\Omega) v |\Omega.n| d\Omega$$
        $$ J_n^+ dS = \int_{(\Omega,n)>0} |\Omega.n| \phi (r,E,\Omega)  d\Omega$$
     - arus parsial negatif
         $$ J_n^- dS= \int_{(\Omega,n)<0} |\Omega.n| \phi (r,E,\Omega) d\Omega$$
    maka arus bersih
      $$ J_n (r,E) dS = (J_n^+ - J_n^-)dS = dS \int_{4\pi} (\Omega.n) \phi(r,E,\Omega) d\Omega$$
      $$ J_n (r,E) dS = dS \ n \int_{4\pi} (\Omega) \phi(r,E,\Omega) d\Omega$$
    misalkan
      $$ J(r,E) = \int_{4\pi} \Omega \phi(r,E,\Omega) d\Omega$$
    maka persamaan dapat di tulis
      $$ J_n (r,E) = J (r,E) n $$

- Penurunan persamaan transport neutron orde pertama

    Dikenal sebagai persamaan Transport Boltzman, prinsip ini menyatakan bahwa laju perubahan jumlah neutron dalam suatu volume yang infinite harus sama dengan laju generasi neutron di kurangi laju kehilangan neutron dari volume tersebut yang dirumuskan dalam :
            $$ \frac{\partial n}{\partial t} = Q - L - R$$
            Dimana
    - $\frac{\partial n}{\partial t}$ : laju perubahan kerapatan neutron
    - Q : laju generasi/produksi neutron
    - L : laju kehilangan neutron akibat aliran
    - R : laju kehilangan neutron akibat tumbukan 

    1. Laju kehilangan akibat aliran (L)

        Menurut definisi fluks sudut, jumlah neutron dengan energi antara $E$ dan $E+\text{d}E$ yang memasuki pias volume $\text{d}V$ melalui $\text{d}A$ per satuan waktu dalam kerucut arah $\text{d}\mathbf{\Omega}$ di sekitar arah $\mathbf{\Omega}$ adalah

        $$ \phi(\mathbf{r}_0 + s\mathbf{\Omega}, E, \mathbf{\Omega}, t)\text{d}A\text{d}E\text{d}\mathbf{\Omega} \qquad $$

        Sedangkan jumlah neutron yang keluar dari pias volume tersebut adalah

        $$ \phi(\mathbf{r}_0 + (s+\text{d}s)\mathbf{\Omega}, E, \mathbf{\Omega}, t)\text{d}A\text{d}E\text{d}\mathbf{\Omega} \qquad  $$

        Oleh karena itu, jumlah neutron yang bocor dari pias volume tersebut adalah

        Tuliskan $\Phi(s)=\phi(\mathbf{r}_0+s\mathbf{\Omega},E,\mathbf{\Omega},t)$. Dengan notasi ini:

        $$
        \begin{aligned}
        L&=[\Phi(s+\text{d}s)-\Phi(s)]\,\text{d}A\,\text{d}E\,\text{d}\mathbf{\Omega}\\
        &=\frac{\text{d}\Phi}{\text{d}s}\,\text{d}V\,\text{d}E\,\text{d}\mathbf{\Omega}.
        \end{aligned}
        $$

        Perhatikan bahwa $\mathbf{r} = \mathbf{r}_0 + s\mathbf{\Omega}$, dan turunan total $\frac{\text{d}\phi}{\text{d}s}$ dapat dinyatakan sebagai

        $$
        \begin{aligned}
        & \frac{\text{d}\phi}{\text{d}s} = \frac{\partial \phi}{\partial x}\frac{\text{d}x}{\text{d}s} \\
        & + \frac{\partial \phi}{\partial y}\frac{\text{d}y}{\text{d}s} \\
        & + \frac{\partial \phi}{\partial z}\frac{\text{d}z}{\text{d}s} \\
        \end{aligned}
        $$

        $$
        \begin{aligned}
        & = \mathbf{\Omega}_x\frac{\partial \phi}{\partial x} + \mathbf{\Omega}_y\frac{\partial \phi}{\partial y} \\
        & + \mathbf{\Omega}_z\frac{\partial \phi}{\partial z} = \mathbf{\Omega} \cdot \nabla\phi \qquad \\
        \end{aligned}
        $$

        Di sini operator $\nabla$ dapat diinterpretasikan sebagai sebuah vektor dalam bentuknya, yaitu,

        $$ \nabla = \mathbf{i}\frac{\partial}{\partial x} + \mathbf{j}\frac{\partial}{\partial y} + \mathbf{k}\frac{\partial}{\partial z} \qquad $$

        $$
        \begin{aligned}
        & \nabla\phi = \text{grad}\ \phi = \frac{\partial \phi}{\partial x}\mathbf{i} \\
        & + \frac{\partial \phi}{\partial y}\mathbf{j} + \frac{\partial \phi}{\partial z}\mathbf{k} \qquad \\
        \end{aligned}
        $$

        Oleh karena itu, laju kehilangan neutron akibat aliran diturunkan sebagai

        $$ L = \mathbf{\Omega} \cdot \nabla\phi \text{d}V\text{d}E\text{d}\mathbf{\Omega} \qquad $$

    2. Laju kehilangan akibat tumbukan (R)

        Jumlah neutron yang hilang per satuan waktu dari elemen ruang fase $\text{d}V\text{d}E\text{d}\mathbf{\Omega}$ bisa disebabkan oleh dua fenomena:
        - neutron diserap (*absorbed*) di dalam volume $\text{d}V$;
        - neutron dihamburkan (*scattered*) oleh inti atom. 
        
        Baik itu hamburan elastis maupun inelastis, proses ini akan mengubah energi neutron $E$ atau arah geraknya $\mathbf{\Omega}$, yang pada akhirnya menyebabkan neutron tersebut keluar atau hilang dari elemen ruang fase $(\mathbf{r}, E, \mathbf{\Omega})$.

        Oleh karena itu, jumlah neutron yang hilang dari elemen $\text{d}V\text{d}E\text{d}\mathbf{\Omega}$ akibat tumbukan ini dirumuskan sebagai:

        $$ R = (\Sigma_s + \Sigma_a)\phi(\mathbf{r}, E, \mathbf{\Omega}, t)\text{d}V\text{d}E\text{d}\mathbf{\Omega} $$

        $$ R = \Sigma_t\phi\text{d}V\text{d}E\text{d}\mathbf{\Omega} \qquad $$

    3.  Laju Pembentukan (Q)

        Ada tiga jenis sumber yang membuat jumlah neutron bertambah di dalam elemen volume ruang fase $\text{d}V\text{d}E\text{d}\mathbf{\Omega}$ diantaranya ialah:

        - Sumber Hamburan (Scattering Source)
        
            Neutron dengan energi $E'$ yang bergerak ke arah $\mathbf{\Omega}'$. lalu menabrak atom, kemudian terhambur, mengakibatkan energi berubah menjadi $E$ dan arahnya berubah menjadi $\mathbf{\Omega}$. Berdasarkan fungsi probabilitas hamburan ($f$), jumlah neutron yang mengalami proses ini di dalam volume $\text{d}V$ adalah:

        $$
            \begin{aligned}
            \mathrm{d}Q_s={}&\Sigma_s(\mathbf{r},E')f(\mathbf{r},E'\to E,\mathbf{\Omega}'\to\mathbf{\Omega})\\
            &\quad\times\phi(\mathbf{r},E',\mathbf{\Omega}',t)\,\mathrm{d}V\,\mathrm{d}E'\,\mathrm{d}\mathbf{\Omega}'.
            \end{aligned}
        $$

        Karena neutron yang terhambur ke arah $\mathbf{\Omega}$ dan menjadi berenergi $E$ itu awalnya bisa dari berbagai macam arah dan energi awal, kita harus menjumlahkan semuanya. Dengan mengintegralkan rumus tadi terhadap $E'$ dan $\mathbf{\Omega}'$:

        $$
            \begin{aligned}
            Q_s={}&\mathrm{d}V\,\mathrm{d}E\,\mathrm{d}\mathbf{\Omega}
            \int_0^\infty\mathrm{d}E'\int_{\mathbf{\Omega}'}\mathrm{d}\mathbf{\Omega}'\\
            &\quad\times\Sigma_s(\mathbf{r},E')f(\mathbf{r},E'\to E,\mathbf{\Omega}'\to\mathbf{\Omega})\\
            &\quad\times\phi(\mathbf{r},E',\mathbf{\Omega}',t).
            \end{aligned}
            $$

        - Sumber Fisi (*Fission Source*)
            Neutron yang lahir dari reaksi pembelahan inti (fisi) di dalam reaktor. Di sini, $\nu(E')$ melambangkan rata-rata jumlah neutron yang lahir per satu reaksi fisi. Sedangkan $\chi(E)$ adalah spektrum fisi (distribusi energi dari neutron yang baru lahir tersebut). Jika di asumsikan semua neutron fisi ini muncul seketika (*prompt*) dan menyebar ke segala arah secara merata (*isotropically*, makanya dibagi $4\pi$), laju pembentukannya dirumuskan sebagai:

            $$
            \begin{aligned}
            Q_f={}&\mathrm{d}V\,\mathrm{d}E\,\mathrm{d}\mathbf{\Omega}\,
            \frac{\chi(E)}{4\pi}\int_0^\infty\mathrm{d}E'\int_{\mathbf{\Omega}'}\mathrm{d}\mathbf{\Omega}'\\
            &\quad\times\nu(E')\Sigma_f(\mathbf{r},E')\phi(\mathbf{r},E',\mathbf{\Omega}',t).
            \end{aligned}
            $$

        - Sumber Eksternal
            Jika pada reaktor terdapat sumber neutron dari luar, sumbernya di tulis sebagai $S(\mathbf{r}, E, \mathbf{\Omega}, t)$, dan dalam sistem menjadi :

            $$ S = S(\mathbf{r}, E, \mathbf{\Omega}, t)\text{d}V\text{d}E\text{d}\mathbf{\Omega} \qquad $$

            Maka, total laju pembentukan neutron ($Q$):

            $$ Q(\mathbf{r}, E, \mathbf{\Omega}, t) = Q_s + Q_f + S \qquad $$

            Sebelumnya dimisalkan laju perubahan kepadatan neutron ($\frac{\partial n}{\partial t}$). Karena kepadatan neutron ($n$) dikali kecepatannya ($v$) sama dengan fluks ($\phi$), maka hal ini dapat di tulis menjadi:

            $$ \frac{\partial}{\partial t}n(\mathbf{r}, E, \mathbf{\Omega}, t) = \frac{1}{v}\frac{\partial}{\partial t}\phi(\mathbf{r}, E, \mathbf{\Omega}, t) \qquad $$


Hasil jadinya adalah persamaan keseimbangan neutron pada waktu $t$ di ruang fase $(\mathbf{r}, E, \mathbf{\Omega})$:

$$
\begin{aligned}
& \frac{1}{v}\frac{\partial \phi}{\partial t} + \mathbf{\Omega} \cdot \nabla\phi \\
& + \Sigma_t(\mathbf{r}, E)\phi = \int_0^\infty \int_{\mathbf{\Omega}'} \Sigma_s(\mathbf{r}, E')f(\mathbf{r}, E' \rightarrow E, \mathbf{\Omega}' \rightarrow \mathbf{\Omega})\phi(\mathbf{r}, E', \mathbf{\Omega}', t)\text{d}E'\text{d}\mathbf{\Omega}' \\
& + Q_f(\mathbf{r}, E, \mathbf{\Omega}, t) + S(\mathbf{r}, E, \mathbf{\Omega}, t) \qquad \\
\end{aligned}
$$

Persamaan inilah yang disebut sebagai **Persamaan Transpor Neutron Keadaan Tak Tunak (*Unsteady State*)** atau sering dipanggil **Persamaan Boltzmann**. Persamaan ini super vital karena jadi fondasi utama buat fisika reaktor dan teori transpor neutron!

Jika reaktor dalam keadaan stabil/tunak (*Steady State*)
Maka tidak ada perubahan fluks terhadap waktu, dimana $\partial n / \partial t = 0$. Maka, suku pertama di sebelah kiri (yang ada turunan waktu) nilainya nol dan hilang. Persamaannya menjadi:

$$
\begin{aligned}
& \mathbf{\Omega} \cdot \nabla\phi \\
& + \Sigma_t(\mathbf{r}, E)\phi = \int_0^\infty \int_{\mathbf{\Omega}'} \Sigma_s(\mathbf{r}, E')f(\mathbf{r}, E' \rightarrow E, \mathbf{\Omega}' \rightarrow \mathbf{\Omega})\phi(\mathbf{r}, E', \mathbf{\Omega}', t)\text{d}E'\text{d}\mathbf{\Omega}' \\
& + Q_f(\mathbf{r}, E, \mathbf{\Omega}, t) + S(\mathbf{r}, E, \mathbf{\Omega}, t) \qquad \\
\end{aligned}
$$

##  <center> <b> Difusi Neutron </b></center>

Jika persamaan transport neutron melacak tiap partikel yang ada dalam teras reaktor berserta posisi, arah laju dan kecepatannya satu persatu. Maka biaya komputasi akan menjadi sangat mahal dan lama. Maka persamaan difusi neutron menyederhanakannya dengan melihat rata rata partikel dalam satu bagian teras. 

* Persamaan Transport Neutron

    Persamaan transport (Boltzmann) untuk neutron menggambarkan **fluks sudut** $\psi(\mathbf{r},\mathbf{\Omega},E,t)$ — jumlah neutron di posisi $\mathbf{r}$, bergerak ke arah $\mathbf{\Omega}$, dengan energi $E$, pada waktu $t$:

    $$
    \begin{aligned} 
    & \frac{1}{v}\frac{\partial \psi}{\partial t} + \mathbf{\Omega}\cdot\nabla\psi + \Sigma_t(\mathbf{r},E)\psi \\
    & = \int dE' \int_{4\pi} d\Omega' \, \Sigma_s(\mathbf{r},E'\to E,\mathbf{\Omega}'\to\mathbf{\Omega})\,\psi(\mathbf{r},\mathbf{\Omega}',E',t) + S \\
     \end{aligned}
    $$

    Masalahnya: persamaan ini punya **7 variabel bebas** (3 posisi, 2 sudut arah, 1 energi, 1 waktu). Hampir mustahil dipecahkan langsung untuk masalah reaktor nyata. Maka kita sederhanakan.


* Pendekatan Difusi (P1)

    Di dalam medium yang banyak menghamburkan neutron (misalnya moderator seperti air), setelah beberapa kali tumbukan, arah gerak neutron jadi hampir acak ke segala arah, maka neutron mengalir dari daerah padat neutron ke daerah jarang neutron.

    Karena itu, fluks sudut di asumsikan hanya dengan dua suku, komponen isotropik (rata ke segala arah) dan satu koreksi arah:

    $$\psi(\mathbf{r},\mathbf{\Omega},E,t) \approx \frac{1}{4\pi}\phi(\mathbf{r},E,t) + \frac{3}{4\pi}\mathbf{\Omega}\cdot\mathbf{J}(\mathbf{r},E,t)$$

    Di sini:
    - $\phi(\mathbf{r},E,t) = \int_{4\pi}\psi\,d\Omega$ → **fluks skalar** (total kepadatan neutron, semua arah dijumlahkan)
    - $\mathbf{J}(\mathbf{r},E,t) = \int_{4\pi}\mathbf{\Omega}\,\psi\,d\Omega$ → **arus neutron** (aliran neto neutron)

    Ini disebut pendekatan **P1**: kita memotong ekspansi sudut hanya sampai orde pertama (Legendre polynomial $l=0$ dan $l=1$). Anggap saja kita mengganti informasi arah yang sangat detail dengan cukup dua angka saja: berapa banyak neutron di sini, dan ke mana arah alirannya secara umum.


* Persamaan Kekekalan Neutron

    Kita integralkan seluruh persamaan transport terhadap semua arah $\mathbf{\Omega}$ (di seluruh bola $4\pi$). Ini setara dengan menjumlahkan neraca dari semua arah jadi satu neraca total.

    Hasilnya :

    $$
    \begin{aligned}
    & \frac{1}{v}\frac{\partial \phi}{\partial t} + \nabla\cdot\mathbf{J} + \Sigma_t(\mathbf{r},E)\phi(\mathbf{r},E,t) \\
    & = \int dE'\,\Sigma_{s0}(\mathbf{r},E'\to E)\,\phi(\mathbf{r},E',t) + S(\mathbf{r},E,t) \\
    \end{aligned}
    $$

    Ini adalah **persamaan kontinuitas neutron**: perubahan populasi = -kebocoran ($\nabla\cdot\mathbf{J}$) − hilang karena tumbukan + masuk karena hamburan + sumber.

    Masalahnya, $\mathbf{J}$ belum kita ketahui hubungannya dengan $\phi$.

* Menurunkan Hukum Fick

    Kali ini, kita kalikan persamaan transport dengan $\mathbf{\Omega}$ lalu integralkan terhadap semua arah. Dengan memasukkan asumsi P1 dan mengabaikan perubahan cepat dari $\mathbf{J}$ terhadap waktu (arus menyesuaikan diri jauh lebih cepat daripada fluks berubah), kita peroleh:

    $$\frac{1}{3}\nabla\phi(\mathbf{r},E,t) + \Sigma_{tr}(\mathbf{r},E)\,\mathbf{J}(\mathbf{r},E,t) = 0$$

    dengan **penampang lintang transport**:

    $$\Sigma_{tr}(\mathbf{r},E) = \Sigma_t(\mathbf{r},E) - \bar{\mu}_0(\mathbf{r},E)\,\Sigma_s(\mathbf{r},E)$$

    ($\bar{\mu}_0$ = kosinus rata-rata sudut hamburan, mengoreksi efek hamburan yang tidak sepenuhnya acak/isotropik).

    Susun ulang persamaan, maka di dapatkan **Hukum Fick**, persis seperti hukum yang sama yang menjelaskan difusi panas atau penyebaran asap:

    $$\boxed{\mathbf{J}(\mathbf{r},E,t) = -D(\mathbf{r},E)\,\nabla\phi(\mathbf{r},E,t)}, \qquad D(\mathbf{r},E) = \frac{1}{3\,\Sigma_{tr}(\mathbf{r},E)}$$

    **Maknanya secara intuitif:** neutron mengalir secara neto dari daerah yang padat neutron ke daerah yang lebih jarang neutron, dengan kecepatan aliran sebanding dengan seberapa "curam" perbedaan kepadatannya ($\nabla\phi$). $D$ besar artinya neutron mudah mengalir (sedikit tumbukan); $D$ kecil artinya neutron "macet" (banyak tumbukan, sering terserap/terhambur).

* Persamaan Difusi Neutron (Energi Kontinu)

    Substitusikan Hukum Fick :

    $$
    \begin{aligned}
    & \frac{1}{v}\frac{\partial \phi(\mathbf{r},E,t)}{\partial t} = \nabla\cdot\big[D(\mathbf{r},E)\nabla\phi(\mathbf{r},E,t)\big] \\
    & - \Sigma_t(\mathbf{r},E)\phi(\mathbf{r},E,t) + \int dE'\,\Sigma_{s0}(\mathbf{r},E'\to E)\phi(\mathbf{r},E',t) \\
    & + S(\mathbf{r},E,t) \\
    \end{aligned}
    $$

    Inilah **persamaan difusi neutron**. Variabel sudut $\mathbf{\Omega}$ sudah hilang sepenuhnya — sudah jauh lebih sederhana dari persamaan transport awal. Tapi ketergantungan terhadap energi $E$ masih kontinu (terus-menerus), dan ini masih sulit dipecahkan karena penampang lintang $\Sigma$ bisa berubah drastis (ada "resonansi" tajam) terhadap energi.

* Energi Kontinu ke Multigrup

    Di sinilah ide **multigrup** masuk. Daripada melacak $\phi(E)$ untuk setiap nilai energi (tak terhingga banyaknya), kita potong sumbu energi menjadi $G$ buah "kotak"/kelompok energi (grup), dari energi tertinggi (grup 1, neutron cepat) sampai energi terendah (grup $G$, neutron termal):

    $$E_0 \;(\text{tertinggi}) > E_1 > E_2 > \cdots > E_G \;(\text{terendah, } \approx 0)$$

    Grup $g$ mencakup rentang energi $[E_g, E_{g-1}]$.

    Kita definisikan **fluks grup** (total neutron di rentang energi itu):

    $$\phi_g(\mathbf{r},t) = \int_{E_g}^{E_{g-1}} \phi(\mathbf{r},E,t)\,dE$$

    Lalu kita **integralkan** persamaan difusi dari Langkah 5 terhadap energi, dari $E_g$ sampai $E_{g-1}$, untuk setiap grup $g$.

    **Soal penting saat melakukan ini:** penampang lintang $D$, $\Sigma_t$, $\Sigma_s$ di dalam satu grup tidaklah konstan — bisa berubah-ubah tajam terhadap energi. Supaya hasil integrasinya tetap akurat (laju reaksi tetap benar), kita harus mendefinisikan **konstanta grup** sebagai rata-rata yang **dibobotkan dengan fluks** sesungguhnya di dalam grup itu:

    $$\Sigma_{t,g}(\mathbf{r}) = \frac{\displaystyle\int_{E_g}^{E_{g-1}} \Sigma_t(\mathbf{r},E)\,\phi(\mathbf{r},E,t)\,dE}{\phi_g(\mathbf{r},t)}, \qquad D_g(\mathbf{r}) = \frac{\displaystyle\int_{E_g}^{E_{g-1}} D(\mathbf{r},E)\,\phi(\mathbf{r},E,t)\,dE}{\phi_g(\mathbf{r},t)}$$

    dan untuk hamburan antar-grup ($g' \to g$):

    $$\Sigma_{s,\,g'\to g}(\mathbf{r}) = \frac{\displaystyle\int_{g'} dE' \int_{g} dE\;\Sigma_{s0}(\mathbf{r},E'\to E)\,\phi(\mathbf{r},E',t)}{\phi_{g'}(\mathbf{r},t)}$$

    **Kenapa pembobotan dengan fluks?** Karena daerah energi di mana banyak neutron berada (fluks tinggi) jauh lebih penting secara fisis untuk "rata-rata efektif" dibanding daerah energi yang jarang dihuni neutron — sama seperti rata-rata pendapatan penduduk seharusnya dibobotkan jumlah orang, bukan dirata-ratakan begitu saja per kategori.


* Difusi Neutron Multigrup

    Setelah integrasi energi selesai, untuk setiap grup $g = 1, 2, \dots, G$ kita peroleh sistem $G$ persamaan yang saling berkaitan:

    $$
    \begin{aligned}
    & \frac{1}{v_g}\frac{\partial \phi_g(\mathbf{r},t)}{\partial t} = \nabla\cdot\big[D_g(\mathbf{r})\nabla\phi_g(\mathbf{r},t)\big] \\
    & - \Sigma_{r,g}(\mathbf{r})\phi_g(\mathbf{r},t) \\
    & + \sum_{g'\neq g}\Sigma_{s,\,g'\to g}(\mathbf{r})\,\phi_{g'}(\mathbf{r},t) \\
    & + \frac{\chi_g}{k_{eff}}\sum_{g'=1}^{G}\nu\Sigma_{f,g'}(\mathbf{r})\,\phi_{g'}(\mathbf{r},t) \\
    \end{aligned}
    $$

    Dimana : 
    - $\nabla\cdot[D_g\nabla\phi_g]$ : kebocoran/difusi neutron grup $g$ (analog hukum Fick) 
    - $\Sigma_{r,g}\,\phi_g$ : **hilang** dari grup $g$ (diserap, atau dihamburkan keluar ke grup lain): $\Sigma_{r,g} = \Sigma_{a,g} + \sum_{g'\neq g}\Sigma_{s,g\to g'}$ 
    - $\sum_{g'\neq g}\Sigma_{s,g'\to g}\,\phi_{g'}$ : **masuk** ke grup $g$ dari hamburan grup lain (biasanya dari grup energi lebih tinggi → "melambat"/slowing down) 
    - $\chi_g \sum \nu\Sigma_{f,g'}\phi_{g'}/k_{eff}$ : neutron baru hasil **fisi**, lahir ke grup $g$ menurut spektrum fisi $\chi_g$ (sebagian besar neutron fisi lahir cepat, jadi $\chi_g$ besar hanya untuk grup energi tinggi) 
    - $k_{eff}$ adalah faktor multiplikasi efektif — nilai eigen yang dicari supaya sistem persamaan ini punya solusi tepat pada kondisi kritis (untuk perhitungan keadaan tunak/steady-state).

    Inilah **persamaan difusi neutron multigrup** — bentuk yang sebenarnya dipakai di kode-kode desain reaktor (PARCS, SIMULATE, dan semacamnya) untuk menghitung distribusi daya dan kekritisan teras reaktor.


    > pendekatan difusi ini akurat ketika medium sering menghamburkan neutron secara hampir isotropik (jauh dari batas vakum, jauh dari penyerap kuat, dan minimal beberapa jalur bebas rata-rata dari sumber titik). Dekat batas reaktor, dekat batang kendali yang sangat menyerap, atau di rongga (void) besar, pendekatan ini kurang akurat maka biasanya dipakai metode transport yang lebih teliti ($S_N$, Monte Carlo) atau koreksi transport tambahan.

##  <center> <b> Bentuk Integral NTE </b></center>
#### **Annotation**
- $\phi(\mathbf r,\boldsymbol\Omega,E)$  (**Fluks sudut neutron**) : jumlah neutron yang lewat per detik, per satuan luas, bergerak ke arah $\boldsymbol\Omega$, pada energi $E$, di titik $\mathbf r$.
- $\phi(\mathbf r,E)$ (**Fluks skalar**) : fluks sudut yang sudah "dijumlahkan" ke semua arah (semua neutron, tidak peduli arahnya).
- $\Sigma(\mathbf r,E)$ (**Penampang lintang makroskopik total**) : seberapa "sering" neutron bertumbukan per satuan jarak. Makin besar $\Sigma$, makin sering tumbukan, makin pendek jarak rata-rata sebelum nabrak sesuatu. 
- $\Sigma_s,\ \Sigma_f$  : Penampang lintang untuk **hamburan** (scatter) dan **fisi**
- $\boldsymbol\Omega,\ \boldsymbol\Omega'$ : Arah gerak neutron — $\boldsymbol\Omega'$ = arah **sebelum** tumbukan, $\boldsymbol\Omega$ = arah **sesudah** tumbukan. 
- $\chi(E)$ (**Spektrum fisi**) : peluang neutron hasil fisi punya energi $E$. 
- $\nu(E)$ : Rata-rata jumlah neutron yang keluar dari satu fisi. 
- $Q(\mathbf r,\boldsymbol\Omega,E)$ (**Sumber luar**) : neutron yang muncul bukan karena hamburan/fisi. 
- $q(\mathbf r,\boldsymbol\Omega,E)$ (**Sumber tumbukan total**) : gabungan hamburan + fisi + sumber luar; "semua neutron baru" yang muncul di titik itu. 
- $\tau(\mathbf r,\mathbf r',E)$  (**Kedalaman optik** (optical depth)) : jarak antara $\mathbf r$ dan $\mathbf r'$, diukur dalam satuan "berapa kali jarak bebas rata-rata", bukan meter. 
- $\Gamma$ : Permukaan/batas dari media (reaktor, perisai, dsb). 
- $\hat{\mathbf n}_s$ : Vektor **normal keluar** di permukaan $\Gamma$. 
- $\Theta(x)$ (**Fungsi tangga Heaviside**) : nilainya $1$ jika $x>0$, dan $0$ jika $x<0$ — berfungsi seperti saklar on/off

Persamaan transport neutron versi dasar punya **6 variabel bebas** (3 posisi, 2 arah, 1 energi):

$$
\begin{aligned}
& \Big[\boldsymbol\Omega\cdot\nabla + \Sigma(\mathbf r,E)\Big]\phi(\mathbf r,\boldsymbol\Omega,E) =
\underbrace{\int_0^{\infty}\! dE' \!\int_{4\pi}\! d\Omega'\; \Sigma_s(\mathbf r,\boldsymbol\Omega'\!\cdot\boldsymbol\Omega,E'\!\to E)\,\phi(\mathbf r,\boldsymbol\Omega',E')}_{\text{hamburan}} \\
& + \underbrace{\frac{\chi(E)}{4\pi}\int_0^{\infty}\! dE' \!\int_{4\pi}\! d\Omega'\; \nu(E')\,\Sigma_f(\mathbf r,E')\,\phi(\mathbf r,\boldsymbol\Omega',E')}_{\text{fisi}} \\
& + \underbrace{Q(\mathbf r,\boldsymbol\Omega,E)}_{\text{sumber luar}} \\
\end{aligned}
$$

#### Penurunan Bentuk Integral

1. Neutron Bergerak Lurus: Garis Karakteristik
    Antara dua tumbukan, neutron bergerak **lurus** (seperti peluru, tidak dibelokkan gravitasi/medan apa pun). Jika neutron bergerak ke arah $\boldsymbol\Omega$ mulai dari titik $\mathbf r'$, maka setelah menempuh jarak $s$, posisinya menjadi:
    
    $$ \mathbf r = \mathbf r' + s\,\boldsymbol\Omega$$
    
    Garis lurus yang dilewati neutron ini disebut **garis karakteristik** (characteristic line). Ide besar "bentuk integral": alih-alih melihat persamaan transport sebagai PDE 3 dimensi yang rumit, kita **menyusuri garis ini satu per satu**, dan persamaan transport berubah menjadi persamaan 1 dimensi yang jauh lebih sederhana sepanjang garis tersebut.

2. Mengubah Turunan Ruang Menjadi Turunan Sepanjang Lintasan (→ Eq.1-3)

    Kita ingin tahu: berapa $\phi$ berubah jika bergeser sedikit **sepanjang arah gerak neutron**? Bayangkan Anda berdiri di titik pengamatan $\mathbf r$, menengok ke belakang sejauh $s$ ke arah dari mana neutron itu datang (arah $-\boldsymbol\Omega$). Titik di belakang Anda itu adalah:

    $$ \mathbf r'(s) = \mathbf r - s\,\boldsymbol\Omega \qquad\Longrightarrow\qquad \frac{\partial \mathbf r'}{\partial s} = -\boldsymbol\Omega$$

    (tanda minus karena makin besar $s$, makin jauh kita mundur **melawan** arah $\boldsymbol\Omega$).

    Aturan rantai (chain rule) memberi:

    $$
    \begin{aligned}
    & \frac{d}{ds}\,\phi(\mathbf r'(s),\boldsymbol\Omega,E) = \frac{\partial \mathbf r'}{\partial s}\cdot \nabla_{\mathbf r'}\phi = \\
    & -\,\boldsymbol\Omega\cdot\nabla_{\mathbf r'}\phi(\mathbf r',\boldsymbol\Omega,E) \\
    \end{aligned}
    $$

    Dibalik:

    $$ \boldsymbol\Omega\cdot\nabla_{\mathbf r'}\,\phi(\mathbf r',\boldsymbol\Omega,E) \;=\; -\,\frac{d}{ds}\,\phi(\mathbf r',\boldsymbol\Omega,E) $$

    Sekarang tulis ulang Eq.(1-2), dievaluasi di titik $\mathbf r'$ (bukan $\mathbf r$), dengan semua suku hamburan+fisi+sumber luar di kanan disingkat $q(\mathbf r',\boldsymbol\Omega,E)$ (definisi lengkapnya di Langkah 3):

    $$
    \begin{aligned}
    & \boldsymbol\Omega\cdot\nabla_{\mathbf r'}\phi(\mathbf r',\boldsymbol\Omega,E) \\
    & + \Sigma(\mathbf r',E)\,\phi(\mathbf r',\boldsymbol\Omega,E) = q(\mathbf r',\boldsymbol\Omega,E) \\
    \end{aligned}
    $$

    Substitusikan hasil di atas:

    $$ -\frac{d}{ds}\phi(\mathbf r',\boldsymbol\Omega,E) + \Sigma(\mathbf r',E)\,\phi(\mathbf r',\boldsymbol\Omega,E) = q(\mathbf r',\boldsymbol\Omega,E) $$

    Kalikan kedua sisi dengan $-1$:

    $$ \frac{d}{ds}\phi(\mathbf r',\boldsymbol\Omega,E) - \Sigma(\mathbf r',E)\,\phi(\mathbf r',\boldsymbol\Omega,E) = -\,q(\mathbf r',\boldsymbol\Omega,E) $$

    atau ditulis rapi:

    $$ \left[\,\frac{d}{ds} - \Sigma(\mathbf r',E)\,\right]\phi(\mathbf r',\boldsymbol\Omega,E) = -\,q(\mathbf r',\boldsymbol\Omega,E) $$

3. Sumber Tumbukan ($q$) 

    $q(\mathbf r,\boldsymbol\Omega,E)$ hanyalah **nama untuk gabungan semua suku di sisi kanan** Eq.(1-2): neutron yang masuk ke kelompok arah/energi ini karena (a) dihamburkan dari arah/energi lain, (b) lahir dari fisi, atau (c) berasal dari sumber luar:

    $$
    \begin{aligned}
    & q(\mathbf r,\boldsymbol\Omega,E) = \int_0^\infty dE'\int_{4\pi}d\Omega'\;\Sigma_s(\mathbf r,\boldsymbol\Omega'\cdot\boldsymbol\Omega,E'\to E)\,\phi(\mathbf r,\boldsymbol\Omega',E') \\
    & + \frac{\chi(E)}{4\pi}\int_0^\infty dE'\int_{4\pi}d\Omega'\;\nu(E')\,\Sigma_f(\mathbf r,E')\,\phi(\mathbf r,\boldsymbol\Omega',E') \\
    & + Q(\mathbf r,\boldsymbol\Omega,E) \\
    \end{aligned}
    $$

4. Kedalaman Optik ($\tau$) : Mengukur Jarak dalam Satuan Tumbukan

    Sebelum menyelesaikan Eq.(1-3), naskah mendefinisikan:

    $$ \tau(\mathbf r,\mathbf r',E) \;\equiv\; \int_0^{|\mathbf r-\mathbf r'|} ds'\;\Sigma\big(\mathbf r'(s'),E\big) $$

    Bayangkan Anda berjalan dari $\mathbf r'$ ke $\mathbf r$. Di setiap titik sepanjang jalan ada "kerapatan tumbukan" $\Sigma$. Jika dijumlahkan (diintegralkan) sepanjang seluruh lintasan, hasilnya adalah $\tau$ — **jumlah rata-rata tumbukan "seharusnya"** sepanjang jarak itu (walau aktualnya bisa nol, satu, atau banyak — $\tau$ hanyalah ukuran panjang jarak dalam satuan *mean free path*, bukan jumlah tumbukan aktual).

    Kenapa penting? Karena peluang neutron **lolos tanpa tumbukan sama sekali** sepanjang jarak itu adalah:

    $$ e^{-\tau(\mathbf r,\mathbf r',E)} $$

    Hukum peluruhan eksponensial ini sama seperti cahaya yang makin redup saat menembus kabut tebal — makin tebal kabut (makin besar $\tau$), makin kecil peluang lolos.

5. Pengintegralan

    Eq.(1-3) adalah **persamaan diferensial linear orde satu** dalam $s$. Kita gunakan trik **faktor pengintegralan** (integrating factor) — trik standar untuk bentuk $\,d\Phi/ds + (\text{sesuatu})\cdot\Phi = (\text{sesuatu lain})$.

    Parametrikan **maju** sepanjang lintasan: mulai dari $\mathbf r'$ (saat $s'=0$), bergerak ke arah $\boldsymbol\Omega$, sehingga titik di sepanjang jalan adalah $\mathbf r'(s') = \mathbf r' + s'\boldsymbol\Omega$. Definisikan singkatan:

    $$
    \Phi(s') \equiv \phi\big(\mathbf r' + s'\boldsymbol\Omega,\ \boldsymbol\Omega,\ E\big)
    $$

    Eq.(1-2) yang dievaluasi sepanjang lintasan ini (arah **maju**, kebalikan dari Langkah 2) memberi bentuk:

    $$
    \frac{d\Phi}{ds'} + \Sigma(s')\,\Phi(s') = q(s')
    \qquad\text{dengan}\qquad \Sigma(s')\equiv\Sigma(\mathbf r'+s'\boldsymbol\Omega,E),\quad q(s')\equiv q(\mathbf r'+s'\boldsymbol\Omega,\boldsymbol\Omega,E)
    $$

    kalikan kedua sisi dengan : 

    $$
    \mu(s') = \exp\!\left[\int_0^{s'} \Sigma(s'')\,ds''\right]
    $$

    Karena $d\mu/ds' = \Sigma(s')\,\mu(s')$, sisi kiri menjadi turunan dari sebuah hasil kali (kebalikan dari *product rule*):

    $$
    \frac{d}{ds'}\Big[\mu(s')\,\Phi(s')\Big] = \mu(s')\,q(s')
    $$

    Integralkan kedua sisi dari $0$ sampai $s$:

    $$
    \mu(s)\,\Phi(s) - \mu(0)\,\Phi(0) = \int_0^{s} \mu(s')\,q(s')\,ds'
    $$

    Karena $\mu(0) = e^0 = 1$, bagi semua sisi dengan $\mu(s)$:

    $$
    \Phi(s) = \Phi(0)\cdot e^{-\int_0^{s}\Sigma(s'')\,ds''} \;+\; \int_0^{s} e^{-\int_{s'}^{s}\Sigma(s'')\,ds''}\;q(s')\,ds'
    $$

    Sekarang kenali bahwa $\int_0^{s}\Sigma\,ds''$ adalah **kedalaman optik** dari $\mathbf r'$ sampai $\mathbf r'+s\boldsymbol\Omega$. Tetapkan $s = |\mathbf r-\mathbf r'|$ sehingga $\mathbf r'+s\boldsymbol\Omega=\mathbf r$:

    - $\displaystyle\int_0^{s}\Sigma\,ds'' = \tau(\mathbf r,\mathbf r',E)$
    - $\displaystyle\int_{s'}^{s}\Sigma\,ds'' = \tau\big(\mathbf r,\mathbf r'(s'),E\big)$ (kedalaman optik dari titik tengah $\mathbf r'(s')=\mathbf r'+s'\boldsymbol\Omega$ sampai $\mathbf r$)
    - $\Phi(0)=\phi(\mathbf r',\boldsymbol\Omega,E)$, dan $\Phi(s)=\phi(\mathbf r,\boldsymbol\Omega,E)$

    Masukkan semuanya:

    $$
    \phi(\mathbf r,\boldsymbol\Omega,E) = \phi(\mathbf r',\boldsymbol\Omega,E)\,e^{-\tau(\mathbf r,\mathbf r',E)}
    \;+\; \int_0^{s} ds'\; e^{-\tau(\mathbf r,\mathbf r'(s'),E)}\;q\big(\mathbf r'(s'),\boldsymbol\Omega,E\big)
    $$
    
    **Cara membaca Eq.(1-5) secara fisis** (ini intinya!):

    > Fluks neutron di titik $\mathbf r$ = **(fluks dari titik $\mathbf r'$, yang berhasil "lolos" tanpa tumbukan sepanjang perjalanan ke $\mathbf r$)** $+$ **(semua neutron baru yang lahir di sepanjang jalan, masing-masing dilemahkan sesuai sisa jarak yang harus ditempuhnya ke $\mathbf r$)**.

    Ini sebenarnya **gambaran fisis yang sama persis** dengan cara kerja simulasi Monte Carlo: neutron bergerak lurus, punya peluang lolos $e^{-\tau}$, dan di sepanjang jalan bisa "melahirkan" neutron baru lewat hamburan/fisi.

6. Menempatkan Titik Awal di Batas Media: Eq.(1-6)

    Eq.(1-5) berlaku untuk **sembarang** titik awal $\mathbf r'$. Supaya berguna sebagai persamaan yang bisa diselesaikan, kita perlu menempatkan $\mathbf r'$ di tempat yang **informasinya kita ketahui** — yaitu di **permukaan/batas** media ($\Gamma$), karena di sanalah syarat batas (boundary condition) biasanya diberikan.

    Definisikan $\mathbf r_s(\boldsymbol\Omega)$ = titik di permukaan tempat neutron itu **masuk** ke dalam media, sebelum sampai ke $\mathbf r$, sambil bergerak ke arah $\boldsymbol\Omega$. (Titik ini bergantung pada arah $\boldsymbol\Omega$, karena itu ditulis $\mathbf r_s(\boldsymbol\Omega)$.)

    Ganti $\mathbf r'\to\mathbf r_s(\boldsymbol\Omega)$ di Eq.(1-5):

    $$
    \begin{aligned}
    \phi(\mathbf{r},\boldsymbol{\Omega},E)
    ={}&
    \phi\bigl(\mathbf{r}_s(\boldsymbol{\Omega}),
            \boldsymbol{\Omega},E\bigr)
    e^{-\tau(\mathbf{r},\mathbf{r}_s(\boldsymbol{\Omega}),E)}
    \Theta\bigl(-\hat{\mathbf{n}}_s\cdot\boldsymbol{\Omega}\bigr)
    \\[6pt]
    &+
    \int_0^{|\mathbf{r}-\mathbf{r}_s|}
    ds'\;
    e^{-\tau(\mathbf{r},\mathbf{r}-s'\boldsymbol{\Omega},E)}
    q\bigl(\mathbf{r}-s'\boldsymbol{\Omega},E\bigr).
    \end{aligned}
    $$

    **Eq.(1-6) + Eq.(1-4) ini disebut "Persamaan Integral Fredholm Jenis Kedua".** Namanya terdengar rumit, tapi maksudnya sederhana: yang dicari ($\phi$) muncul di **kedua sisi** — di kiri sebagai $\phi(\mathbf r,\boldsymbol\Omega,E)$, dan tersembunyi lagi di kanan, di dalam $q$, lewat $\phi(\mathbf r,\boldsymbol\Omega',E')$ (lihat Eq.1-4). Karena fungsi yang tak-diketahui "muncul lagi" di dalam integral di sisi kanan, persamaan ini disebut "jenis kedua" (berbeda dari "jenis pertama" yang fungsi tak-diketahuinya hanya muncul di dalam integral saja).

7. Fluks Skalar: Menjumlahkan ke Semua Arah (Eq.1-7, Eq.1-8)

    Fluks sudut $\phi(\mathbf r,\boldsymbol\Omega,E)$ masih punya variabel arah $\boldsymbol\Omega$. Kadang kita hanya butuh **total neutron di semua arah**, yaitu fluks skalar:

    $$
    \phi(\mathbf r,E) \equiv \int_{4\pi} d\Omega\;\phi(\mathbf r,\boldsymbol\Omega,E)
    $$

    **Eq.(1-7)**

    ($\int_{4\pi}d\Omega$ artinya menjumlahkan/mengintegralkan ke seluruh permukaan bola arah — total $4\pi$ steradian, yaitu **semua** kemungkinan arah.)

    Untuk mendapatkan persamaan bagi $\phi(\mathbf r,E)$ saja, kita **integralkan Eq.(1-6) terhadap $\boldsymbol\Omega$** di kedua sisi:

    $$
    \begin{aligned}
    \phi(\mathbf{r},E)
    ={}&
    \int_{\hat{\mathbf{n}}_s\cdot\boldsymbol{\Omega}<0}
    d\Omega\;
    \phi\bigl(\mathbf{r}_s(\boldsymbol{\Omega}),
            \boldsymbol{\Omega},E\bigr)
    e^{-\tau(\mathbf{r},\mathbf{r}_s(\boldsymbol{\Omega}),E)}
    \\[6pt]
    &+
    \int_{4\pi} d\Omega
    \int_0^{|\mathbf{r}-\mathbf{r}_s|}
    ds'\;
    e^{-\tau(\mathbf{r},\mathbf{r}'(s'),E)}
    q\bigl(\mathbf{r}'(s'),\boldsymbol{\Omega},E\bigr).
    \end{aligned}
    $$

    **Eq.(1-8)**

    Perhatikan: suku pertama sekarang diintegralkan hanya untuk arah $\boldsymbol\Omega$ yang **memang masuk** ($\hat{\mathbf n}_s\cdot\boldsymbol\Omega<0$) — hasil otomatis dari fungsi tangga $\Theta$ di Eq.(1-6) yang "menyaring" arah, sehingga batas integralnya berubah dari $\int_{4\pi}$ menjadi $\int_{\hat{\mathbf n}_s\cdot\boldsymbol\Omega<0}$. Suku kedua tetap diintegralkan ke seluruh $4\pi$ arah karena tidak ada batasan arah di sana.

8. Mengganti Variabel Sudut dan Jarak Menjadi Volume : Eq.(1-9)

    Suku kedua Eq.(1-8) berbentuk $\int d\Omega \int ds'$. Ini bisa diubah menjadi **integral volume tunggal** $\int d\mathbf r'$, dengan trik **transformasi koordinat bola** (mengingatkan elemen volume $dV=r^2\,dr\,d\Omega$ dalam koordinat bola dari kalkulus/fisika dasar).

    Di sini, "titik pusat bola"-nya adalah $\mathbf r$ (titik pengamatan), dan $s'$ berperan sebagai "jarak radial" dari $\mathbf r$. Elemen volume di sekitar $\mathbf r'$ (dengan $\mathbf r' = \mathbf r - s'\boldsymbol\Omega$) adalah:

    $$
    d\mathbf r' = s'^2\, d\Omega\, ds'
    $$

    Substitusikan ke Eq.(1-8) (sehingga $ds' = d\mathbf r'/s'^2$, dan $d\Omega$ "terserap" ke dalam integral volume):

    $$
    \phi(\mathbf r,E) = \int_{\hat{\mathbf n}_s\cdot\boldsymbol\Omega<0} d\Omega\;\phi\big(\mathbf r_s(\boldsymbol\Omega),\boldsymbol\Omega,E\big)\,e^{-\tau(\mathbf r,\mathbf r_s(\boldsymbol\Omega),E)}
    \;+\; \int_V d\mathbf r'\;\frac{e^{-\tau(\mathbf r,\mathbf r',E)}}{|\mathbf r-\mathbf r'|^2}\;
    q\!\left(\mathbf r',\ \frac{\mathbf r-\mathbf r'}{|\mathbf r-\mathbf r'|},\ E\right)
    $$

    **Eq.(1-9)**

    Catat juga: arah $\boldsymbol\Omega$ di dalam $q(\cdots)$ sekarang ditulis sebagai $\dfrac{\mathbf r-\mathbf r'}{|\mathbf r-\mathbf r'|}$ — yaitu **arah dari $\mathbf r'$ menuju $\mathbf r$** — karena hanya neutron yang lahir di $\mathbf r'$ dengan arah **tepat menuju $\mathbf r$** yang bisa berkontribusi ke fluks di $\mathbf r$.

    > **Kenapa Eq.(1-9) "belum" jadi persamaan murni untuk fluks skalar?** Karena $q(\mathbf r',\boldsymbol\Omega,E)$ di kanan (lihat Eq.1-4) pada umumnya masih bergantung pada $\phi(\mathbf r',\boldsymbol\Omega',E')$ — fluks **sudut** di $\mathbf r'$, bukan fluks **skalar**-nya saja. Jadi walau sudah ditulis sebagai integral volume, persamaan ini belum "tertutup" hanya dengan variabel $\phi(\mathbf r,E)$.

9. Trik Penutup: Asumsi Hamburan & Sumber Isotropik → Eq.(1-10) dan Eq.(1-11)

    Untuk membuat persamaan benar-benar tertutup hanya dalam $\phi(\mathbf r,E)$, naskah mengasumsikan dua hal:

    **1. Hamburan isotropik** — peluang neutron terhambur ke segala arah **sama saja**, tidak peduli arah datangnya:

    $$
    f_s(\boldsymbol\Omega'\cdot\boldsymbol\Omega,E'\to E) = \frac{1}{4\pi}f_s(E'\to E)
    $$

    **2. Sumber isotropik** — sumber luar juga memancar ke segala arah sama rata:

    $$
    Q(\mathbf r,\boldsymbol\Omega,E) = \frac{1}{4\pi}Q(\mathbf r,E)
    $$

    Lihat apa yang terjadi pada $q$ (Eq.1-4) dengan asumsi ini. Karena bagian arahnya sekarang konstan ($1/4\pi$, tak bergantung $\boldsymbol\Omega'$ lagi), integral terhadap $\boldsymbol\Omega'$ di setiap suku menjadi **mudah**: ia tinggal mengambil $\int d\Omega'\,\phi(\mathbf r,\boldsymbol\Omega',E') = \phi(\mathbf r,E')$ — **persis definisi fluks skalar** di Eq.(1-7)! Inilah kuncinya — dengan hamburan & sumber isotropik, integral sudut otomatis "menyederhanakan" fluks sudut menjadi fluks skalar.

    Gabungkan suku hamburan dan fisi menjadi satu kernel:

    $$
    \Sigma(\mathbf r,E'\to E) \equiv \Sigma_s(\mathbf r,E')\,f_s(E'\to E) \;+\; \nu(E')\,\Sigma_f(\mathbf r,E')\,\chi(E)
    $$

    Sehingga $q$ menjadi:

    $$
    q(\mathbf r,\boldsymbol\Omega,E) = \frac{1}{4\pi}\left[\int_0^\infty dE'\;\Sigma(\mathbf r,E'\to E)\,\phi(\mathbf r,E') \;+\; Q(\mathbf r,E)\right]
    $$

    **Eq.(1-11)**

    Perhatikan: $q$ sekarang **tidak lagi bergantung pada arah $\boldsymbol\Omega$** secara eksplisit (kecuali faktor $1/4\pi$ konstan), dan hanya butuh $\phi(\mathbf r,E')$ — fluks skalar saja!

    Masukkan $q$ versi isotropik ini ke Eq.(1-9), dan kita peroleh persamaan yang **benar-benar tertutup** untuk fluks skalar:

    $$ \begin{aligned}
    & \phi(\mathbf r,E) = \int_{\hat{\mathbf n}_s\cdot\boldsymbol\Omega<0} d\Omega\;\phi\big(\mathbf r_s(\boldsymbol\Omega),\boldsymbol\Omega,E\big)\,e^{-\tau(\mathbf r,\mathbf r_s(\boldsymbol\Omega),E)}
    \; \\
    &+\; \int_V d\mathbf r'\;\frac{e^{-\tau(\mathbf r,\mathbf r',E)}}{4\pi\,|\mathbf r-\mathbf r'|^2}
    \left[\int_0^\infty dE'\;\Sigma(\mathbf r',E'\to E)\,\phi(\mathbf r',E') \;+\; Q(\mathbf r',E)\right]
    \end{aligned}
    $$

    **Eq.(1-10)**

    dengan $Q(\mathbf r,E) \equiv \int_{4\pi} d\Omega\;Q(\mathbf r,\boldsymbol\Omega,E)$ (sumber luar yang sudah dijumlahkan ke semua arah).

    **Ringkasnya Langkah 9**: Eq.(1-9) "macet" karena $q$ butuh info fluks per-arah. Asumsi isotropik membuat info per-arah itu **tidak diperlukan lagi**, karena rata-ratanya ke semua arah sama saja — sehingga seluruh persamaan bisa ditulis hanya dengan fluks skalar $\phi(\mathbf r,E)$.

10. Kasus Tanpa Neutron Masuk dan Vakum dengan Media Homogen → Eq.(1-12)

      Tambahkan dua penyederhanaan terakhir:

      **1. Tidak ada neutron yang masuk dari luar (vakum):** $\phi(\mathbf r_s,\boldsymbol\Omega,E) \equiv 0$ untuk semua arah masuk. Akibatnya, suku **pertama** di Eq.(1-10) (suku batas) langsung lenyap menjadi nol.

      **2. Media homogen:** sifat nuklir ($\Sigma$) **sama di semua titik**, tidak bergantung posisi $\mathbf r$. Kedalaman optik tidak perlu lagi diintegralkan sepanjang jalur — ia tinggal:

      $$
      \tau(\mathbf r,\mathbf r',E) = \Sigma(E)\cdot|\mathbf r-\mathbf r'|
      $$

      (cukup dikali jarak garis lurus, karena $\Sigma$ konstan di mana-mana).

      Masukkan kedua penyederhanaan ini ke Eq.(1-10):

      $$
      \phi(\mathbf r,E) = \int_V d\mathbf r'\;\frac{e^{-\Sigma(E)|\mathbf r-\mathbf r'|}}{4\pi\,|\mathbf r-\mathbf r'|^2}
      \left[\int_0^\infty dE'\;\Sigma(E'\to E)\,\phi(\mathbf r',E') \;+\; Q(\mathbf r',E)\right]
      $$

      **Kegunaannya**:
      - Sangat cocok untuk **pendekatan tumbukan berganda** (*multiple collision approximation*) ketika serapan ($\Sigma_a$) jauh lebih dominan daripada hamburan.
      - Bisa diselesaikan secara numerik lewat **metode peluang tumbukan** (*collision probability methods*) — banyak dipakai untuk menghitung fluks dalam rangka **homogenisasi penampang lintang** (*cross section homogenization*), yaitu proses meratakan sifat nuklir suatu rakitan bahan bakar menjadi satu nilai efektif untuk dipakai di perhitungan skala besar (nodal/diffusion) — persis seperti disebut di bagian 1.1.1 di awal bab Anda.

**Kamu kira sudah selesai? tentu saja masih jauh perjuanganmu HAHAHHAHA**

##  <center> <b> Deterministik  </b></center>

Pada bagian ini akan di bahas bagaimana penyelesaian metode deterministik di lakukan, dengan menggunakan 3 lapisan pemodelan dimana yang pertama menentukan persamaan yang akan di selesaikan yaitu difusi atau transport, secara garis besar pada persamaan transport di gunakan diskritisasi sudut yang dimana pada difusi sudut di anggap searah. Bagian kedua akan membahas bagaimana diskritisasi energi, ruang dan sudut. Kemudian bagian ketiga membahas metode aljabar apa yang akan di gunakan untuk menyelesaikan masalah fix source atau eigenvalue.

#### 1.1 Masalah yang Ingin Dipecahkan

Neutron di reaktor bergerak, bertumbukan, tersebar, diserap, dan memicu fisi. Perilakunya dijelaskan oleh **persamaan transport neutron**. Bacanya: **neutron yang hilang (bocor + tumbukan) = sumber hamburan + sumber fisi dibagi $k$**. Bilangan $k=k_\text{eff}$ adalah eigenvalue yang dicari.

**Deterministik vs Monte Carlo.** Monte Carlo menyimulasikan nasib neutron satu per satu secara acak. Metode deterministik menuliskan persamaan transport sebagai sistem persamaan aljabar lalu menyelesaikannya. Hasilnya tidak berisik secara statistik dan cepat, tetapi akurasinya dibatasi oleh pendekatan diskretisasi.

#### 1.2 Tiga Lapisan Independen

Setiap kode transport/difusi reaktor pada dasarnya punya **tiga lapisan independen**. Memahami ini membuat semua metode (difusi, Sn, Pn, MOC, dan lainnya) mudah dipetakan.

| Lapisan | Pertanyaan | Pilihan metode |
|---|---|---|
| **A. Model fisika** | Persamaan apa yang diselesaikan? | Difusi, transport (BTE), SPN, dll. |
| **B. Diskritisasi** | Bagaimana variabel kontinu dibuat diskrit? | Ruang, energi, sudut |
| **C. Solusi aljabar** | Bagaimana sistem diskrit dan nilai eigen diselesaikan? | Power iteration, Krylov, dll. |

#### 1.3 Lapisan A: Model Fisika

##### Persamaan transport Boltzmann (bentuk eigen)

Persamaan eksak dengan variabel $\mathbf{r},\boldsymbol{\Omega},E$ (keadaan tunak):

$$
\begin{aligned}
& \boldsymbol{\Omega}\cdot\nabla\psi \\
& + \Sigma_t\,\psi = \int_0^\infty\!\!\int_{4\pi} \Sigma_s(E'\!\to E,\boldsymbol{\Omega}'\!\cdot\boldsymbol{\Omega})\,\psi(\mathbf{r},\boldsymbol{\Omega}',E')\,d\Omega'\,dE' \\
& + \frac{\chi(E)}{4\pi k}\int_0^\infty \nu\Sigma_f\,\phi\,dE' \\
\end{aligned}
$$

**Dimana:**

- $\psi(\mathbf{r},\boldsymbol{\Omega},E)$: **fluks sudut**, laju lintasan neutron per satuan luas yang bergerak ke arah $\boldsymbol{\Omega}$ dengan energi $E$ di posisi $\mathbf{r}$.
- $\boldsymbol{\Omega}$: vektor satuan **arah gerak** neutron.
- $\boldsymbol{\Omega}\cdot\nabla\psi$: **suku streaming (kebocoran)**, neutron yang mengalir keluar-masuk elemen ruang.
- $\Sigma_t\,\psi$: **suku removal total**, neutron hilang karena tumbukan apa pun (serapan atau hamburan).
- $\Sigma_t$: **cross section makroskopik total**, peluang tumbukan per satuan panjang lintasan.
- $\Sigma_s(E'\!\to E,\boldsymbol{\Omega}'\!\cdot\boldsymbol{\Omega})$: **cross section hamburan** dari energi $E'$ ke $E$ dan dari arah $\boldsymbol{\Omega}'$ ke $\boldsymbol{\Omega}$, sumber neutron dari hamburan.
- $\frac{\chi(E)}{4\pi k}\int\nu\Sigma_f\phi\,dE'$: **sumber fisi** yang isotropik.
- $\chi(E)$: **spektrum fisi**, distribusi energi neutron hasil fisi.
- $\nu$: **jumlah neutron per fisi**.
- $\Sigma_f$: **cross section fisi**.
- $k$ ($=k_{\text{eff}}$): **faktor multiplikasi efektif**, rasio produksi terhadap kehilangan neutron; $k=1$ berarti kritis.

**Fluks skalar:**

$$
\phi(\mathbf{r},E)=\int_{4\pi}\psi(\mathbf{r},\boldsymbol{\Omega},E)\,d\Omega
$$

- $\phi$: **fluks neutron skalar**, total panjang lintasan neutron per volume per waktu dari semua arah. Ukuran "banyaknya neutron" yang menentukan laju reaksi.

**Bentuk multigrup** (setelah diskritisasi energi), untuk $g=1,\dots,G$:

$$
\begin{aligned}
& \boldsymbol{\Omega}\cdot\nabla\psi_g \\
& + \Sigma_{t,g}\,\psi_g = \sum_{g'=1}^{G}\int_{4\pi}\Sigma_{s,g'\to g}(\boldsymbol{\Omega}'\!\cdot\boldsymbol{\Omega})\,\psi_{g'}\,d\Omega' \\
& + \frac{\chi_g}{4\pi k}\sum_{g'=1}^{G}\nu\Sigma_{f,g'}\,\phi_{g'} \\
\end{aligned}
$$

dengan $\phi_g=\int_{4\pi}\psi_g\,d\Omega$.

- $g$: indeks **grup energi** (1 = tercepat/energi tertinggi).
- $\Sigma_{s,g'\to g}$: peluang hamburan dari grup $g'$ ke grup $g$ (**downscatter** jika $g>g'$, **upscatter** jika $g<g'$).
- $\chi_g$: fraksi neutron fisi yang lahir di grup $g$ ($\sum_g\chi_g=1$).

Fluks sudut $\psi$ bergantung pada tiga posisi $(x,y,z)$, dua arah $\boldsymbol{\Omega}$, energi, dan waktu (pada kasus transien).

**Kondisi batas vakum:**

$$
\psi_g(\mathbf{r}_s,\boldsymbol{\Omega})=0\quad\text{untuk }\boldsymbol{\Omega}\cdot\mathbf{n}<0
$$

- $\mathbf{r}_s$: titik di **permukaan** domain; $\mathbf{n}$: **normal keluar**. Artinya tidak ada neutron yang masuk dari luar.

#### Difusi sebagai pendekatan dari transport

Persamaan difusi adalah pendekatan dari transport dengan asumsi:

1. Fluks sudut hampir isotropik (hanya PN orde-1).
2. Hamburan hampir isotropik.
3. Medium tidak terlalu absorber kuat, dan jauh dari batas/sumber.
4. Hukum Fick: $\mathbf{J} = -D\nabla\phi$.

**Persamaan Difusi yang Dipecahkan**

$$
\begin{aligned}
& -\nabla\cdot D_g\nabla\phi_g \\
& + \Sigma_{r,g}\,\phi_g = \sum_{\substack{g'=1\\ g'\neq g}}^{G}\Sigma_{s,g'\to g}\,\phi_{g'} \\
& + \frac{\chi_g}{k}\sum_{g'=1}^{G}\nu\Sigma_{f,g'}\,\phi_{g'} \\
\end{aligned}
$$

- $-\nabla\cdot D_g\nabla\phi_g$: **kebocoran** neutron grup $g$ akibat difusi.
- $\Sigma_{r,g}=\Sigma_{t,g}-\Sigma_{s,g\to g}$: **cross section removal**, kehilangan neutron dari grup $g$ (serapan + hamburan keluar grup).
- $\Sigma_{s,g'\to g}\phi_{g'}$: **sumber hamburan antar-grup** (neutron yang pindah dari grup lain ke $g$).
- $\frac{\chi_g}{k}\sum\nu\Sigma_{f,g'}\phi_{g'}$: **sumber fisi** yang lahir di grup $g$.

**Perbedaan**

| Keluarga | Persamaan | Unknown | Dimensi ruang fase |
|---|---|---|---|
| **Transport** | Boltzmann (eksak) | $\psi(\mathbf{r},\boldsymbol{\Omega},E)$ | 6 (3 ruang + 2 sudut + 1 energi) |
| **Difusi** | P1 + hukum Fick (pendekatan) | $\phi(\mathbf{r},E)$ | 4 (3 ruang + 1 energi) |

```text
              Persamaan Transport Boltzmann
                         │
        ┌────────────────┴─────────────────┐
        │                                  │
  Diskritisasi sudut                  Reduksi momen sudut
  (SN, PN, MOC, CP)                   (P1 + Fick)
        │                                  │
   TRANSPORT                            DIFUSI
```

#### 1.4 Lapisan B: Diskritisasi

Tiga dimensi harus didiskretisasi:

| Dimensi | Penanganan |
|---|---|
| Energi | Hampir semua metode memakai **multigrup**. Bagian ini sama untuk semua metode di modul ini. |
| Sudut | Di sinilah **Sn** dan **Pn** berbeda jauh. Tidak ada di difusi. |
| Ruang | Di sinilah **MOC**, **CPM**, **nodal**, dan **CMFD** berbeda. |

##### B1. Diskritisasi energi (multigrup)

$$
\Sigma_{x,g} = \frac{\int_{E_g}^{E_{g-1}}\Sigma_x(E)\,\varphi(E)\,dE}{\int_{E_g}^{E_{g-1}}\varphi(E)\,dE}
$$

- $\Sigma_{x,g}$: cross section reaksi $x$ (serapan, fisi, hamburan) yang **dirata-rata** pada grup $g$.
- $\varphi(E)$: **spektrum bobot**, perkiraan bentuk fluks terhadap energi dalam grup. Hasil rata-rata mempertahankan **laju reaksi**.
- $[E_g,E_{g-1}]$: **batas energi** grup $g$.

| Metode | Keterangan |
|---|---|
| **Multigrup (MG)** | Energi dibagi grup, $\Sigma$ dirata-rata berbobot spektrum. Dipakai kode Anda (5 grup). |
| **Fine-group** | 70-300 grup, untuk lattice transport. |
| **Few-group / collapsing** | Kolaps dari fine-group (mis. 100+ grup) ke 2-8 grup untuk simulasi teras. |
| Continuous energy | Dipakai Monte Carlo, bukan deterministik. |

##### B2. Diskritisasi ruang

| Metode | Ciri | Dipakai di |
|---|---|---|
| **Finite Difference (FDM)** | Grid terstruktur, matriks sparse, sederhana | difusi klasik |
| **Finite Volume (FVM)** | Konservasi neutron per sel, cocok geometri tak seragam | Banyak kode difusi/transport |
| **Finite Element (FEM)** | Basis fungsi, geometri kompleks, orde tinggi | MOOSE/Griffin, DENOVO |
| **Nodal methods** (NEM, ANM) | Sel kasar (assembly), solusi analitik/polinom per node, koefisien kopling | Kode teras industri (PARCS, SIMULATE, DYN3D) |
| **Characteristics** | Integrasi sepanjang garis lintasan | MOC |
| **Collision probability Metode (CPM)** | Probabilitas tumbukan antar region | WIMS, APOLLO |
| Mesh kasar (CMFD) | Finite difference pada mesh kasar sebagai operator low-order untuk akselerasi | |


##### B3. Diskritisasi sudut (hanya untuk transport)

| Metode | Prinsip |
|---|---|
| **SN (Discrete Ordinates)** | Sudut dipilih pada sejumlah arah diskrit (quadrature) dengan bobot: $\psi(\boldsymbol{\Omega}) \to \psi_m$ pada $\boldsymbol{\Omega}_m$. Integral sudut menjadi jumlah berbobot: $\int \psi\,d\Omega \approx \sum_m w_m \psi_m$. |
| **PN (Spherical Harmonics)** | $\psi(\boldsymbol{\Omega})$ diekspansi dalam harmonik bola orde $N$: $\psi \approx \sum_{l=0}^{N}\sum_{m=-l}^{l} \phi_{lm}\,Y_{lm}(\boldsymbol{\Omega})$. Integral dihitung secara analitik lewat ortogonalitas. |
| **SPN (Simplified PN)** | Reduksi PN 1D menjadi sistem difusi-like terkopel (biaya lebih kecil dari PN penuh 3D). |
| **MOC (Method of Characteristics)** | Sudut didiskritisasi (quadrature seperti SN), tetapi ruang diselesaikan dengan integrasi **sepanjang lintasan (ray)** yang ditelusuri melalui geometri. |
|Pendekatan difusi ($P_1$ + hukum Fick) |	Hanya dua suku sudut: fluks skalar dan arus|

Jenis kuadratur sudut ($S_N$ dan MOC):
- Level-symmetric ($LQ_N$)
- Gauss-Legendre
- Gauss-Chebyshev (produk azimut dan polar)
- Equal-weight
- Tabuchi-Yamamoto (optimal untuk sudut polar pada MOC)
- Quadruple range (QR)

#### 1.5 Lapisan C: Penyelesaian Aljabar dan Eigen

##### C1. Masalah eigen dan pola umum

**Persamaan yang diselesaikan**

**Outer** menyelesaikan

$$
\mathbf{M}\boldsymbol{\phi}=\frac{1}{k}\,\mathbf{F}\boldsymbol{\phi}
$$

Di sini $\boldsymbol{\phi}$ dan $k$ **sama-sama tidak diketahui**, dan sumber fisi $\mathbf{F}\boldsymbol{\phi}$ bergantung pada fluks yang dicari. Karena itu dikerjakan dengan iterasi (power iteration):

$$
\mathbf{M}\boldsymbol{\phi}^{(n+1)}=\frac{1}{k^{(n)}}\mathbf{F}\boldsymbol{\phi}^{(n)},\qquad
k^{(n+1)}=k^{(n)}\frac{\mathbf{1}^T\mathbf{F}\boldsymbol{\phi}^{(n+1)}}{\mathbf{1}^T\mathbf{F}\boldsymbol{\phi}^{(n)}}
$$

**Inner** menyelesaikan satu langkah dari persamaan di atas, yaitu

$$
\mathbf{M}\,\boldsymbol{\phi}^{(n+1)}=\mathbf{b},\qquad \mathbf{b}=\frac{1}{k^{(n)}}\mathbf{F}\boldsymbol{\phi}^{(n)}
$$

Ruas kanan $\mathbf{b}$ **sudah diketahui** (dari iterasi outer sebelumnya), jadi ini hanya sistem linear biasa $\mathbf{A}\mathbf{x}=\mathbf{b}$. Tidak ada $k$ yang dicari di sini.

- **Outer** menyelesaikan **masalah eigenvalue** (mencari $k$ dan bentuk sumber fisi).
- **Inner** menyelesaikan **masalah sumber tetap** (mencari fluks, dengan sumber fisi dianggap sudah diketahui).

**Perbandingan**

| | Outer | Inner |
|---|---|---|
| Jenis masalah | Eigenvalue | Linear sumber tetap |
| Yang dicari | $k$ dan distribusi sumber fisi | Fluks $\boldsymbol{\phi}$ untuk sumber $\mathbf{b}$ tertentu |
| Yang dianggap tetap | Tidak ada, semuanya berubah | Sumber $\mathbf{b}$ (dan $k$) |
| Apa yang diperbarui tiap iterasi | $k$ dan sumber fisi | Fluks (atau sumber hamburan pada Sn/MOC) |
| Kriteria berhenti | Perubahan $k$ dan bentuk sumber fisi kecil | Residual $\|\mathbf{M}\boldsymbol{\phi}-\mathbf{b}\|$ kecil |
| Metode umum | Power iteration, Wielandt, Krylov, CMFD | LU, Jacobi, Gauss-Seidel, SOR, CG, GMRES, multigrid |
| Penghambat konvergensi | Dominance ratio $\rho=\lambda_2/\lambda_1\to1$ | Hamburan dominan, mesh halus |

##### C2. Iterasi outer (iterasi sumber fisi / metode pangkat)

Pada masalah eigenvalue ada **dua lapis ketidaktahuan**:

1. **Sumber fisi** tidak diketahui (bergantung pada fluks yang dicari).
2. Untuk sumber fisi tertentu, **persamaan fluks** masih harus diselesaikan (sistem persamaan besar).

Iterasi outer mencari **$k$ dan distribusi sumber fisi**:

$$
\mathbf{M}\,\boldsymbol{\phi}^{(n+1)}=\frac{1}{k^{(n)}}\,\mathbf{F}\,\boldsymbol{\phi}^{(n)},\qquad
k^{(n+1)}=k^{(n)}\,\frac{\mathbf{1}^{T}\mathbf{F}\,\boldsymbol{\phi}^{(n+1)}}{\mathbf{1}^{T}\mathbf{F}\,\boldsymbol{\phi}^{(n)}}
$$

Untuk transport, bentuknya ditulis dengan operator transport $\mathbf{L}$:

$$
\boldsymbol{\phi}^{(n+1)} = \frac{1}{k^{(n)}}\,\mathbf{L}^{-1}\mathbf{F}\,\boldsymbol{\phi}^{(n)},\qquad k^{(n+1)} = k^{(n)}\frac{\langle \mathbf{F}\boldsymbol{\phi}^{(n+1)}\rangle}{\langle \mathbf{F}\boldsymbol{\phi}^{(n)}\rangle}
$$

- $n$: **nomor iterasi**.
- $\mathbf{L}$: **operator transport** (streaming + removal $-$ hamburan).
- $\mathbf{F}$: **operator produksi fisi**.
- $\mathbf{1}^T\mathbf{F}\boldsymbol{\phi}$ atau $\langle\mathbf{F}\boldsymbol{\phi}\rangle$: **total laju produksi fisi** (penjumlahan/integral seluruh domain dan grup).
- Rasio produksi fisi antar-iterasi menyesuaikan $k$: produksi naik berarti $k$ naik.

Berhenti bila perubahan $k$ dan bentuk sumber fisi lebih kecil dari toleransi.

**Laju konvergensi:**

$$
\rho=\frac{\lambda_2}{\lambda_1}
$$

- $\rho$: **dominance ratio**, rasio eigenvalue kedua terhadap pertama. Konvergensi lambat jika $\rho\to1$ (teras besar, kopling longgar). Pada reaktor besar outer menjadi sangat lambat, sehingga perlu akselerasi.

| Metode outer | Ide | Catatan |
|---|---|---|
| **Power iteration / Source iteration** | Iterasi $\boldsymbol{\phi}^{(n+1)} = \mathbf{A}^{-1}\dfrac{1}{k^{(n)}}\mathbf{B}\boldsymbol{\phi}^{(n)}$ | Dipakai di kode Anda. Lambat jika $\rho$ mendekati 1. |
| **Shifted inverse power (Wielandt shift)** | Geser eigenvalue agar rasio dominansi lebih kecil | Mempercepat drastis. |
| **Chebyshev acceleration** | Ekstrapolasi polinomial atas iterasi power | Klasik di kode difusi lama. |
| **Krylov: Arnoldi / Lanczos / Krylov-Schur** | Proyeksi ke subruang Krylov | Via SLEPc, ARPACK (`scipy.sparse.linalg.eigs`). |
| **JFNK (Jacobian-Free Newton-Krylov)** | Newton nonlinier pada sistem eigen yang digabung | MOOSE/Griffin, modern. |
| **Coarse-mesh finite difference (CMFD)** | Akselerasi dengan sistem difusi kasar | Sering dipakai sebagai akselerator; tidak wajib untuk setiap metode. |
| **Diffusion Synthetic Acceleration (DSA)** | Pakai difusi untuk mempercepat iterasi hamburan SN | Mempercepat inner iteration SN. |

##### C3. Iterasi inner (penyelesaian fixed-source)

Untuk sumber fisi yang sudah ditetapkan, tinggal masalah sumber tetap per grup energi:

$$
\mathbf{A}_g\,\boldsymbol{\phi}_g=\mathbf{q}_g
$$

- **Pada difusi, Pn, CPM, nodal:** inner adalah penyelesaian sistem linear (Gauss–Seidel, SOR, Krylov, atau langsung). Bila ada *upscatter*, ada lapisan tengah (iterasi grup).
- **Pada Sn dan MOC:** inner adalah **source iteration**: tebak sumber hamburan, sapu, perbarui, ulangi. Lambat bila medium didominasi hamburan, sehingga dipercepat dengan DSA atau CMFD.

| Solver linear | Tipe | Catatan |
|---|---|---|
| **Direct (LU)** | `np.linalg.solve` | Boros memori $O(N^2)$ jika dense, hanya layak untuk grid kecil. |
| **Sparse direct** (`spsolve`, `splu`) | LU untuk matriks sparse | Jauh lebih efisien daripada dense untuk FDM. |
| **Jacobi** | Iteratif klasik, semua titik diperbarui dari iterasi lama | Paling sederhana dan mudah diparalelkan, tetapi paling lambat. |
| **Gauss-Seidel / SOR** | Iteratif klasik, mudah diimplementasikan | Dipakai di kode difusi lama; SOR adalah relaksasi. |
| **Krylov (CG, GMRES, BiCGSTAB) + preconditioner (ILU, AMG)** | Iteratif modern | Standar untuk skala besar. |
| **Multigrid** | Menggunakan hirarki grid | Sangat cepat untuk elliptik (difusi). |

##### C4. Struktur iterasi bersarang

```text
tebak phi^0 dan k^0
LOOP OUTER (n = 0, 1, 2, ...)              <- sumber fisi dan k
    S_fisi = (1/k^n) * chi * nuSigma_f * phi^n
    LOOP GRUP g = 1 ... G                   <- sapuan energi
        (ulangi bila ada upscatter)
        q_g = S_fisi,g + sumber hamburan dari grup lain
        LOOP INNER                          <- fixed-source satu grup
            selesaikan A_g phi_g = q_g      (difusi: solve linear;
                                             SN/MOC: sweep)
        sampai konvergen
    k^(n+1) = k^n * (sumber fisi baru / lama)
    cek toleransi k dan sumber fisi -> berhenti bila konvergen
```

Ringkasnya:

```text
Outer iteration (eigen: keff, sumber fisi)
 └─ Group sweep (grup energi: downscatter, upscatter)
     └─ Inner iteration (sumber hamburan dalam grup)
         └─ Sweep ruang-sudut (SN/MOC) ATAU solve linear (difusi)
```

### Dasar kekritisan dan neraca neutron

Faktor multiplikasi menyatakan perbandingan produksi neutron fisi satu generasi terhadap jumlah neutron pada generasi sebelumnya. Dalam neraca global, pada keadaan tunak tanpa sumber eksternal, produksi neutron fisi menyeimbangkan absorpsi dan kebocoran. Hamburan antarkeadaan energi tidak menghilangkan neutron dari neraca total, meskipun mengubah distribusi energi dan peluang neutron untuk kemudian diserap atau bocor.

Untuk sistem hingga, $k_{eff}$ memasukkan kebocoran. Secara neraca generasi dapat ditulis $k_{eff}=P/L$, dengan $P$ laju produksi neutron fisi dan $L$ laju kehilangan neutron melalui absorpsi serta kebocoran, untuk bentuk spektrum dan distribusi yang konsisten dengan mode eigenvalue. Pada sistem ideal tak hingga tanpa kebocoran, faktor multiplikasi disebut $k_{\infty}$; secara konseptual $k_{eff}=k_{\infty}P_{NL}$, dengan $P_{NL}$ peluang efektif neutron tidak bocor. Hubungan ini tidak berarti faktor kebocoran selalu berupa satu konstanta universal: kebocoran mengubah spektrum dan distribusi fluks, sehingga $k_{eff}$ harus diperoleh dari persamaan transport/difusi dengan geometri dan syarat batas yang sesuai.

Reaktivitas adalah ukuran jarak dari kekritisan:

$$\boxed{\rho=\frac{k_{eff}-1}{k_{eff}}=1-\frac{1}{k_{eff}}.}$$

Maka $k_{eff}<1$ memberi $\rho<0$ (subkritis), $k_{eff}=1$ memberi $\rho=0$ (kritis), dan $k_{eff}>1$ memberi $\rho>0$ (superkritis). Kritis berarti populasi neutron rata-rata tetap dari satu generasi ke generasi berikutnya pada model yang ditinjau; tidak otomatis berarti daya tertentu atau kondisi operasi aman. Pada reaktor riil, umpan balik temperatur, racun, kendali, dan sumber juga menentukan perilaku waktu.

#### Rumus enam faktor

Untuk interpretasi reaktor termal, rumus enam faktor memfaktorkan pendekatan $k_{eff}$ menjadi:

$$\boxed{k_{eff}\approx\eta\,f\,p\,\varepsilon\,P_{FNL}\,P_{TNL}=k_{\infty}P_{FNL}P_{TNL}},\qquad k_{\infty}=\eta f p\varepsilon.$$

Dengan:

- $\eta$: faktor reproduksi; neutron fisi yang dihasilkan per neutron yang diserap bahan bakar.
- $f$: faktor pemanfaatan termal; fraksi absorpsi neutron termal yang terjadi di bahan bakar.
- $p$: peluang lolos resonansi; peluang neutron yang melambat dari energi fisi mencapai energi termal tanpa tertangkap resonansi.
- $\varepsilon$: faktor fisi cepat; peningkatan produksi neutron akibat fisi yang terjadi sebelum neutron menjadi termal.
- $P_{FNL}$: peluang neutron cepat tidak bocor selama fase cepat/perlambatan.
- $P_{TNL}$: peluang neutron termal tidak bocor sebelum diserap.
- $k_{\infty}$: faktor multiplikasi tanpa kebocoran; $k_{eff}$: faktor multiplikasi sistem hingga.

Faktorisasi ini paling berguna sebagai neraca konseptual untuk reaktor termal dengan pemisahan fase cepat, perlambatan/resonansi, dan termal yang bermakna. Definisi operasional faktor dapat berbeda menurut konvensi analisis, dan faktor-faktornya tidak selalu independen karena perubahan spektrum, heterogenitas, temperatur, maupun kebocoran dapat mengubah beberapa faktor sekaligus. Untuk reaktor cepat atau geometri/komposisi yang tidak sesuai asumsi, gunakan neraca transport/eigenvalue langsung; jangan menganggap enam faktor sebagai identitas eksak universal.

#### Sumber neutron eksternal

Dengan sumber eksternal, persamaan neraca waktu menyertakan sumber tersebut:

$$\frac{dN_n}{dt}=P_f+S_{ext}-A-L,$$

dengan $N_n$ populasi neutron, $P_f$ produksi fisi, $S_{ext}$ laju sumber eksternal, $A$ kehilangan absorpsi, dan $L$ kebocoran. Sumber dapat berupa sumber startup, neutron spontan, atau fotoneutron. Ia dapat menghasilkan fluks terukur dan penggandaan neutron pada sistem subkritis, tetapi tidak mengubah definisi kritisitas eigenvalue: sistem tetap subkritis bila $k_{eff}<1$. Pada model generasi ideal, satu neutron sumber memicu penggandaan generasi dengan faktor $1+k+k^2+\cdots=1/(1-k)$ untuk $k<1$; respons detektor aktual juga bergantung lokasi, spektrum, geometri, dan efisiensi deteksi.

### Kinetika neutron dan neutron tunda

Persamaan eigenvalue tunak menentukan bentuk fluks dan $k_{eff}$, tetapi tidak langsung memberi evolusi daya terhadap waktu. Kinetika titik mengaproksimasi bentuk fluks ruang tetap, sementara amplitudo neutron dan populasi prekursor berubah terhadap waktu. Ini adalah model terintegral, bukan pengganti kinetika ruang ketika distribusi daya atau bentuk fluks berubah kuat.

#### Neutron prompt dan neutron tunda

Sebagian besar neutron fisi lahir prompt, hampir seketika terhadap skala waktu operasi reaktor. Sebagian kecil lahir dari peluruhan produk fisi yang disebut prekursor neutron tunda; waktu peluruhannya jauh lebih panjang dan dikelompokkan menjadi $I$ grup dengan konstanta peluruhan $\lambda_i$. Fraksi neutron tunda efektif total ialah $\beta_{eff}=\sum_{i=1}^{I}\beta_i$. Walaupun jumlahnya kecil, neutron tunda memperpanjang respons dinamik dan memungkinkan kendali pada skala waktu lebih lambat daripada dinamika prompt saja.

#### Persamaan kinetika titik

Untuk reaktivitas $\rho(t)$ dan sumber eksternal $S_n(t)$, bentuk kinetika titik multigrup adalah:

$$\boxed{\frac{dn}{dt}=\frac{\rho(t)-\beta_{eff}}{\Lambda}n+\sum_{i=1}^{I}\lambda_i C_i+S_n(t),}$$
$$\boxed{\frac{dC_i}{dt}=\frac{\beta_i}{\Lambda}n-\lambda_i C_i,\qquad i=1,\ldots,I.}$$

Dengan:

- $n(t)$: amplitudo populasi neutron atau besaran proporsional terhadap daya; satuan harus konsisten dengan normalisasi sumber.
- $C_i(t)$: populasi/variabel konsentrasi prekursor grup $i$ dengan normalisasi yang konsisten terhadap $n$.
- $\rho$: reaktivitas; $\beta_i$: fraksi neutron tunda efektif pada grup $i$; $\beta_{eff}=\sum_i\beta_i$.
- $\Lambda$: waktu generasi neutron prompt efektif, dalam sekon.
- $\lambda_i$: konstanta peluruhan prekursor grup $i$, dalam $\mathrm{s}^{-1}$.
- $S_n(t)$: sumber neutron eksternal pada persamaan amplitudo; satuannya sama dengan $dn/dt$.

Persamaan pertama menyatakan perubahan amplitudo akibat produksi prompt bersih, neutron tunda yang dilepas prekursor, dan sumber eksternal. Persamaan kedua menyatakan prekursor terbentuk dari fisi dan berkurang melalui peluruhan. Untuk kondisi awal kritis tanpa sumber, $\rho=0$ dan $n,C_i$ berada pada kesetimbangan yang membuat $dn/dt=dC_i/dt=0$.

#### Persamaan inhour dan periode reaktor

Untuk sistem tanpa sumber eksternal, parameter tetap, dan solusi eksponensial $n(t)\propto e^{\omega t}$, periode reaktor didefinisikan $T=1/\omega$ untuk mode dengan $\omega\ne0$. Substitusi bentuk eksponensial ke persamaan prekursor memberi $C_i=\beta_i n/[\Lambda(\omega+\lambda_i)]$. Menggantinya ke persamaan neutron menghasilkan persamaan inhour:

$$\boxed{\rho=\omega\Lambda+\sum_{i=1}^{I}\frac{\beta_i\omega}{\omega+\lambda_i}=\frac{\Lambda}{T}+\sum_{i=1}^{I}\frac{\beta_i}{1+\lambda_iT}.}$$

Untuk setiap reaktivitas, persamaan ini menentukan laju pertumbuhan/peluruhan mode kinetika (dengan pemilihan akar yang sesuai kondisi). $T>0$ berarti amplitudo tumbuh; $T<0$ berarti meluruh. Jika $\omega=0$, periode tak hingga dan keadaan konstan. Untuk langkah prompt-superkritis dengan $\rho>\beta_{eff}$, perkiraan prompt tanpa kontribusi prekursor memiliki periode prompt $T_p\approx\Lambda/(\rho-\beta_{eff})$; ini bukan periode umum ketika prekursor berperan.

#### Asumsi dan batas penerapan

Model titik mengasumsikan bentuk fluks ruang dan spektrum yang dipakai dalam parameter kinetika tidak berubah secara signifikan, atau perubahan tersebut telah diringkas dalam parameter efektif seperti $\Lambda$ dan $\beta_i$. Reaktivitas dapat berubah terhadap waktu, tetapi persamaan di atas tidak dengan sendirinya menghitung umpan balik Doppler, temperatur moderator, racun fisi, atau gerak batang kendali; model-model tersebut perlu dikopel untuk memperoleh $\rho(t)$. Bila redistribusi daya ruang penting, gunakan kinetika difusi/transport bergantung waktu atau pendekatan kinetika kuasi-statik.

##  <center> <b> Metode Diskritisasi  </b></center>

### **B1. Diskritisasi Energi**

### **Pendahuluan Diskritisasi Energi**

**Daerah energi neutron**

Pembagian berikut bersifat praktis; batas grup dipilih sesuai reaktor dan library, bukan batas fisika yang tegas.

| Daerah | Rentang ilustratif | Ciri |
|---|---:|---|
| **Fast (cepat)** | kira-kira $0.1\,\mathrm{MeV}$ hingga energi neutron fisi (umumnya beberapa sampai sekitar $10\,\mathrm{MeV}$) | Neutron fisi yang belum banyak melambat; fisi cepat dapat berperan. |
| **Epithermal (epitermal)** | kira-kira $0.5\,\mathrm{eV}$?$0.1\,\mathrm{MeV}$ | Neutron sedang melambat; banyak resonansi tangkapan, terutama pada nuklida fertil seperti $^{238}\mathrm{U}$. |
| **Thermal (termal)** | di bawah kira-kira $0.5\,\mathrm{eV}$ | Neutron mendekati kesetimbangan dengan moderator; hamburan termal dan upscatter dapat penting. |

Batas termal $0.5\,\mathrm{eV}$ adalah konvensi yang sering dipakai (antara lain terkait cut-off kadmium); batas lain mungkin dipilih. Resonansi adalah puncak pada energi tertentu, terutama di epitermal, bukan pita dengan batas tajam. Temperatur memperlebar puncak melalui Doppler broadening.

**Persamaan energi kontinu**

Persamaan transport tunak kontinu energi:

$$
\boldsymbol{\Omega}\cdot\nabla\psi(\mathbf r,\boldsymbol{\Omega},E)+\Sigma_t(\mathbf r,E)\psi(\mathbf r,\boldsymbol{\Omega},E)=\int_0^\infty\!\int_{4\pi}\Sigma_s(\mathbf r;E',\boldsymbol{\Omega}'\!\to E,\boldsymbol{\Omega})\psi(\mathbf r,\boldsymbol{\Omega}',E')\,d\Omega'\,dE' $$
$$+\frac{\chi(\mathbf r,E)}{4\pi k_{eff}}\int_0^\infty\nu\Sigma_f(\mathbf r,E')\phi(\mathbf r,E')\,dE' $$

Fluks skalar per energi adalah $\phi(\mathbf r,E)=\int_{4\pi}\psi(\mathbf r,\boldsymbol{\Omega},E)\,d\Omega$. Persamaan memuat kebocoran, kehilangan total, hamburan yang mengubah energi/arah, serta produksi fisi. Untuk masalah sumber tetap, sumber fisi bisa dianggap telah diketahui.

Bagi energi dengan batas $E_0>E_1>\cdots>E_G$; grup $g$ adalah $[E_g,E_{g-1}]$, dan $g=1$ menyatakan energi tertinggi. Fluks grup:

$$
\phi_g(\mathbf r)=\int_{E_g}^{E_{g-1}}\phi(\mathbf r,E)\,dE
$$

Penampang grup untuk reaksi $x$ dirata-rata berbobot fluks agar laju reaksi terjaga:

$$
\boxed{\Sigma_{x,g}=\frac{\int_{E_g}^{E_{g-1}}\Sigma_x(E)\phi(E)\,dE}{\int_{E_g}^{E_{g-1}}\phi(E)\,dE}}
$$

Di resonansi, $\Sigma_x(E)$ dan $\phi(E)$ berubah tajam dan saling berkorelasi. Absorpsi mengurangi fluks di puncak resonansi (*self-shielding*), sehingga penampang grup efektif bergantung pada suhu, komposisi, geometri, dan spektrum. Narrow Resonance, Intermediate Resonance, dan Bondarenko adalah pendekatan untuk membentuk konstanta grup/self-shielded; bukan persamaan transport yang berbeda.

**Arti simbol:** $\mathbf r$ posisi; $\boldsymbol\Omega$ arah neutron; $E,E'$ energi; $\psi$ fluks sudut per energi; $\phi$ fluks skalar per energi; $\Sigma_t,\Sigma_s,\Sigma_f$ penampang total, hamburan, dan fisi; $\nu$ jumlah neutron per fisi; $\chi$ spektrum fisi ternormalisasi; $k_{eff}$ faktor multiplikasi efektif; $g,G$ indeks dan jumlah grup; $\Sigma_{x,g}$ penampang grup untuk reaksi $x$.

###  <center> <b> Narrow Resonance approximation  </b></center>

#### Asumsi dan bentuk fluks

NR menganggap resonansi sempit dibanding perubahan energi per tumbukan moderator, resonansi terisolasi, dan sumber perlambatan hampir konstan di dalam resonansi. Di sekitar nuklida resonansi $r$, fluks didekati berbanding terbalik dengan penampang total:

$$
\phi(E)\propto\frac{1}{\Sigma_b+N_r\sigma_{t,r}(E,T)}=\frac{1/N_r}{\sigma_0+\sigma_{t,r}(E,T)},\qquad \sigma_0=\frac{\Sigma_b}{N_r}
$$

$\Sigma_b$ ialah background makroskopik dari bahan selain resonansi target; $N_r$ densitas atom target; $\sigma_0$ background mikroskopik/dilution; $T$ suhu. Identitasnya memakai $\Sigma_r=N_r\sigma_r$.

#### Penurunan penampang efektif grup

Dari definisi yang menjaga laju reaksi:

$$
\sigma_{x,g}^{eff}=\frac{\int_{E_g}^{E_{g-1}}\sigma_{x,r}(E,T)\phi(E)\,dE}{\int_{E_g}^{E_{g-1}}\phi(E)\,dE}
$$

Substitusi fluks NR; faktor konstan saling menghapus:

$$
\boxed{
\sigma_{x,g}^{NR}(T,\sigma_0)=
\frac{\displaystyle\int_{E_g}^{E_{g-1}}\frac{\sigma_{x,r}(E,T)}{\sigma_0+\sigma_{t,r}(E,T)}\,dE}
{\displaystyle\int_{E_g}^{E_{g-1}}\frac{1}{\sigma_0+\sigma_{t,r}(E,T)}\,dE}
}
$$

Numerator mewakili laju reaksi relatif, denominator fluks relatif. Grup epitermal biasanya perlu dibagi menjadi interval energi halus agar puncak resonansi terintegrasi dengan baik.

#### Matriks tiga grup (fast?epitermal?thermal)

Penampang makroskopik tiap grup dibentuk dari penampang mikroskopik efektif, misalnya $\Sigma_{x,g}=\sum_r N_r\sigma_{x,r,g}$; removal grup didefinisikan $\Sigma_{rem,g}=\Sigma_{t,g}-\Sigma_{s,g\to g}$. 
Untuk satu sel homogen, abaikan kebocoran pada contoh. Indeks grup: $F$ fast, $E$ epitermal, $T$ termal. Elemen $\Sigma_{s,g'\to g}$ adalah hamburan dari grup asal kolom $g'$ ke grup tujuan baris $g$. Dengan upscatter termal-ke-epitermal dipertahankan:

$$
\mathbf A^{NR}=\begin{bmatrix}
\Sigma_{rem,F}^{NR}&0&0\\
-\Sigma_{s,F\to E}^{NR}&\Sigma_{rem,E}^{NR}&-\Sigma_{s,T\to E}^{NR}\\
-\Sigma_{s,F\to T}^{NR}&-\Sigma_{s,E\to T}^{NR}&\Sigma_{rem,T}^{NR}
\end{bmatrix},\qquad
\mathbf A^{NR}\begin{bmatrix}\phi_F\\\phi_E\\\phi_T\end{bmatrix}=\frac1{k_{eff}}\mathbf F^{NR}\begin{bmatrix}\phi_F\\\phi_E\\\phi_T\end{bmatrix}
$$

$$
\mathbf F^{NR}=\begin{bmatrix}
\chi_F\nu\Sigma_{f,F}^{NR}&\chi_F\nu\Sigma_{f,E}^{NR}&\chi_F\nu\Sigma_{f,T}^{NR}\\
\chi_E\nu\Sigma_{f,F}^{NR}&\chi_E\nu\Sigma_{f,E}^{NR}&\chi_E\nu\Sigma_{f,T}^{NR}\\
\chi_T\nu\Sigma_{f,F}^{NR}&\chi_T\nu\Sigma_{f,E}^{NR}&\chi_T\nu\Sigma_{f,T}^{NR}
\end{bmatrix}
$$

Jika upscatter termal-ke-epitermal diabaikan, $\Sigma_{s,T\to E}=0$. Untuk banyak sel, operator kebocoran grup ditambahkan ke diagonal. Struktur matriks sama untuk ketiga grup; NR terutama mengubah nilai efektif resonansi di grup epitermal.

**Kelebihan/keterbatasan:** sederhana dan murah untuk resonansi sempit-terisolasi; kurang akurat untuk resonansi tumpang tindih/lebar, interferensi, heterogenitas kuat, atau kontribusi sumber hamburan resonansi yang signifikan.

**Arti simbol:** $r$ nuklida resonansi; $x$ jenis reaksi; $\sigma_x,\sigma_t$ penampang mikroskopik reaksi dan total; $\Sigma_b$ background makroskopik; $N_r$ densitas atom; $\sigma_0$ dilution; $\sigma_{r,g}$ removal grup; $\Sigma_s$ penampang hamburan makroskopik; $\chi_g$ fraksi spektrum fisi; $\mathbf A$ operator kehilangan/transfer; $\mathbf F$ operator fisi; $\phi_g$ fluks grup.

###  <center> <b> Intermediate Resonance approximation </b></center>

#### Ide dan penurunan pendekatan

IR memperbaiki asumsi NR bahwa sumber perlambatan konstan sepenuhnya: sebagian hamburan resonansi diperlakukan sebagai sumber neutron lokal di sekitar resonansi. Bentuk penutupan pedagogis untuk nuklida $r$:

$$
\phi(E)=\frac{q_b(E)+\lambda_rN_r\sigma_{s,r}(E,T)\phi(E)}{\Sigma_b+N_r\sigma_{t,r}(E,T)}
$$

$q_b(E)$ adalah sumber latar yang berubah lambat di interval resonansi; $\lambda_r$ parameter IR yang mengatur kontribusi efektif hamburan resonansi sebagai sumber lokal. Susun ulang dan bagi dengan $N_r$:

$$
\phi(E)=\frac{q_b(E)/N_r}{\sigma_0+\sigma_{t,r}(E,T)-\lambda_r\sigma_{s,r}(E,T)},\qquad \sigma_0=\frac{\Sigma_b}{N_r}
$$

Karena $\sigma_t=\sigma_a+\sigma_s$, denominator sama dengan $\sigma_0+\sigma_a+(1-\lambda_r)\sigma_s$. Saat $\lambda_r=0$, bentuk ini kembali ke NR; kontribusi hamburan sumber makin diperhitungkan jika $\lambda_r$ meningkat. Definisi dan pemilihan parameter IR dapat berbeda antar formulasi/kode?persamaan ini menyajikan ide penutupan, bukan konvensi universal.

Anggap $q_b$ hampir konstan dalam grup; faktor tersebut hilang dalam rasio laju reaksi:

$$
\boxed{
\sigma_{x,g}^{IR}=
\frac{\displaystyle\int_{E_g}^{E_{g-1}}\frac{\sigma_{x,r}(E,T)}{\sigma_0+\sigma_{t,r}(E,T)-\lambda_r\sigma_{s,r}(E,T)}\,dE}
{\displaystyle\int_{E_g}^{E_{g-1}}\frac{1}{\sigma_0+\sigma_{t,r}(E,T)-\lambda_r\sigma_{s,r}(E,T)}\,dE}
}
$$

#### Matriks tiga grup

Penampang makroskopik tiap grup dibentuk dari penampang mikroskopik efektif, misalnya $\Sigma_{x,g}=\sum_r N_r\sigma_{x,r,g}$; removal grup didefinisikan $\Sigma_{rem,g}=\Sigma_{t,g}-\Sigma_{s,g\to g}$. 
Urutan grup $F,E,T$ dan konvensi baris=grup tujuan, kolom=grup asal sama seperti NR. Ganti konstanta grup dengan hasil IR:

$$
\mathbf A^{IR}=\begin{bmatrix}
\Sigma_{rem,F}^{IR}&0&0\\
-\Sigma_{s,F\to E}^{IR}&\Sigma_{rem,E}^{IR}&-\Sigma_{s,T\to E}^{IR}\\
-\Sigma_{s,F\to T}^{IR}&-\Sigma_{s,E\to T}^{IR}&\Sigma_{rem,T}^{IR}
\end{bmatrix},\qquad \mathbf A^{IR}\boldsymbol\phi=\frac1{k_{eff}}\mathbf F^{IR}\boldsymbol\phi,
\quad \boldsymbol\phi=\begin{bmatrix}\phi_F\\\phi_E\\\phi_T\end{bmatrix}
$$

$$
\mathbf F^{IR}=\begin{bmatrix}
\chi_F\nu\Sigma_{f,F}^{IR}&\chi_F\nu\Sigma_{f,E}^{IR}&\chi_F\nu\Sigma_{f,T}^{IR}\\
\chi_E\nu\Sigma_{f,F}^{IR}&\chi_E\nu\Sigma_{f,E}^{IR}&\chi_E\nu\Sigma_{f,T}^{IR}\\
\chi_T\nu\Sigma_{f,F}^{IR}&\chi_T\nu\Sigma_{f,E}^{IR}&\chi_T\nu\Sigma_{f,T}^{IR}
\end{bmatrix}
$$

Jika upscatter termal-ke-epitermal ditiadakan, elemen $\Sigma_{s,T\to E}=0$. Untuk masalah ruang-diskrit tambahkan operator kebocoran $\mathbf L_g$ ke diagonal. IR mengubah effective cross sections (terutama epitermal), bukan struktur neraca energi.

**Kegunaan:** pendekatan antara NR sederhana dan pemrosesan resonansi lebih rinci. Hasilnya bergantung pada $\lambda_r$, background, dan model geometri; parameter tidak boleh dianggap universal.

**Arti simbol:** $q_b$ sumber perlambatan/latar; $\lambda_r$ parameter IR; $\sigma_s,\sigma_a,\sigma_t$ penampang mikroskopik hamburan, absorpsi, total; simbol lain mengikuti definisi bagian NR.

###  <center> <b> Advanced Bondarenko dan self-shielding resonansi </b></center>

#### Tujuan dan batas istilah

Metode Bondarenko merepresentasikan *resonance self-shielding* melalui penampang grup atau faktor self-shielding yang bergantung pada temperatur dan penampang latar (*background/dilution cross section*). Istilah **Advanced Bondarenko** bukan satu algoritma universal. Implementasi dapat menambahkan interpolasi tabel, perlakuan resonansi saling tumpang tindih, koreksi heterogen, atau subgroup/probability table; detailnya bergantung pada library dan kode.

Self-shielding terjadi karena absorpsi resonansi menekan fluks pada energi puncak resonansi. Maka penampang grup efektif bergantung bukan hanya pada nuklida target, tetapi juga spektrum, temperatur, komposisi, dan representasi geometri.

#### Penampang latar dan pengenceran

Untuk nuklida target resonansi $r$ dengan densitas atom $N_r$, didefinisikan penampang latar makroskopik ekuivalen $\Sigma_{b,r}$ dan parameter mikroskopik:

$$
\boxed{\sigma_{0,r}=\frac{\Sigma_{b,r}}{N_r}.}
$$

Pendekatan sederhana dapat menulis $\Sigma_{b,r}\approx\sum_{j\ne r}N_j\sigma_{p,j}+\Sigma_{e,r}$, dengan kontribusi hamburan potensial nuklida lain dan koreksi ekuivalen kebocoran/heterogen. Ini adalah model penutupan, bukan identitas eksak; definisinya harus mengikuti metode/library. Secara kualitatif, $\sigma_0$ besar berarti resonansi lebih diencerkan, sedangkan $\sigma_0$ kecil memberi self-shielding lebih kuat.

#### Tabel penampang dan faktor self-shielding

Library biasanya menyimpan penampang grup pada beberapa temperatur dan nilai $\sigma_0$, atau faktor relatif terhadap penampang pada pengenceran tak hingga:

$$
\boxed{f_{x,r,g}(T,\sigma_0)=\frac{\sigma_{x,r,g}(T,\sigma_0)}{\sigma_{x,r,g}^{\infty}(T)},\qquad \sigma_{x,r,g}^{sh}(T,\sigma_0)=f_{x,r,g}(T,\sigma_0)\,\sigma_{x,r,g}^{\infty}(T).}
$$

$\sigma^{\infty}$ adalah nilai *infinite-dilution* menurut konvensi library; $f$ mengoreksinya untuk self-shielding. Penampang makroskopik campuran kemudian dirakit sebagai $\Sigma_{x,g}=\sum_jN_j\sigma_{x,j,g}^{sh}$ dengan koreksi yang sesuai pada masing-masing nuklida. Interpolasi terhadap $T$ dan $\sigma_0$ harus mengikuti skema tabel; interpolasi linier tidak selalu sesuai, dan ekstrapolasi di luar domain data perlu dihindari atau dibenarkan secara khusus.

#### Dasar spektral dan pendekatan subgroup

Definisi penampang grup yang menjaga laju reaksi ialah:

$$
\sigma_{x,r,g}^{eff}=\frac{\int_{E_g}^{E_{g-1}}\sigma_{x,r}(E,T)\phi(E)\,dE}{\int_{E_g}^{E_{g-1}}\phi(E)\,dE}
$$

Model idealisasi Bondarenko memakai $\phi(E)\propto[\sigma_0+\sigma_{t,r}(E,T)]^{-1}$:

$$
\sigma_{x,g}^{B}=\frac{\int_{E_g}^{E_{g-1}}\dfrac{\sigma_{x,r}(E,T)}{\sigma_0+\sigma_{t,r}(E,T)}\,dE}{\int_{E_g}^{E_{g-1}}\dfrac{1}{\sigma_0+\sigma_{t,r}(E,T)}\,dE}
$$

Integral ini menjelaskan pembobotan spektral pada model ideal. Dalam pemrosesan praktis, nilai tersebut dapat direpresentasikan oleh tabel Bondarenko atau faktor self-shielding; spektrum dan latar harus konsisten dengan asumsi tabel.

Subgroup merepresentasikan variasi penampang di dalam grup melalui probabilitas $p_{g,m}$ dan penampang karakteristik $\sigma_{x,g,m},\sigma_{t,g,m}$. Bentuk pendekatan bobot fluks:

$$
w_{g,m}=\frac{p_{g,m}}{\sigma_0+\sigma_{t,g,m}(T)},\qquad \boxed{\sigma_{x,g}^{sub}\approx\frac{\sum_mw_{g,m}\sigma_{x,g,m}}{\sum_mw_{g,m}}}
$$

Parameter subgroup harus konsisten dengan representasi data yang digunakan. Subgroup/probability table dapat mempertahankan variasi dan korelasi penampang yang hilang pada satu nilai rata-rata, tetapi bukan fitur wajib setiap implementasi Advanced Bondarenko. Rumus di atas menjelaskan prinsip pembobotan, bukan satu resep universal.

#### Contoh penerapan pada matriks tiga grup

Self-shielding mengubah konstanta grup, bukan struktur dasar neraca. Gunakan urutan grup $F,E,T$ (fast, epitermal, thermal), kolom=grup asal dan baris=grup tujuan. Untuk menjaga matriks tetap terbaca, definisikan:

$$
R_g=\Sigma_{rem,g}^{sh},\qquad
T_{g'\to g}=\Sigma_{s,g'\to g}^{sh},\qquad
P_g=\nu\Sigma_{f,g}^{sh}.
$$

Elemen $\mathbf L_g$ adalah operator kebocoran setelah diskritisasi ruang:

$$
\mathbf A^{sh}=\begin{bmatrix}
\mathbf L_F+R_F & 0 & 0 \\
-T_{F\to E} & \mathbf L_E+R_E & -T_{T\to E} \\
-T_{F\to T} & -T_{E\to T} & \mathbf L_T+R_T
\end{bmatrix}
$$

$$
\mathbf F^{sh}=\begin{bmatrix}
\chi_F P_F & \chi_F P_E & \chi_F P_T \\
\chi_E P_F & \chi_E P_E & \chi_E P_T \\
\chi_T P_F & \chi_T P_E & \chi_T P_T
\end{bmatrix}
$$

Persamaan eigen dan vektor fluks ditulis terpisah agar tidak melebar:

$$
\mathbf A^{sh}\boldsymbol\phi=\frac{1}{k_{eff}}\mathbf F^{sh}\boldsymbol\phi,
\qquad
\boldsymbol\phi=\begin{bmatrix}\phi_F\\\phi_E\\\phi_T\end{bmatrix}.
$$

$$\sum_g\chi_g=1.$$

Entri nol pada baris $F$ mengasumsikan tidak ada upscatter ke grup fast; transfer $T\to E$ dipertahankan untuk menunjukkan kemungkinan upscatter termal. Untuk satu sel tanpa kebocoran, $\mathbf L_g=0$. Bentuk matriks fisi di atas mengasumsikan spektrum fisi tidak bergantung grup asal; jika bergantung, gunakan $F_{g,g'}=\chi_{g'\to g}\nu\Sigma_{f,g'}^{sh}$.

#### Alur pemrosesan dan pemeriksaan

1. Tetapkan library, batas grup, temperatur, komposisi, dan model geometri.
2. Proses temperatur data resonansi (Doppler broadening) dan hamburan termal bila relevan.
3. Hitung $\sigma_0$ sesuai model; perlakukan heterogenitas/interferensi hanya dengan model yang didukung.
4. Ambil atau hitung penampang/faktor self-shielding tiap nuklida, grup, suhu, dan kondisi latar; interpolasikan dalam domain tabel.
5. Rakit penampang makroskopik, transfer hamburan, dan produksi fisi multigrup; terapkan subgroup bila memang bagian dari metode.
6. Verifikasi limit pengenceran, tren terhadap temperatur/komposisi, laju reaksi, konvergensi subgroup, dan hasil terhadap referensi energi halus atau benchmark yang sesuai.

##### Dengan:

- $r,j$: indeks nuklida target dan nuklida campuran; $x$: kanal reaksi; $g$: grup energi.
- $N_r,N_j$: densitas atom; $T$: temperatur; $E_g,E_{g-1}$: batas energi grup.
- $\Sigma_{b,r}$: penampang latar makroskopik ekuivalen; $\sigma_{0,r}$: parameter pengenceran mikroskopik.
- $\sigma_{p,j}$: penampang hamburan potensial; $\Sigma_{e,r}$: koreksi ekuivalen menurut model.
- $\sigma_{x,r,g}^{\infty}$: penampang *infinite-dilution*; $f_{x,r,g}$: faktor self-shielding; $\sigma_{x,r,g}^{sh}$: penampang terkoreksi.
- $p_{g,m}$: probabilitas subgroup; $w_{g,m}$: bobot fluks subgroup; $\phi(E)$: spektrum fluks skalar.
- $\Sigma_{s,g'\to g}^{sh}$: transfer hamburan dari grup asal ke tujuan; $\Sigma_{rem,g}^{sh}$: penampang removal.
- $\mathbf L_g$: operator kebocoran; $\chi_g$: fraksi spektrum fisi; $\nu\Sigma_{f,g}^{sh}$: produksi fisi; $k_{eff}$: faktor multiplikasi efektif.
- Superskrip $sh$, $sub$, dan $\infty$: self-shielded, subgroup-effective, dan infinite-dilution; notasi dapat berbeda antar-library/kode.

#### Pembentukan konstanta grup dan penampang lintang multigrup

Perlakuan resonansi sebelumnya membentuk data efektif dengan mempertimbangkan perubahan spektrum lokal. Selanjutnya data energi kontinu dirata-ratakan dan, bila perlu, dikondensasikan agar dapat digunakan solver multigrup. Konstanta grup harus mempertahankan laju reaksi untuk spektrum acuan; nilainya bergantung pada spektrum, temperatur, komposisi, serta region material.

##### Fluks grup dan konstanta reaksi

Ambil batas energi menurun $E_0>E_1>\cdots>E_G$; grup $g$ mencakup $E_g\le E<E_{g-1}$. Fluks skalar terintegrasi pada grup:

$$\phi_g(\mathbf r)=\int_{E_g}^{E_{g-1}}\phi(\mathbf r,E)\,dE,\qquad \phi(E)=\int_{4\pi}\psi(\mathbf r,\boldsymbol\Omega,E)\,d\Omega.$$

Rata-rata mikroskopik berbobot fluks acuan diperoleh dengan menyamakan laju reaksi kontinu dan grup:

$$\boxed{\sigma_{x,i,g}=\frac{\int_{E_g}^{E_{g-1}}\sigma_{x,i}(E,T)\phi_{ref}(E)\,dE}{\int_{E_g}^{E_{g-1}}\phi_{ref}(E)\,dE}},\qquad R_{x,i,g}=N_i\sigma_{x,i,g}\phi_g.$$

Untuk campuran nuklida, $\Sigma_{x,g}=\sum_iN_i\sigma_{x,i,g}$ dan $R_{x,g}=\Sigma_{x,g}\phi_g$. $\phi_{ref}$ adalah spektrum pembobot, umumnya hasil solusi transport/self-shielding; bukan nilai universal. Rata-rata ini menjaga laju reaksi untuk spektrum tersebut, tetapi tidak otomatis akurat bila spektrum aktual berubah besar. Konstanta difusi/transport juga perlu perlakuan arus/kebocoran yang konsisten, sehingga tidak selalu dapat dibentuk dengan rata-rata reaksi sederhana.

##### Transfer hamburan dan matriks multigrup

Gunakan konvensi kolom=grup asal $g'$, baris=grup tujuan $g$. Untuk hamburan isotropik, koefisien transfer didefinisikan agar sumber hamburan terintegrasi terjaga:

$$\boxed{\Sigma_{s,g'\to g}=\frac{\int_{E_{g'}}^{E_{g'-1}}\phi_{ref}(E')\left[\int_{E_g}^{E_{g-1}}\Sigma_s(E'\to E)\,dE\right]dE'}{\int_{E_{g'}}^{E_{g'-1}}\phi_{ref}(E')\,dE'}}.$$

Matriks $S_{g,g'}=\Sigma_{s,g'\to g}$ mengandung hamburan dalam grup dan transfer antargup. Untuk urutan baris/kolom $F,E,T$ (fast, epitermal, thermal):

$$\mathbf S=\begin{bmatrix}S_{F,F}&S_{F,E}&S_{F,T}\\S_{E,F}&S_{E,E}&S_{E,T}\\S_{T,F}&S_{T,E}&S_{T,T}\end{bmatrix},\qquad S_{g,g'}=\Sigma_{s,g'\to g},\qquad (\mathbf S\boldsymbol\phi)_g=\sum_{g'}\Sigma_{s,g'\to g}\phi_{g'}.$$

Tanpa upscatter, hamburan hanya berpindah menuju energi lebih rendah; pada energi termal upscatter dapat membuat matriks tidak segitiga. Jika anisotropi penting, gunakan momen sudut dan konstanta transfer per orde. Kehilangan bersih grup memakai removal $\Sigma_{rem,g}=\Sigma_{t,g}-\Sigma_{s,g\to g}$; hamburan dalam grup tetap dimasukkan sebagai sumber dan tidak boleh dihitung ganda.

##### Spektrum dan sumber fisi

Spektrum fisi kontinu ternormalisasi, $\int_0^\infty\chi(E)\,dE=1$. Fraksi kelahiran di grup $g$ adalah integral spektrum pada batas grup:

$$\boxed{\chi_g=\int_{E_g}^{E_{g-1}}\chi(E)\,dE,\qquad \sum_g\chi_g=1.}$$

Jika spektrum fisi tidak bergantung energi neutron penyebab fisi, sumber grup eigenvalue ialah $F_g=\dfrac{\chi_g}{k_{eff}}\sum_{g'}\nu\Sigma_{f,g'}\phi_{g'}$. Jika $\chi$ bergantung pada energi datang $E'$, spektrum efektif perlu dibobot oleh produksi fisi grup asal:

$$\chi_{g'\to g}=\frac{\int_{E_{g'}}^{E_{g'-1}}\nu\Sigma_f(E')\phi_{ref}(E')\left[\int_{E_g}^{E_{g-1}}\chi(E'\to E)\,dE\right]dE'}{\int_{E_{g'}}^{E_{g'-1}}\nu\Sigma_f(E')\phi_{ref}(E')\,dE'}.$$

##### Kondensasi energi dan homogenisasi ruang

Bila konstanta dihitung pada grup halus $h$ lalu digabung menjadi grup kasar $G$, penampang reaksi terkondensasi:

$$\boxed{\Sigma_{x,G}^{coarse}=\frac{\sum_{h\in G}\Sigma_{x,h}^{fine}\phi_h^{ref}}{\sum_{h\in G}\phi_h^{ref}}.}$$

Transfer hamburan dikondensasikan dengan menjumlahkan sumber dari semua grup asal halus dan tujuan halus dalam grup kasar, lalu membaginya dengan fluks total grup asal kasar. Spektrum fisi kasar diperoleh dengan menjumlahkan fraksi kelahiran grup halus. Kondensasi menjaga laju untuk spektrum acuan, sehingga spektrum yang berubah signifikan dapat memerlukan kondensasi ulang.

Penggabungan region juga memerlukan pembobotan fluks ruang. Untuk reaksi $x$:

$$\Sigma_{x,g}^{hom}=\frac{\int_V\Sigma_{x,g}(\mathbf r)\phi_g(\mathbf r)\,dV}{\int_V\phi_g(\mathbf r)\,dV}. $$

Homogenisasi ruang berbeda dari kondensasi energi. Pada perhitungan nodal/difusi, rata-rata penampang saja mungkin tidak menjaga arus di batas; dapat diperlukan konstanta difusi terkoreksi arus atau faktor diskontinuitas.

Dengan konvensi tersebut, persamaan eigenvalue multigrup skematis adalah:

$$\mathcal L_g\phi_g+\Sigma_{t,g}\phi_g=\sum_{g'}\Sigma_{s,g'\to g}\phi_{g'}+\frac{\chi_g}{k_{eff}}\sum_{g'}\nu\Sigma_{f,g'}\phi_{g'}.$$

$\mathcal L_g$ adalah operator streaming/kebocoran ruang grup $g$; pada difusi isotropik umumnya $-\nabla\cdot D_g\nabla$. Untuk masalah sumber tetap, suku fisi diganti sumber yang diketahui.

##### Pengaruh temperatur, komposisi, dan spektrum acuan

- **Temperatur:** Doppler broadening memperlebar resonansi dan mengubah self-shielding/penampang efektif. Hamburan termal moderator terikat dapat memerlukan data $S(\alpha,\beta)$ yang sesuai temperatur. Gunakan tabel pada suhu relevan atau interpolasi yang konsisten.
- **Komposisi:** $\Sigma_x=\sum_iN_i\sigma_{x,i}$ berubah dengan densitas nuklida. Burnup, pengayaan, racun, dan densitas moderator juga mengubah background/dilution $\sigma_0$ sehingga spektrum serta self-shielding ikut berubah; efeknya bukan hanya penskalaan densitas pada penampang lama.
- **Spektrum acuan:** konstanta grup yang menjaga laju reaksi untuk satu spektrum tidak menjamin laju yang sama pada spektrum lain. Pilih spektrum yang mewakili kondisi sasaran; bila kondisi berubah, perbarui transport/self-shielding, homogenisasi, dan kondensasi secara konsisten.

##### Alur praktis pengolahan

1. Tetapkan library data nuklir, temperatur, komposisi, dan batas grup.
2. Proses data energi kontinu, termasuk broadening dan hamburan termal bila diperlukan.
3. Hitung spektrum referensi dan self-shielding (misalnya NR, IR, Bondarenko/subgroup) untuk material/region.
4. Bentuk konstanta reaksi, transfer hamburan, dan spektrum fisi dengan pembobot yang sesuai.
5. Homogenisasi region, lalu kondensasikan grup halus ke struktur grup solver.
6. Verifikasi $\sum_g\chi_g=1$, laju reaksi, neraca transfer hamburan, dan sensitivitas terhadap spektrum serta struktur grup.

Dengan:

- $\psi,\phi(E),\phi_g$: fluks sudut, fluks skalar per energi, dan fluks terintegrasi grup.
- $\phi_{ref}$: spektrum referensi pembobot; $E_g,E_{g-1}$: batas bawah dan atas grup $g$.
- $N_i,\sigma_{x,i},\Sigma_{x,g}$: densitas atom, penampang mikroskopik reaksi $x$, dan penampang makroskopik grup.
- $\Sigma_{s,g'\to g}$: konstanta hamburan dari grup asal $g'$ ke tujuan $g$; $\mathbf S$: matriks transfer.
- $\Sigma_{rem,g}$: penampang removal; $\nu\Sigma_f$: produksi neutron fisi per panjang lintasan.
- $\chi(E),\chi_g$: spektrum fisi kontinu dan fraksi kelahiran pada grup; $k_{eff}$: faktor multiplikasi efektif.
- $T$: temperatur; $V$: volume homogenisasi; $\mathcal L_g$: operator streaming/kebocoran.

### **B2. Diskritisasi Ruang**

###  <center> <b> Finite Difference Metode  </b></center>

WHUAHAHAHHA, Untuk mendapatkan persamaan Finite Difference Metode (FDM) kita bisa menggunakan deret taylor, maka begini caranya wkwkwk

Bentuk umum deret Taylor:

$$ f(x) = f(x_0) + \frac{(x-x_0)}{1!} f'(x_0) + \frac{(x-x_0)^2}{2!}f''(x_0) + \dots + \frac{(x-x_0)^m}{m!}f^{(m)}(x_0) + \dots $$

Persamaan ini memiliki panjang yang tak berhingga. Untuk memudahkan penulisan, biasanya dimisalkan $h = x-x_0$, sehingga persamaan menjadi:

$$ f(x) = f(x_0) + \frac{h}{1!} f'(x_0) + \frac{h^2}{2!}f''(x_0) + \dots + \frac{h^m}{m!}f^{(m)}(x_0) + \dots $$

Kasus khusus dengan $x_0 = 0$ disebut deret Maclaurin:

$$ f(x) = f(0) + \frac{(x-0)}{1!} f'(0) + \frac{(x-0)^2}{2!}f''(0) + \dots + \frac{(x-0)^m}{m!}f^{(m)}(0) + \dots $$

Salah satu fungsi deret Taylor dalam metode numerik adalah untuk penurunan numerik, yaitu pada metode *finite difference*. Biasanya ada 3 jenis *finite difference*, yaitu *forward*, *backward*, dan *central*.

Dalam metode **finite difference**, deret Taylor digunakan untuk mencari nilai turunan. Misalkan pada **forward difference**, metode ini menggunakan nilai fungsi pada titik saat ini $x_i$ dan titik berikutnya $x_{i+1}$ untuk memperkirakan nilai turunan. Sebagai contoh, untuk **mencari nilai turunan pertama** dengan deret Taylor dalam *forward difference* didapatkan:

$$ f(x_{i+1}) = f(x_i) + \frac{(x_{i+1}-x_i)}{1!} f'(x_i) + \frac{(x_{i+1}-x_i)^2}{2!}f''(x_i) + \dots + \frac{(x_{i+1}-x_i)^m}{m!}f^{(m)}(x_i) + \dots $$

Jika dimisalkan $h = (x_{i+1}-x_i)$, maka persamaan menjadi:

$$ f(x_{i+1}) = f(x_i) + \frac{h}{1!} f'(x_i) + \dots $$

atau dapat dituliskan sebagai berikut:

$$ f(x_{i+1}) = f(x_i) + h f'(x_i) + \dots $$

$$ - h f'(x_i) = -f(x_{i+1}) + f(x_i) + \dots $$

$$ f'(x_i) = \frac{-f(x_{i+1}) + f(x_i)}{-h} + \dots $$

Maka didapatkan turunan pertama dari *Forward Difference*:

$$ f'(x_i) = \frac{f(x_{i+1}) - f(x_i)}{h} + \dots $$

Sedangkan *Backward Difference* menggunakan deret Taylor dengan nilai saat ini $x_i$ dan titik sebelumnya $x_{i-1}$, sehingga persamaan menjadi:

$$ f(x_{i-1}) = f(x_i) - \frac{(x_i-x_{i-1})}{1!} f'(x_i) + \frac{(x_i-x_{i-1})^2}{2!}f''(x_i) - \dots + \frac{(x_i-x_{i-1})^m}{m!}f^{(m)}(x_i) + \dots $$

Jika dimisalkan $h = (x_i-x_{i-1})$, maka persamaan menjadi:

$$ f(x_{i-1}) = f(x_i) - \frac{h}{1!} f'(x_i) + \dots $$

$$ f(x_{i-1}) = f(x_i) - h f'(x_i) + \dots $$

$$ h f'(x_i) = f(x_i) - f(x_{i-1}) + \dots $$

Maka didapatkan turunan pertama dari *Backward Difference*:

$$ f'(x_i) = \frac{f(x_i) - f(x_{i-1})}{h} + \dots $$

*Central Difference* didapatkan dari hasil pengurangan antara ekspansi *Forward* dan *Backward*, sebagai berikut:

$$ f'(x_i) = \frac{f(x_{i+1}) - f(x_{i-1})}{2h} $$

#### Operator Laplace ($\nabla^2$)

Operator Laplace (Laplacian) adalah divergensi dari gradien suatu fungsi skalar $f$:

$$ \nabla^2 f = \nabla \cdot (\nabla f) $$

Persamaan Laplace berbentuk $\nabla^2 f = 0$, sedangkan persamaan Poisson berbentuk $\nabla^2 f = g$. Bentuk $\nabla^2$ bergantung pada sistem koordinat yang dipakai.

##### Koordinat Kartesian $(x, y, z)$

$$ \nabla^2 f = \frac{\partial^2 f}{\partial x^2} + \frac{\partial^2 f}{\partial y^2} + \frac{\partial^2 f}{\partial z^2} $$

##### Koordinat Polar 2D $(r, \theta)$

$$ \nabla^2 f = \frac{1}{r}\frac{\partial}{\partial r}\left(r\frac{\partial f}{\partial r}\right) + \frac{1}{r^2}\frac{\partial^2 f}{\partial \theta^2} $$

##### Koordinat Silinder $(r, \theta, z)$

$$
\begin{aligned}
& \nabla^2 f = \frac{1}{r}\frac{\partial}{\partial r}\left(r\frac{\partial f}{\partial r}\right) + \frac{1}{r^2}\frac{\partial^2 f}{\partial \theta^2} + \frac{\partial^2 f}{\partial z^2} \\
\end{aligned}
$$

atau dalam bentuk yang diturunkan:

$$
\begin{aligned}
& \nabla^2 f = \frac{\partial^2 f}{\partial r^2} + \frac{1}{r}\frac{\partial f}{\partial r} + \frac{1}{r^2}\frac{\partial^2 f}{\partial \theta^2} + \frac{\partial^2 f}{\partial z^2} \\
\end{aligned}
$$

##### Koordinat Bola (Spherical) $(r, \theta, \phi)$

Dengan $\theta$ sebagai sudut polar (dari sumbu $z$) dan $\phi$ sebagai sudut azimut:

$$
\begin{aligned}
& \nabla^2 f = \frac{1}{r^2}\frac{\partial}{\partial r}\left(r^2\frac{\partial f}{\partial r}\right) + \frac{1}{r^2\sin\theta}\frac{\partial}{\partial \theta}\left(\sin\theta\,\frac{\partial f}{\partial \theta}\right) + \frac{1}{r^2\sin^2\theta}\frac{\partial^2 f}{\partial \phi^2} \\
\end{aligned}
$$

#### **Contoh Penyelesaian Difusi Neutron 2 Dimensi Silinder $(r, z)$ Multigrup (5 grup)**

**Persamaan difusi tiap grup**

- **Grup I**

$$
\begin{aligned}
& D_1 \nabla^2 \phi^1_{(r,z)} - \Sigma_{a1} \phi^1_{(r,z)} - \Sigma_{s1 \rightarrow 2} \phi^1_{(r,z)} \\
& - \Sigma_{s1 \rightarrow 3} \phi^1_{(r,z)} - \Sigma_{s1 \rightarrow 4} \phi^1_{(r,z)} \\
& - \Sigma_{s1 \rightarrow 5} \phi^1_{(r,z)} \\
& + \frac{\chi_1}{k} \left(\nu_1 \Sigma_{f1} \phi^1_{(r,z)} + \dots + \nu_5 \Sigma_{f5} \phi^5_{(r,z)}\right) = 0 \\
\end{aligned}
$$

- **Grup II**

$$
\begin{aligned}
& D_2 \nabla^2 \phi^2_{(r,z)} - \Sigma_{a2} \phi^2_{(r,z)} - \Sigma_{s2 \rightarrow 3} \phi^2_{(r,z)} \\
& - \Sigma_{s2 \rightarrow 4} \phi^2_{(r,z)} - \Sigma_{s2 \rightarrow 5} \phi^2_{(r,z)} \\
& + \Sigma_{s1 \rightarrow 2} \phi^1_{(r,z)} \\
& + \frac{\chi_2}{k} \left(\nu_1 \Sigma_{f1} \phi^1_{(r,z)} + \dots + \nu_5 \Sigma_{f5} \phi^5_{(r,z)}\right) = 0 \\
\end{aligned}
$$

- **Grup III**

$$
\begin{aligned}
& D_3 \nabla^2 \phi^3_{(r,z)} - \Sigma_{a3} \phi^3_{(r,z)} - \Sigma_{s3 \rightarrow 4} \phi^3_{(r,z)} \\
& - \Sigma_{s3 \rightarrow 5} \phi^3_{(r,z)} + \Sigma_{s1 \rightarrow 3} \phi^1_{(r,z)} \\
& + \Sigma_{s2 \rightarrow 3} \phi^2_{(r,z)} \\
& + \frac{\chi_3}{k} \left(\nu_1 \Sigma_{f1} \phi^1_{(r,z)} + \dots + \nu_5 \Sigma_{f5} \phi^5_{(r,z)}\right) = 0 \\
\end{aligned}
$$

- **Grup IV**

$$
\begin{aligned}
& D_4 \nabla^2 \phi^4_{(r,z)} - \Sigma_{a4} \phi^4_{(r,z)} - \Sigma_{s4 \rightarrow 5} \phi^4_{(r,z)} \\
& + \Sigma_{s1 \rightarrow 4} \phi^1_{(r,z)} + \Sigma_{s2 \rightarrow 4} \phi^2_{(r,z)} \\
& + \Sigma_{s3 \rightarrow 4} \phi^3_{(r,z)} \\
& + \frac{\chi_4}{k} \left(\nu_1 \Sigma_{f1} \phi^1_{(r,z)} + \dots + \nu_5 \Sigma_{f5} \phi^5_{(r,z)}\right) = 0 \\
\end{aligned}
$$

- **Grup V**

$$
\begin{aligned}
& D_5 \nabla^2 \phi^5_{(r,z)} - \Sigma_{a5} \phi^5_{(r,z)} + \Sigma_{s1 \rightarrow 5} \phi^1_{(r,z)} \\
& + \Sigma_{s2 \rightarrow 5} \phi^2_{(r,z)} + \Sigma_{s3 \rightarrow 5} \phi^3_{(r,z)} \\
& + \Sigma_{s4 \rightarrow 5} \phi^4_{(r,z)} \\
& + \frac{\chi_5}{k} \left(\nu_1 \Sigma_{f1} \phi^1_{(r,z)} + \dots + \nu_5 \Sigma_{f5} \phi^5_{(r,z)}\right) = 0 \\
\end{aligned}
$$

**Laplacian silinder arah $(r, z)$**

$$ \nabla^2 f_{(r,z)} = \frac{1}{r} \frac{\partial}{\partial r} \left( r \frac{\partial f_{(r,z)}}{\partial r} \right) + \frac{\partial^2 f_{(r,z)}}{\partial z^2} $$

$$
\begin{aligned}
& \nabla^2 f_{(r,z)} = \frac{1}{r} \left( r \frac{\partial}{\partial r} \frac{\partial f_{(r,z)}}{\partial r} + \frac{\partial r}{\partial r} \frac{\partial f_{(r,z)}}{\partial r} \right) + \frac{\partial^2 f_{(r,z)}}{\partial z^2} \\
\end{aligned}
$$

$$
\begin{aligned}
& \nabla^2 f_{(r,z)} = \frac{1}{r} \left( r \frac{\partial^2 f_{(r,z)}}{\partial r^2} + 1 \cdot \frac{\partial f_{(r,z)}}{\partial r} \right) + \frac{\partial^2 f_{(r,z)}}{\partial z^2} \\
\end{aligned}
$$

$$ \nabla^2 f_{(r,z)} = \frac{\partial^2 f_{(r,z)}}{\partial r^2} + \frac{1}{r} \frac{\partial f_{(r,z)}}{\partial r} + \frac{\partial^2 f_{(r,z)}}{\partial z^2} $$

**Diskritisasi dengan *central difference***

Arah $r$:

$$ \frac{\partial f_{(r,z)}}{\partial r} = \frac{f_{(r+\Delta r, z)} - f_{(r-\Delta r,z)}}{2 \Delta r} $$

$$ \frac{\partial^2 f_{(r,z)}}{\partial r^2} = \frac{f_{(r+\Delta r, z)} - 2 f_{(r,z)} + f_{(r-\Delta r,z)}}{\Delta r^2} $$

Arah $z$:

$$ \frac{\partial^2 f_{(r,z)}}{\partial z^2} = \frac{f_{(r, z+\Delta z)} - 2 f_{(r,z)} + f_{(r,z-\Delta z)}}{\Delta z^2} $$

Maka setelah didiskritisasi, Laplacian menjadi:

$$
\begin{aligned}
(\nabla_h^2 f)_{i,j}={}
\frac{f_{i+1,j}-2f_{i,j}+f_{i-1,j}}{\Delta r^2} +\frac{f_{i+1,j}-f_{i-1,j}}{2r_i\Delta r} +\frac{f_{i,j+1}-2f_{i,j}+f_{i,j-1}}{\Delta z^2}.
\end{aligned}
$$

**Substitusi ke persamaan difusi multigrup**

Agar rumus tetap terbaca, gunakan indeks titik ruang $(i,j)$ dan definisikan sumber fisi lokal serta removal:

$$
q_{f,i,j}=\sum_{g'=1}^{5}\nu_{g'}\Sigma_{f,g'}\phi_{g',i,j},\qquad
R_g=\Sigma_{a,g}+\sum_{g'>g}\Sigma_{s,g\to g'}.
$$

Koefisien stencil untuk grup $g$ adalah:

$$
\begin{aligned}
A_{g,r}^{-}&=\frac{D_g}{\Delta r^2}-\frac{D_g}{2r_i\Delta r}, &
A_{g,r}^{+}&=\frac{D_g}{\Delta r^2}+\frac{D_g}{2r_i\Delta r},\\
A_{g,z}&=\frac{D_g}{\Delta z^2}, &
A_g&=\frac{2D_g}{\Delta r^2}+\frac{2D_g}{\Delta z^2}+R_g.
\end{aligned}
$$

Dengan demikian, persamaan pada setiap grup $g=1,\ldots,5$ dapat ditulis dalam satu bentuk ringkas:

$$
\begin{aligned}
&A_{g,r}^{-}\phi_{g,i-1,j}+A_{g,z}\phi_{g,i,j-1}-A_g\phi_{g,i,j}\\
&+A_{g,r}^{+}\phi_{g,i+1,j}+A_{g,z}\phi_{g,i,j+1}\\
&+\sum_{g'<g}\Sigma_{s,g'\to g}\phi_{g',i,j}
+\frac{\chi_g}{k}q_{f,i,j}=0.
\end{aligned}
$$

Suku penjumlahan hamburan masuk bernilai nol untuk grup pertama. Bentuk ini merangkum lima persamaan grup sebelumnya; koefisien dan sumber fisi tetap dapat diperiksa dari definisi di atas.

**Bentuk matriks FDM (ilustrasi 3 grup, 3 titik ruang)**

Untuk memperlihatkan pola matriks tanpa membuatnya terlalu lebar, ambil tiga titik berurutan pada satu baris mesh dan susun vektor fluks per grup:

$$
\boldsymbol\phi=
\begin{bmatrix}
\phi_{1,1}&\phi_{1,2}&\phi_{1,3}&
\phi_{2,1}&\phi_{2,2}&\phi_{2,3}&
\phi_{3,1}&\phi_{3,2}&\phi_{3,3}
\end{bmatrix}^{T}.
$$

Definisikan $a_g$ sebagai koefisien diagonal negatif pada persamaan grup $g$, $a_g^-$ dan $a_g^+$ sebagai koefisien titik ruang kiri dan kanan, serta $s_{g'\to g}=\Sigma_{s,g'\to g}$. Matriks kehilangan dan hamburan menjadi:

$$
\mathbf M=\begin{bmatrix}
-a_1&a_1^+&0&0&0&0&0&0&0\\
a_1^-&-a_1&a_1^+&0&0&0&0&0&0\\
0&a_1^-&-a_1&0&0&0&0&0&0\\
s_{1\to2}&0&0&-a_2&a_2^+&0&0&0&0\\
0&s_{1\to2}&0&a_2^-&-a_2&a_2^+&0&0&0\\
0&0&s_{1\to2}&0&a_2^-&-a_2&0&0&0\\
s_{1\to3}&0&0&s_{2\to3}&0&0&-a_3&a_3^+&0\\
0&s_{1\to3}&0&0&s_{2\to3}&0&a_3^-&-a_3&a_3^+\\
0&0&s_{1\to3}&0&0&s_{2\to3}&0&a_3^-&-a_3
\end{bmatrix}.
$$

Setiap diagonal grup berisi stencil spasial tridiagonal; koefisien hamburan masuk muncul di kolom grup asal pada titik ruang yang sama. Untuk sumber fisi, tuliskan $p_{g,g'}=\chi_g\nu_{g'}\Sigma_{f,g'}$. Produksi fisi bersifat lokal pada titik ruang, sehingga matriksnya adalah:

$$
\mathbf F=\begin{bmatrix}
p_{1,1}&0&0&p_{1,2}&0&0&p_{1,3}&0&0\\
0&p_{1,1}&0&0&p_{1,2}&0&0&p_{1,3}&0\\
0&0&p_{1,1}&0&0&p_{1,2}&0&0&p_{1,3}\\
p_{2,1}&0&0&p_{2,2}&0&0&p_{2,3}&0&0\\
0&p_{2,1}&0&0&p_{2,2}&0&0&p_{2,3}&0\\
0&0&p_{2,1}&0&0&p_{2,2}&0&0&p_{2,3}\\
p_{3,1}&0&0&p_{3,2}&0&0&p_{3,3}&0&0\\
0&p_{3,1}&0&0&p_{3,2}&0&0&p_{3,3}&0\\
0&0&p_{3,1}&0&0&p_{3,2}&0&0&p_{3,3}
\end{bmatrix},
\qquad
\mathbf M\boldsymbol\phi=-\frac{1}{k_{eff}}\mathbf F\boldsymbol\phi.
$$

Ini adalah potongan ilustratif untuk tiga titik pada satu baris mesh. Pada mesh 2D silinder, tambahkan koefisien titik aksial $a_{g,z}$ pada kolom tetangga atas/bawah; batas domain mengubah baris stencil di tepi.

###  <center> <b> Collision Probability Method  </b></center>

* Persamaan Transport Neutron Bentuk Integral

    Dalam CPM, kita tidak menggunakan bentuk diferensial dari persamaan transport, melainkan bentuk **integral**. Fluks sudut neutron $\phi_{g}(r,\Omega)$ pada suatu titik $r$ dengan arah $\Omega$ untuk grup energi $g$ dapat dituliskan sebagai:

    $$
    \begin{aligned}
    & \phi_{g}(r,\Omega)=\int_{0}^{l_{0}}Q_{g}(r-l^{\prime}\Omega,\Omega)e_{g}(r-l^{\prime}\Omega\rightarrow r)dl^{\prime} \\
    & + \phi_{g}(r-l_{0}\Omega,\Omega)e_{g}(r-l_{0}\Omega\rightarrow r) \\
    \end{aligned}
    $$

    **Makna Fisis Persamaan:**
    Fluks neutron di suatu titik berasal dari dua sumber utama:

    1. Suku Pertama (Sumber Internal): Kontribusi dari sumber neutron $Q_{g}$ di sepanjang lintasan $l'$ dari titik asal ke lokasi target.

    2. Suku Kedua (Sumber Eksternal/Batas): Fluks sudut yang masuk dari batas domain (sejauh $l_0$).

    Kedua fluks ini akan melemah (atenuasi) secara eksponensial seiring bertambahnya jarak akibat interaksi dengan material. Efek pelemahan ini diwakili oleh **faktor pelemahan (weakening factor)** $e_g$:


    $$e_{g}(r-l_{0}\Omega\rightarrow r)=exp\left[-\int_{0}^{l_{0}}\Sigma_{t,g}(r-l^{\prime}\Omega)dl^{\prime}\right]$$


    Dengan asumsi bahwa sumber neutron dan hamburan bersifat isotropik (menyebar merata ke segala arah), persamaan fluks skalar $\Phi_{g}(r)$ dapat disederhanakan menjadi penjumlahan fluks dari dalam volume ($V$) dan dari permukaan batas ($S$).

* Diskritisasi Domain dan Konsep Probabilitas Tumbukan

    Untuk menyelesaikan persamaan integral yang rumit ini secara numerik dengan komputer, kita harus membagi reaktor menjadi bagian-bagian kecil (diskritisasi):

    * Volume dibagi menjadi $I$ region, di mana setiap region memiliki volume $V_i$. Sifat material di dalam satu region dianggap konstan.


    * Permukaan (Batas) dibagi menjadi $M$ region permukaan, masing-masing dengan luas $S_m$.

    Kita mengasumsikan bahwa sumber neutron merata di setiap region (*flat source approximation*). Persamaan keseimbangan neutron untuk suatu region $i$ diturunkan menjadi bentuk aljabar linier:

    $$\Sigma_{t,g,i}\Phi_{g,i}V_{i}=\sum_{i^{\prime}=1}^{I}Q_{g,i^{\prime}}P_{g,i^{\prime}}V_{i^{\prime}}+\sum_{m=1}^{M}J_{g,m}^{-}P_{g,im}S_{m}$$

    **Penjelasan Parameter Kunci (Probabilitas Tumbukan):**
    Inti dari CPM adalah menghitung empat parameter probabilitas $P$ berikut sebelum iterasi fluks dimulai:

    * $P_{g,i\vec{u}^{\prime}}$ (atau secara umum ditulis $P_{ii'}$): Probabilitas sebuah neutron yang lahir secara seragam di region $i'$, mengalami tumbukan pertamanya di region $i$.

    * $P_{g,im}$: Probabilitas sebuah neutron yang masuk dari permukaan luar $m$, mengalami tumbukan pertamanya di region $i$.

    * $P_{g,mi}$: Probabilitas sebuah neutron yang lahir di region $i$, berhasil lolos keluar melalui permukaan $m$.

    * $P_{g,mm^{\prime}}$: Probabilitas sebuah neutron yang masuk dari permukaan $m'$, terbang dan keluar lagi melalui permukaan $m$ tanpa menumbuk apapun.

    Evaluasi probabilitas ini dihitung menggunakan metode analitik untuk geometri 1D , atau **teknik pelacakan sinar (ray tracing / Method of Characteristics)** untuk geometri 2D/3D yang kompleks.

* Sifat Resiprositas (Timbal Balik)

    Menghitung probabilitas tumbukan untuk semua region sangat memakan waktu komputer. Untungnya, probabilitas ini memiliki sifat **resiprositas (timbal balik)**, yang berarti probabilitas dari A ke B berhubungan langsung dengan B ke A :

    1. $P_{g,ii^{\prime}}V_{i^{\prime}}=P_{g,i^{\prime}i}V_{i}$ 

    2. $P_{g,mi}=P_{g,im}$ 

    3. $P_{g,mm^{\prime}}S_{m}=P_{g,m^{\prime}m}S_{m^{\prime}}$ 

    **Keuntungan komputasi:** Dengan rumus ini, kode program hanya perlu menghitung separuh dari total probabilitas matriks, sehingga menghemat waktu komputasi hingga 50%.

* Alur Penyelesaian Program (Flowchart Komputasi)

    1. Alur Penyelesaian "Fixed Source" (Untuk 1 Grup Energi)

        Ini adalah permasalahan reaktor subkritis dengan sumber eksternal.

        1. Evaluasi Probabilitas Tumbukan, Hitung matriks $P_{ii'}, P_{im}, P_{mi}, P_{mm'}$ menggunakan *ray tracing*. (Langkah ini hanya dilakukan 1x di awal karena geometri tidak berubah )

        2. Inisialisasi, Berikan nilai tebakan awal untuk fluks neutron region ($\Phi_{g,i}$) dan arus parsial ($J_{g,m}^-$).

        3. Cek Kondisi Batas (Fix B.C.):
            * Jika batas bergantung pada fluks yang keluar (seperti kondisi albedo), selesaikan persamaan aljabar linier untuk mencari arus parsial ($J_{g,m}^-$) yang baru.
            * Jika batas sudah tetap secara mutlak, lewati langkah ini.

        4. Selesaikan Fluks Region, Gunakan persamaan dasar keseimbangan (Persamaan 2.7) untuk mencari nilai fluks region ($\Phi_{g,i}$) terbaru.

        5. Stop, Algoritma selesai untuk perhitungan satu grup energi.

    2. Alur Penyelesaian "Fission Source" (Multigrup & Iterasi Nilai Eigen)

        Ini adalah alur untuk reaktor kritis komersial biasa di mana sumber neutron berasal dari fisi.

        1. Evaluasi Probabilitas Tumbukan, Hitung semua matriks probabilitas $P$.

        2. Inisialisasi, Beri tebakan awal untuk nilai $k_{eff}$ (biasanya 1.0), fluks region, dan arus parsial.

        3. Update Sumber Fisi, Hitung distribusi sumber fisi berdasarkan nilai fluks saat ini.

        4. Mulai Loop Grup Energi ($g = 1 \dots G$): 
        * Update Sumber Hamburan (Scattering Source), Hitung neutron yang berpindah grup akibat hamburan.
        * Selesaikan Arus Parsial (jika diperlukan oleh kondisi batas): .
            * Selesaikan Fluks Region, Hitung fluks untuk grup energi $g$ ini.
            * Lanjut ke grup berikutnya, ($g = g + 1$) sampai semua grup selesai.

        5. Update Nilai $k$ (Eigenvalue), Hitung rasio total sumber fisi baru terhadap sumber fisi lama untuk mendapatkan $k_{eff}$ yang baru.
        
        6. Cek Konvergensi, Apakah iterasi sumber fisi (fluks dan nilai $k$) sudah stabil / tidak berubah signifikan? 
            * Jika **Belum (N)**: Ulangi kembali dari Langkah 3.
            * Jika **Sudah (Y)**: Iterasi selesai (Stop).

### **B3. Diskritisasi Sudut**

####  <center> <b> Method of Characteristics  </b></center>

* Persamaan Dasar (Basic Equations)

    Metode karakteristik klasik telah berhasil diterapkan untuk menyelesaikan Persamaan Transport Neutron (NTE) dan diimplementasikan dalam berbagai program analisis reaktor.

    Bentuk dasar kelompok-energi (groupwise) dari NTE untuk suatu sistem dengan batas $\partial R$ dinyatakan sebagai:

    $$\Omega\cdot\nabla\phi_{g}(r,\Omega)+\Sigma_{t,g}\phi_{g}(r,\Omega)=Q_{g}(r,\Omega)$$

    **Dimana:**

    * $\phi_{g}(r,\Omega)$: Fluks sudut (angular flux) untuk kelompok energi $g$ pada posisi $r$ dan arah $\Omega$.
    * $\Sigma_{t,g}$: Penampang lintang makroskopik total (kemungkinan probabilitas interaksi neutron).
    * $Q_{g}(r,\Omega)$: Suku sumber total.

    Sumber total $Q_{g}(r,\Omega)$ adalah gabungan dari sumber fisi (pembelahan) $Q_{f,g}$ dan sumber hamburan (scattering) $Q_{s,g}$:
    $$Q_{g}(r,\Omega)=Q_{f,g}(r)+Q_{s,g}(r,\Omega)$$

    Jika dijabarkan, persamaan sumber fisi dan hamburan adalah:
    $$Q_{f,g}(r,\Omega)=\sum_{g=1}\frac{\chi(r,\Omega)}{4\pi k_{eff}}\int_{4\pi}(\nu\Sigma_{f,g}(r))\phi(r,\Omega)d\Omega$$

    $$Q_{S,g}(r,\Omega)=\sum_{g^{\prime}=1}^{G}\int_{0}^{4\pi}\Sigma_{S,g^{\prime}g}(r,\Omega^{\prime}\rightarrow\Omega)\phi_{g^{\prime}}(r,\Omega^{\prime})d\Omega^{\prime}$$

    Adapun kondisi batas (boundary condition) sistem ini ditentukan oleh:


    $$\phi_{g}(r,\Omega)=f(r,\Omega),\quad r \in \partial R,\quad \Omega\cdot n<0$$

    Ini berarti fluks sudut yang masuk dari luar didistribusikan sebagai suatu fungsi $f$ pada batas eksternal sistem.

* Penurunan Rumus 1: Mengubah Turunan Parsial Menjadi Turunan Biasa

    Dalam sistem koordinat Kartesian, arah $\Omega$ direpresentasikan oleh komponen vektor kecepatan terhadap jarak tempuh (lintasan/sinar $s$):

    $$\Omega=\Omega_{x}\vec{i}+\Omega_{y}\vec{j}+\Omega_{z}\vec{k}=\frac{dx}{ds}\vec{i}+\frac{dy}{ds}\vec{j}+\frac{dz}{ds}\vec{k}$$

    Suku kebocoran (leakage term) $\Omega\cdot\nabla\phi$ dalam NTE melibatkan turunan parsial ruang ($\nabla\phi$). Dengan aturan rantai (chain rule) dalam kalkulus, kita bisa menyederhanakan turunan parsial ini menjadi operator diferensial biasa di sepanjang garis lurus $s$:

    $$\frac{d\phi}{ds}=\frac{\partial\phi}{\partial x}\frac{dx}{ds}+\frac{\partial\phi}{\partial y}\frac{dy}{ds}+\frac{\partial\phi}{\partial z}\frac{dz}{ds}$$


    Substitusikan $\Omega_{x} = \frac{dx}{ds}$, $\Omega_{y} = \frac{dy}{ds}$, dan $\Omega_{z} = \frac{dz}{ds}$, maka:

    $$\frac{d\phi}{ds}=\Omega_{x}\frac{\partial\phi}{\partial x}+\Omega_{y}\frac{\partial\phi}{\partial y}+\Omega_{z}\frac{\partial\phi}{\partial z}$$

    $$\frac{d\phi}{ds}=\Omega\cdot\nabla\phi$$

    Dengan keistimewaan ini, NTE yang awalnya rumit berubah menjadi Persamaan Diferensial Biasa (PDB) orde pertama di sepanjang garis linier tertentu dengan arah $\Omega_{m}$:

    $$\frac{d\phi(r_{0}+s\Omega_{m},\Omega_{m})}{ds}+\Sigma_{t}(r_{0}+s\Omega_{m})\phi(r_{0}+s\Omega_{m},\Omega_{m})=Q(r_{0}+s\Omega_{m},\Omega_{m})$$

    Di mana $r_{0}$ adalah titik awal sinar karakteristik dan $s$ adalah jarak dari titik awal di sepanjang arah $\Omega_{m}$.

* Penurunan Rumus 2: Solusi Analitik Fluks Sudut (Persamaan 5.10 & 5.11)

    Untuk memecahkan sistem ini, kita menggunakan pendekatan **Flat Source Approximation** (Pendekatan Sumber Datar). Asumsinya adalah domain spasial dibagi menjadi daerah-daerah kecil ($D_i$), di mana bahan bernilai konstan ($\Sigma_{t,i}$) dan sumber juga konstan ($Q_i$) di dalam wilayah tersebut.

    Persamaan diferensial kita di wilayah kecil $i$ menyederhana menjadi:

    $$\frac{d\phi}{ds} + \Sigma_{t,i}\phi = Q_i$$

    **Langkah Penurunan:**

    1. Kalikan kedua sisi dengan faktor integrasi $e^{\int \Sigma_{t,i} ds} = e^{\Sigma_{t,i}s}$:

    $$e^{\Sigma_{t,i}s} \frac{d\phi}{ds} + e^{\Sigma_{t,i}s} \Sigma_{t,i}\phi = Q_i e^{\Sigma_{t,i}s}$$


    2. Sisi kiri persamaan sekarang merupakan bentuk turunan dari produk $(\phi \cdot e^{\Sigma_{t,i}s})$:

    $$\frac{d}{ds} \left( \phi \cdot e^{\Sigma_{t,i}s} \right) = Q_i e^{\Sigma_{t,i}s}$$

    3. Integralkan kedua sisi dari titik masuk ($s=0$) hingga jarak $s$:

    $$\int_{0}^{s} \frac{d}{ds} \left( \phi \cdot e^{\Sigma_{t,i}s} \right) ds = \int_{0}^{s} Q_i e^{\Sigma_{t,i}s} ds$$


    $$\phi(s) e^{\Sigma_{t,i}s} - \phi(0) e^0 = \frac{Q_i}{\Sigma_{t,i}} \left[ e^{\Sigma_{t,i}s} \right]_{0}^{s}$$


    $$\phi(s) e^{\Sigma_{t,i}s} - \phi^{in} = \frac{Q_i}{\Sigma_{t,i}} (e^{\Sigma_{t,i}s} - 1)$$


    4. Kalikan semua sisi dengan $e^{-\Sigma_{t,i}s}$ untuk mendapatkan $\phi(s)$:

    $$\phi(s) = \phi^{in} e^{-\Sigma_{t,i}s} + \frac{Q_i}{\Sigma_{t,i}} (1 - e^{-\Sigma_{t,i}s})$$

    Ini menghasilkan **Persamaan 5.10**:

    $$\phi_{i,k}(r_{0}+s\Omega_{m},\Omega_{m})=\phi_{i,k}^{in}(\Omega_{m})\exp(-\Sigma_{t,i}s)+\frac{Q_{i,k}(\Omega_{m})}{\Sigma_{t,i}}[1-\exp(-\Sigma_{t,i}s)]$$

    Jika kita ingin mencari fluks sudut yang *keluar* (outgoing flux) dari wilayah $D_i$, kita ganti $s$ dengan panjang total lintasan $S_{i,k}$ di daerah tersebut:

    $$\phi_{i,k}^{out}(\Omega_{m})=\phi_{i,k}^{in}(\Omega_{m})\exp(-\Sigma_{t,i}S_{i,k})+\frac{Q_{i,k}(\Omega_{m})}{\Sigma_{t,i}}[1-\exp(-\Sigma_{t,i}S_{i,k})]$$


* Penurunan Rumus 3: Rata-Rata Fluks Segmen (Persamaan 5.12)

    Fluks sudut rata-rata untuk suatu segmen didefinisikan dengan mengintegralkan fluks sepanjang $s$ lalu membaginya dengan panjang lintasan $S_{i,m,k}$.

    Dengan rumus:

    $$\bar{\phi}_{i,k}(\Omega_{m}) \cdot S_{i,m,k} = \int_{0}^{S_{i,m,k}} \left[ \phi_{i,k}^{in} \exp(-\Sigma_{t,i}s) + \frac{Q_i}{\Sigma_{t,i}} (1 - \exp(-\Sigma_{t,i}s)) \right] ds$$

    **Langkah Penurunan Integrasi:**

    1. Bagi integral tersebut menjadi dua bagian yang mudah diselesaikan:

    $$\int_{0}^{S} \phi^{in} e^{-\Sigma_t s} ds + \int_{0}^{S} \frac{Q_i}{\Sigma_t} ds - \int_{0}^{S} \frac{Q_i}{\Sigma_t} e^{-\Sigma_t s} ds$$

    2. Evaluasi integralnya:

    $$
    \begin{aligned}
    & = \left[ -\frac{\phi^{in}}{\Sigma_t} e^{-\Sigma_t s} \right]_{0}^{S} \\
    & + \left[ \frac{Q_i}{\Sigma_t} s \right]_{0}^{S} - \left[ -\frac{Q_i}{\Sigma_t^2} e^{-\Sigma_t s} \right]_{0}^{S} \\
    \end{aligned}
    $$

    $$= -\frac{\phi^{in}}{\Sigma_t}(e^{-\Sigma_t S} - 1) + \frac{Q_i}{\Sigma_t}S + \frac{Q_i}{\Sigma_t^2}(e^{-\Sigma_t S} - 1)$$

    3. Kita susun ulang dan kelompokkan suku yang mengandung $(e^{-\Sigma_t S} - 1)$:

    $$= \frac{Q_i}{\Sigma_t}S + \frac{1}{\Sigma_t} \left[ \phi^{in} - \left( \phi^{in}e^{-\Sigma_t S} + \frac{Q_i}{\Sigma_t}(1 - e^{-\Sigma_t S}) \right) \right]$$


    4. Perhatikan bahwa bagian di dalam kurung lengkung terakhir tepat sama dengan definisi **fluks sudut keluar** ($\phi^{out}$) pada Persamaan 5.11!

    $$= \frac{Q_i}{\Sigma_t}S + \frac{\phi^{in} - \phi^{out}}{\Sigma_t}$$

    Hasil akhirnya menjadi Persamaan 5.12:


    $$\bar{\phi}_{i,k}(\Omega_{m}) \cdot S_{i,m,k} = \frac{Q_{i}(\Omega_{m})}{\Sigma_{t,i}}S_{i,m,k}+\frac{\Delta\phi_{i,k}(\Omega_{m})}{\Sigma_{t,i}}$$

    Setelah fluks per segmen ini diketahui, kita dapat menghitung rata-rata fluks di seluruh area (region) dengan menjumlahkannya sesuai luas spasial setiap sinar (Persamaan 5.13) , dan akhirnya mendapatkan Fluks Skalar dengan menjumlahkannya ke seluruh sudut berbobot $\omega_m$ (Persamaan 5.14).

####  **MOC Dua Dimensi (Two-Dimensional MOC)**

Teori dasar MOC itu sederhana; pembeda utamanya terletak pada algoritma penelusuran sinar (ray tracing). Dalam 2D MOC, terdapat dua teknik utama:

1. Penelusuran Sinar Panjang (Long Ray Tracing)

    Sinar ditarik membelah keseluruhan sistem dari satu batas terluar hingga batas seberangnya (contoh: dari batas A tembus ke batas B melintasi berbagai sel bahan bakar).
    
    **Kekurangan:** Sangat memakan memori komputer. Penyimpanan yang dibutuhkan sebanding dengan jumlah wilayah (ukuran problem).

    **Kondisi Batas Pantulan (Reflective):** Menggunakan "Interpolasi Direksional". Fluks masuk $\phi_{l}^{in}$ diproksimasi dari sudut-sudut fluks terdekat yang memantul keluar. Rumusnya adalah interpolasi linear sederhana:

    $$\phi_{l}^{in}=\phi_{r}^{out}=C_{l}\cdot\phi_{m}^{out}+(1-C_{l})\cdot\phi_{n}^{out}$$

    $$C_{l}=\frac{\theta_{n}-\theta_{r}}{\theta_{n}-\theta_{m}}$$

    Pada metode karakteristik (MOC) 2D dengan *Long Ray Tracing*, garis-garis sinar karakteristik ditembakkan melintasi keseluruhan teras reaktor. Ketika sebuah sinar menabrak batas luar yang bersifat memantul (seperti cermin), secara ideal sinar tersebut akan memantul kembali ke dalam reaktor dengan sudut pantul ideal $\theta_r$.

    Namun, secara komputasi, kita hanya memiliki sejumlah **sudut diskret yang terbatas** (disebut sudut kuadratur arah, misalnya $\Omega_m$ dan $\Omega_n$). Sudut pantul ideal $\theta_r$ hampir dipastikan **tidak berhimpit** dengan salah satu sudut kuadratur diskret yang tersedia di komputer.

    Oleh karena itu, fluks sudut yang masuk kembali ke reaktor pada arah ideal tersebut ($\phi_l^{in}$ atau $\phi_r^{out}$) tidak bisa langsung diambil nilainya. Nilai tersebut harus **diinterpolasi secara linear** dari fluks sudut keluar pada dua arah kuadratur diskret terdekat yang mengapitnya, yaitu arah $\Omega_m$ (dengan sudut $\theta_m$) dan arah $\Omega_n$ (dengan sudut $\theta_n$).

    Maka penurunan matematis Faktor Interpolasi ($C_l$) :

    Misalkan sudut pantul ideal $\theta_r$ berada di antara dua sudut arah diskret komputer $\theta_m$ dan $\theta_n$, sedemikian rupa sehingga memenuhi kondisi:


    $$\theta_m \le \theta_r \le \theta_n$$

    Kita tahu dari prinsip kalkulus dasar bahwa persamaan interpolasi linear antara dua titik koordinat $(\theta_m, \phi_m^{out})$ dan $(\theta_n, \phi_n^{out})$ untuk mencari nilai fluks $\phi_r^{out}$ pada sudut $\theta_r$ adalah sebagai berikut:


    $$\frac{\phi_r^{out} - \phi_m^{out}}{\theta_r - \theta_m} = \frac{\phi_n^{out} - \phi_m^{out}}{\theta_n - \theta_m}$$

    Mari kita turunkan persamaan di atas langkah demi langkah tanpa ada yang terlewat:

    **Langkah 1:** Kalikan kedua ruas dengan $(\theta_r - \theta_m)$ untuk mengisolasi suku fluks di ruas kiri:


    $$\phi_r^{out} - \phi_m^{out} = \left( \frac{\theta_r - \theta_m}{\theta_n - \theta_m} \right) \left( \phi_n^{out} - \phi_m^{out} \right)$$

    **Langkah 2:** Distribusikan pengali ke dalam kurung siku di ruas kanan:


    $$
    \begin{aligned}
    & \phi_r^{out} - \phi_m^{out} = \left( \frac{\theta_r - \theta_m}{\theta_n - \theta_m} \right) \phi_n^{out} \\
    & - \left( \frac{\theta_r - \theta_m}{\theta_n - \theta_m} \right) \phi_m^{out} \\
    \end{aligned}
    $$

    **Langkah 3:** Pindahkan $-\phi_m^{out}$ dari ruas kiri ke ruas kanan:


    $$
    \begin{aligned}
    & \phi_r^{out} = \phi_m^{out} - \left( \frac{\theta_r - \theta_m}{\theta_n - \theta_m} \right) \phi_m^{out} \\
    & + \left( \frac{\theta_r - \theta_m}{\theta_n - \theta_m} \right) \phi_n^{out} \\
    \end{aligned}
    $$

    **Langkah 4:** Kelompokkan suku-suku yang mengandung variabel $\phi_m^{out}$:


    $$
    \begin{aligned}
    & \phi_r^{out} = \left( 1 - \frac{\theta_r - \theta_m}{\theta_n - \theta_m} \right) \phi_m^{out} \\
    & + \left( \frac{\theta_r - \theta_m}{\theta_n - \theta_m} \right) \phi_n^{out} \\
    \end{aligned}
    $$

    **Langkah 5:** Sederhanakan bentuk pecahan di dalam kurung koefisien $\phi_m^{out}$ dengan menyamakan penyebutnya:

    $$1 - \frac{\theta_r - \theta_m}{\theta_n - \theta_m} = \frac{(\theta_n - \theta_m) - (\theta_r - \theta_m)}{\theta_n - \theta_m}$$

    $$= \frac{\theta_n - \theta_m - \theta_r + \theta_m}{\theta_n - \theta_m}$$

    $$= \frac{\theta_n - \theta_r}{\theta_n - \theta_m}$$

    **Langkah 6:** Substitusikan kembali hasil penyederhanaan tersebut ke dalam persamaan fluks utama kita:

    $$\phi_r^{out} = \left( \frac{\theta_n - \theta_r}{\theta_n - \theta_m} \right) \phi_m^{out} + \left( \frac{\theta_r - \theta_m}{\theta_n - \theta_m} \right) \phi_n^{out}$$

    misal :
    $$C_l = \frac{\theta_n - \theta_r}{\theta_n - \theta_m}$$

    Mari kita cek apa yang terjadi pada koefisien pengali untuk arah $n$, yaitu $\left( \frac{\theta_r - \theta_m}{\theta_n - \theta_m} \right)$, jika dinyatakan dalam bentuk $C_l$:

    $$1 - C_l = 1 - \frac{\theta_n - \theta_r}{\theta_n - \theta_m}$$

    $$= \frac{(\theta_n - \theta_m) - (\theta_n - \theta_r)}{\theta_n - \theta_m}$$

    $$= \frac{\theta_n - \theta_m - \theta_n + \theta_r}{\theta_n - \theta_m}$$

    $$= \frac{\theta_r - \theta_m}{\theta_n - \theta_m}$$

    Ternyata polanya sangat konsisten dan membentuk nilai $(1 - C_l)$. Dengan demikian, kita mendapatkan formula utuh persamaannya:

    $$\phi_l^{in} = \phi_r^{out} = C_l \cdot \phi_m^{out} + (1 - C_l) \cdot \phi_n^{out}$$

    Interpretasi Fisik Nilai $C_l$

    * **Kasus A ($\theta_r$ mendekati $\theta_m$):** Jika sudut pantul ideal sangat dekat dengan kuadratur sudut $m$, maka pembilang $(\theta_n - \theta_r)$ nilainya akan membesar mendekati nilai penyebut $(\theta_n - \theta_m)$. Akibatnya $C_l \rightarrow 1$ dan $(1 - C_l) \rightarrow 0$. Fluks yang memantul kembali akan didominasi oleh nilai fluks dari arah $m$.
    * **Kasus B ($\theta_r$ mendekati $\theta_n$):** Jika sudut pantul ideal sangat dekat dengan kuadratur sudut $n$, maka pembilang $(\theta_n - \theta_r)$ nilainya mengecil mendekati $0$. Akibatnya $C_l \rightarrow 0$ dan $(1 - C_l) \rightarrow 1$. Fluks yang memantul akan didominasi oleh nilai fluks dari arah $n$.


2. Penelusuran Sinar Modular (Modular Ray Tracing)

    Karena teras reaktor PWR umumnya terdiri dari susunan perakitan bahan bakar (assembly) yang bentuknya berulang secara seragam ($15\times15$ atau $17\times17$ pin cells) , kita dapat secara cerdas **hanya menyimpan data satu modul saja**. Hal ini menurunkan kebutuhan memori secara drastis. Sinar yang keluar dari satu modul akan otomatis diteruskan sejajar ke modul sebelahnya.

    **Aturan Susunan Sudut:** Agar sinar ini menyambung dengan sempurna antar modul, sudut azimuthal sinar tidak boleh sembarangan. Sudutnya terikat oleh persamaan geometri berikut:

    $$\tan(\varphi) = (\Delta y / \Delta x) \frac{n_x}{n_y}$$

    Di mana $\Delta x, \Delta y$ adalah jarak jaring, dan $n_x, n_y$ adalah jumlah jarak pada sumbu X dan Y.

    **Keuntungan Tambahan:** Pendekatan modular ini tidak memerlukan interpolasi pendekatan untuk batas pantul (seperti yang dibutuhkan pada Long Ray Tracing). Sinar pantulan akan selalu memiliki jejak presisi di titik dan sudut yang tepat, meminimalisasi error komputasi.

#### **MOC Tiga Dimensi (Three-Dimensional MOC)**

Sama seperti konsep modular 2D yang membagi geometri menjadi kotak-kotak (modul) identik untuk menghemat memori, MOC 3D membagi reaktor menjadi balok-balok 3D (voksel/modul). Kunci utamanya adalah memastikan sinar yang keluar dari satu modul akan menyambung tepat dengan sinar di modul sebelahnya.

Pembentukan sinar modular 3D dilakukan dalam dua tahap: mengurus sudut azimuthal (horizontal) dan sudut polar (vertikal).

1. Menentukan Sudut Azimuthal ($\varphi$) dan Jarak Sinar
    Sama seperti 2D, sinar pada bidang X-Y dibatasi oleh ukuran jaring (mesh) agar posisinya periodik. Rumusnya adalah:

    $$\tan(\varphi) = \left(\frac{\Delta y}{\Delta x}\right) \frac{n_x}{n_y}$$

    **Penurunan Jarak Antar Sinar ($\delta_\varphi$):**
    Jika kita melihat sumbu X, jarak antara titik-titik tembus sinar di batas modul adalah $\frac{\Delta x}{n_x}$. Jarak tegak lurus (spasi) antara dua sinar sejajar ($\delta_\varphi$) dapat dicari menggunakan trigonometri dasar segitiga siku-siku:

    $$\delta_{\varphi}=\frac{\Delta x}{n_x}\sin(\varphi)$$

    Atau, jika ditinjau dari sumbu Y (jarak antar titik $\frac{\Delta y}{n_y}$):

    $$\delta_{\varphi}=\frac{\Delta y}{n_y}\cos(\varphi)$$

2. Menentukan Sudut Polar ($\theta$) dan Jarak Vertikal**
    Ide ini diperluas untuk sudut polar. Bayangkan sinar 2D tadi diangkat ke atas menjadi "potongan bidang" (cutaway sections) yang tegak lurus dengan bidang X-Y.
    Panjang total jejak sinar di bidang dasar (azimuthal) kita sebut $\Delta l_\varphi$, yang merupakan penjumlahan dari semua segmen garis di bidang tersebut:

    $$\Delta l_{\varphi}=\sum_{k}S_{k}$$

    Sudut elevasi sinar dari bidang X-Y kita sebut $\theta'$ (sudut terhadap bidang horizontal). Agar sinar ini konsisten di sumbu Z, sudut elevasi harus memenuhi:

    $$\tan(\theta^{\prime})=\left(\frac{\Delta z}{\Delta l_{\varphi}}\right)\frac{n_{\varphi}}{n_z}$$

    Namun, dalam fisika reaktor, sudut polar $\theta$ biasanya diukur dari sumbu Z vertikal (sudut zenith), sehingga:

    $$\theta=\frac{\pi}{2}-\theta^{\prime}$$

    Sama dengan penurunan 2D, jarak spasi antar sinar paralel di arah polar ($\delta_\theta$) adalah:

    $$\delta_{\theta}=\frac{\Delta l_{\varphi}}{n_{\varphi}}\sin\theta^{\prime}=\frac{\Delta z}{n_z}\cos\theta^{\prime}$$

    **Luas Penampang Sinar:**
    Karena sekarang sinar 3D berbentuk "tabung/prisma" abstrak, luas penampang tegak lurus dari satu sinar dengan arah $\Omega(\varphi,\theta)$ adalah perkalian dari spasi horizontal dan spasi vertikal:

    $$\delta A(\Omega)=\delta_{\varphi}\delta_{\theta}$$

    Metode ini memungkinkan perhitungan MOC 3D untuk seluruh teras reaktor tanpa perlu aproksimasi apa pun pada antarmuka batas modul maupun batas pantulan (*reflective boundary*).

    Umumnya, program transportasi neutron menggunakan set kuadratur standar (seperti *Level Symmetric*) di mana arah dan bobot sudut sudah dipatenkan. Namun, pada metode *Modular Ray Tracing* kita, sudut-sudutnya "dipaksa" mengikuti ukuran jaring (Persamaan 5.19 dan 5.22) sehingga tidak cocok dengan kuadratur standar. Oleh karena itu, kita harus menghitung "bobot integrasi" ($w_k$) baru untuk arah-arah sudut yang dipaksa tersebut.

    Untuk kuadratur simetris, hubungan antara jumlah arah $M$ di dalam satu oktan (1/8 bola) dengan orde $S_N$ (orde diskretisasi) adalah:

    $$M=\frac{(N/2)(N/2+1)}{2}$$

    **Penurunan Rumus Bobot ($w_k$) Menggunakan Harmonik Bola (Spherical Harmonics):**

    1. Dalam matematika, fungsi Harmonik Bola $Y_{2n}^{2m}(\theta,\varphi)$ adalah sistem ortogonal yang lengkap untuk ruang oktan ($\varphi \in [0, \pi/2], \theta \in [0, \pi/2]$).

    2. Fungsi sebarang $f(\theta,\varphi)$ di ruang ini bisa diekspansi menyerupai deret Taylor/Fourier, namun menggunakan Harmonik Bola:

    $$f(\theta,\varphi)=\sum_{n}^{\infty}\sum_{m=0}^{n}a_{n,m}Y_{2n}^{2m}(\theta,\varphi)$$

    3. Konsep dasar integrasi numerik adalah mengganti proses integral analitik dengan penjumlahan perkalian nilai fungsi pada titik tertentu dengan suatu bobot $w_k$:

    $$\int_{0}^{\pi/2}\int_{0}^{\pi/2}f(\theta,\varphi)\sin\theta d\theta d\varphi=\sum_{k}w_{k}f(\theta_{k},\varphi_{k})$$

    4. Jika persamaan deret fungsi (Langkah 2) disubstitusikan ke persamaan integrasi numerik (Langkah 3), maka setiap basis fungsi $Y_{2n}^{2m}$ harus memenuhi syarat kekekalan integral numerik tersebut:

    $$\int_{0}^{\pi/2}\int_{0}^{\pi/2}Y_{2n}^{2m}(\theta,\varphi)\sin\theta d\theta d\varphi=\sum_{k}w_{k}Y_{2n}^{2m}(\theta_{k},\varphi_{k})$$


    **Penyelesaian Akhir:**
    Persamaan di atas sebenarnya adalah sistem persamaan linear (SPL). Kita memiliki sejumlah $M$ sudut diskret (yaitu $k = 1, 2, ..., M$). Oleh karena itu, kita membutuhkan $M$ buah persamaan independen untuk mencari $M$ buah nilai bobot $w_k$. Kita menggunakan variasi indeks $n$ dan $m$ pada fungsi $Y_{2n}^{2m}$ untuk menyusun matriks SPL tersebut:


    $$\sum_{k}^{M}w_{k}Y_{2n}^{2m}(\theta_{k},\varphi_{k})=\int_{0}^{\pi/2}\int_{0}^{\pi/2}Y_{2n}^{2m}(\theta,\varphi)\sin\theta d\theta d\varphi$$

    *(Untuk $n=0,1,\cdots,N$; $m=0,1,\cdots,n$; total persamaan $M$)*.
    Dengan memecahkan matriks ini, kita akan mendapatkan bobot valid $w_k$ untuk set sudut arah apa pun yang dibentuk oleh ukuran modul kita.

    Untuk MOC 3D yang riil, menggambar dan membagi modul satu per satu secara manual itu mustahil. Sistem biasanya mengandalkan program CAD (seperti AutoCAD) yang diprogram khusus untuk otomatisasi. Alur kerja algoritmanya terdiri dari 3 bagian penting:

    1. Pemodelan Geometri dan Material (Geometric and Material Modeling)
        Di AutoCAD, kita dapat menggambar tabung, bola, atau balok untuk memodelkan pin bahan bakar. Namun AutoCAD standar tidak mengerti "material nuklir". Oleh karena itu, digunakan skrip VBA (Visual Basic) untuk menginjeksi informasi "Identitas Material" ke dalam objek AutoCAD menggunakan variabel khusus yang disebut *Xdata*. *Xdata* melekat permanen pada bentuk geometri sehingga meskipun bentuk tersebut dipotong-potong nanti, identitas materialnya tidak hilang.

    2. Modularisasi (Modularization)
    Setelah digambar penuh, geometri dipotong-potong seperti kue (mesh) secara otomatis dalam interval X, Y, dan Z yang sama ukurannya. Program akan memindai potongan demi potongan untuk menemukan "Modul Unik" (typical modules).

    **Detail Logika Sortir:** Bagaimana komputer tahu bahwa dua modul potong itu sama persis sehingga yang satu boleh dihapus dari memori?
    * Bandingkan jumlah entitas (benda) di dalam modul.
    * Bandingkan volume setiap benda.
    * Bandingkan identitas material benda.
    * Bandingkan pusat massa gravitasi setiap benda di dalamnya.
    Jika semuanya identik, modul tersebut dianggap redundan (terduplikasi), dicatat lokasinya di *ExtensionDictionary*, lalu dihapus untuk sangat menghemat RAM komputer.



    3. Pembuatan Segmen Sinar Modular (Modular Segments)
    MOC membutuhkan ukuran *panjang* sinar menembus suatu material. Sayangnya, memprogram komputer (API AutoCAD) untuk memotong objek solid 3D dengan sebuah garis 1D (sinar) secara matematis sangat rumit dan berat.
    
    **Trik yang digunakan:** Komputasinya diturunkan menjadi 2D!
    * Alih-alih memakai garis 3D, program menggunakan **permukaan datar 2D vertikal** (mengikuti pola arah sinar) untuk membelah objek 3D tersebut.
    * Hasil belahannya berbentuk penampang datar 2D (intersection surface regions).
    * Barulah program menembakkan sinar (yang direpresentasikan sebagai garis lurus 2D) untuk memotong penampang 2D tadi. Ini jauh lebih mudah dihitung secara komputasi untuk mendapatkan panjang persis sinar $S_k$ di setiap material.

##  <center> <b> Penyelesaian Aljabar  </b></center>

###  <center> <b> Pendahuluan Eigenvalue  </b></center>

#### Matriks sebagai Operator Transformasi

Sebuah matriks dapat dianggap sebagai **mesin transformasi**.

Misalkan terdapat vektor

$$
\mathbf{x}=
\begin{bmatrix}
1\\
0
\end{bmatrix}
$$

Artinya

- bergerak 1 langkah ke arah sumbu-x
- tidak bergerak pada sumbu-y

Sekarang terdapat matriks

$$
A=
\begin{bmatrix}
2&0\\
0&3
\end{bmatrix}
$$

Hitung

$$
A\mathbf{x}
=
\begin{bmatrix}
2&0\\
0&3
\end{bmatrix}
\begin{bmatrix}
1\\
0
\end{bmatrix}
$$

Perkalian matriks menghasilkan

$$
=
\begin{bmatrix}
2(1)+0(0)\\
0(1)+3(0)
\end{bmatrix}
=
\begin{bmatrix}
2\\
0
\end{bmatrix}
$$

**Interpretasi**

Vektor awal

$$
\begin{bmatrix}
1\\
0
\end{bmatrix}
$$

berubah menjadi

$$
\begin{bmatrix}
2\\
0
\end{bmatrix}
$$

Artinya

- arah tetap ke kanan
- panjang menjadi dua kali lipat

Matriks **tidak mengubah arah**, hanya memperbesar panjangnya.

#### Konsep Eigenvalue

Karena

$$
\begin{bmatrix}
2\\
0
\end{bmatrix}
=
2
\begin{bmatrix}
1\\
0
\end{bmatrix}
$$

maka dapat ditulis

$$
A\mathbf{x}=2\mathbf{x}
$$

Bandingkan dengan bentuk umum

$$
\boxed{A\mathbf{x}=\lambda\mathbf{x}}
$$

Sehingga

- eigenvector

$$
\mathbf{x}=
\begin{bmatrix}
1\\
0
\end{bmatrix}
$$

- eigenvalue

$$
\boxed{\lambda=2}
$$

> Eigenvalue merupakan **faktor pengali panjang suatu vektor yang arah transformasinya tetap**.

Misalnya

Jika

$$
\lambda=2
$$

maka panjang menjadi dua kali.

Jika

$$
\lambda=0.5
$$

maka panjang menjadi setengah.

Jika

$$
\lambda=-2
$$

maka

- panjang menjadi dua kali
- arah berbalik 180°


#### Cara Menemukan Eigenvalue

Misalkan matriks

$$
A=
\begin{bmatrix}
2&0\\
0&3
\end{bmatrix}
$$

Yang diketahui hanya matriks.

Eigenvalue belum diketahui.

Kita mulai dari definisi

$$
A\mathbf{x}=\lambda\mathbf{x}
$$


##### Langkah 1

Pindahkan semua ke kiri

$$
A\mathbf{x}-\lambda\mathbf{x}=0
$$

##### Langkah 2

**Kenapa tiba-tiba muncul matriks identitas?**

Ini bagian yang sering membingungkan.

Kita tidak bisa mengurangkan

$$
A-\lambda
$$

karena

- \(A\) adalah matriks
- \(\lambda\) hanyalah angka.

Supaya tipe matematikanya sama, angka harus diubah menjadi matriks.

Gunakan identitas

$$
I=
\begin{bmatrix}
1&0\\
0&1
\end{bmatrix}
$$

Karena

$$
I\mathbf{x}=\mathbf{x}
$$

maka

$$
\lambda\mathbf{x}
=
\lambda I\mathbf{x}
$$

Sehingga

$$
A\mathbf{x}-\lambda I\mathbf{x}=0
$$


##### Langkah 3

Sekarang kedua suku memiliki vektor yang sama.

Maka bisa difaktorkan

$$
(A-\lambda I)\mathbf{x}=0
$$

Inilah bentuk yang sangat penting.

**Penggunaan Determinan**

Inilah bagian yang biasanya membuat bingung.

Kita punya

$$
(A-\lambda I)\mathbf{x}=0
$$

Persamaan ini **selalu mempunyai solusi**

$$
\mathbf{x}=0
$$

tetapi

Eigenvector **tidak boleh nol**.

Kita ingin solusi

$$
\mathbf{x}\neq0
$$

**Kapan solusi non nol bisa muncul?**

Dalam sistem persamaan linear

$$
M\mathbf{x}=0
$$

terdapat dua kemungkinan.

##### Kasus 1

Jika

$$
\det(M)\neq0
$$

maka solusi hanya $\mathbf{x}=0$

##### Kasus 2

Jika

$$
\det(M)=0
$$

maka muncul solusi tak hingga. Artinya terdapat vektor selain nol.

Karena

$$
M=A-\lambda I
$$

maka syaratnya menjadi

$$
\boxed{\det(A-\lambda I)=0}
$$

Inilah asal-usul **Persamaan Karakteristik**.

**Contoh**

Misalkan

$$
A=
\begin{bmatrix}
2&0\\
0&3
\end{bmatrix}
$$

Hitung

$$
A-\lambda I
$$

$$
=
\begin{bmatrix}
2-\lambda&0\\
0&3-\lambda
\end{bmatrix}
$$

Hitung determinan

$$
(2-\lambda)(3-\lambda)=0
$$

Karena hasil kali nol

maka

$$
2-\lambda=0
$$

atau

$$
3-\lambda=0
$$

Sehingga

$$
\boxed{\lambda_1=2}
$$

$$
\boxed{\lambda_2=3}
$$

**Menemukan Eigenvector**

Misalkan

$$
\lambda=2
$$

Masukkan ke

$$
(A-\lambda I)\mathbf{x}=0
$$

Sehingga

$$
\begin{bmatrix}
0&0\\
0&1
\end{bmatrix}
\begin{bmatrix}
x\\
y
\end{bmatrix}
=
0
$$

Hasil perkalian

Baris pertama

$$
0x+0y=0
$$

Baris kedua

$$
0x+y=0
$$

Maka

$$
y=0
$$

Sedangkan

$$
x
$$

bebas dipilih.

Biasanya dipilih

$$
x=1
$$

Sehingga

$$
\boxed{
\mathbf{v}=
\begin{bmatrix}
1\\
0
\end{bmatrix}
}
$$

Kenapa x boleh sembarang?

> Karena Eigenvector menunjukkan **arah**, bukan panjang.

**Hubungan Dengan Sistem Persamaan Linear**

Misalkan terdapat

$$
2x+y=5
$$

$$
x+2y=4
$$

Ditulis menjadi

$$
A\mathbf{x}=\mathbf{b}
$$

dengan

$$
A=
\begin{bmatrix}
2&1\\
1&2
\end{bmatrix}
$$

$$
\mathbf{x}=
\begin{bmatrix}
x\\
y
\end{bmatrix}
$$

$$
\mathbf{b}=
\begin{bmatrix}
5\\
4
\end{bmatrix}
$$

Perhatikan bentuknya

Sistem linear biasa

$$
A\mathbf{x}=\mathbf{b}
$$

Sedangkan masalah eigen

$$
A\mathbf{x}=\lambda\mathbf{x}
$$

Perbedaannya hanya ruas kanan.

Pada sistem linear ruas kanan sudah diketahui.

Pada masalah eigen ruas kanan justru bergantung pada vektor itu sendiri.


#### Standard Eigenvalue Problem

Bentuk

$$
\boxed{
A\mathbf{x}
=
\lambda\mathbf{x}
}
$$

Hanya ada satu matriks.


#### Generalized Eigenvalue Problem

Bentuk

$$
\boxed{
A\mathbf{x}
=
\lambda B\mathbf{x}
}
$$

Sekarang ada dua matriks.

- Matriks pertama melakukan satu operasi.
- Matriks kedua melakukan operasi lain.
- Kita mencari nilai \(\lambda\) yang membuat kedua operasi tersebut seimbang untuk suatu vektor tertentu.

Jika

$$
B=I
$$

maka kembali menjadi

Standard Eigenvalue Problem.

#### Hubungan Dengan Persamaan Difusi Neutron

Persamaan difusi neutron satu kelompok

$$
-\nabla\cdot(D\nabla\phi)
+\Sigma_a\phi
=
\frac1{k_{eff}}
\nu\Sigma_f\phi
$$

Makna fisiknya

**Ruas kiri**

Semua neutron yang **hilang**

- bocor
- diserap

**Ruas kanan**

Semua neutron **baru** yang dihasilkan fisi.

**Setelah Diskretisasi**

Komputer tidak dapat langsung menyelesaikan persamaan diferensial.

Daerah reaktor dibagi menjadi banyak node.

Operator diferensial berubah menjadi matriks.

Sehingga

$$
\boxed{
A\phi
=
\frac1{k_{eff}}
F\phi
}
$$

di mana

- $A$ = matriks kehilangan neutron (difusi, absorpsi, dan dalam formulasi tertentu juga hamburan antarkelompok).
- #F$ = matriks produksi neutron akibat fisi.
- $\phi$ = distribusi fluks neutron.

**Mengapa Ini Disebut Generalized Eigenvalue Problem?**

Bandingkan

Eigen biasa

$$
A\mathbf{x}
=
\lambda\mathbf{x}
$$

Generalized

$$
A\phi
=
\lambda
F\phi
$$

dengan

$$
\lambda=\frac1{k_{eff}}
$$

Jadi yang dicari adalah

$$\phi \ dan \ k_{eff} $$

secara bersamaan.

#### Alur Besarnya

**1. Persamaan Linear**
$$A x = b$$
**Mencari:** $x$

**2. Eigenvalue Problem**
$$A x = \lambda x$$
**Mencari:** $\lambda$ dan $x$

**3. Generalized Eigenvalue**
$$A \phi = \lambda F \phi$$
**Mencari:** $\lambda$ dan $\phi$


**4. Persamaan Reaktor**
$$A \phi = \frac{1}{k_{\text{eff}}} F \phi$$
**Mencari:**
* Distribusi fluks neutron
* Nilai $k_{\text{eff}}$

####  <center> <b> Metode Penyelesaian Inner </b></center>

#####  <center> <b> Metode Jacobi </b></center>

#### Konsep Dasar Metode Jacobi

Metode Jacobi adalah metode iteratif untuk menyelesaikan sistem persamaan linear:

$$
A\mathbf{x}=\mathbf{b}
$$

dengan:

- $A$: matriks koefisien berukuran $n\times n$.
- $\mathbf{x}$: vektor variabel yang ingin dicari.
- $\mathbf{b}$: vektor ruas kanan.
- $n$: jumlah persamaan dan variabel.
- $k$: indeks iterasi.

Metode Jacobi mencari solusi secara bertahap melalui pendekatan berulang.

**Prinsip utama:** setiap komponen solusi baru dihitung menggunakan komponen-komponen dari iterasi sebelumnya.

**Dekomposisi Matriks**

Dalam pembahasan ini, kita menggunakan konvensi:

$$
\boxed{A=D-L-U}
$$

dengan:

- $D$: matriks diagonal yang memuat elemen diagonal $A$.
- $L$: Lower/bagian segitiga bawah dengan tanda negatif dari elemen asli $A$.
- $U$: Upper/bagian segitiga atas dengan tanda negatif dari elemen asli $A$.

Secara matematis:

$$
D=
\begin{bmatrix}
a_{11}&0&\cdots&0\\
0&a_{22}&\cdots&0\\
\vdots&\vdots&\ddots&\vdots\\
0&0&\cdots&a_{nn}
\end{bmatrix}
$$

$$
L=
\begin{bmatrix}
0&0&\cdots&0\\
-a_{21}&0&\cdots&0\\
\vdots&\vdots&\ddots&\vdots\\
-a_{n1}&-a_{n2}&\cdots&0
\end{bmatrix}
$$

$$
U=
\begin{bmatrix}
0&-a_{12}&\cdots&-a_{1n}\\
0&0&\cdots&-a_{2n}\\
\vdots&\vdots&\ddots&\vdots\\
0&0&\cdots&0
\end{bmatrix}
$$

#### Menurunkan Persamaan Jacobi dari Dekomposisi

Mulai dari sistem:

$$
A\mathbf{x}=\mathbf{b}
$$

Substitusikan dekomposisi $A=D-L-U$:

$$
(D-L-U)\mathbf{x}=\mathbf{b}
$$

Kembangkan perkalian matriks:

$$
D\mathbf{x}-L\mathbf{x}-U\mathbf{x}=\mathbf{b}
$$

Pindahkan suku $-L\mathbf{x}$ dan $-U\mathbf{x}$ ke ruas kanan:

$$
\boxed{D\mathbf{x}=\mathbf{b}+(L+U)\mathbf{x}}
$$

Sampai tahap ini, persamaan masih merupakan bentuk aljabar yang ekuivalen dengan sistem awal.

Untuk membentuk iterasi Jacobi, gunakan nilai pendekatan sebelumnya pada ruas kanan dan nilai baru pada ruas kiri:

$$
\boxed{
D\mathbf{x}^{(k+1)}
=
\mathbf{b}+(L+U)\mathbf{x}^{(k)}
}
$$

Karena $D$ merupakan matriks diagonal dan setiap $a_{ii}\ne0$, matriks $D$ dapat diinvers.

Kalikan kedua ruas dengan $D^{-1}$:

$$
\mathbf{x}^{(k+1)}
=
D^{-1}\mathbf{b}
+
D^{-1}(L+U)\mathbf{x}^{(k)}
$$

Definisikan vektor konstanta:

$$
\boxed{\boldsymbol{\beta}=D^{-1}\mathbf{b}}
$$

dan matriks iterasi Jacobi:

$$
\boxed{B=D^{-1}(L+U)}
$$

Dengan demikian, bentuk ringkas metode Jacobi adalah:

$$
\boxed{
\mathbf{x}^{(k+1)}
=
\boldsymbol{\beta}+B\mathbf{x}^{(k)}
}
$$

**Penurunan Rumus Komponen ke-$i$**

Dengan menggunakan contoh matriks tiga variabel:

$$
A=
\begin{bmatrix}
a_{11}&a_{12}&a_{13}\\
a_{21}&a_{22}&a_{23}\\
a_{31}&a_{32}&a_{33}
\end{bmatrix}
$$

Dengan konvensi yang digunakan:

$$
L+U=
\begin{bmatrix}
0&-a_{12}&-a_{13}\\
-a_{21}&0&-a_{23}\\
-a_{31}&-a_{32}&0
\end{bmatrix}
$$

Perkalian dengan vektor iterasi menghasilkan:

$$
(L+U)\mathbf{x}^{(k)}
=
\begin{bmatrix}
-a_{12}x_2^{(k)}-a_{13}x_3^{(k)}\\
-a_{21}x_1^{(k)}-a_{23}x_3^{(k)}\\
-a_{31}x_1^{(k)}-a_{32}x_2^{(k)}
\end{bmatrix}
$$

Tambahkan $\mathbf{b}$:

$$
\mathbf{b}+(L+U)\mathbf{x}^{(k)}
=
\begin{bmatrix}
b_1-a_{12}x_2^{(k)}-a_{13}x_3^{(k)}\\
b_2-a_{21}x_1^{(k)}-a_{23}x_3^{(k)}\\
b_3-a_{31}x_1^{(k)}-a_{32}x_2^{(k)}
\end{bmatrix}
$$

Dengan demikian, komponen ke-$i$ pada ruas kanan adalah:

$$
\boxed{
b_i-\sum_{\substack{j=1\\j\ne i}}^n
a_{ij}x_j^{(k)}
}
$$


Maka persamaan baris ke-$i$ menjadi:

$$
a_{ii}x_i^{(k+1)}
=
b_i-
\sum_{\substack{j=1\\j\ne i}}^n
a_{ij}x_j^{(k)}
$$

Bagi kedua ruas dengan $a_{ii}$:

$$
x_i^{(k+1)}
=
\frac{b_i}{a_{ii}}
-
\sum_{\substack{j=1\\j\ne i}}^n
\frac{a_{ij}}{a_{ii}}x_j^{(k)}
$$

Definisikan:

$$
\boxed{\beta_i=\frac{b_i}{a_{ii}}}
$$

dan koefisien iterasi:

$$
\boxed{\beta_{ij}=-\frac{a_{ij}}{a_{ii}},\quad j\ne i}
$$

Maka diperoleh rumus komponen Jacobi:

$$
\boxed{
x_i^{(k+1)}
=
\beta_i+
\sum_{\substack{j=1\\j\ne i}}^n
\beta_{ij}x_j^{(k)}
}
$$


Jika variabel iterasi menggunakan simbol $\xi_i$, bentuk yang sama menjadi:

$$
\boxed{
\xi_i^{(k+1)}
=
\beta_i+
\sum_{\substack{j=1\\j\ne i}}^n
\beta_{ij}\xi_j^{(k)}
}
$$

**Penting:** dengan konvensi $A=D-L-U$ yang digunakan di sini, koefisien iterasi adalah $\beta_{ij}=-a_{ij}/a_{ii}$. Tanda negatif ini tetap diperlukan karena $L$ dan $U$ telah didefinisikan sebagai negatif dari bagian luar diagonal $A$.

#### Konvergensi Metode Jacobi

Dari bentuk iterasi:

$$
\mathbf{x}^{(k+1)}
=
\boldsymbol{\beta}+B\mathbf{x}^{(k)}
$$

dengan:

$$
B=D^{-1}(L+U)
$$

Misalkan $\mathbf{x}^*$ adalah solusi eksak. Karena solusi eksak memenuhi:

$$
\mathbf{x}^*=\boldsymbol{\beta}+B\mathbf{x}^*
$$

definisikan galat:

$$
\mathbf{e}^{(k)}
=
\mathbf{x}^{(k)}-\mathbf{x}^*
$$

Kurangkan persamaan solusi eksak dari persamaan iterasi:

$$
\begin{aligned}
\mathbf{e}^{(k+1)}
&=\mathbf{x}^{(k+1)}-\mathbf{x}^*\\
&=\boldsymbol{\beta}+B\mathbf{x}^{(k)}
-\left(\boldsymbol{\beta}+B\mathbf{x}^*\right)\\
&=B\left(\mathbf{x}^{(k)}-\mathbf{x}^*\right)
\end{aligned}
$$

Sehingga:

$$
\boxed{\mathbf{e}^{(k+1)}=B\mathbf{e}^{(k)}}
$$

Dengan menerapkan persamaan tersebut berulang kali:

$$
\boxed{\mathbf{e}^{(k)}=B^k\mathbf{e}^{(0)}}
$$

Konvergensi untuk setiap tebakan awal dijamin jika spectral radius matriks iterasi memenuhi:

$$
\boxed{\rho(B)<1}
$$

dengan:

$$
\rho(B)=\max_i|\lambda_i(B)|
$$

di mana $\lambda_i(B)$ merupakan eigenvalue matriks iterasi $B$.

Dominasi diagonal ketat pada setiap baris merupakan salah satu kondisi cukup yang umum untuk menjamin konvergensi Jacobi.


#### Algoritma Jacobi

1. Siapkan sistem $A\mathbf{x}=\mathbf{b}$.
2. Dekomposisikan matriks menggunakan $A=D-L-U$.
3. Tentukan tebakan awal $\mathbf{x}^{(0)}$.
4. Hitung setiap komponen baru menggunakan seluruh nilai dari iterasi sebelumnya.
5. Hitung perubahan solusi.
6. Hentikan iterasi jika kriteria toleransi terpenuhi; jika belum, ulangi.

Salah satu kriteria penghentian adalah:

$$
\left\|\mathbf{x}^{(k+1)}-\mathbf{x}^{(k)}\right\|_\infty
<\varepsilon
$$

dengan $\varepsilon$ merupakan toleransi numerik yang dipilih.

Perubahan yang kecil saja tidak selalu menjamin bahwa solusi sudah akurat jika metode tidak konvergen.

**Penerapan dalam Difusi Neutron**

Setelah persamaan difusi neutron didiskretisasi, sistem linear yang dihasilkan dapat ditulis sebagai:

$$
A\boldsymbol{\phi}=\mathbf{q}
$$

dengan:

- $\boldsymbol{\phi}$: vektor fluks neutron pada node atau sel komputasi.
- $A$: matriks operator diskret yang mencakup kontribusi kebocoran dan interaksi neutron.
- $\mathbf{q}$: vektor sumber neutron.

Metode Jacobi dapat memperbarui fluks setiap node berdasarkan nilai fluks node lain dari iterasi sebelumnya.

Untuk sistem ini, bentuk iterasinya adalah:

$$
\boldsymbol{\phi}^{(k+1)}
=
D^{-1}\mathbf{q}
+
D^{-1}(L+U)\boldsymbol{\phi}^{(k)}
$$

Metode Jacobi adalah metode penyelesaian sistem linear. Dalam perhitungan eigenvalue reaktor, metode ini dapat digunakan sebagai bagian dari algoritma yang lebih besar, tetapi tidak dengan sendirinya menyelesaikan masalah eigenvalue reaktor.

#####  <center> <b> Gauss Siedel </b></center>

#### Konsep Dasar Metode Gauss-Seidel

Metode Gauss-Seidel adalah metode iteratif untuk menyelesaikan sistem persamaan linear:

$$
A\mathbf{x}=\mathbf{b}
$$

Gunakan konvensi dekomposisi yang sama seperti pada metode Jacobi:

$$
\boxed{A=D-L-U}
$$

dengan $D$ bagian diagonal matriks $A$, sedangkan $L$ dan $U$ adalah bagian segitiga bawah dan atas yang elemennya bertanda negatif terhadap elemen asli $A$. Indeks $k$ menyatakan iterasi.

**Prinsip utama:** Gauss-Seidel memperbarui komponen solusi secara berurutan. Nilai yang sudah dihitung pada iterasi baru langsung digunakan, sedangkan komponen yang belum dihitung masih memakai nilai iterasi sebelumnya.

#### Menurunkan Persamaan Gauss-Seidel dari Dekomposisi

Mulai dari sistem dan substitusikan $A=D-L-U$:

$$
(D-L-U)\mathbf{x}=\mathbf{b}
$$

Untuk membentuk iterasi, gunakan nilai baru pada bagian segitiga bawah dan nilai lama pada bagian segitiga atas:

$$
(D-L)\mathbf{x}^{(k+1)}=\mathbf{b}+U\mathbf{x}^{(k)}
$$

Pindahkan semua suku ke ruas kiri, lalu kalikan dengan $-1$:

$$
\boxed{\mathbf{b}+L\mathbf{x}^{(k+1)}-D\mathbf{x}^{(k+1)}+U\mathbf{x}^{(k)}=\mathbf{0}}
$$

Bentuk ekuivalennya adalah:

$$
\boxed{(D-L)\mathbf{x}^{(k+1)}=\mathbf{b}+U\mathbf{x}^{(k)}}
$$

Karena $D-L$ matriks segitiga bawah, sistem ini dapat diselesaikan berurutan dengan substitusi maju. Bentuk iterasi eksplisitnya:

$$
\mathbf{x}^{(k+1)}=(D-L)^{-1}\mathbf{b}+(D-L)^{-1}U\mathbf{x}^{(k)}
$$

Invers biasanya tidak dibentuk secara eksplisit; sistem segitiga bawah diselesaikan langsung.

**Penurunan Rumus Komponen ke-$i$**

Baris ke-$i$ dari sistem adalah:

$$
a_{ii}x_i+\sum_{j=1}^{i-1}a_{ij}x_j+\sum_{j=i+1}^{n}a_{ij}x_j=b_i
$$

Komponen dengan indeks lebih kecil dari $i$ sudah diperbarui, sedangkan komponen yang lebih besar masih memakai iterasi lama:

$$
a_{ii}x_i^{(k+1)}+\sum_{j=1}^{i-1}a_{ij}x_j^{(k+1)}+\sum_{j=i+1}^{n}a_{ij}x_j^{(k)}=b_i
$$

Pindahkan suku selain diagonal ke ruas kanan dan bagi dengan $a_{ii}$ (dengan syarat $a_{ii}\ne0$):

$$
\boxed{x_i^{(k+1)}=\frac{1}{a_{ii}}\left(b_i-\sum_{j=1}^{i-1}a_{ij}x_j^{(k+1)}-\sum_{j=i+1}^{n}a_{ij}x_j^{(k)}\right)}
$$

Perbedaan dengan Jacobi adalah penggunaan $x_j^{(k+1)}$ untuk $j<i$; Jacobi menggunakan nilai iterasi lama untuk semua komponen pada ruas kanan.

**Contoh tiga variabel**

Untuk sistem:

$$
\begin{aligned}
a_{11}x_1+a_{12}x_2+a_{13}x_3&=b_1,\\
a_{21}x_1+a_{22}x_2+a_{23}x_3&=b_2,\\
a_{31}x_1+a_{32}x_2+a_{33}x_3&=b_3,
\end{aligned}
$$

pembaruan berurutannya:

$$
x_1^{(k+1)}=\frac{b_1-a_{12}x_2^{(k)}-a_{13}x_3^{(k)}}{a_{11}}
$$

$$
x_2^{(k+1)}=\frac{b_2-a_{21}x_1^{(k+1)}-a_{23}x_3^{(k)}}{a_{22}}
$$

$$
x_3^{(k+1)}=\frac{b_3-a_{31}x_1^{(k+1)}-a_{32}x_2^{(k+1)}}{a_{33}}
$$

#### Konvergensi Metode Gauss-Seidel

Matriks iterasinya adalah:

$$
\mathbf{x}^{(k+1)}=(D-L)^{-1}\mathbf{b}+(D-L)^{-1}U\mathbf{x}^{(k)}
$$

Untuk galat $\mathbf{e}^{(k)}=\mathbf{x}^{(k)}-\mathbf{x}^*$ terhadap solusi eksak $\mathbf{x}^*$:

$$
\boxed{\mathbf{e}^{(k+1)}=B_{GS}\mathbf{e}^{(k)}}
$$

Konvergensi untuk setiap tebakan awal dijamin jika:

$$
\boxed{\rho(B_{GS})<1}
$$

dengan $\rho$ spectral radius matriks iterasi. Dominasi diagonal ketat pada setiap baris merupakan salah satu kondisi cukup yang umum, tetapi bukan satu-satunya.

#### Algoritma Gauss-Seidel

1. Siapkan sistem $A\mathbf{x}=\mathbf{b}$ dan tebakan awal $\mathbf{x}^{(0)}$.
2. Untuk setiap iterasi, hitung komponen $i=1,2,\ldots,n$ secara berurutan memakai rumus di atas.
3. Gunakan nilai baru untuk komponen yang telah diperbarui dan nilai lama untuk komponen yang belum diperbarui.
4. Hentikan iterasi jika, misalnya, $\|\mathbf{x}^{(k+1)}-\mathbf{x}^{(k)}\|_\infty<\varepsilon$; jika belum, lanjutkan.

Perubahan iterasi yang kecil tidak selalu menjamin solusi akurat apabila metode tidak konvergen. Hasilnya juga dapat bergantung pada urutan pembaruan variabel.

**Penerapan dalam Difusi Neutron**

Jika sistem hasil diskretisasi ditulis sebagai $A\boldsymbol{\phi}=\mathbf{q}$, iterasi Gauss-Seidel adalah:

$$
\boxed{(D-L)\boldsymbol{\phi}^{(k+1)}=\mathbf{q}+U\boldsymbol{\phi}^{(k)}}
$$

Fluks pada node diperbarui berurutan dan nilai baru langsung digunakan untuk node berikutnya. Gauss-Seidel menyelesaikan sistem linear; pada perhitungan eigenvalue reaktor, metode ini dapat menjadi penyelesai inner untuk masalah sumber tetap, tetapi tidak dengan sendirinya menyelesaikan masalah eigenvalue.

#####  <center> <b> SOR </b></center>

#### Konsep Dasar Metode SOR

Metode **Successive Over-Relaxation (SOR)** merupakan pengembangan metode Gauss-Seidel. Untuk sistem persamaan linear:

$$
A\mathbf{x}=\mathbf{b}
$$

digunakan dekomposisi yang sama seperti pada metode Jacobi dan Gauss-Seidel:

$$
\boxed{A=D-L-U}
$$

dengan $D$ bagian diagonal matriks $A$, sementara $L$ dan $U$ adalah bagian segitiga bawah dan atas yang elemennya bertanda negatif terhadap elemen asli $A$.

SOR menggunakan parameter relaksasi $\omega$ untuk mengatur besar perubahan pada setiap pembaruan:

- $\omega=1$: SOR sama dengan Gauss-Seidel.
- $0<\omega<1$: **under-relaxation**, pembaruan dibuat lebih kecil.
- $1<\omega<2$: **over-relaxation**, pembaruan diperbesar untuk mempercepat konvergensi pada sistem yang sesuai.

### Apa Arti Parameter Relaksasi $\omega$?

Misalkan $x_{i,GS}^{(k+1)}$ adalah nilai komponen yang akan diberikan oleh langkah Gauss-Seidel. Selisih antara nilai itu dan nilai lama disebut koreksi Gauss-Seidel:

$$
\Delta x_i^{(k)}=x_{i,GS}^{(k+1)}-x_i^{(k)}
$$

SOR tidak selalu mengambil seluruh koreksi tersebut. SOR mengambil fraksi $\omega$ dari koreksi, sehingga:

$$
x_i^{(k+1)}=x_i^{(k)}+\omega\Delta x_i^{(k)}
$$

Jadi, $\omega$ mengatur **panjang langkah** dari nilai lama ke arah nilai Gauss-Seidel. Parameter ini bukan perubahan ruas kanan atau perubahan sistem linear; nilai solusi eksaknya tetap sama, tetapi jalur iterasi untuk mendekati solusi itu berubah.

**Contoh sederhana:** jika nilai lama $x_i^{(k)}=2$ dan langkah Gauss-Seidel memberi $x_{i,GS}^{(k+1)}=5$, maka koreksinya $\Delta x_i^{(k)}=3$.

| $\omega$ | Perhitungan | Nilai baru | Makna |
|---:|---|---:|---|
| $0.5$ | $2+0.5(3)$ | $3.5$ | Mengambil setengah koreksi (under-relaxation). |
| $1$ | $2+1(3)$ | $5$ | Mengambil tepat koreksi Gauss-Seidel. |
| $1.2$ | $2+1.2(3)$ | $5.6$ | Melewati nilai Gauss-Seidel (over-relaxation). |

Under-relaxation dapat membuat iterasi lebih terkendali pada masalah tertentu, tetapi juga dapat memperlambat kemajuan. Over-relaxation mencoba mengurangi jumlah iterasi dengan melangkah melewati nilai Gauss-Seidel; jika langkah terlalu besar, iterasi dapat berosilasi atau divergen. Karena itu, $\omega>1$ **tidak otomatis** membuat metode lebih cepat. Nilai yang baik bergantung pada matriks, urutan pembaruan, dan sifat masalah, dan biasanya dipilih dengan memantau konvergensi. Untuk matriks simetris positif definit, SOR konvergen jika $0<\omega<2$; batas ini tidak berarti setiap nilai dalam rentang tersebut sama cepatnya.

#### Menurunkan Persamaan SOR dari Gauss-Seidel

Dengan konvensi $A=D-L-U$, baris ke-$i$ pada pembaruan Gauss-Seidel menggunakan nilai terbaru untuk komponen yang telah dihitung:

$$
a_{ii}x_{i,GS}^{(k+1)}=b_i-\sum_{j=1}^{i-1}a_{ij}x_j^{(k+1)}-\sum_{j=i+1}^{n}a_{ij}x_j^{(k)}
$$

SOR mengalikan perubahan dari nilai lama menuju nilai Gauss-Seidel dengan parameter relaksasi $\omega$:

$$
x_i^{(k+1)}=x_i^{(k)}+\omega\left(x_{i,GS}^{(k+1)}-x_i^{(k)}\right)
$$

Susun ulang:

$$
x_i^{(k+1)}=(1-\omega)x_i^{(k)}+\omega x_{i,GS}^{(k+1)}
$$

Substitusikan rumus komponen Gauss-Seidel:

$$
x_i^{(k+1)}=(1-\omega)x_i^{(k)}+\frac{\omega}{a_{ii}}\left(b_i-\sum_{j=1}^{i-1}a_{ij}x_j^{(k+1)}-\sum_{j=i+1}^{n}a_{ij}x_j^{(k)}\right)
$$

Kalikan kedua ruas dengan $a_{ii}$, lalu pindahkan suku yang memuat komponen baru ke ruas kiri:

$$
a_{ii}x_i^{(k+1)}+\omega\sum_{j=1}^{i-1}a_{ij}x_j^{(k+1)}=\omega b_i+(1-\omega)a_{ii}x_i^{(k)}-\omega\sum_{j=i+1}^{n}a_{ij}x_j^{(k)}
$$

Menggabungkan persamaan untuk semua baris dan memakai $L_{ij}=-a_{ij}$ serta $U_{ij}=-a_{ij}$ menghasilkan:

$$
\boxed{(D-\omega L)\mathbf{x}^{(k+1)}=\omega\mathbf{b}+\left[(1-\omega)D+\omega U\right]\mathbf{x}^{(k)}}
$$

Karena $D-\omega L$ matriks segitiga bawah, sistem ini dapat diselesaikan berurutan dengan substitusi maju. Bentuk iterasi eksplisitnya adalah:

$$
\mathbf{x}^{(k+1)}=(D-\omega L)^{-1}\left\{\omega\mathbf{b}+\left[(1-\omega)D+\omega U\right]\mathbf{x}^{(k)}\right\}
$$

Invers tidak perlu dibentuk secara eksplisit; pada setiap iterasi cukup menyelesaikan sistem segitiga bawah.

#### Penurunan Rumus Komponen ke-$i$

Baris ke-$i$ dari sistem linear adalah:

$$
a_{ii}x_i+\sum_{j=1}^{i-1}a_{ij}x_j+\sum_{j=i+1}^{n}a_{ij}x_j=b_i
$$

Nilai Gauss-Seidel untuk komponen ke-$i$ dihitung menggunakan komponen baru untuk $j<i$ dan nilai lama untuk $j>i$:

$$
x_{i,GS}^{(k+1)}=\frac{1}{a_{ii}}\left(b_i-\sum_{j=1}^{i-1}a_{ij}x_j^{(k+1)}-\sum_{j=i+1}^{n}a_{ij}x_j^{(k)}\right)
$$

SOR mencampurkan nilai lama dengan nilai Gauss-Seidel:

$$
x_i^{(k+1)}=(1-\omega)x_i^{(k)}+\omega x_{i,GS}^{(k+1)}
$$

Substitusikan rumus $x_{i,GS}^{(k+1)}$:

$$
\boxed{x_i^{(k+1)}=(1-\omega)x_i^{(k)}+\frac{\omega}{a_{ii}}\left(b_i-\sum_{j=1}^{i-1}a_{ij}x_j^{(k+1)}-\sum_{j=i+1}^{n}a_{ij}x_j^{(k)}\right)}
$$

Seperti Gauss-Seidel, pembaruan dilakukan berurutan: nilai baru untuk $j<i$ langsung digunakan, sedangkan nilai lama digunakan untuk $j>i$.

**Contoh tiga variabel**

Untuk sistem tiga variabel, rumus pembaruannya adalah:

$$
x_1^{(k+1)}=(1-\omega)x_1^{(k)}+\frac{\omega}{a_{11}}\left(b_1-a_{12}x_2^{(k)}-a_{13}x_3^{(k)}\right)
$$

$$
x_2^{(k+1)}=(1-\omega)x_2^{(k)}+\frac{\omega}{a_{22}}\left(b_2-a_{21}x_1^{(k+1)}-a_{23}x_3^{(k)}\right)
$$

$$
x_3^{(k+1)}=(1-\omega)x_3^{(k)}+\frac{\omega}{a_{33}}\left(b_3-a_{31}x_1^{(k+1)}-a_{32}x_2^{(k+1)}\right)
$$

#### Konvergensi Metode SOR

Bentuk iterasi SOR dapat ditulis sebagai:

$$
\mathbf{x}^{(k+1)}=\boldsymbol{\beta}_{SOR}+B_{SOR}\mathbf{x}^{(k)}
$$

dengan:

$$
\boldsymbol{\beta}_{SOR}=\omega(D-\omega L)^{-1}\mathbf{b}
$$

$$
B_{SOR}=(D-\omega L)^{-1}\left[(1-\omega)D+\omega U\right]
$$

Untuk galat $\mathbf{e}^{(k)}=\mathbf{x}^{(k)}-\mathbf{x}^*$ terhadap solusi eksak $\mathbf{x}^*$, berlaku:

$$
\boxed{\mathbf{e}^{(k+1)}=B_{SOR}\mathbf{e}^{(k)}}
$$

Konvergensi untuk setiap tebakan awal dijamin jika:

$$
\boxed{\rho(B_{SOR})<1}
$$

Untuk matriks $A$ yang simetris positif definit, SOR konvergen jika $0<\omega<2$. Nilai $\omega$ terbaik bergantung pada sistem; nilai yang terlalu kecil atau terlalu besar dapat membuat konvergensi lebih lambat atau menyebabkan divergensi.

#### Algoritma SOR

1. Siapkan sistem $A\mathbf{x}=\mathbf{b}$, tebakan awal $\mathbf{x}^{(0)}$, toleransi $\varepsilon$, dan parameter $\omega$.
2. Untuk setiap iterasi, hitung komponen $x_i^{(k+1)}$ berurutan menggunakan rumus SOR.
3. Gunakan nilai baru untuk komponen yang telah diperbarui dan nilai lama untuk komponen yang belum diperbarui.
4. Periksa kriteria berhenti, misalnya:

$$
\left\|\mathbf{x}^{(k+1)}-\mathbf{x}^{(k)}\right\|_\infty<\varepsilon
$$

5. Jika toleransi belum terpenuhi, lanjutkan iterasi.

#### Penerapan dalam Difusi Neutron

Jika sistem hasil diskretisasi difusi neutron ditulis sebagai $A\boldsymbol{\phi}=\mathbf{q}$, persamaan iterasi SOR adalah:

$$
\boxed{(D-\omega L)\boldsymbol{\phi}^{(k+1)}=\omega\mathbf{q}+\left[(1-\omega)D+\omega U\right]\boldsymbol{\phi}^{(k)}}
$$

Parameter $\omega$ mengatur seberapa jauh fluks baru bergerak dari nilai sebelumnya menuju hasil Gauss-Seidel. SOR tetap merupakan metode penyelesaian sistem linear; pada perhitungan eigenvalue reaktor, SOR dapat digunakan sebagai penyelesai inner untuk masalah sumber tetap, tetapi tidak dengan sendirinya menyelesaikan masalah eigenvalue.

####  <center> <b> Metode Penyelesaian Outter </b></center>

#####  <center> <b> CMFD </b></center>

##### Posisi CMFD di dalam penyelesaian deterministik

Pada masalah eigenvalue reaktor, **outer iteration** mencari bentuk fluks fisi dan faktor multiplikasi efektif $k_{eff}$. Untuk suatu tebakan sumber fisi, metode high-order seperti $S_N$ atau MOC menyelesaikan persamaan transport diskret; iterasi sumber hamburan dan sweep untuk menyelesaikan masalah sumber tetap termasuk proses inner.

CMFD (*Coarse-Mesh Finite Difference*) menghubungkan hasil transport high-order dengan persamaan neraca neutron/difusi berorde rendah pada mesh lebih kasar. Persamaan kasar menghitung koreksi fluks/sumber dan koreksi dikembalikan ke transport. CMFD mempercepat konvergensi outer/source iteration; ia bukan pengganti persamaan transport high-order atau model fisika baru. Letaknya dalam loop berbeda antar-kode.

##### Persamaan deterministik yang diselesaikan

Persamaan transport multigrup tunak masalah eigenvalue:

$$
\boldsymbol{\Omega}\cdot\nabla\psi_g(\mathbf{r},\boldsymbol{\Omega})+\Sigma_{t,g}\psi_g=\sum_{g'=1}^{G}\int_{4\pi}\Sigma_{s,g'\to g}(\boldsymbol{\Omega}'\to\boldsymbol{\Omega})\psi_{g'}(\boldsymbol{\Omega}')\,d\Omega'+\frac{\chi_g}{4\pi k_{eff}}\sum_{g'=1}^{G}\nu\Sigma_{f,g'}\phi_{g'}
$$

Setelah diskretisasi ruang, energi, dan arah:

$$
\boxed{\mathbf{A}\boldsymbol{\phi}=\frac{1}{k_{eff}}\mathbf{F}\boldsymbol{\phi}},\qquad \mathbf{A}=\mathbf{L}-\mathbf{S}
$$

Untuk outer ke-$n$, masalah sumber tetap yang diselesaikan high-order:

$$
\boxed{\mathbf{A}\boldsymbol{\phi}^{(n+1)}=\frac{1}{k_{eff}^{(n)}}\mathbf{F}\boldsymbol{\phi}^{(n)}}
$$

$\mathbf{A}$ mencakup streaming/kebocoran, removal, dan pengurangan hamburan menurut konvensi ini; $\mathbf{F}$ adalah operator produksi fisi. CMFD memakai hasil high-order untuk membangun sistem koreksi kasar.

##### Menurunkan neraca neutron sel kasar

Untuk memperoleh bentuk ringkas berikut, anggap hamburan isotropik; pada hamburan anisotropik, suku hamburan harus ditulis dengan momen sudut yang sesuai. Integralkan persamaan transport terhadap arah (momen sudut):

$$
\nabla\cdot\mathbf{J}_g+\Sigma_{t,g}\phi_g=\sum_{g'=1}^{G}\Sigma_{s,g'\to g}\phi_{g'}+\frac{\chi_g}{k_{eff}}\sum_{g'=1}^{G}\nu\Sigma_{f,g'}\phi_{g'}
$$

Definisikan removal dan pindahkan hamburan dalam-grup ke kiri:

$$
\Sigma_{r,g}=\Sigma_{t,g}-\Sigma_{s,g\to g},\qquad \nabla\cdot\mathbf{J}_g+\Sigma_{r,g}\phi_g=\sum_{g'\ne g}\Sigma_{s,g'\to g}\phi_{g'}+\frac{\chi_g}{k_{eff}}\sum_{g'}\nu\Sigma_{f,g'}\phi_{g'}
$$

Integralkan pada sel kasar $V_I$ dan gunakan teorema divergensi, $\int_{V_I}\nabla\cdot\mathbf{J}\,dV=\oint_{\partial V_I}\mathbf{J}\cdot\mathbf{n}\,dA$. Dengan nilai rata-rata sel:

$$
\boxed{\sum_{f\in\partial I}A_fJ_{g,I,f}+V_I\Sigma_{r,g,I}\phi_{g,I}=V_I\sum_{g'\ne g}\Sigma_{s,g'\to g,I}\phi_{g',I}+\frac{V_I\chi_{g,I}}{k_{eff}}\sum_{g'=1}^{G}\nu\Sigma_{f,g',I}\phi_{g',I}}
$$

$J_{g,I,f}$ adalah arus keluar melalui muka $f$, positif ke luar sel. Persamaan menyatakan kebocoran bersih + removal = hamburan masuk + produksi fisi; inilah neraca dasar CMFD.

##### Homogenisasi high-order ke coarse-mesh

Jika sel kasar $I$ berisi sel high-order $i$, fluks rata-rata volume:

$$
\phi_{g,I}^{HO}=\frac{\sum_{i\in I}V_i\phi_{g,i}^{HO}}{V_I},\qquad V_I=\sum_{i\in I}V_i
$$

Contoh penampang homogen yang menjaga laju reaksi:

$$
\Sigma_{r,g,I}=\frac{\sum_iV_i\Sigma_{r,g,i}\phi_{g,i}^{HO}}{\sum_iV_i\phi_{g,i}^{HO}},\qquad \Sigma_{s,g'\to g,I}=\frac{\sum_iV_i\Sigma_{s,g'\to g,i}\phi_{g',i}^{HO}}{\sum_iV_i\phi_{g',i}^{HO}}
$$

$$
\nu\Sigma_{f,g',I}=\frac{\sum_iV_i\nu\Sigma_{f,g',i}\phi_{g',i}^{HO}}{\sum_iV_i\phi_{g',i}^{HO}}
$$

Spektrum fisi $\chi_{g,I}$ lazimnya dibobot dengan produksi fisi. Rumus homogenisasi dapat bervariasi; prinsipnya mempertahankan laju reaksi saat mengubah mesh.

##### Penurunan koreksi arus CMFD

Difusi biasa mengaproksimasi arus hanya dari gradien fluks. Pada mesh kasar, gradien dapat tidak mewakili arus transport. Untuk sel tetangga $I,J$ pada muka $f$ (arah positif dari $I$ ke $J$), gunakan:

$$
J_{g,f}^{CMFD}=-D_{g,f}\frac{\phi_{g,J}-\phi_{g,I}}{d_f}+\widehat D_{g,f}(\phi_{g,I}+\phi_{g,J})
$$

Samakan dengan arus high-order $J_{g,f}^{HO}$ pada fluks high-order iterasi kini, lalu isolasi $\widehat D$:

$$
J_{g,f}^{HO}=-D_{g,f}\frac{\phi_{g,J}^{HO}-\phi_{g,I}^{HO}}{d_f}+\widehat D_{g,f}(\phi_{g,I}^{HO}+\phi_{g,J}^{HO})
$$

$$
\boxed{\widehat D_{g,f}=\frac{J_{g,f}^{HO}+D_{g,f}(\phi_{g,J}^{HO}-\phi_{g,I}^{HO})/d_f}{\phi_{g,I}^{HO}+\phi_{g,J}^{HO}}}
$$

Maka arus CMFD mereproduksi arus high-order pada fluks pembentuk koefisien. Jika penyebut mendekati nol, rasio tidak stabil dan perlu safeguards. $D$ adalah koefisien difusi muka (umumnya terkait $D_g\approx1/(3\Sigma_{tr,g})$); rata-rata muka dan perlakuan batas bergantung geometri/kode.

##### Penurunan stencil CMFD 1D

Untuk slab 1D berluas satuan, neraca grup $g$ dalam sel $i$ (lebar $h_i$):

$$
J_{g,i+1/2}-J_{g,i-1/2}+h_i\Sigma_{r,g,i}\phi_{g,i}=h_i\sum_{g'\ne g}\Sigma_{s,g'\to g,i}\phi_{g',i}+\frac{h_i\chi_{g,i}}{k_{eff}}\sum_{g'}\nu\Sigma_{f,g',i}\phi_{g',i}
$$

Arus positif ke arah $+x$, sehingga arus keluar bersih adalah kanan dikurangi kiri. Relasi pada muka kanan dan kiri:

$$
J_{g,i+1/2}=-D_{g,i+1/2}\frac{\phi_{g,i+1}-\phi_{g,i}}{d_{i+1/2}}+\widehat D_{g,i+1/2}(\phi_{g,i+1}+\phi_{g,i})
$$

$$
J_{g,i-1/2}=-D_{g,i-1/2}\frac{\phi_{g,i}-\phi_{g,i-1}}{d_{i-1/2}}+\widehat D_{g,i-1/2}(\phi_{g,i}+\phi_{g,i-1})
$$

Kurangkan arus kiri dari kanan dan kelompokkan koefisien:

$$
\begin{aligned}
&J_{g,i+1/2}-J_{g,i-1/2}={}\left(\frac{D_{g,i+1/2}}{d_{i+1/2}}+\frac{D_{g,i-1/2}}{d_{i-1/2}}+\widehat D_{g,i+1/2}-\widehat D_{g,i-1/2}\right)\phi_{g,i} \\
&+\left(-\frac{D_{g,i+1/2}}{d_{i+1/2}}+\widehat D_{g,i+1/2}\right)\phi_{g,i+1}+\left(-\frac{D_{g,i-1/2}}{d_{i-1/2}}-\widehat D_{g,i-1/2}\right)\phi_{g,i-1}
\end{aligned}
$$

Substitusikan ke neraca sel; removal menambah diagonal:

$$
\begin{aligned}
&\left[\frac{D_{g,i+1/2}}{d_{i+1/2}}+\frac{D_{g,i-1/2}}{d_{i-1/2}}+\widehat D_{g,i+1/2}-\widehat D_{g,i-1/2}+h_i\Sigma_{r,g,i}\right]\phi_{g,i} \\
&+\left[-\frac{D_{g,i+1/2}}{d_{i+1/2}}+\widehat D_{g,i+1/2}\right]\phi_{g,i+1}+\left[-\frac{D_{g,i-1/2}}{d_{i-1/2}}-\widehat D_{g,i-1/2}\right]\phi_{g,i-1} \\
&=h_i\sum_{g'\ne g}\Sigma_{s,g'\to g,i}\phi_{g',i}+\frac{h_i\chi_{g,i}}{k_{eff}}\sum_{g'}\nu\Sigma_{f,g',i}\phi_{g',i}
\end{aligned}
$$

Gabungkan semua sel dan grup energi:

$$
\boxed{\mathbf{A}_{CMFD}\boldsymbol{\Phi}=\frac{1}{k_{eff}}\mathbf{F}_{CMFD}\boldsymbol{\Phi}}
$$

$\mathbf{A}_{CMFD}$ merangkum kebocoran, removal, hamburan; $\mathbf{F}_{CMFD}$ merangkum fisi; $\boldsymbol{\Phi}$ adalah fluks semua sel kasar dan grup.

##### Algoritma outer dengan CMFD

1. **Inisialisasi:** tebakan fluks positif $\phi_{g,i}^{(0)}$, sumber fisi, $k_{eff}^{(0)}$, toleransi, dan pemetaan mesh high-order ke kasar.
2. **Bentuk sumber:** hitung sumber fisi dari fluks dan $k$ tebakan; siapkan sumber hamburan.
3. **Selesaikan high-order:** lakukan sweep $S_N$/MOC dan inner iteration hamburan sampai kriteria inner tercapai; hitung fluks dan arus high-order.
4. **Proyeksi/homogenisasi:** hitung fluks kasar, penampang berbobot laju reaksi, dan arus pada muka kasar.
5. **Bangun sistem CMFD:** hitung $D_{g,f}$ dan $\widehat D_{g,f}$; susun persamaan neraca semua sel/grup.
6. **Selesaikan coarse-mesh:** misalnya power iteration, untuk indeks CMFD $m$:

$$
\mathbf{A}_{CMFD}\boldsymbol{\Phi}^{(m+1)}=\frac{1}{k_{CMFD}^{(m)}}\mathbf{F}_{CMFD}\boldsymbol{\Phi}^{(m)}
$$

Perbarui eigenvalue dari produksi fisi dan normalkan fluks. Beberapa kode menggunakan sistem fixed-source untuk koreksi, bukan eigenproblem kasar penuh.
7. **Kembalikan koreksi:** untuk grup $g$ dan sel kasar $I$:

$$
C_{g,I}=\frac{\Phi_{g,I}^{CMFD,new}}{\Phi_{g,I}^{CMFD,old}},\qquad \phi_{g,i}^{HO,new}=C_{g,I}\phi_{g,i}^{HO,old}\quad(i\in I)
$$

Ini ide koreksi coarse-to-fine; pembaruan fluks sudut/sumber bergantung kode.
8. **Perbarui $k$ dan normalkan:** dapat memakai eigenvalue CMFD atau rasio produksi fisi high-order:

$$
k_{eff}^{(n+1)}=k_{eff}^{(n)}\frac{P^{(n+1)}}{P^{(n)}},\qquad P^{(n)}=\sum_I V_I\sum_g\nu\Sigma_{f,g,I}\Phi_{g,I}^{(n)}
$$

9. **Uji konvergensi:** pantau perubahan relatif $k_{eff}$, bentuk fluks/sumber fisi, dan residual high-order. Jika belum toleran, ulangi dari pembentukan sumber; pemeriksaan akhir tetap berdasarkan solusi high-order.

##### Arti simbol dan notasi

- $\psi_g(\mathbf{r},\boldsymbol{\Omega})$: fluks sudut posisi $\mathbf{r}$, arah $\boldsymbol{\Omega}$, grup $g$; $\phi_g=\int_{4\pi}\psi_gd\Omega$: fluks skalar.
- $\mathbf{J}_g=\int_{4\pi}\boldsymbol{\Omega}\psi_gd\Omega$: arus grup $g$; $J_{g,I,f}$: arus pada muka $f$, positif keluar sel.
- $g,g'$: indeks grup tujuan/asal; $G$: jumlah grup; $i$: sel high-order; $I$: sel kasar; $f$: muka; $\partial I$: muka batas sel.
- $\Sigma_t$: penampang total; $\Sigma_s$: penampang hamburan; $\Sigma_r=\Sigma_t-\Sigma_{s,g\to g}$: penampang removal; $\nu\Sigma_f$: produksi fisi; $\chi$: fraksi spektrum fisi.
- $k_{eff}$: faktor multiplikasi efektif/eigenvalue; $\mathbf{A}=\mathbf{L}-\mathbf{S}$: operator high-order; $\mathbf{F}$: operator fisi.
- $V_i,V_I$: volume sel kecil/kasar; $A_f$: luas muka; $h_i$: lebar slab; $d_f,d_{i\pm1/2}$: jarak antarpusat sel bertetangga.
- $D_{g,f}$: koefisien difusi muka; $\Sigma_{tr,g}$: penampang transport; $\widehat D_{g,f}$: koefisien koreksi arus.
- $\mathbf{A}_{CMFD},\mathbf{F}_{CMFD}$: operator neraca dan fisi coarse-mesh; $\boldsymbol{\Phi}$: vektor fluks kasar; superskrip $HO$/$CMFD$: high-order/low-order.
- $n$: outer iteration; $m$: iterasi eigenvalue CMFD; $C_{g,I}$: faktor koreksi fluks kasar baru/lama; $P^{(n)}$: produksi fisi total; $\varepsilon$: toleransi; $\nabla\cdot$: divergensi; $\mathbf{n}$: normal keluar.

**Inti metode:** solusi transport menghasilkan fluks dan arus high-order; neraca coarse-mesh menjaga keseimbangan neutron; koreksi arus membuat arus low-order konsisten dengan transport; solusi CMFD memperbaiki tebakan outer agar bentuk sumber fisi dan $k_{eff}$ lebih cepat konvergen.

##  <center> <b> Deplesi  </b></center>

#### Persamaan dasar deplesi dan notasi

Untuk $M$ nuklida, definisikan vektor densitas atom $\mathbf N(t)=[N_1,\ldots,N_M]^T$. Persamaan deplesi:

$$\boxed{\frac{d\mathbf N}{dt}=\mathbf A(\mathbf N,t)\mathbf N,\qquad \mathbf N(t_0)=\mathbf N_0.}$$

Dengan konvensi kolom=induk $j$, baris=produk $i$:

$$A_{ij}=q_{j\to i}\;(i\ne j),\quad A_{jj}=-\ell_j,$$

$$q_{j\to i}=\lambda_{j\to i}+\sum_r y_{j\to i,r}\sigma_{j,r}\phi_r,\qquad \ell_j=\lambda_j+\sum_r\sigma_{j,r}\phi_r.$$

$\lambda_{j\to i}=b_{j\to i}\lambda_j$ adalah konstanta peluruhan parsial; $b$ fraksi cabang; $y$ hasil produk per reaksi neutron. Indeks $r$ hanya mencakup reaksi nuklir yang mengubah nuklida (misalnya tangkapan, fisi, atau reaksi partikel bermuatan), bukan hamburan elastik yang tidak mengubah nuklida. Reaksi menuju nuklida yang tidak dilacak tetap termasuk pada kehilangan diagonal, tetapi tidak menambah elemen off-diagonal. Karena fluks neutron dan laju reaksi berubah bersama komposisi, umumnya $\mathbf A=\mathbf A(\mathbf N,t)$.

Jika $\mathbf A$ konstan selama langkah $h$, solusi tepat adalah $\mathbf N(t_0+h)=e^{h\mathbf A}\mathbf N_0$. Metode integrasi di bawah mengaproksimasi perubahan $\mathbf A$ dan/atau aksi eksponensial pada vektor.

##### Matriks contoh rantai tiga nuklida

Untuk rantai $X_1\rightarrow X_2\rightarrow X_3$, $q_1,q_2$ adalah laju transisi per atom induk dan $q_3$ kehilangan $X_3$ ke luar rantai:

$$\boxed{\mathbf A_3(t)=\begin{bmatrix}-q_1(t)&0&0\\q_1(t)&-q_2(t)&0\\0&q_2(t)&-q_3(t)\end{bmatrix}},\quad \dot{\mathbf N}=\mathbf A_3\mathbf N,\quad \mathbf N=\begin{bmatrix}N_1\\N_2\\N_3\end{bmatrix}.$$

Untuk rantai tanpa cabang dan peluruhan murni $X_1\xrightarrow{\lambda_1}X_2\xrightarrow{\lambda_2}X_3$ dengan $X_3$ stabil, $q_1=\lambda_1$, $q_2=\lambda_2$, $q_3=0$. Jika ada cabang ke produk tak terlacak, koefisien kehilangan diagonal harus memuat seluruh peluruhan tetapi elemen produksi ke $X_2$ atau $X_3$ dikalikan fraksi cabang. Dalam iradiasi, $q_j$ juga memuat laju reaksi neutron. Matriks contoh yang sama dicantumkan pada setiap metode.

Dengan:

- $N_i$: densitas atom nuklida ke-$i$; satuan atom $\mathrm{cm}^{-3}$.
- $\mathbf N$: vektor densitas atom semua nuklida; satuan atom $\mathrm{cm}^{-3}$.
- $t$: waktu; satuan sekon (s).
- $h$: ukuran langkah waktu; satuan sekon (s).
- $\mathbf A$: matriks deplesi atau transmutasi; satuan $s^{-1}$.
- $A_{ij}$: koefisien produksi nuklida $i$ dari nuklida $j$; satuan $s^{-1}$.
- $q_{j\to i}$: laju transisi dari induk $j$ ke produk $i$ per atom induk; satuan $s^{-1}$.
- $\ell_j$: laju kehilangan total nuklida $j$ per atom; satuan $s^{-1}$.
- $\lambda_j$: konstanta peluruhan total nuklida $j$; satuan $s^{-1}$.
- $\lambda_{j\to i}$: konstanta peluruhan parsial dari $j$ ke $i$; satuan $s^{-1}$.
- $b_{j\to i}$: fraksi cabang peluruhan menuju $i$; tak berdimensi.
- $r$: indeks kanal reaksi neutron; tak berdimensi.
- $\sigma_{j,r}$: penampang mikroskopik kanal $r$ pada nuklida $j$; satuan $\mathrm{cm}^{2}$.
- $\phi_r$: fluks neutron efektif untuk kanal $r$; satuan $\mathrm{cm}^{-2}\,\mathrm{s}^{-1}$.
- $y_{j\to i,r}$: hasil nuklida produk $i$ per reaksi pada nuklida induk $j$; satuan atom per reaksi.
- $\mathbf N_0$: vektor densitas atom pada waktu awal $t_0$; satuan sama dengan $\mathbf N$.
- $e^{h\mathbf A}$: eksponensial matriks untuk satu langkah waktu; tak berdimensi.

**Kopling transport-deplesi:** transport menghitung fluks/laju reaksi dari komposisi saat ini; deplesi memperbarui komposisi, yang selanjutnya mengubah transport. Karena itu matriks laju diperbarui selama iradiasi.

#### Laju reaksi, perakitan matriks, dan langkah burnup

Untuk satu nuklida $j$ dalam grup energi $g$, laju reaksi per atom adalah $r_{j,r,g}=\sigma_{j,r,g}\phi_g$; laju reaksi per volume adalah $N_j r_{j,r,g}$. Dengan banyak grup:

$$
r_{j,r}=\sum_g\sigma_{j,r,g}\phi_g,\qquad R_{j,r}=N_j r_{j,r}.
$$

Satuan $r_{j,r}$ ialah $\mathrm{s}^{-1}$ dan $R_{j,r}$ ialah reaksi $\mathrm{cm}^{-3}\,\mathrm{s}^{-1}$. Untuk setiap kanal yang menghilangkan induk $j$, tambahkan lajunya ke $\ell_j$. Untuk setiap produk $i$ yang dilacak, tambahkan $y_{j\to i,r}r_{j,r}$ ke $A_{ij}$. Tambahkan konstanta peluruhan total ke diagonal negatif dan konstanta peluruhan parsial $b_{j\to i}\lambda_j$ ke elemen produksi. Dengan demikian setiap kolom matriks mewakili neraca satu induk:

$$
\frac{dN_i}{dt}=\sum_{j\ne i}A_{ij}N_j+A_{ii}N_i.
$$

Untuk reaksi tangkapan satu-produk $X_1(n,\gamma)X_2$ dan peluruhan $X_2\to X_3$, misalnya, laju transisi pertama dapat ditulis $q_1=\lambda_{1\to2}+\sigma_{1,\gamma}\phi$; laju kedua $q_2=\lambda_{2\to3}$, jika reaksi lain diabaikan. Jika tangkapan atau peluruhan bercabang, pecah laju produksi menurut hasil/fraksi cabang.

##### Urutan kopling transport-deplesi

1. Pada komposisi $\mathbf N_i$ dan kondisi daya/iradiasi, selesaikan transport untuk memperoleh fluks grup $\phi_g$ dan laju reaksi.
2. Bangun matriks $\mathbf A_i$ dari laju reaksi neutron, konstanta peluruhan, cabang peluruhan, dan yield produk.
3. Integrasikan selama langkah $h_i=t_{i+1}-t_i$ memakai salah satu metode pada sel berikutnya; hasilnya $\mathbf N_{i+1}$.
4. Perbarui komposisi dan penampang makroskopik, lalu hitung ulang transport dan $\mathbf A$ pada langkah berikutnya.
5. Jika daya total ditetapkan, skala fluks terhadap target daya dengan menggunakan laju fisi dan energi recoverable per fisi yang konsisten; daya tidak boleh disamakan dengan fluks tanpa faktor penampang, densitas, volume, dan energi.

Dengan:

- $i$: indeks langkah burnup; dibedakan dari indeks nuklida.
- $g$: indeks grup energi.
- $r$: indeks kanal reaksi nuklir.
- $R_{j,r}$: laju reaksi volumetrik untuk nuklida $j$ dan kanal $r$; satuan reaksi $\mathrm{cm}^{-3}\,\mathrm{s}^{-1}$.
- $\phi_g$: fluks neutron pada grup energi $g$; satuan $\mathrm{cm}^{-2}\,\mathrm{s}^{-1}$.
- $h_i$: ukuran langkah burnup ke-$i$; satuan waktu.

Konstanta peluruhan dan laju reaksi per atom harus memakai satuan waktu yang sama.

#### Constant Extrapolation (CE)

Bekukan matriks pada awal langkah, $\mathbf A_0=\mathbf A(\mathbf N_0,t_0)$. ODE menjadi $\dot{\mathbf N}=\mathbf A_0\mathbf N$ sehingga:

$$\boxed{\mathbf N_1=e^{h\mathbf A_0}\mathbf N_0.}$$

Dari ODE, $\mathbf N''=(\dot{\mathbf A}_0+\mathbf A_0^2)\mathbf N_0$. Solusi sejati:

$$\mathbf N(t_0+h)=\mathbf N_0+h\mathbf A_0\mathbf N_0+\frac{h^2}{2}(\dot{\mathbf A}_0+\mathbf A_0^2)\mathbf N_0+O(h^3).$$

Ekspansi CE tidak memuat suku $\dot{\mathbf A}_0$, jadi metode berorde satu jika laju berubah. Untuk peluruhan murni dengan $\mathbf A$ konstan, CE eksponensial tepat.

**Contoh matriks tiga nuklida:** untuk $X_1\to X_2\to X_3$,

$$\mathbf A_3(t)=\begin{bmatrix}-q_1(t)&0&0\\q_1(t)&-q_2(t)&0\\0&q_2(t)&-q_3(t)\end{bmatrix},\qquad \mathbf N=\begin{bmatrix}N_1\\N_2\\N_3\end{bmatrix}.$$

Dengan:

- $X_1,X_2,X_3$: nuklida dalam rantai peluruhan berurutan.
- $q_1,q_2$: laju transisi per atom dari $X_1$ ke $X_2$ dan dari $X_2$ ke $X_3$; satuan $s^{-1}$.
- $q_3$: laju kehilangan $X_3$ ke luar rantai; satuan $s^{-1}$.
- $\lambda_1,\lambda_2$: konstanta peluruhan pada contoh peluruhan murni; jika $X_3$ stabil, $q_3=0$.
- $\mathbf A_3$: matriks transmutasi rantai tiga nuklida; satuan $s^{-1}$.

Pada iradiasi, laju $q_j$ dapat mencakup reaksi neutron dan bergantung pada fluks serta komposisi. Jika $\mathbf A_3$ konstan, propagasi eksponensial menyelesaikan rantai tepat.

#### Constant Extrapolation / Constant Midpoint (CE/CM)

Hitung $\mathbf A_0=\mathbf A(\mathbf N_0,t_0)$ dan prediksi titik tengah:

$$\mathbf N_{1/2}^{p}=e^{(h/2)\mathbf A_0}\mathbf N_0.$$

Evaluasi ulang $\mathbf A_{1/2}=\mathbf A(\mathbf N_{1/2}^{p},t_0+h/2)$, lalu bekukan untuk satu langkah penuh dari kondisi awal:

$$\boxed{\mathbf N_1^{CE/CM}=e^{h\mathbf A_{1/2}}\mathbf N_0.}$$

Nilai titik tengah mengaproksimasi matriks rata-rata pada langkah dengan galat orde dua; CE/CM berorde dua pada asumsi regularitas yang sesuai. Matriks koreksi diterapkan pada $\mathbf N_0$, bukan pada prediksi tengah. Urutan kerja: evaluasi awal, prediksi tengah, evaluasi ulang laju/transport, lalu koreksi.

**Contoh matriks tiga nuklida:** untuk $X_1\to X_2\to X_3$,

$$\mathbf A_3(t)=\begin{bmatrix}-q_1(t)&0&0\\q_1(t)&-q_2(t)&0\\0&q_2(t)&-q_3(t)\end{bmatrix},\qquad \mathbf N=\begin{bmatrix}N_1\\N_2\\N_3\end{bmatrix}.$$

Dengan:

- $X_1,X_2,X_3$: nuklida dalam rantai peluruhan berurutan.
- $q_1,q_2$: laju transisi per atom dari $X_1$ ke $X_2$ dan dari $X_2$ ke $X_3$; satuan $s^{-1}$.
- $q_3$: laju kehilangan $X_3$ ke luar rantai; satuan $s^{-1}$.
- $\lambda_1,\lambda_2$: konstanta peluruhan pada contoh peluruhan murni; jika $X_3$ stabil, $q_3=0$.
- $\mathbf A_3$: matriks transmutasi rantai tiga nuklida; satuan $s^{-1}$.

Pada iradiasi, laju $q_j$ dapat mencakup reaksi neutron dan bergantung pada fluks serta komposisi. Jika $\mathbf A_3$ konstan, propagasi eksponensial menyelesaikan rantai tepat.

#### Constant Extrapolation / Linear Interpolation (CE/LI)

Prediksi ujung dengan CE dan hitung matriks di ujung prediksi:

$$\mathbf N_1^p=e^{h\mathbf A_0}\mathbf N_0,\qquad \mathbf A_1=\mathbf A(\mathbf N_1^p,t_0+h).$$

Interpolasi matriks untuk $0\le\tau\le h$:

$$\widehat{\mathbf A}(\tau)=\left(1-\frac{\tau}{h}\right)\mathbf A_0+\frac{\tau}{h}\mathbf A_1.$$

Integralkan interpolasi:

$$\overline{\mathbf A}=\frac1h\int_0^h\widehat{\mathbf A}(\tau)d\tau=\frac{\mathbf A_0+\mathbf A_1}{2},\qquad \boxed{\mathbf N_1=e^{h\overline{\mathbf A}}\mathbf N_0.}$$

Untuk $m$ sublangkah, $\tau_s=(s-1/2)h/m$, $\mathbf B_s=(h/m)\widehat{\mathbf A}(\tau_s)$, lalu $\mathbf N_1\approx e^{\mathbf B_m}\cdots e^{\mathbf B_1}\mathbf N_0$. Urutan penting karena matriks pada waktu berbeda umumnya tidak komutatif.

Dengan:

- $p$: superskrip yang menandai nilai prediksi.
- $s$: indeks sublangkah.
- $m$: jumlah sublangkah dalam satu langkah burnup.
- $\tau_s$: waktu lokal titik tengah sublangkah ke-$s$.
- $\mathbf B_s$: matriks eksponen untuk sublangkah ke-$s$; tak berdimensi.

**Contoh matriks tiga nuklida:** untuk $X_1\to X_2\to X_3$,

$$\mathbf A_3(t)=\begin{bmatrix}-q_1(t)&0&0\\q_1(t)&-q_2(t)&0\\0&q_2(t)&-q_3(t)\end{bmatrix},\qquad \mathbf N=\begin{bmatrix}N_1\\N_2\\N_3\end{bmatrix}.$$

Dengan:

- $X_1,X_2,X_3$: nuklida dalam rantai peluruhan berurutan.
- $q_1,q_2$: laju transisi per atom dari $X_1$ ke $X_2$ dan dari $X_2$ ke $X_3$; satuan $s^{-1}$.
- $q_3$: laju kehilangan $X_3$ ke luar rantai; satuan $s^{-1}$.
- $\lambda_1,\lambda_2$: konstanta peluruhan pada contoh peluruhan murni; jika $X_3$ stabil, $q_3=0$.
- $\mathbf A_3$: matriks transmutasi rantai tiga nuklida; satuan $s^{-1}$.

Pada iradiasi, laju $q_j$ dapat mencakup reaksi neutron dan bergantung pada fluks serta komposisi. Jika $\mathbf A_3$ konstan, propagasi eksponensial menyelesaikan rantai tepat.

#### Ekspansi Magnus dan commutator-free CE/LI

Untuk ODE nonotonom $\dot{\mathbf N}=\widehat{\mathbf A}(\tau)\mathbf N$, solusi ditulis $\mathbf N_1=e^{\boldsymbol\Omega(h)}\mathbf N_0$. Suku awal Magnus:

$$\boldsymbol\Omega_1=\int_0^h\widehat{\mathbf A}(\tau_1)d\tau_1,$$

$$\boldsymbol\Omega_2=\frac12\int_0^h d\tau_1\int_0^{\tau_1}d\tau_2[\widehat{\mathbf A}(\tau_1),\widehat{\mathbf A}(\tau_2)],\quad [X,Y]=XY-YX.$$

Komutator merepresentasikan efek urutan matriks; jika matriks saling komutatif, suku ini nol. CF4 mengaproksimasi efek Magnus dengan produk eksponensial tanpa membentuk komutator. Ambil dua titik Gauss:

$$c_{1,2}=\frac12\mp\frac{\sqrt3}{6},\quad \mathbf B_j=h\widehat{\mathbf A}(c_jh),\quad a_1=\frac14+\frac{\sqrt3}{6},\quad a_2=\frac14-\frac{\sqrt3}{6}.$$

$$\boxed{\mathbf N_1\approx e^{a_2\mathbf B_1+a_1\mathbf B_2}e^{a_1\mathbf B_1+a_2\mathbf B_2}\mathbf N_0.}$$

Pada varian CE/LI Magnus, $\widehat{\mathbf A}$ diperoleh dari interpolasi linear matriks awal dan akhir. Faktor paling kanan dalam produk eksponensial diterapkan lebih dahulu.

Dengan:

- $\widehat{\mathbf A}(t)$: matriks laju hasil interpolasi terhadap waktu.
- $c_j$: posisi titik kuadratur ke-$j$ yang dinormalisasi terhadap langkah.
- $a_j$: koefisien kombinasi matriks pada metode CF4.
- $\mathbf B_j$: matriks laju di titik kuadratur setelah dikalikan ukuran langkah; tak berdimensi.

**Contoh matriks tiga nuklida:** untuk $X_1\to X_2\to X_3$,

$$\mathbf A_3(t)=\begin{bmatrix}-q_1(t)&0&0\\q_1(t)&-q_2(t)&0\\0&q_2(t)&-q_3(t)\end{bmatrix},\qquad \mathbf N=\begin{bmatrix}N_1\\N_2\\N_3\end{bmatrix}.$$

Dengan:

- $X_1,X_2,X_3$: nuklida dalam rantai peluruhan berurutan.
- $q_1,q_2$: laju transisi per atom dari $X_1$ ke $X_2$ dan dari $X_2$ ke $X_3$; satuan $s^{-1}$.
- $q_3$: laju kehilangan $X_3$ ke luar rantai; satuan $s^{-1}$.
- $\lambda_1,\lambda_2$: konstanta peluruhan pada contoh peluruhan murni; jika $X_3$ stabil, $q_3=0$.
- $\mathbf A_3$: matriks transmutasi rantai tiga nuklida; satuan $s^{-1}$.

Pada iradiasi, laju $q_j$ dapat mencakup reaksi neutron dan bergantung pada fluks serta komposisi. Jika $\mathbf A_3$ konstan, propagasi eksponensial menyelesaikan rantai tepat.

#### Lie-group commutator-free CF4

Pada langkah $[t_i,t_i+h]$, hitung tahap:

$$\begin{aligned}
\mathbf B_1&=h\mathbf A(\mathbf N_i,t_i),&\widehat{\mathbf N}_1&=e^{\mathbf B_1/2}\mathbf N_i,\\
\mathbf B_2&=h\mathbf A(\widehat{\mathbf N}_1,t_i+h/2),&\widehat{\mathbf N}_2&=e^{\mathbf B_2/2}\mathbf N_i,\\
\mathbf B_3&=h\mathbf A(\widehat{\mathbf N}_2,t_i+h/2),&\widehat{\mathbf N}_3&=e^{-\mathbf B_1/2+\mathbf B_3}\widehat{\mathbf N}_1,\\
\mathbf B_4&=h\mathbf A(\widehat{\mathbf N}_3,t_i+h).&&
\end{aligned}$$

Koreksi akhir:

$$\boxed{\mathbf N_{i+1}=e^{\mathbf B_1/4+\mathbf B_2/6+\mathbf B_3/6-\mathbf B_4/12}e^{-\mathbf B_1/12+\mathbf B_2/6+\mathbf B_3/6+\mathbf B_4/4}\mathbf N_i.}$$

Jumlah bobot kedua eksponen untuk $\mathbf B_1,\ldots,\mathbf B_4$ adalah $1/6,1/3,1/3,1/6$, sama dengan bobot Simpson. Produk dua eksponensial memperhitungkan ketakkomutatifan; skema berorde empat ini memerlukan empat evaluasi matriks/transport.

Dengan:

- $t_i$: waktu awal langkah ke-$i$.
- $\mathbf B_j$: matriks laju tahap ke-$j$ dikalikan ukuran langkah; tak berdimensi.
- $\widehat{\mathbf N}_j$: vektor densitas pada tahap prediksi untuk mengevaluasi matriks laju.
- $h$: ukuran langkah waktu.

**Contoh matriks tiga nuklida:** untuk $X_1\to X_2\to X_3$,

$$\mathbf A_3(t)=\begin{bmatrix}-q_1(t)&0&0\\q_1(t)&-q_2(t)&0\\0&q_2(t)&-q_3(t)\end{bmatrix},\qquad \mathbf N=\begin{bmatrix}N_1\\N_2\\N_3\end{bmatrix}.$$

Dengan:

- $X_1,X_2,X_3$: nuklida dalam rantai peluruhan berurutan.
- $q_1,q_2$: laju transisi per atom dari $X_1$ ke $X_2$ dan dari $X_2$ ke $X_3$; satuan $s^{-1}$.
- $q_3$: laju kehilangan $X_3$ ke luar rantai; satuan $s^{-1}$.
- $\lambda_1,\lambda_2$: konstanta peluruhan pada contoh peluruhan murni; jika $X_3$ stabil, $q_3=0$.
- $\mathbf A_3$: matriks transmutasi rantai tiga nuklida; satuan $s^{-1}$.

Pada iradiasi, laju $q_j$ dapat mencakup reaksi neutron dan bergantung pada fluks serta komposisi. Jika $\mathbf A_3$ konstan, propagasi eksponensial menyelesaikan rantai tepat.

#### Extended Predictor-Corrector eksponensial (EPC)

Untuk koefisien Runge-Kutta $a_{kj},b_j,c_j$, bentuk tahap:

$$\widehat{\mathbf N}_1=\mathbf N_i,\quad \widehat{\mathbf N}_k=\exp\!\left(h\sum_{j<k}a_{kj}\mathbf A(\widehat{\mathbf N}_j,t_i+c_jh)\right)\mathbf N_i,$$

$$\boxed{\mathbf N_{i+1}=\exp\!\left(h\sum_{j=1}^{s}b_j\mathbf A(\widehat{\mathbf N}_j,t_i+c_jh)\right)\mathbf N_i.}$$

Untuk tableau RK4 klasik, $c=(0,1/2,1/2,1)$, $a_{21}=a_{32}=1/2$, $a_{43}=1$, $b=(1/6,1/3,1/3,1/6)$. Definisikan $\mathbf B_j=h\mathbf A(\widehat{\mathbf N}_j,t_i+c_jh)$, dengan tahap $\widehat{\mathbf N}_1=\mathbf N_i$, $\widehat{\mathbf N}_2=e^{\mathbf B_1/2}\mathbf N_i$, $\widehat{\mathbf N}_3=e^{\mathbf B_2/2}\mathbf N_i$, $\widehat{\mathbf N}_4=e^{\mathbf B_3}\mathbf N_i$. Maka:

$$\boxed{\mathbf N_{i+1}=\exp\!\left(\frac{\mathbf B_1}{6}+\frac{\mathbf B_2}{3}+\frac{\mathbf B_3}{3}+\frac{\mathbf B_4}{6}\right)\mathbf N_i.}$$

Rumus ini menggabungkan matriks tahap memakai bobot RK4, bukan penjumlahan RK4 standar pada vektor.

Dengan:

- $s$: jumlah tahap.
- $c_j$: posisi tahap ke-$j$ di dalam langkah.
- $a_{kj}$: koefisien yang membentuk tahap $k$ dari tahap-tahap sebelumnya.
- $b_j$: bobot tahap $j$ pada pembaruan akhir.
- $\mathbf B_j$: matriks laju tahap ke-$j$ dikalikan $h$; tak berdimensi.
- $\widehat{\mathbf N}_j$: vektor prediksi pada tahap ke-$j$.

**Contoh matriks tiga nuklida:** untuk $X_1\to X_2\to X_3$,

$$\mathbf A_3(t)=\begin{bmatrix}-q_1(t)&0&0\\q_1(t)&-q_2(t)&0\\0&q_2(t)&-q_3(t)\end{bmatrix},\qquad \mathbf N=\begin{bmatrix}N_1\\N_2\\N_3\end{bmatrix}.$$

Dengan:

- $X_1,X_2,X_3$: nuklida dalam rantai peluruhan berurutan.
- $q_1,q_2$: laju transisi per atom dari $X_1$ ke $X_2$ dan dari $X_2$ ke $X_3$; satuan $s^{-1}$.
- $q_3$: laju kehilangan $X_3$ ke luar rantai; satuan $s^{-1}$.
- $\lambda_1,\lambda_2$: konstanta peluruhan pada contoh peluruhan murni; jika $X_3$ stabil, $q_3=0$.
- $\mathbf A_3$: matriks transmutasi rantai tiga nuklida; satuan $s^{-1}$.

Pada iradiasi, laju $q_j$ dapat mencakup reaksi neutron dan bergantung pada fluks serta komposisi. Jika $\mathbf A_3$ konstan, propagasi eksponensial menyelesaikan rantai tepat.

#### Stochastic Implicit Euler (SIE)

Matriks laju dievaluasi pada komposisi akhir yang belum diketahui:

$$\boxed{\mathbf N_{i+1}=e^{h\mathbf A(\mathbf N_{i+1},t_i+h)}\mathbf N_i.}$$

Mulai dari tebakan $\mathbf N_{i+1}^{(0)}$. Jika laju transport memiliki noise statistik, iterasi titik tetap dapat direlaksasi:

$$\widehat{\mathbf A}^{(m)}=\mathbf A(\mathbf N_{i+1}^{(m)},t_i+h),$$

$$\boxed{\mathbf N_{i+1}^{(m+1)}=(1-\alpha_m)\mathbf N_{i+1}^{(m)}+\alpha_m e^{h\widehat{\mathbf A}^{(m)}}\mathbf N_i,\quad 0<\alpha_m\le1.}$$

Hentikan iterasi saat perubahan komposisi dan estimasi laju memenuhi toleransi statistik/numerik. SIE dasar berorde satu; evaluasi transport berulang meningkatkan biaya. Stabilitas dan konvergensi bergantung pada sistem serta pengaturan iterasi.

Dengan:

- $m$: indeks iterasi koreksi di dalam satu langkah burnup.
- $\alpha_m$: bobot relaksasi pada iterasi ke-$m$; tak berdimensi.
- $\widehat{\mathbf A}^{(m)}$: matriks laju yang dievaluasi pada tebakan komposisi iterasi ke-$m$.

**Contoh matriks tiga nuklida:** untuk $X_1\to X_2\to X_3$,

$$\mathbf A_3(t)=\begin{bmatrix}-q_1(t)&0&0\\q_1(t)&-q_2(t)&0\\0&q_2(t)&-q_3(t)\end{bmatrix},\qquad \mathbf N=\begin{bmatrix}N_1\\N_2\\N_3\end{bmatrix}.$$

Dengan:

- $X_1,X_2,X_3$: nuklida dalam rantai peluruhan berurutan.
- $q_1,q_2$: laju transisi per atom dari $X_1$ ke $X_2$ dan dari $X_2$ ke $X_3$; satuan $s^{-1}$.
- $q_3$: laju kehilangan $X_3$ ke luar rantai; satuan $s^{-1}$.
- $\lambda_1,\lambda_2$: konstanta peluruhan pada contoh peluruhan murni; jika $X_3$ stabil, $q_3=0$.
- $\mathbf A_3$: matriks transmutasi rantai tiga nuklida; satuan $s^{-1}$.

Pada iradiasi, laju $q_j$ dapat mencakup reaksi neutron dan bergantung pada fluks serta komposisi. Jika $\mathbf A_3$ konstan, propagasi eksponensial menyelesaikan rantai tepat.

#### CRAM untuk eksponensial matriks

CRAM (*Chebyshev Rational Approximation Method*) menghitung $e^{h\mathbf A}\mathbf N_0$ setelah matriks langkah ditentukan; ia bukan metode untuk mengaproksimasi perubahan $\mathbf A(t)$. Bentuk incomplete partial fraction (IPF):

$$e^{h\mathbf A}\approx\alpha_0\prod_{\ell=1}^{K/2}\left[\mathbf I+2\operatorname{Re}\left(\widetilde\alpha_\ell(h\mathbf A-\theta_\ell\mathbf I)^{-1}\right)\right].$$

Jangan membentuk inverse penuh. Terapkan secara berurutan dengan menyelesaikan sistem sparse:

$$(h\mathbf A-\theta_\ell\mathbf I)\mathbf y_\ell=\mathbf N^{(\ell-1)},\quad \mathbf N^{(\ell)}=\mathbf N^{(\ell-1)}+2\operatorname{Re}(\widetilde\alpha_\ell\mathbf y_\ell),$$

$$\boxed{\mathbf N_1\approx\alpha_0\mathbf N^{(K/2)},\qquad \mathbf N^{(0)}=\mathbf N_0.}$$

PFD adalah aproksimasi pecahan parsial berbentuk jumlah dengan algoritma berbeda; koefisien IPF dan PFD tidak dapat dipertukarkan. CRAM efisien untuk matriks deplesi sparse dan stiff.

Dengan:

- $K$: orde aproksimasi CRAM.
- $\ell$: indeks pole atau pasangan pole.
- $\theta_\ell$: pole kompleks ke-$\ell$.
- $\widetilde{\alpha}_\ell,\alpha_0$: koefisien CRAM yang telah ditabulasi.
- $\mathbf I$: matriks identitas.
- $\operatorname{Re}(\cdot)$: operator yang mengambil bagian real.
- $\mathbf y_\ell$: solusi sistem linear sparse pada tahap CRAM ke-$\ell$.

**Contoh matriks tiga nuklida:** untuk $X_1\to X_2\to X_3$,

$$\mathbf A_3(t)=\begin{bmatrix}-q_1(t)&0&0\\q_1(t)&-q_2(t)&0\\0&q_2(t)&-q_3(t)\end{bmatrix},\qquad \mathbf N=\begin{bmatrix}N_1\\N_2\\N_3\end{bmatrix}.$$

Dengan:

- $X_1,X_2,X_3$: nuklida dalam rantai peluruhan berurutan.
- $q_1,q_2$: laju transisi per atom dari $X_1$ ke $X_2$ dan dari $X_2$ ke $X_3$; satuan $s^{-1}$.
- $q_3$: laju kehilangan $X_3$ ke luar rantai; satuan $s^{-1}$.
- $\lambda_1,\lambda_2$: konstanta peluruhan pada contoh peluruhan murni; jika $X_3$ stabil, $q_3=0$.
- $\mathbf A_3$: matriks transmutasi rantai tiga nuklida; satuan $s^{-1}$.

Pada iradiasi, laju $q_j$ dapat mencakup reaksi neutron dan bergantung pada fluks serta komposisi. Jika $\mathbf A_3$ konstan, propagasi eksponensial menyelesaikan rantai tepat.

# **Daftar Pustaka**
- **Syeilendra Pramuditya**, Pengembangan Kode komputer terintegrasi untuk studi desain awal pembangkit listrik tenaga nuklir jenis PWR
- **Liangzhi Cao, et. al**, Deterministic Numerical Methods for Unstructured-Mesh Neutron Transport Calculation
- **James J. Duderstadt, et. al**, Nuclear Reactor Analysis
- **Keisuke Okumura, et. al**, SRAC2006: A comprehensive neutronics calculation code system
- **Wahid Luthfi, et. al.**, Deskripsi dan perhitungan terkait reaktor generasi IV
- **Dwi Irwanto, et. al**, Rekayasa Keselamatan Instalasi Nuklir (RN5081)
- **Yousef Saad**, Iterative Methods for space linear system
- **Paul K. Romano, et. al**, Depletion capabilities in the OpenMC Monte carlo particle transport code
