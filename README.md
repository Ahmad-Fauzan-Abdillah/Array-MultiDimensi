package tugasprogram;
/**
 *
 * @fauzann
 */
import java.util.Scanner;
public class ArrayMultiDimensi {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String brg[] = new String[5];
        int nota[][] = new int[5][3];
        int pilih = 0, jumlah = 0, total = 0, baris = 0, kolom = 0, grandTotal = 0;

        do{
            System.out.println("\n==========================================================");
            System.out.println("MINI BAKERY ");
            System.out.println("==========================================================");
            System.out.println("(1) Brownies Keju\n(2) Banana Cake\n(3) Japanese Cheese Cake\n(4) Butter Croisant");
            System.out.println("(5) Selesai\n(6) Keluar Program");
            System.out.print("Pilih: ");
            pilih=sc.nextInt();
            switch(pilih){
                    case 1:
                            System.out.println("\n==========================================================");
                            System.out.println("Pilihan Belanja");
                            System.out.println("1. Brwonies Keju  Rp 98.000,-");
                            if(baris < 5){
                                    brg[baris] = "Brownies Keju";
                                    nota[baris][0] = 98000;
                                    System.out.print("Jumlah : ");
                                    jumlah = sc.nextInt();
                                    System.out.println("==========================================================");
                                    nota[baris][1] = jumlah;
                                    nota[baris][2] = nota[baris][0] * nota[baris][1];
                                    grandTotal = grandTotal + nota[baris][2];
                                    //tampilkan daftar belanja
                                    System.out.println("\n==========================================================");
                                    System.out.println("Daftar belanja");
                                    for (int i = 0; i <= baris; i++) {
                                            System.out.print((i + 1) + " ");
                                            System.out.print(brg[i] + " ");
                                            System.out.print(nota[i][0] + " ");
                                            System.out.print(nota[i][1] + " ");
                                            System.out.println(nota[i][2] + " ");
                                    }
                                    baris++;
                                    System.out.println("==========================================================");
                                    System.out.println("");
                            }
                            else{
                                    System.out.println("Keranjang penuh");
                                    System.out.println("==========================================================");
                            }
                            break;
                    case 2:
                            System.out.println("\n==========================================================");
                            System.out.println("Pilihan Belanja");
                            System.out.println("2.Banana Cake  Rp 68.000,-");
                            if(baris < 5){
                                    brg[baris] = "Banana Cake";
                                    nota[baris][0] = 68000;
                                    System.out.print("Jumlah : ");
                                    jumlah = sc.nextInt();
                                    System.out.println("==========================================================");
                                    nota[baris][1] = jumlah;
                                    nota[baris][2] = nota[baris][0] * nota[baris][1];
                                    grandTotal = grandTotal + nota[baris][2];
                                    //tampilkan daftar belanja
                                    System.out.println("\n==========================================================");
                                    System.out.println("Daftar belanja");
                                    for (int i = 0; i <= baris; i++) {
                                            System.out.print((i + 1) + " ");
                                            System.out.print(brg[i] + " ");
                                            System.out.print(nota[i][0] + " ");
                                            System.out.print(nota[i][1] + " ");
                                            System.out.println(nota[i][2] + " ");
                                    }
                                    baris++;
                                    System.out.println("==========================================================");
                                    System.out.println("");
                            }
                            else{
                                    System.out.println("Keranjang penuh");
                                    System.out.println("==========================================================");
                            }
                            break;
                    case 3:
                            System.out.println("\n==========================================================");
                            System.out.println("Pilihan Belanja");
                            System.out.println("3. Japanese Cheese Cake  Rp 47.000,-");
                            if(baris < 5){
                                    brg[baris] = "Japanese Cheese Cake";
                                    nota[baris][0] = 47000;
                                    System.out.print("Jumlah : ");
                                    jumlah = sc.nextInt();
                                    System.out.println("==========================================================");
                                    nota[baris][1] = jumlah;
                                    nota[baris][2] = nota[baris][0] * nota[baris][1];
                                    grandTotal = grandTotal + nota[baris][2];
                                    //tampilkan daftar belanja
                                    System.out.println("\n==========================================================");
                                    System.out.println("Daftar belanja");
                                    for (int i = 0; i <= baris; i++) {
                                            System.out.print((i + 1) + " ");
                                            System.out.print(brg[i] + " ");
                                            System.out.print(nota[i][0] + " ");
                                            System.out.print(nota[i][1] + " ");
                                            System.out.println(nota[i][2] + "");
                                    }
                                    baris++;
                                    System.out.println("==========================================================");
                                    System.out.println("");
                            }
                            else{
                                    System.out.println("Keranjang penuh");
                                    System.out.println("==========================================================");
                            }
                            break;
                    case 4:
                            System.out.println("\n==========================================================");
                            System.out.println("Pilihan Belanja");
                            System.out.println("4. Butter Croisant  Rp 18.000,-");
                            if(baris < 5){
                                    brg[baris] = "Butter Croisant";
                                    nota[baris][0] = 18000;
                                    System.out.print("Jumlah : ");
                                    jumlah = sc.nextInt();
                                    System.out.println("==========================================================");
                                    nota[baris][1] = jumlah;
                                    nota[baris][2] = nota[baris][0] * nota[baris][1];
                                    grandTotal = grandTotal + nota[baris][2];
                                    //tampilkan daftar belanja
                                    System.out.println("\n==========================================================");
                                    System.out.println("Daftar belanja");
                                    for (int i = 0; i <= baris; i++) {
                                            System.out.print((i + 1) + " ");
                                            System.out.print(brg[i] + " ");
                                            System.out.print(nota[i][0] + " ");
                                            System.out.print(nota[i][1] + " ");
                                            System.out.println(nota[i][2] + "");
                                    }
                                    baris++;
                                    System.out.println("==========================================================");
                                    System.out.println("");
                            }
                            else{
                                    System.out.println("Keranjang penuh");
                                    System.out.println("==========================================================");
                            }
                        break;
                    case 5:
                            System.out.println("\n==========================================================");
                                    System.out.println("Daftar belanja");
                            for (int i = 0; i < baris; i++) {
                                    System.out.print((i + 1) + " ");
                                    System.out.print(brg[i] + " ");
                                    System.out.print(nota[i][0] + " ");
                                    System.out.print(nota[i][1] + " ");
                                    System.out.println(nota[i][2] + " ");
                            }
                            System.out.println("Grand Total : " + grandTotal);
                            System.out.println("Terimakasih.....");
                            System.out.println("==========================================================");
                            System.out.println("");
                            baris = 0;
                            grandTotal = 0;
                            break;

                    case 6:
                            System.out.println("Terimakasih.....");
                            break;
                    default:
                            System.out.println("Pilihan anda tidak ditemukan");
                }
        }while(pilih != 6);
    }
}
