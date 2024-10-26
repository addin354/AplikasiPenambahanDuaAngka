# AplikasiPenambahanDuaAngka
 Latihan 1 - Addin Husnan Nadhari
 
# Pada Button Tambah saya menggunakan coding
 try {
    int angka1 = Integer.parseInt(txtAngka1.getText());
    int angka2 = Integer.parseInt(txtAngka2.getText());
    int hasil = angka1 + angka2;
    txtHasil.setText(String.valueOf(hasil));
} catch (NumberFormatException e) {
    JOptionPane.showMessageDialog(this, "Masukkan angka yang valid", "Error", JOptionPane.ERROR_MESSAGE);
}

# Pada Button Hapus saya menggunakan coding
txtAngka1.setText("");
txtAngka2.setText("");
txtHasil.setText("");
txtAngka1.requestFocus();

# Pada Button Keluar saya menggunakan Coding
System.exit(0);

# Pada JTextField, tambahkan KeyAdapter untuk memastikan hanya angka yang bisa dimasukkan dengan Coding
char karakter = evt.getKeyChar();
if (!Character.isDigit(karakter)) {
    evt.consume();
}

# Pada JTextField, saya Tambahkan FocusListener untuk membersihkan JTextField saat mendapatkan fokus dengan coding
txtAngka1.setText("");
txtAngka2.setText("");

