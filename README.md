public class Mobil {
    private String id_mobil;
    private String seri_mobil;
    private String jenis;
    private String nama_mobil;
    private String warna;
    private String bahan_bakar;
    private String foto;
    private int tahun;
    private int cc;
    private int stok;
    private int harga;
     private static ArrayList<Mobil> daftarMobil = new ArrayList<>();

    public Mobil(String id_mobil, String seri_mobil, String jenis, String nama_mobil, String warna, String bahan_bakar, int tahun, int cc, int stok, int harga,String foto) {
        this.id_mobil = id_mobil;
        this.seri_mobil = seri_mobil;
        this.jenis = jenis;
        this.nama_mobil = nama_mobil;
        this.warna = warna;
        this.bahan_bakar = bahan_bakar;
        this.tahun = tahun;
        this.cc = cc;
        this.stok = stok;
        this.harga = harga;
        this.foto=foto;
    }
    public Mobil(String id_mobil, String seri_mobil, String jenis, String nama_mobil, String warna, String bahan_bakar, int tahun, int cc, int stok, int harga) {
        this.id_mobil = id_mobil;
        this.seri_mobil = seri_mobil;
        this.jenis = jenis;
        this.nama_mobil = nama_mobil;
        this.warna = warna;
        this.bahan_bakar = bahan_bakar;
        this.tahun = tahun;
        this.cc = cc;
        this.stok = stok;
        this.harga = harga;

    }

    public Mobil(String id_mobil) {
        this.id_mobil = id_mobil;
    }

    public Mobil(String id_mobil, String foto) {
        this.id_mobil = id_mobil;
        this.foto = foto;
    }
    
    public Mobil(String seri_mobil, String jenis, String nama_mobil, String warna, String bahan_bakar, int tahun, int cc, int stok, int harga) {
        this.seri_mobil = seri_mobil;
        this.jenis = jenis;
        this.nama_mobil = nama_mobil;
        this.warna = warna;
        this.bahan_bakar = bahan_bakar;
        this.tahun = tahun;
        this.cc = cc;
        this.stok = stok;
        this.harga = harga;
    }

    public String getFoto() {
        return foto;
    }

    public void setFoto(String foto) {
        this.foto = foto;
    }

    public String getId_mobil() {
        return id_mobil;
    }

    public void setId_mobil(String id_mobil) {
        this.id_mobil = id_mobil;
    }

    public String getSeri_mobil() {
        return seri_mobil;
    }

    public void setSeri_mobil(String seri_mobil) {
        this.seri_mobil = seri_mobil;
    }

    public String getJenis() {
        return jenis;
    }

    public void setJenis(String jenis) {
        this.jenis = jenis;
    }

    public String getNama_mobil() {
        return nama_mobil;
    }

    public void setNama_mobil(String nama_mobil) {
        this.nama_mobil = nama_mobil;
    }

    public String getWarna() {
        return warna;
    }

    public void setWarna(String warna) {
        this.warna = warna;
    }

    public String getBahan_bakar() {
        return bahan_bakar;
    }

    public void setBahan_bakar(String bahan_bakar) {
        this.bahan_bakar = bahan_bakar;
    }

    public int getTahun() {
        return tahun;
    }

    public void setTahun(int tahun) {
        this.tahun = tahun;
    }

    public int getCc() {
        return cc;
    }

    public void setCc(int cc) {
        this.cc = cc;
    }

    public int getStok() {
        return stok;
    }

    public void setStok(int stok) {
        this.stok = stok;
    }

    public int getHarga() {
        return harga;
    }

    public void setHarga(int harga) {
        this.harga = harga;
    }
    
    public static ArrayList<Mobil> getDaftarMobil() {
        return daftarMobil;
    }

    public static void addDaftarMobil(Mobil data) {
        daftarMobil.add(data);
    }
    }
