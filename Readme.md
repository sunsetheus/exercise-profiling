1. What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?
Pendekatan performance testing dengan menggunaman JMeter lebih mentitik beratkan pada performa ketika terdapat user banyak menggunakannya bersamaan. Performa yang dimaksud meliputi waktu respons, output / cara web memberikan respons, waktu mendapatkan respons.

Sedangkan pendekatan profiling dengan menggunakan IntelliJ Profiler lebih berfokus pada detail waktu eksekusi tiap code sehingga kita dapat mengetahui secara detail method/kode yang memiliki waktu eksekusi relatif lama. Dengan demikian, kita menjadi tahu batasan kode kita dapat bekerja secara optimal dan bagian yang perlu dioptimasi.


2. How does the profiling process help you in identifying and understanding the weak points in your application?
Proses profiling membantu saya mengidentifikasi bagian kode mana yang memerlukan waktu relatif lebih lama sehingga saya dapat menghemat waktu dalam mengidentifikasi bagian kodenya (chunks dari barisan kode). Proses profiling memberikan data waktu yang dapat dilakukan komparasi langsung dengan kode lainnya, data empiris ini yang saya gunakan untuk menarik kesimpulan dan menentukan titik lemah aplikasi saya.



3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?
Saya merasa IntelliJ Profiling telah memberikan efektivitas dalam melakukan screening data efektivitas suatu code sehingga saya merasa lebih mudah dalam menganalisa kode mana yang perlu saya ubah.


4. What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?
Salah satu tantangan saya dalam menggunakan / melakukan profiling adalah membaca hasil yang diprovide profiling karena banyak informasi yang teesedia, solusinya adalah membaca bagian krusial saja. Selain itu proses berpikir dalam mencari cara untuk mengoptimasi juga merupakan tantangan baru karena harus mencari seoptimal mungkin.


5. What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?
Keuntungan utama yang saya rasakan adalah kemudahan akses profiling dan memanfaatkan utilitasnya, informasi yang ditampilkan sangat rangkap dan detail sehingga saya dapat menentukan code mana yang memiliki execution time buruk.


6. How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?
Performa prpfiler dipangeruhi banyak aspek seperti OS, Java virtual machine dan sebagainya. Walaupun demikian, berbedaan running timenya tidam signifikan itu sehingga saya belum merasakan hal yang menjadi masalah pada kasus ini

7. What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?
Setelah profiling, saya mengoptimasi kode tersebut dan mencari bottleneck kode yang diberikan. Menghindari penggunaan nested loop dan untuk memastikaan optimasi kode masih memberikan fungsi benar, diperlukan unit test
