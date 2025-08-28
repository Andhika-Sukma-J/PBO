public class Bank {
    private int saldo;

    public Bank(int saldoAwal) {
        this.saldo = saldoAwal;
    }

    public void simpanUang(int jumlah) {
        saldo += jumlah;
        System.out.println("Simpan uang: Rp. " + jumlah);
        System.out.println("Saldo saat ini: Rp. " + saldo);
        System.out.println();
    }

    public void ambilUang(int jumlah) {
        saldo -= jumlah;
        System.out.println("Ambil uang: Rp. " + jumlah);
        System.out.println("Saldo saat ini: Rp. " + saldo);
        System.out.println();
    }

    public void getSaldo() {
        System.out.println("Saldo saat ini: Rp. " + saldo);
        System.out.println();
    }

    public static void main(String[] args) {
        Bank rekening = new Bank(100000); 
        rekening.getSaldo();

        rekening.simpanUang(500000);
        rekening.ambilUang(150000);
        rekening.getSaldo();
    }
}
