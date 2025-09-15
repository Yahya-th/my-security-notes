## Bandit Level 2

- Hedef: Level 1’den Level 2’ye geçmek
- Çözüm:
  1. ssh ile bağlandım: ssh bandit1@bandit.labs.overthewire.org -p 2220
  2. Dizindeki dosyaları inceledim: ls -l ve ls -a
  3. Şifreyi içeren dosyayı buldum: ./-
  4. Dosya içeriğini okudum: cat ./-
  5. Level 2 şifresini aldım ve Level 2’ye geçtim.
- Notlar: Dosya adı '-' olduğu için cat ./- kullanmak gerekiyor.
