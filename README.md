# Langkah-langkah pembuatan latihan dari project PBO
- [Modul 3](README.md#modul-3) Mengenali Lingkup Pemrograman Anda
- [Modul 4](README.md#modul-4) Dasar-Dasar Pemrograman
- [Modul 5](README.md#modul-5) Mendapatkan Input dari Keyboard
- [Modul 6](README.md#modul-6)
- [Modul 7](README.md#modul-7)

## Modul 3
# 3.6 Latihan
### `3.6.1 Hello World!`
Menggunakan NetBeans, membuat class dengan nama : [NamaAnda]. Hasil dari
program yang harus tampil dilayar :
```
Welcome to Java Programming [NamaAnda]!!!
```
Kode Program :
```java
public class HelloWord {
    public static void main(String[] args) {
        System.out.println("Welcome to Java Programming [Siti Nurhaliza Yus]!!!");
    }
}
```
Hasil Run/Output :

![2](https://user-images.githubusercontent.com/114122090/197296812-818549ef-c509-42f0-8670-05f394a15425.png)

### `3.6.2 The Tree`
Menggunakan NetBeans, membuat class dengan nama : TheTree. Hasil dari program
yang harus tampil dilayar :
```
I think that I shall never see,
a poem as lovely as a tree. 
A tree whose hungry mouth is pressed 
Against the Earth’s sweet flowing breast.
```
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
Hasil Run/Output :

![3](https://user-images.githubusercontent.com/114122090/197296833-d85de8f8-ba46-46cb-ae83-bc19eb5843aa.png)

Variasi lainnya 

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
### `4.11.1 Mendeklarasikan dan mencetak variabel `
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
Hasil Run/Output :

Masukan karakter dengan klik terlebih dahulu untuk menginputkan karakter

![1](https://user-images.githubusercontent.com/114122090/197332775-5a52d639-daff-47ab-8253-b6a246c8fb55.png)

Output

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

Hasil Run/Output :

![3](https://user-images.githubusercontent.com/114122090/197332988-381e6eaf-7b02-471e-b2da-98728a545328.png)
*inputan pertama*

![4](https://user-images.githubusercontent.com/114122090/197333049-d7eb5386-6799-483a-9339-c204e0e9ab04.png)
*inputan kedua*

![5](https://user-images.githubusercontent.com/114122090/197333056-cd40c3df-2873-4bb8-a79b-632908587922.png)
*output*
