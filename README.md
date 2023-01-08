# Langkah-langkah pembuatan latihan dari project PBO
- [Modul 3](README.md#modul-3) Mengenali Lingkup Pemrograman Anda
- [Modul 4](README.md#modul-4) Dasar-Dasar Pemrograman
- [Modul 5](README.md#modul-5) Mendapatkan Input dari Keyboard
- [Modul 6](README.md#modul-6) Stuktur Kontrol
- [Modul 7](README.md#modul-7) Java Array
- [Modul 8](README.md#modul-8) Argumen dari Command-line
- [Modul 9](README.md#modul-9) Bekerja dengan Java Class Library
- [Modul 10](README.md#modul-10) Membuat Class Sendiri
- [Modul 11](README.md#modul-11) Pewarisan, Polimorfisme, dan Interface
- [Modul 12](README.md#modul-12) Dasar Exception Handling

## Modul 3
# 3.6 Latihan
### `3.6.1 Hello World!`
Menggunakan NetBeans, membuat class dengan nama : [NamaAnda]. Hasil dari
program yang harus tampil dilayar :

Welcome to Java Programming [NamaAnda]!!!


Kode Program :
```java
public class HelloWord {
    public static void main(String[] args) {
        System.out.println("Welcome to Java Programming [Siti Nurhaliza Yus]!!!");
    }
}
```
file : [soal1.java](https://github.com/SitiNurhalizaYus/PBO_2101091013_Teori/blob/139610d364cf67e0fe5fc5eb5322cad9b6e4daa3/SITI160922/heloworld.java)

Hasil Run/Output :

![2](https://user-images.githubusercontent.com/114122090/197296812-818549ef-c509-42f0-8670-05f394a15425.png)

### `3.6.2 The Tree`
Menggunakan NetBeans, membuat class dengan nama : TheTree. Hasil dari program
yang harus tampil dilayar :

I think that I shall never see,
a poem as lovely as a tree. 
A tree whose hungry mouth is pressed 
Against the Earth’s sweet flowing breast.


Kode Program :
```java
public class TheTree {
    public static void main(String[] args) {
        System.out.println("I think that I shall never see,");
        System.out.println("a poem as lovely as a tree. ");
        System.out.println("A tree whose hungry mouth is pressed ");
        System.out.println("Against the Earth’s sweet flowing breast.");
    }
}
```
file : [soal2.java](https://github.com/SitiNurhalizaYus/PBO_2101091013_Teori/blob/139610d364cf67e0fe5fc5eb5322cad9b6e4daa3/SITI160922/TheTree.java)

Hasil Run/Output :

![3](https://user-images.githubusercontent.com/114122090/197296833-d85de8f8-ba46-46cb-ae83-bc19eb5843aa.png)

Variasi lainnya 

file : [soal.java](https://github.com/SitiNurhalizaYus/PBO_2101091013_Teori/blob/139610d364cf67e0fe5fc5eb5322cad9b6e4daa3/SITI160922/HelloWord.java)

Kode Program :
```java
public class HelloWord {
    public static void main(String[] args) {
        System.out.println("HelloWord\n" + "MI2C" + "\nPemograman berbasis objek");
        System.out.println("\nNama\t: Siti Nurhaliza Yus");
        System.out.println("No bp\t: 2101091013");
        System.out.println("Prodi\t: D3 Manajemen Informatika");
        System.out.println("Jurusan\t: Teknologi Informasi");
        System.out.println("Alamat\t: Jln.Ampang No.34 RT002/RW003");
    }
}
```
Hasil Run/Output :

![1](https://user-images.githubusercontent.com/114122090/197296845-73ec9c0b-f946-4fca-9e29-a9fe58b19e50.png)

## Modul 4
# 4.11 Latihan
### `4.11.1 Mendeklarasikan dan mencetak variabel`
Diberikan tabel dibawah ini, deklarasikan variabel yang terdapat didalamnya dengan tipe 
data yang sesuai dan berikan nilai inisialisasi. Tampilkan hasil outputnya yaitu nama 
variabel dan nilainya. 
| Variable name | Data tipe | Initial value |  
| ----------- | :---------: | ----------: |
| number | integer| 10 |
| letter | character| a |
| result | boolean |true |
| str |String | hello |


Berikut ini merupakan tampilan yang diharapkan sebagai hasil eksekusi program, 
Number = 10 
letter = a 
result = true 
str = hello 

Kode Program :
```java
public static void main(String[] args) {
        int i = 10;
        char j = 'a';
        boolean k = true;
        String l = "hello";
        
        System.out.println("Number = " + i);
        System.out.println("letter = " + j);
        System.out.println("result = " + k);
        System.out.println("str = " + l);    
    }
```
file : [soal1.java](https://github.com/SitiNurhalizaYus/PBO_2101091013_Praktek/blob/105b53866d65bfa82295b4737b0b4f473972b0cf/src/SITI230922/latihan10.java)

Hasil Run/Output :

![1](https://user-images.githubusercontent.com/114122090/197332249-4ee469e9-4f19-4b30-b1e3-e5a7450cbe12.png)

### `4.11.2. Mendapatkan nilai rata-rata dari tiga angka `
Buatlah program yang menghasilkan output nilai rata-ratadari tiga angka. Nilai dari masingmasing tiga angka tersebut adalah 10, 20 dan 45. Tampilan Output yang diharapkan 
adalah, 
number 1 = 10 
number 2 = 20 
number 3 = 45 
Average is = 25 

Kode Program :
```java
public static void main(String[] args) {
       int i = 10;
       int j = 20;
       int k = 45; 
       
       System.out.println("number 1 = " + i);
       System.out.println("number 1 = " + j);
       System.out.println("number 1 = " + k);
      
       System.out.println("Average is = " + (i + j + k)/3);       
    }
```
file : [soal2.java](https://github.com/SitiNurhalizaYus/PBO_2101091013_Praktek/blob/105b53866d65bfa82295b4737b0b4f473972b0cf/src/SITI230922/latihan11.java)

Hasil Run/Output :

![2](https://user-images.githubusercontent.com/114122090/197332179-8c9c375c-9952-4518-b5ea-86305fdd7d79.png)

### `4.11.3. Menampilkan nilai terbesar`
Diberikan tiga angka, tuliskan program yang menghasilkan output angka dengan nilai 
terbesar diantara tiga angka tersebut. Gunakan operator kondisi ?: yang telah kita pelajari 
sebelumnya (HINT: Anda akan perlu menggunakan dua set operator ?: untuk 
memecahkan permasalahan ini). Sebagai contoh , diberikan angka 10, 23 dan 5, Program 
anda akan menghasilkan output, 
number 1 = 10 
number 2 = 23 
number 3 = 5 

Nilai tertingginya adalah angka = 23 

Kode Program :
```java
public static void main(String[] args) {
       int i = 10;
       int j = 23;
       int k = 5;
       int hasil;
       
       System.out.println("number 1 = " + i);
       System.out.println("number 2 = " + j);
       System.out.println("number 3 = " + k);
       
       hasil = (i>=j)?i:j;
       hasil = (k>=hasil)?i:hasil;      
       
       System.out.println("Nilai tertingginya adalah = "+hasil);
    }
```
file : [soal3.java](https://github.com/SitiNurhalizaYus/PBO_2101091013_Praktek/blob/105b53866d65bfa82295b4737b0b4f473972b0cf/src/SITI230922/latihan12.java)

Hasil Run/Output :

![3](https://user-images.githubusercontent.com/114122090/197332117-90999fc3-6863-4b9b-be64-a3d751a61fe5.png)

### `4.11.4. Operator precedence`
Diberikan pernyataan berikut ini, tulis kembali soal tersebut dengan menambahkan tanda 
kurung pada urutan sesuai dengan bagaimana pernyataan tersebut akan dievaluasi. 
1. a / b ^ c ^ d – e + f – g * h + i 
2. 3 * 10 *2 / 15 – 2 + 4 ^ 2 ^ 2 
3. r ^ s * t / u – v + w ^ x – y++ 

Kode Program :
```java
public static void main(String[] args) {
        int a=1,b=1,c=1,d=1,e=1,f=1,g=1,h=1,i=1,r=1,s=1,t=1,u=1,v=1,w=1,x=1,y=1;
        int n1;
        int n2;
        int n3;
       
        n1 = (((a/b)^c)^d)-e+f-(g*h)+i;
        n2 = (((3*10)*2)/15)-2+((4^2)^2);
        n3 = (((r^s)*t)/u)-v+(w^x)-(y++);
        
        System.out.println("1."+n1);
        System.out.println("2."+n2);
        System.out.println("3."+n3);
    }
```
file : [soal4.java](https://github.com/SitiNurhalizaYus/PBO_2101091013_Praktek/blob/105b53866d65bfa82295b4737b0b4f473972b0cf/src/SITI230922/latihan13.java)

Hasil Run/Output :

![4](https://user-images.githubusercontent.com/114122090/197332035-141a61e3-6747-4fd3-8b2f-cbdd670544e6.png)

## Modul 5
# 5.1 Latihan 
### `5.1.1 Kata Terakhir (versi BufferedReader)`
Menggunakan BufferedReader, tanyakan tiga kata dari user dan tampilkan output dari 
input user tersebut ke layar. Contoh, 
Enter word1:Goodbye 
Enter word2:and 
Enter word3:Hello 
Goodbye and Hello 

Kode Program :
```java
public static void main(String[] args) {
        BufferedReader dataIn = new BufferedReader(new InputStreamReader( System.in));
        String word = "";
        String word2 = "";
        String word3 = "";
        
        try{
            System.out.print("Enter word1 : ");
            word = dataIn.readLine();
            System.out.print("Enter word2 : ");
            word2 = dataIn.readLine();
            System.out.print("Enter word3 : ");
            word3 = dataIn.readLine();
        }
        catch( IOException e ){
            System.out.println("Error !");
        }
        System.out.println(word+" "+word2+" "+word3);
    }
```
file : [soal1.java](https://github.com/SitiNurhalizaYus/PBO_2101091013_Teori/blob/139610d364cf67e0fe5fc5eb5322cad9b6e4daa3/SITI300922/Latihan5.java)

Hasil Run/Output :

*Masukan karakter dengan klik terlebih dahulu untuk menginputkan karakter*

![1](https://user-images.githubusercontent.com/114122090/197332775-5a52d639-daff-47ab-8253-b6a246c8fb55.png)

*Output*

![2](https://user-images.githubusercontent.com/114122090/197332780-ac8359b8-609c-4547-9e24-e224f982101a.png)

### `5.1.2 Kata Terakhir (versi JOptionPane)` 
Menggunakan JOptionPane, tanyakan tiga kata dari user dan tampilkan output dari input 
user tersebut ke layar. 
Kode Program :
```java
 public static void main(String[] args) {
        String word = "";
        String word2 = "";
        
        word = JOptionPane.showInputDialog("Masukan kata pertama");
        word2 = JOptionPane.showInputDialog("Masukan kata kedua");
        
        String msg = word +" and "+word2;
        
        JOptionPane.showMessageDialog(null, msg);
    }
```
file : [soal2.java](https://github.com/SitiNurhalizaYus/PBO_2101091013_Teori/blob/139610d364cf67e0fe5fc5eb5322cad9b6e4daa3/SITI300922/Latihan6.java)

Hasil Run/Output :

*inputan pertama*

![3](https://user-images.githubusercontent.com/114122090/197332988-381e6eaf-7b02-471e-b2da-98728a545328.png)

*inputan kedua*

![4](https://user-images.githubusercontent.com/114122090/197333049-d7eb5386-6799-483a-9339-c204e0e9ab04.png)

*output*

![5](https://user-images.githubusercontent.com/114122090/197333056-cd40c3df-2873-4bb8-a79b-632908587922.png)

## Modul 6
# 6.5 Latihan 
### `6.5.1 Nilai` 
Ambil tiga nilai ujian dari user dan hitung nilai rata-rata dari nilai tersebut. Berikan 
output rata-rata dari tiga ujian. Berikan juga smiley face pada output jika nilai rata-rata 
lebih besar atau sama dengan 60, selain itu beri output :-(. 
1. Gunakan BufferedReader untuk mendapat input dari user, dan System.out untuk 
output hasilnya.

Kode Program :
```java
public static void main(String[] args) {
    BufferedReader nilai = new BufferedReader(new InputStreamReader(System.in));
    String r="";
    String s="";
    String t="";

    try{
     System.out.print("Masukkan nilai pertama Anda: ");
     r = nilai.readLine();
     
     System.out.print("Masukkan nilai kedua Anda: ");
     s = nilai.readLine();

     System.out.print("Masukkan nilai ketiga Anda: ");
     t = nilai.readLine();
    }catch(IOException e){
       System.out.println("Kata yang Anda masukkan salah, silahkan coba lagi.");
    }
    
    int pertama;
    int kedua;
    int ketiga;
    
    pertama = Integer.parseInt(r);
    kedua = Integer.parseInt(s);
    ketiga = Integer.parseInt(t);

    int rata_rata=(pertama+kedua+ketiga)/3;

    System.out.println("Rata-rata nilai Anda: "+rata_rata);
        if (rata_rata>=60){
            System.out.println(":)");
        }
        else {
            System.out.println(":(");
        }
   }
```  
file : [soal1.java](https://github.com/SitiNurhalizaYus/PBO_2101091013_Teori/blob/139610d364cf67e0fe5fc5eb5322cad9b6e4daa3/SITI071022/latihan1.java)

Hasil Run/Output :

![1](https://user-images.githubusercontent.com/114122090/197333529-b21be5f2-c599-4724-9c7e-c7033184c286.png)

2. Gunakan JOptionPane untuk mendapat input dari user dan output hasilnya.

Kode Program :
```java
public static void main(String[] args) {
    String r="";
    String s="";
    String t="";

    r=JOptionPane.showInputDialog("Masukkan nilai pertama Anda");

    int pertama = Integer.valueOf(r).intValue();
    s=JOptionPane.showInputDialog("Masukkan nilai kedua Anda");

    int kedua = Integer.valueOf(s).intValue();
    t=JOptionPane.showInputDialog("Masukkan nilai ketiga Anda");

    int ketiga = Integer.valueOf(t).intValue();   
    int rata_rata=(pertama+kedua+ketiga)/3;

    String hasil= "";

    hasil += "Nilai pertama: " +pertama +"\n";
    hasil += "Nilai kedua: " +kedua +"\n";
    hasil += "Nilai ketiga: " +ketiga +"\n";
    hasil += "Rata-rata nilai Anda adalah " +rata_rata+"\n";

      if (rata_rata<=60){
         hasil +=":("+"\n";
      }
      else {
         hasil +=":)"+"\n";
      }
    JOptionPane.showMessageDialog(null, hasil);
    }
```
file : [soal2.java](https://github.com/SitiNurhalizaYus/PBO_2101091013_Teori/blob/139610d364cf67e0fe5fc5eb5322cad9b6e4daa3/SITI071022/latihan2.java)

Hasil Run/Output :

*masukan input ke 1*

![3](https://user-images.githubusercontent.com/114122090/197369718-d8397e0f-d818-433d-8ada-7ab7c4331c9e.png)

*masukan input ke 2*

![3a](https://user-images.githubusercontent.com/114122090/197369721-619a34b9-deca-48b7-8a6b-81ce6e3ddcee.png)

*masukan input ke 3*

![3b](https://user-images.githubusercontent.com/114122090/197369722-67866ec8-adb5-4629-89be-eb7ff9bb6f26.png)

*output*

![3c](https://user-images.githubusercontent.com/114122090/197369725-78be9e98-8c4d-4bd8-8fae-53c472203ccc.png)


### `6.5.2 Membaca Bilangan`
Ambil sebuah angka sebagai input dari user, dan outputnya berupa kata yang sesuai 
dengan angka. Angka yang dimasukkan antara 1-10. Jika user memasukkan nilai yang 
tidak sesuai berikan output “Invalid number”. 
1. Gunakan statement if-else untuk menyelesaikan 

Kode Program :
```java
public static void main(String[]args){
    String angka="";
    angka=JOptionPane.showInputDialog("Silahkan masukkan angka ");
    int z = Integer.valueOf(angka).intValue();

    String hasil ="";
        if (z>=1&&z<=10){
             hasil += "Valid number";
        }
        else{
             hasil += "Invalid Number";
        }
    JOptionPane.showMessageDialog(null, hasil);
    }
}
```
file : [soal1.java](https://github.com/SitiNurhalizaYus/PBO_2101091013_Teori/blob/139610d364cf67e0fe5fc5eb5322cad9b6e4daa3/SITI071022/latihan3.java)

Hasil Run/Output :

*jika angka yang diinput valid*

![2](https://user-images.githubusercontent.com/114122090/197370066-8d58775a-6b54-4504-bde6-27cb6ebced59.png)

![2a](https://user-images.githubusercontent.com/114122090/197370068-2f42196e-a8c8-4671-b865-9c860de405af.png)


*jika angka yang diinput tidak valid*

![2b](https://user-images.githubusercontent.com/114122090/197370069-362effb3-efac-4044-9dce-531881a388b1.png)

![2c](https://user-images.githubusercontent.com/114122090/197370072-3f0c6657-a022-4f29-825f-31c445a040d7.png)


2. Gunakan statement switch untuk menyelesaikan 

Kode Program :
```java
public static void main(String[]args){
    String angka="";
    angka=JOptionPane.showInputDialog("Silahkan masukkan angka ");
    int z = Integer.valueOf(angka).intValue();

    String hasil="";
    switch(z){
    case 1: hasil+= "Valid Number"; break;
    case 2: hasil+= "Valid Number"; break;
    case 3: hasil+= "Valid Number"; break;
    case 4: hasil+= "Valid Number"; break;
    case 5: hasil+= "Valid Number"; break;
    case 6: hasil+= "Valid Number"; break;
    case 7: hasil+= "Valid Number"; break;
    case 8: hasil+= "Valid Number"; break;
    case 9: hasil+= "Valid Number"; break;
    case 10: hasil+= "Valid Number"; break;
    default: hasil+= "Invalid Number"; break;
    }
    JOptionPane.showMessageDialog(null, hasil);
  }
```
file : [soal2.java](https://github.com/SitiNurhalizaYus/PBO_2101091013_Teori/blob/139610d364cf67e0fe5fc5eb5322cad9b6e4daa3/SITI071022/latihan4.java)

Hasil Run/Output :

*jika angka yang diinput valid*

![2d](https://user-images.githubusercontent.com/114122090/197370328-b095ba85-64bc-4ad9-944f-2c6a8f6bb75b.png)

![2a](https://user-images.githubusercontent.com/114122090/197370068-2f42196e-a8c8-4671-b865-9c860de405af.png)


*jika angka yang diinput tidak valid*

![2e](https://user-images.githubusercontent.com/114122090/197370326-ab37f106-3055-4501-897d-f2dea61f9cbf.png)

![2c](https://user-images.githubusercontent.com/114122090/197370072-3f0c6657-a022-4f29-825f-31c445a040d7.png)


### `6.5.3 Cetak Seratus Kali`
Buat sebuah program yang mencetak nama Anda selama seratus kali. Buat tiga versi 
program ini menggunakan while loop, do while dan for-loop. 

Kode Program :

**Versi.1 (While)**
```java
public static void main(String args[]){
    int r=0;
    while (r<100){
        System.out.println("SITI");
        r++;
    }
  }
```
file : [v1.java](https://github.com/SitiNurhalizaYus/PBO_2101091013_Teori/blob/139610d364cf67e0fe5fc5eb5322cad9b6e4daa3/SITI211022/latihan1.java)


**Versi.2 (Do While)**
```java
public static void main(String args[]){
    int r = 0;
    do {
        System.out.println("SITI");
        r++;
    } while (r<100);
  }
```
file : [v2.java](https://github.com/SitiNurhalizaYus/PBO_2101091013_Teori/blob/139610d364cf67e0fe5fc5eb5322cad9b6e4daa3/SITI211022/latihan2.java)


**Versi.3  (For)**
```java
public static void main(String args[]){
    int r;
    for (r=0; r<100; r++){
        System.out.println("SITI"); 
    }
  }
```
file : [v3.java](https://github.com/SitiNurhalizaYus/PBO_2101091013_Teori/blob/139610d364cf67e0fe5fc5eb5322cad9b6e4daa3/SITI211022/latihan3.java)

Hasil Run/Output :

![8](https://user-images.githubusercontent.com/114122090/197370519-0ffdb2a0-b8e9-44e3-8e05-53ca5eb86f2b.png)

### `6.5.4 Perpangkatan`
Hitung pangkat sebuah nilai berdasarkan angka dan nilai pangkatnya. Buat tiga versi 
dari program ini menggunakan while loop, do-while dan for-loop. 

Kode Program :

**Versi.1 (While)**
```java
public static void main (String[]args){
    int i =1;
    int hasil =1;
    String str1="";
    String str2="";
    
    str1=JOptionPane.showInputDialog("Masukkan angka");
    int angka=Integer.valueOf(str1).intValue();
    
    str2=JOptionPane.showInputDialog("Masukkan pangkat");
    int pangkat=Integer.valueOf(str2).intValue();
    
        while(i<=pangkat){
            hasil=hasil*angka;
            i++;
        }
        
    String str3=angka+" pangkat "+pangkat+ " = "+hasil;
    JOptionPane.showMessageDialog(null, str3 );
    }
```
file : [v1.java](https://github.com/SitiNurhalizaYus/PBO_2101091013_Teori/blob/139610d364cf67e0fe5fc5eb5322cad9b6e4daa3/SITI211022/latihan4.java)


**Versi.2 (Do While)**
```java
public static void main (String[]args){
    int i =1;
    int hasil =1;
    String str1="";
    String str2="";
    
    str1=JOptionPane.showInputDialog("Masukkan angka");
    int angka=Integer.valueOf(str1).intValue();
    
    str2=JOptionPane.showInputDialog("Masukkan pangkat");
    int pangkat=Integer.valueOf(str2).intValue();
    
        do{
            hasil=hasil*angka;
            i++;
        }
        while(i<=pangkat);
        
    String str3=angka+" pangkat "+pangkat+ " = "+hasil;
    JOptionPane.showMessageDialog(null, str3 );
    }
```
file : [v2.java](https://github.com/SitiNurhalizaYus/PBO_2101091013_Teori/blob/139610d364cf67e0fe5fc5eb5322cad9b6e4daa3/SITI211022/latihan5.java)


**Versi.3  (For)**
```java
public static void main (String[]args){
    int hasil =1;
    String str1="";
    String str2="";
    
    str1=JOptionPane.showInputDialog("Masukkan angka");
    int angka=Integer.valueOf(str1).intValue();
    
    str2=JOptionPane.showInputDialog("Masukkan pangkat");
    int pangkat=Integer.valueOf(str2).intValue();
    
        for(int i=1;i<=pangkat;i++){
            hasil=hasil*angka;
        }
        
    String str3=angka+" pangkat "+pangkat+ " = "+hasil;
    JOptionPane.showMessageDialog(null, str3 );
    }
```
file : [v3.java](https://github.com/SitiNurhalizaYus/PBO_2101091013_Teori/blob/139610d364cf67e0fe5fc5eb5322cad9b6e4daa3/SITI211022/latihan6.java)

Hasil Run/Output :

*masukan input ke 1*

![9](https://user-images.githubusercontent.com/114122090/197370620-ebbf964b-afea-4003-9afd-b85f5dbc5bd5.png)

*masukan input ke 2*

![9a](https://user-images.githubusercontent.com/114122090/197370623-7bc8235c-01fb-45be-878b-b0f65bf68b65.png)

*output*

![9b](https://user-images.githubusercontent.com/114122090/197370624-0a7d772a-6b60-4ab5-85a5-cefcc91c4f5a.png)

## Modul 7
# 7.7 Latihan 
### `7.7.1 Hari dalam seminggu` 
Buatlah sebuah String array yang akan menginisialisasi 7 hari dalam seminggu. Sebagai contoh, 
```
String days[] = {“Monday”, “Tuesday”….}; 
````
Gunakan while-loop, kemudian print semua nilai dari array (Gunakan juga untuk dowhile dan for-loop)Using a while-loop. 

Kode Program :
**Versi.1  (While)**
**Versi.2  (Do-While)**
**Versi.3  (For)**

### `7.7.2 Nomor terbesar` 
Gunakanlah BufferedReader dan JoptionPane, tanyakan kepada user untuk 10 nomor. 
Kemudian gunakan array untuk menyimpan 10 nomor tersebut. Tampilkan kepada user, 
input terbesar yang telah diberikan user. 

Kode Program :


### `7.7.3 Buku Alamat` 
Berikut ini adalah array multidimensi yang menyatakan isi dari sebuah buku alamat: 
```
String entry = {{"Florence", "735-1234", "Manila"}, 
 {"Joyce", "983-3333", "Quezon City"}, 
 {"Becca", "456-3322", "Manila"}}; 
```

Kode Program :


Cetak buku alamat tersebut dalam format berikut ini: 
```
Name : Florence 
Tel. # : 735-1234 
Address : Manila 
Name : Joyce 
Tel. # : 983-3333 
Address : Quezon City 
Name : Becca 
Tel. # : 456-3322 
Address : Manila
```

Kode Program :

## Modul 8

## Modul 9
# 9.6 Latihan 
## 9.6.1 Mendefinisikan Istilah 
Dengan kata-kata Anda sendiri, definisikan istilah-istilah berikut ini : 
1. Class 
2. Object 
3. Instantiate 
4. Instance Variable 
5. Instance Method 
6. Class Variables atau static member variables 
7. Constructor 

## 9.6.2 Java Scavanger Hunt 
Pipoy adalah suatu anggota baru dalam bahasa pemrograman Java. Dia hanya 
memperdengarkan bahwa telah ada APIs siap pakai dalam Java yang salah satunya dapat 
digunakan dalam program mereka, dan ia ingin sekali untuk mengusahakan mereka keluar. 
Masalahnya adalah, Pipoy tidak memiliki copy dari dokumentasi Java, dan dia juga tidak 
memiliki acces internet, jadi tidak ada jalan untuknya untuk menunjukkan Java APIs. 
Tugas Anda adalah untuk membantu Pipoy memperhatikan APIs (Application Programming 
Interface). Anda harus menyebutkan class dimana seharusnya method berada, deklarasi 
method dan penggunaan contoh yang dinyatakan method. 
Sebagai contoh, jika Pipoy ingin untuk mengetahui method yang mengknversisebuah String 
ke integer,jawaban Anda seharusnya menjadi: 
 Class: Integer 
 Method Declaration: public static int parseInt( String value ) 
 Sample Usage: 
 String strValue = "100"; 
 int value = Integer.parseInt( strValue ); 
yakinkan bahwa snippet dari kode yang Anda tulis dalam contoh Anda menggunakan 
compiles dan memberi output jawaban yang benar, jadi tidak membingungkan Pipoy. 
(Hint: Semua methods adalah dalam java.lang package). Dalam kasus dimana Anda 
dapat menemukan lebih banyak methods yang dapat menyelesaikan tugas, berikan hanya 
satu. 

Sekarang mari memulai pencarian! 
1. Perhatikan sebuah method yang diuji jika String pasti diakhiri suffix yang pasti. Sebagai 
contoh, jika diberikan string "Hello", Method harus mengembalikan nilai true suffix yang 
diberikan adalah "lo", dan false jika suffix yang diberikan adalah "alp". 

2. Perhatikan untuk method yang mengenali character yang mewakili sebuah digit yang 
spesifik dalam radix khusus. Sebagai contoh, jika input digit adalah 15, dan the radix 
adalah 16, method akan mengembalikan Character F, sejak F adalah representasi 
hexadecimal untuk angka 15 (berbasis 10). 

3. Perhatikan untuk method yang mengakhiri running Java Virtual Machine yang sedang 
berjalan 

4. Perhatikan untuk method yang memperoleh lantai dari sebuah nilai double. Sebagai 
contoh, jika Saya input a 3.13, method harus mengembalikan nilai 3. 
5. Perhatikan untuk method yang mengenali jika character yang dipakai adalah sebuah 
digit. Sebagai contoh, jika Saya input '3', dia akan mengembalikan nilai true

## Modul 10
# 10.10. Latihan 
## 10.10.1 Entry Buku Alamat 
Tugas Anda adalah membuat sebuah class yang memuat data-data pada buku alamat. 
Tabel berikut mendefinisikan informasi yang dimiliki oleh buku alamat. 
Attribut Deskripsi 
Nama Nama Lengkap perseorangan 
Alamat Alamat Lengkap 
Nomor Telepon Nomor telepon personal 
Alamat E-Mail Alamat E-Mail personal 
Tabel 1: Atribut dan Deskripsi Atribut 

Buat implementasi dari method sebagai berikut : 
1. Menyediakan accessor dan mutator method terhadap seluruh atribut 
2. Constructor 

## 10.10.2 Buku Alamat 
Buat sebuah class buku alamat yang dapat menampung 100 data. Gunakan class yang telah 
dibuat pada nomor pertama. Anda harus mengimplementasikan method berikut pada buku 
alamat : 
1. Memasukkan data 
2. Menghapus data 
3. Menampilkan seluruh data 
4. Update data

## Modul 11
# 11.6 Latihan 
## 11.6.1 Extend StudentRecord 
Dalam latihan ini, kita ingin untuk membuat catatan siswa yang lebih khusus yang berisi 
informasi tambahan tentang pengetahuan komputer siswa. Tugasnya adalah meng-extend 
class StudentRecord yang mengimplementasikan pelajaran sebelumnya. Cobalah untuk 
meng-override beberapa method yang ada dalam superclass StudentRecord, jika Anda 
benar-benar membutuhkannya. 

## 11.6.2 Bentuk Abstract Class 
Cobalah untuk membuat class abstract yang dinamai Shape dengan method abstract 
getArea() dan getName(). Tulis dua subclasses-nya yaitu Circle dan Square. Anda dapat 
menambahkan method tambahan ke dalam subclasses jika diinginkan.

## Modul 12
## 12.4.1 Menangkap Exception 1
Diberikan kode berikut:
```java
public class TestExceptions{
public static void main( String[] args ){
for( int i=0; true; i++ ){
System.out.println("args["+i+"]="+
args[i]); 
}
}
}
```
Compile dan jalankan program TestExceptions. Keluarannya akan tampak seperti ini:
```java
javac TestExceptions one two three
args[0]=one
args[1]=two
args[2]=three
Exception in thread "main"
java.lang.ArrayIndexOutOfBoundsException: 3
 at TestExceptions.main(1.java:4)
 ```
Ubah program TestExceptions untuk menangani exception, keluaran program setelah ditangkap
exception-nya akan seperti ini:
```java
javac TestExceptions one two three
args[0]=one
args[1]=two
args[2]=three
Exception caught:
java.lang.ArrayIndexOutOfBoundsException: 3
Quiting...
```

## 12.4.2 Menangkap Exception 2
Melakukan percobaan pada beberapa program yang telah Anda tulis adalah hal yang baik sebelum
menghadapi exception. Karena pada program di atas Anda tidak menangkap exception, maka
eksekusi dengan mudahnya berhenti mengeksekusi program Anda. Kembali kepada program
diatas dan gunakan penanganan exception.
