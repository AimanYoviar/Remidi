# Remidi

hasil remidi

![Screenshot (237)](https://user-images.githubusercontent.com/68726545/120145699-27eb6100-c20e-11eb-8f32-d8c3526b837a.png)


     public class Remidi {
    public static void main(String[] arg){
        String Merk, Warna, Jenis, Kategori, berapapasang;
        int Size, Harga;
          Scanner keyboard = new Scanner(System.in);    
          
       System.out.println("SELAMAT DATANG DI TOKO JayaBaru");
       
       
       
       System.out.println("<<Masukan sepatu yang anda mau>>");
       
       System.out.println("Pilih Merk anda   : ");
       System.out.println("Tersedia adidas, nike, skechers, puma, reebok, vans, converse, fila  ");
       System.out.print(": ");
       Merk = keyboard.next();
       
       System.out.println("Pilih Size anda   : ");
       System.out.println("Tersedia mulai dari 25, 26,27, 28, 29, 30, 31, 32, 33, 34 "); 
       System.out.print(": ");
       Size = keyboard.nextInt();
       
       System.out.println("Pilih Warna anda   : ");
       System.out.println("Tersedia warna black, white, gold, silver, orange, green, yellow, blue, red "); 
       System.out.print(": ");
       Warna = keyboard.next();
       
       System.out.println("Pilih Jenis anda   : ");
       System.out.println("Tersedia cowok dan cewek"); 
       System.out.print(": ");
       Jenis = keyboard.next();
       
       System.out.println("Pilih Kategori anda   : ");
       System.out.println("Tersedia kategori olahraga, lari, santai, kantoran"); 
       System.out.print(": ");
       Kategori = keyboard.next();
       
       System.out.println("Pilih Harga    : ");
       System.out.println("Tersedia 200k, 300k, 400k, 500k, 600k, 700k, 800k, 900k"); 
       System.out.print(": ");
       Harga = keyboard.nextInt();
             
       System.out.print("Pilih berapapasang : ");
       System.out.println("Tersedia duapasang dan tigapasang"); 
       System.out.print(": ");
       berapapasang = keyboard.next();
       
      
       
        //proses
        System.out.println("==============================");
        System.out.println("BarangAnda");
        System.out.println("Tanggal : 31 mei 2021");
        System.out.println("NamaBarang = "+Merk);
        System.out.println("JumlahBarang = "+berapapasang);
        System.out.println("HargaBarang = "+Harga);
        
       switch(berapapasang){
           case"duapasang":
               System.out.println("anda mendapat diskon 50k");
               System.out.println("==============================");
               break;
           case"tigapasang":
               System.out.println("anda mendapat diskon 100k");
               System.out.println("==============================");
               
        
               
        
        
    }
    
    }
}
