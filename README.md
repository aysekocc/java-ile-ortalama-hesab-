package calculate_avg_with_your_notes;

import java.util.Scanner;

public class calculate_avg_with_your_notes {
	public static void main(String[] args) {
		Scanner scan = new Scanner (System.in);
		
		System.out.println("matematik notunuzu giriniz: ");
		int mat = scan.nextInt();
		
		System.out.println("fizik notunuzu giriniz: ");
		int fizik = scan.nextInt();
		
		System.out.println("kimya notunuzu giriniz: ");
		int kimya = scan.nextInt();
		
		System.out.println("turkce notunuzu giriniz: ");
		int turkce = scan.nextInt();
		
		System.out.println("tarih notunuzu giriniz: ");
		int tarih = scan.nextInt();
		
		System.out.println("muzik notunuzu giriniz: ");
		int muzik = scan.nextInt();
		
		double ortalama = (mat+fizik+kimya+turkce+tarih+muzik)/6;
		System.out.println("ortalama: " +ortalama);
}}
