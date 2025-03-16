1. What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?

JMeter memiliki kemampuan untuk mensimulasikan interaksi user dengan aplikasi. Kita dapat dengan mudah mengatur berapa banyak request oleh user dalam suatu waktu melalui thread group. Dilengkapi dengan timer, listener, dan configuration element, JMeter memberikan ulasan terkait performa software kita dengan baik. Sementara itu, Intellij profiler memberikan informasi yang lebih detail saat menjalankan software tersebut. Kita dapat melihat bagaimana setiap method dieksekusi dan resource yang dibutuhkan. Ini sangat memudahkan proses debugging dan optimisasi performa untuk low-level. dengan jelas, kita dapat mengetahui bahwa Profiler memberikan informasi detail mengenai proses berjalannya software. sementara, JMeter dapat mensimulasikan heavy load pada aplikasi tetapi hanya menyediakan informasi dasar saja. Keduanya sangat bermanfaat bagi proses optimisasi dan harus dikombinasikan untuk membuat software yang reliable dan bagus secara general.

2. How does the profiling process help you in identifying and understanding the weak points in your application?

Profiling memberikan feedback dari hasil berjalannya aplikasi. Kita dapat melihat proses apa saja yang dijalankan serta berapa resource yang dibutuhkan. Mencari weak point pada aplikasi dapat memakan waktu yang lama apabila yang dilakukan hanya dengan membaca kode saja. Dengan adanya profiler, proses ini dapat berjalan dengan cepat. Kita cukup melihat proses mana yang memakan banyak waktu dan memori dari laporan yang diberikan. Saat selesai dioptimasi, kode yang sebelumnya bermasalah dapat diuji kembali dengan profiler untuk memastikan keberhasilan optimisasi.

3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?

Saya dapat dengan mudah mengetahui apa saja proses yang memakan banyak komputasi seperti highest-gpa dan all-student-name. Saya menemukan bahwa kode pada module service untuk masing - masing endpoint tidak berguna. Sebab, kita dapat menggunakan JPA untuk meringkas query redundant menjadi query ringkas. Ini menghemat penggunaan resource dan waktu eksekusi. Dengan ini, pengguna aplikasi akan lebih nyaman mengakses sistem informasi ini.

4. What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?

Saya awalnya mengalami kesulitan dalam mengoptimasi performance saat pemanggilan highest-gpa dan all-student-number. Kelihatannya kode yang diberikan sudah sesuai dengan tujuannya dan tidak ada yang bisa diubah. Kemudian, saya mulai mencari tau tentang JPA. Ternyata, JPA banyak menyediakan query bawaan untuk berbagai model, mempermudah proses query database. Inilah yang membuat software dapat berjalan dengan cepat. Kita memangkas berbagai redundant query untuk query yang lebih ringkas dan murah secara biaya komputasional.

5. What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?

Intellij Profiler sangat mudah untuk digunakan. Tidak seperti JMeter yang memerlukan berbagai setup yang awalnya membingungkan, Intellij ini sangatlah mudah. Hal yang perlu kita lakukan hanyalah menjalankan button profiller, kemudian menggunakan software kita seperti biasanya. Setelah itu, Kita diberikan laporan yang mudah sekali untuk dipahami. Saya dengan cepat dapat mencari sumber bottleneck pada software ini berkat laporan profiler yang ramah pembaca awam.

6. How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?

Saya menyadari bahwa pada endpoint all-student-name, meskipun terdapat pengurangan signifikan, lebih dari 50%. Pada, kenyataannya uji coba dengan JMeter tidak menunjukan perubahan yang sama. Memang benar, bahwa latency nya berkurang, tetapi apabila kita melihat persentase perubahan di Intellij profiler dan JMeter, ada perbedaan yang cukup jomplang. Menurut saya, ini terjadi karena fokus kedua tools ini berbeda. Intellij profiler berfokus pada performa cpu, memory, dll. Sementara, JMeter berfokus pada throughput, latency, response time, dll. Salah satu faktornya adalah koneksi database. Melakukan koneksi dan query pada database adalah proses yang mahal dan tidak diperhitungkan di Intellij profiler. 

7. What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?

Untuk memastikan bahwa perubahannya tidak berubah, saya dapat melakukan validasi pada jmeter. JMeter sendiri menyediakan fitur validasi untuk memastikan bahwa aplikasi memberikan response yang seharusnya kepada user yang melakukan request. Lebih jelasnya, dengan assertion pada data sebelum perubahan.

Berikut ini hasil screenshot: https://drive.google.com/drive/folders/1kluWgj_7x5LTgbAWSHTB9hI_5js_RT_o