import java.util.Scanner;

public class konversiWaktu {

	public static void main(String[] args) {
		int totalDetik, detikSekarang, totalMenit, menitSekarang, totalJam, jamSekarang;
		Scanner masukan;
		masukan = new Scanner(System.in);
		
		//1203183086
		System.out.print("masukkan total detik : ");
		totalDetik = masukan.nextInt();
		
		detikSekarang = totalDetik%60;
		System.out.println("detik saat ini : "+detikSekarang);
		
		totalMenit = totalDetik/60;
		System.out.println("total menit    : "+totalMenit+" menit");
		
		menitSekarang = totalMenit%60;
		System.out.println("menit saat ini : "+menitSekarang);
		
		totalJam = totalMenit/60;
		System.out.println("total jam      : "+totalJam+" jam");
		
		jamSekarang = totalJam%24;
		System.out.println("jam saat ini   : "+jamSekarang+"\n");
		
		System.out.println("waktu => "+jamSekarang+":"+menitSekarang+":"+detikSekarang);
		
	}

}
