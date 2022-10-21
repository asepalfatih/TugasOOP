# TugasOOP

package BelajarJava.com;

public class PersonBeraksi{
    public static void main(String[] args) {
        
        Person Anton = new Person();

        Anton.Nama = "Anton";
        Anton.JenisKelamin = "LakiLaki";
        Anton.Umur = 19;

        Person  Riko = new Person();

        Riko.Nama = "Riko";
        Riko.JenisKelamin = "Laki-Laki";
        Riko.Umur = 20;
        
        System.out.println("Nama : " + Anton.Nama);
        System.out.println("Jenis Kelamin : " + Anton.JenisKelamin);
        System.out.println("Umur : " + Anton.Umur);

        System.out.println("");

        System.out.println("Nama : " + Riko.Nama);
        System.out.println("Jenis Kelamin : " + Riko.JenisKelamin);
        System.out.println("Umur : " + Riko.Umur);

        
        
    }
}
![output](https://user-images.githubusercontent.com/115930300/197236168-350b9e52-cac0-4ccc-a14c-8dd190e11604.png)



