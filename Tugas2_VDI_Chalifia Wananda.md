---
title: "Tugas2_VDI_Chalifia Wananda"
output: github_document
---

**4 Prinsip Dasar Visualisasi Data:**

1.  Kesederhanaan (*Simplicity*)

    Visualisasinya harus mudah dipahami dan tidak merumitkan pembaca.

2.  Akurasi (*Accuracy*)

    Visualisasi harus menampilkan data yang benar serta mewakili data sebenarnya.

3.  Relevan (*Relevance*)

    Validasi haru fokus pada informasi yang penting dalam data dan juga relevan dengan tujuan analisisnya.

4.  Efektivitas (*Effectiveness*)

    Visualisasi harus mampu menyelesaikan pesan yang jelas dan juga efektif.

**Contoh Visualisasi:**

-   *Bad Visualisation*

    ```{r}
    install.packages("imager")
    library(imager)

    ```

    ![Gambar 1](D:/kampus/sem%205/vdi/tugas%202/bad%202.jpg)

    ```{r}
    img <- load.image("D:/kampus/sem 5/vdi/tugas 2/bad 2.jpg")
    plot(img)
    ```

    Visualisasi data diatas merupakan visualisasi data jejaringan sosial facebook. Mengapa dikatakan *bad*, karena terlalu banyak garis yang memenuhi data sehingga menyulitkan untuk dibaca. Prinsip kesederhaaan dan relevansi tidak terpenuhi.

    ![Gambar 2](D:/kampus/sem%205/vdi/tugas%202/1RJmF.png)

    ```{r}
    img <- load.image("D:/kampus/sem 5/vdi/tugas 2/1RJmF.png")
    plot(img)
    ```

    Visualisasi diatas merupakan pie chart, dikatakan *bad* karena terlalu banyak memiliki segmen yang terdapat pada datanya. Prinsip kesederhanaan dan efektivitasnya tidak terpenuhi.

-   *Good Visualisation*

    ![Gambar 3](D:/kampus/sem%205/vdi/tugas%202/good1.png)

    Visualisai diatas merupakan visualisasi scatterplot yang menunjukkan dua variabel numerik. Dan dengan *trendline* yang memberikan gambaran umum tentang tren data tersebut. Dikatakan *good visualisatio*n karena memenuhi prinsip kesederhanaan,akurasi dan relevansi

    ![Gambar 4](D:/kampus/sem%205/vdi/tugas%202/good2.jpeg)

    Visualisasi diatas merupak jenis visualisasi Heatmap, visualisasi ini menampilkan data dalam bentuk matriks, yang menunjukkan pola dan anomali. Dikatakan *good visualization* karena memenuhi 4 prinsip visualisasi yang baik.

**Kesimpulan:**

Visualisasi data yang baik adalah yang mampu menyampaikan informasi dengan jelas, akurat, dan efektif. Dengan mengikuti prinsip-prinsip dasar visualisasi data, Anda dapat membuat visualisasi yang membantu orang lain memahami data dengan lebih mudah.
