# Gradle
- buat tugas Gradle sederhana untuk menerima parameter CLI dan mencetaknya dengan pesan ucapan
- Proyek skrip Gradle harus dibuat di repositori yang berbeda dan dorong ke GitHub

greetingTask(ketik: DefaultTask) {
doLast {
String name = project.hasProperty('name') ? project.property('name') : 'Gradle User'
println "Hello, $name! Welcome to Gradle World!"
}
}

apat menjalankan tugas dengan menjalankan perintah berikut: "./gradlew greetingTask -Pname=YourName"

![image](https://github.com/WRAP1994/Gradle/assets/144769621/1526f8c4-d92c-4f3a-b712-b5e7e00f325d)

