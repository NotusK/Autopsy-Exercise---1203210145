# Autopsy-Exercise---1203210145

1. Buat Case Number <br />
![IMAGE!](Images/1.png)

2. Buat struktur folder untuk autopsy didalam folder case number
![IMAGE!](Images/2.png)

3. Buat file txt untuk dokumentasi
![IMAGE!](Images/3.png)

4. Copy paste SuspectData ke folder Images/Exhibit001/
![IMAGE!](Images/4.png)

5. Buka Autopsy dan buat case baru
![IMAGE!](Images/5.png)

6. Set case name sesuai dengan case number dan set base directory ke "F:\Forensik\CASES\001-H-adit-XX\Autopsy"
![IMAGE!](Images/6.png)

7. Set case number dan data dari examiner serta organization
![IMAGE!](Images/7.png)

8. Set host name
![IMAGE!](Images/8.png)

9. Set data source type ke Disk Images
![IMAGE!](Images/9.png)

10. Select data source "SuspectData.dd" dan set timezone ke (GMT +0:00) UTC karena kita tidak tau tersangka ada di timezone berapa. Serta set hash value dari "SuspectData.dd"
![IMAGE!](Images/10.png)

11. Set Modules yang ingin digunakan untuk investigasi
![IMAGE!](Images/11.png)

12. Klik next dan Finish
![IMAGE!](Images/12.png)

13. Lihat-lihat filenya (Found a Secret Code!)
![IMAGE!](Images/13.png)

14. Lihat deleted files list
![IMAGE!](Images/14.png)

15. Lihat Images dengan gallery view
![IMAGE!](Images/15.png)

16. Lihat Hex suatu file dan buka pada HxD
![IMAGE!](Images/16.png)

17. Gunakan Keyword search, cari "key" dan "code"
![IMAGE!](Images/17.png)
![IMAGE!](Images/17-2.png)

18. Tag file hello sebagai notable dan SMBR sebagai bookmark
![IMAGE!](Images/18.png)
![IMAGE!](Images/18-2.png)

19. Buat file report
![IMAGE!](Images/19.png)

20. Cek Report
![IMAGE!](Images/20.png)

# Part 2 is still downloading "15Gb :((((("

1.	Add data source

2.	Specify new host name, lanjutan Exhibit001

3.	Set Source data type as Disk Image or VM File
4.	Set path to Image di Exhibit002 dan set timezone (GMT +0:00) UTC
5.	Configure Modules yang ingin digunakan untuk investigasi
6.	Adding data source (Started 8PM – Finished 8.30PM)
7.	Pada Vol3 NTFS terdapat file $MFT yang berarti vol3 merupakan C drive
8.	Pada Folder User terdapat NTUSER.DAT yang merupakan registry hive, tempat Dimana settings user disimpan
9.	Pada Installed Programs di Data Artifact menampilkan informasi aplikasi apa saja yang telah di install di sistem
10.	Pada Operation System Information terdapat info tentang OS yang digunakan pada kasus ini yang digunakan adalah Windows 10 Home yang berada di direktori “C:\Windows
11.	Pada Recent Documents menunjukan informasi file “baru” di akses dan darimana file tersebut di akses
12.	Pada Recycle Bin terdapat file yang berada pada recycle bin sistem dan file dapat direcover
13.	Bookmarking NMAP-setup dan NMAP pada Run Programs
14.	Bookmarking ConsoleHost-History.txt yang ada command menjalankan NMAP
15.	Shell Bags menunjukan folder yang diakses users/suspect
16.	USB Devices Attached menunjukan device apa saja yang tersambung ke sistem melalui USB
17.	Pada Web Accounts menunjukan login data
18.	Web Cache menunjukan informasi domain web dan kapan domain tersebut di akses
19.	Web Cookies hampir sama dengan Web cache dan juga menunjukan dari browser mana domain tersebut di akses
20.	Web Downloads menunjukan files yang didownload dan darimana file tersebut didownload serta kapan file tersebut didownload
21.	Bookmarking History download nmap setup
22.	Web Form Autofill Menunjukan yang mungkin adalah username dari user/suspect
23.	Web History Menunjukan informasi web history user (bisa locally)
24.	Web Search Menunjukan apa yang di typing oleh user dan pada browser apa
25.	EXIF Metadata berisi gambar jpg dan informasinya seperti date created, device model, device make, altitude, dll
26.	Extension Mismatch Detected berisi files yang extensi filenya tidak cocok dengan MIME typenya
27.	User Content Suspected berisi files yang Autopsy piker adalah file yang dibuat user
28.	Web Account Type Menunjukan tipe-tipe akun user
29.	Web Categories memisahkan informasi-informasi sesuai dengan domain dan hostnya
30.	Generate Report
31.	Hasil Report [The warning is because the ingestion took too long :<]

