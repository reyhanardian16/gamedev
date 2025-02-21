# ****Tutorial 2****
- **Apa saja pesan log yang dicetak pada panel Output?**  
Pesan log yang ditunjukkan output: "Platform initialized"
- **Coba gerakkan landasan ke batas area bawah, lalu gerakkan kembali ke atas hingga hampir menyentuh batas atas. Apa saja pesan log yang dicetak pada panel Output?**  
Pesan log yang ditunjukkan output saat menggerakkan landasan ke batas atas: "Reached objective!"
- **Buka scene MainLevel dengan tampilan workspace 2D. Apakah lokasi scene ObjectiveArea memiliki kaitan dengan pesan log yang dicetak pada panel Output pada percobaan sebelumnya?**  
Output "Reached Objective!" menandakan bahwa objek BlueShip telah memasuki objek area
- **Scene BlueShip dan StonePlatform sama-sama memiliki sebuah child node bertipe Sprite. Apa fungsi dari node bertipe Sprite?**  
Fungsi node bertipe Sprite adalah untuk menampilkan model 2d dari sebuah objek
- **Root node dari scene BlueShip dan StonePlatform menggunakan tipe yang berbeda. BlueShip menggunakan tipe RigidBody2D, sedangkan StonePlatform menggunakan tipe StaticBody2D. Apa perbedaan dari masing-masing tipe node?**  
Perbedaan RigidBody2D dengan StaticBody2D adalah RigidBody2D dapat digerakkan oleh fisika game, sedangkan StaticBody2D tidak dapat digerakkan dari sumber eksternal
- **Ubah nilai atribut Disabled pada tipe CollisionShape2D di scene StonePlatform, lalu coba jalankan scene MainLevel. Apa yang terjadi?**  
Fungsi disabled pada StonePlatform membuat objek tersebut tidak berpengaruh di dunia game, sehingga BlueShip yang seharusnya terdorong keatas tidak terpengaruh oleh pergerakan StonePlatform
- **Pada scene MainLevel, coba manipulasi atribut Position, Rotation, dan Scale milik node BlueShip secara bebas. Apa yang terjadi pada visualisasi BlueShip di Viewport?**  
Atribut Position menentukan posisi objek pada main level, rotation menentukan orientasi objek, dan scale menentukan ukuran objek
- **Pada scene MainLevel, perhatikan nilai atribut Position node PlatformBlue, StonePlatform, dan StonePlatform2. Mengapa nilai Position node StonePlatform dan StonePlatform2 tidak sesuai dengan posisinya di dalam scene (menurut Inspector) namun visualisasinya berada di posisi yang tepat?**
Karena StonePlatform dan StonePlatform2 merupakan child dari PlatformBlue, maka posisinya berganting dan relatif terhadap posisi PlatformBlue, dapat dilihat dari node StonePlatform2 yang memiliki posisi (70,0) terhadap posisiPlatformBlue bukan dari scene
