# Code-Chapter-3
Nama : Welson Mario Naibaho

Kelas : TI 3C

NIM : 2041720253


Matakuliah : Big Data


## Langkah-langkah dan penjelasan

1. Pertama masuk ke folder spark dengan cara

    <code> cd spark-2.0.0-bin-hadoop2.7</code>
    
2. Kemudian jalankan

    <code> bin/pyspark </code>

![](screenshoot/bin_pyspark.jpeg)

3. Mencoba <code>Accumulator.py</code>

![](screenshoot/Accumulatorpy.jpeg)

    Disini berhasil untuk print myaccum.value. dan outputnya adalah 4950

4. Mencoba <code>BroadCast.py</code>

![](screenshoot/BroadCastpy.jpeg)

    Pada percobaan BroadCast, berhasil membuat list 1 sampai dengan 99 dengan atribut broadcastVar.value

5. Mencoba <code>LogAnalytics</code>

![](screenshoot/LogAnalyticspy.jpeg)

    - Disini membuat file dummy berformat .text kedalam direktori file://home/cloudera
    - Code diatas berfungsi untuk memfilter kata "Error" dan "Product"
    - Hasil dari LogAnalyrics menujukkan bahwa Total number of error record are 0 and Number of product pages visited that have Errors is 0
    - Menujukkan bahwa file sample3.txt tidak memiliki nilai error dan nilai product pada log file.

6. Mencoba <code>PairRDD</code>

![](screenshoot/PairRDDpy.jpeg)

    myPairRDD.key().collect()
        - menampilkan nilai dari mylist
    myPairRDD.values().collect()
        - Menampilkan jumlah kata dari collection

7. Mencoba <code>UnderstandingRDDS.py</code>

![](screenshoot/Understanding1py.jpeg)
![](screenshoot/Understanding2py.jpeg)

    Pada percobaan diatas, membuat sebuah list dengan menghitung jumlah partisi dan kemudian menampilkan data pada collection

8. Mencoba <code>WordCount.py</code>

![](screenshoot/WordCountpy.jpeg)

    Dari percobaan diatas, dilakukan penjumlahan menggunakan atribut counts.collect()


### UJI COBA FILE .SCALA

    Pada terminal jalankan spark-shell dengan cara

- <code>cd spark-2.0.0-bin-hadoop2.7</code>


        Kemudian lakukan


- <code>bin/spark-shell</code>

![](screenshoot/spark-shell.jpeg)

    Pada Cloudera Manager, jalankan service HDFS


![](screenshoot/HDFS_service.jpeg)

1. Mencoba <code>SystemCommandsOutput.scala</code>


![](screenshoot/SystemCommandsOutputscala.jpeg)

    Hasil dari percobaan diatas adalah string "" dan result = , dikarenakan tidak terdapat file yang akan dihadoop

2. Mencoba <code>SystemCommandsReturnCode.scala</code>

![](screenshoot/SystemCommandsReturnCodescala.jpeg)

    Dari percobaan diatas, menampilkan folder yang berisi temp file




