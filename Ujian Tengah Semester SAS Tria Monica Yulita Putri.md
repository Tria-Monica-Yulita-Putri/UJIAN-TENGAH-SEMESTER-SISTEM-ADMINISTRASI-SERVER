## **UJIAN TENGAH SEMESTER SISTEM ADMINISTRASI SERVER**

1.  Download ISO installer windows server 2022 terlebih dahulu dengan mengklik link 
    [](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022 )

   
   
   ```markdown
   Klik Download the ISO 
   ```

   

   ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\1 (A).png)
   
   

   ```markdown
   Setelah klik download the ISO, maka selanjutnya yaitu mengikuti step by stepnya. Dan pastikan jangan lupa untuk klik centang yes kemudian klik continue
   ```
   
   
   
   ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\1 (B).png)
   
   


   ```markdown
   Setelah itu pilih Bahasa, lalu klik download dan tunggu hingga download selesai
   ```

   ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\1 (C).png)

   

   2. a. Instalasi Windows Server 2022

      ```markdown
      Setelah download selesai, Maka langkah selanjutnya yaitu buka Virtual Box lalu klik new dan buat mahchine baru, lalu ikuti step by step dan setting seperti gambar-gambar dibawah ini:
      ```

      
      
      ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\1 (D).png)
      
      

```markdown
Beri nama untuk machine dan jenis sistemnya, lalu klik next
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\1 (D).png)



```markdown
Lalu sesuaikan memory size nya 
```

  

![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2.PNG)



```markdown
 Lalu, klik a virtual hard disk now dan selanjutnya klik create 
```

 

![](C:\Users\TRIA YULITA\Downloads\UTS SAS\3.PNG)



````markdown
Pilih VDI (VirtualBox Disk Image) untuk type file hard disknya. Lalu klik next
````

 

![](C:\Users\TRIA YULITA\Downloads\UTS SAS\4.PNG)



```markdown
 Klik Dynamically allocated dan klik next
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\5.PNG)



```markdown
Atur file location dan size, disini menggunakan 40,00 GB
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\6.PNG)



```markdown
Select ISO Download yang sudah di download tadi, lalu klik start
```

 

![](C:\Users\TRIA YULITA\Downloads\UTS SAS\7.PNG)



```markdown
Langkah selanjutnya yaitu klik “start”, maka Windows Server 2022 installation wizard will load, Jangan lupa sesuaikan Bahasa nya sebelum menginstal 
```

 

![](C:\Users\TRIA YULITA\Downloads\UTS SAS\8.PNG)



```markdown
Langkah selanjutnya yaitu, klik “Instal Now” 
```

 

![](C:\Users\TRIA YULITA\Downloads\UTS SAS\9.PNG)



```markdown
 Selanjutnya yaitu Enter the license (if you have on), kemudian tentukan edisi yang akan digunakan, Accept the license dan kemudian lanjutkan dengan instalasi Windows Server 2022
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\10.PNG)

  

![](C:\Users\TRIA YULITA\Downloads\UTS SAS\11.PNG)



```markdown
Pilih “Custom” untuk type instalnya
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\12 (pilih custom).PNG)



```markdown
Lalu klik next 
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\13.PNG)



```markdown
Dan tunggu hingga proses selesai 
```

  

![](C:\Users\TRIA YULITA\Downloads\UTS SAS\14.PNG)



```markdown
 Setelah proses Instal selesai, maka tampilan akan menjadi seperti gambar dibawah ini 
```

  

![](C:\Users\TRIA YULITA\Downloads\UTS SAS\15.png)



```markdown
Setelah ready, maka langkah selanjutnya yaitu, membuat password, lalu klik Finish
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\18.PNG)



```markdown
Langkah selanjutnya yaitu, klik device -> insert guest additions CD image 
```

 

![](C:\Users\TRIA YULITA\Downloads\UTS SAS\17.png)



```markdown
Selanjutnya yaitu masuk ke file explorer -> CD Drive Vortual box -> Lalu pilih Vbox WindowdAdditions
```

 

![](C:\Users\TRIA YULITA\Downloads\UTS SAS\23.PNG)



```markdown
 Lalu klik next 
```

  

![](C:\Users\TRIA YULITA\Downloads\UTS SAS\24.PNG)

  

![](C:\Users\TRIA YULITA\Downloads\UTS SAS\25.PNG)



```markdown
Lalu Langkah selanjutnya yaitu, klik “install”
```

 

![](C:\Users\TRIA YULITA\Downloads\UTS SAS\26.PNG)



```markdown
 Tunggu hingga install selesai 
```

 

![](C:\Users\TRIA YULITA\Downloads\UTS SAS\27.PNG)



```markdown
 Setelah itu klik “reboot now” dan klik finish
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\28.PNG)



```markdown
 Setelah Reboot selesai, maka akan muncuk tampilan seperti gambar dibawah ini.
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\19.PNG)



```markdown
Untuk Unlock yaitu klik input -> Keyboard -> Insert ctrl-alt-del 
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\19 (2).png)



```markdown
 Setelah terbuka, maka tampilan akan seperti gambar dibawah ini. Maka Langkah selanjutnya yaitu masukkan password yang sudah dibuat di awal tadi.
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\22.PNG)



```markdown
 Ketika berhasil masuk ke Windows Server 2022, maka tampilan akan seperti gambar dibawah ini. Dan proses instalasi  Windows Server 2022 telah selesai.
```

  

![](C:\Users\TRIA YULITA\Downloads\UTS SAS\20.PNG)

  

![](C:\Users\TRIA YULITA\Downloads\UTS SAS\21.PNG)


​      

2. b. Instalasi Active Directory Domain Services

   

```markdown
Pertama-tama Sebelum menginstall Active Directory Domain Services yaitu masuk ke Windows powerShell terlebih dahulu untuk mengganti nama computer di windows
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2B\1.PNG)




```markdown
Lalu, Langkah selanjutnya yaitu ubah nama di Windows powerShell dengan mengetik rename-computer -Newname Server 2022
```

![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2B\2.PNG)



```markdown
Lalu, Langkah selanjutnya yaitu masuk ke server manager, dan pilih menu manage
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2B\3.PNG)



```markdown
Kemudian Langkah selanjutnya yaitu pilih Add Roles and features. Lalu klik next
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2B\4.PNG)



```markdown
Setelah itu, klik Role-Based or feature-based installation kemudian next
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2B\5.PNG)



```markdown
Setelah itu, pilih select a server from the server pool
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2B\6.PNG)



```markdown
Selanjutnya pilih active directory domain server
```

```markdown
Setelah itu, klik Add features
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2B\7.PNG)



```markdown
Langkah selanjutnya yaitu, masuk ke features lalu centang Group Policy Management. Lalu klik next 
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2B\8.PNG)



```markdown
Lalu Langkah selanjutnya yaitu klik next
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2B\9.PNG)



```markdown
Lalu klik install 
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2B\10.PNG)



```markdown
Tunggu hingga proses install selesai 
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2B\11.PNG)



```markdown
Setelah proses install selesai, maka install Active Directory Domain Services telah berhasil dilakukan. Lalu Langkah selanjutnya klik close
```



![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2B\12.PNG)



2. c. Instalasi DNS server

   

   ```markdown
   Pertama-tama masuk ke menu “Server Manager”. Lalu pilih opsi Manage, terus lanjut klik “Add Roles and Features”. Kemudian klik “Next”. Lalu pilih “DNS Server” 
   ```

   ```markdown
   Setelah itu klik Add Features
   ```

   

   ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2C\1.PNG)

   

   ```markdown
   Langkah selanjutnya yaitu, klik continue
   ```

   

   ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2C\2.PNG)

   

   ```markdown
   Langkah selanjutnya masuk ke features lalu centang Group Policy Management. Lalu klik next 
   ```

   

   ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2C\3.PNG)

   

   ```markdown
   Setelah itu klik next 
   ```

   

   ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2C\4.PNG)

   

   ```markdown
   Lalu, Langkah selanjutnya yaitu klik “Install”
   ```

   

   ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2C\5.PNG)

   

   ```markdown
   Tunggu hingga proses install selesai
   ```

   

   ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2C\6.PNG)

   

   ```markdown
   Setelah proses install selesai, maka instal DNS Servers berhasil dilakukan . Lalu Langkah selanjutnya klik close
   ```

   

   ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2C\7.PNG)

   

   2. d. Instalasi Net Framework 3.5

      

      ```markdown
      Pertama-tama yaitu masuk ke menu “Server Manager”. Lalu pilih opsi Manage, terus lanjut klik “Add Roles and Features”. Kemudian klik “Next”. Lalu pilih “NET Framework 3.5 features”. Lalu klik “next”
      ```

      

      ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2D\1.PNG)

      

      ```markdown
      Langkah selanjutnya yaitu, klik “install”
      ```

      

      ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2D\2.PNG)

      

      ```markdown
      Tunggu hingga proses instalasi selesai
      ```

      

      ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2D\3.PNG)

      

      ```markdown
      Setelah proses instalasi selesai, maka instalasi “NET Framework 3.5 features” telah berhasil dilakukan. Lalu selanjutnya klik “close”
      ```

      

      ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2D\4.PNG)

      

      2. e. Promote Server to a Domain Controller

         

         ```markdown
         Pertama-tama yaitu masuk ke “Command Prompt” terlebih dahulu. 
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\1.PNG)

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\2.PNG)

         

         * Konfigurasi ADDS

         ```markdown
         Setting IP Address Server-ADDS dan mengarah DNS ke IP address static yang digunakan
         ```

         ```markdown
         Lalu setting Ip dengan mengetik sconfig
         ```

         ```markdown
         Lalu pilih option “Network setting”
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\3.PNG)

         

         ```markdown
         Lalu ketik angka 1
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\4.PNG)

         

         ```markdown
         Maka disini dapat dilihat sudah mendapatkan IP address 10.0.2.15
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\5.PNG)

         

         ```markdown
         Lalu ketikan ip addres yang sudah di dapat tadi.
         ```

         ```markdown
         Ketikkan subnet mask 255.255.255.0
         ```

         ```markdown
         Lalu klik enter
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\6.PNG)

         

         ```markdown
         Lalu Langkah selanjutnya yaitu masuk ke setting, lalu klik “Change adapter options” untuk setting IP address
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\7.PNG)

         

         ```markdown
         Lalu klik Ethernet
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\8.PNG)

         

         ```markdown
         Lalu klik properties
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\9.PNG)

         

         ```markdown
         Lalu Langkah selanjutnya yaitu klik Internet protocol version 4 (TCP/IPv4)
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\10.PNG)

         

         ```markdown
         Lalu Langkah selanjutnya yaitu setting IP address Server-ADDS yang mengarah ke DNS ke IP address satatic yang digunakan
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\11.PNG)

         

         ```markdown
         Lalu Langkah selnjutnya yaitu klik Promote this server to a domain controller untuk konfigurasi ADDS
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\12.PNG)

         

         ```markdown
         Pilih “Add a new forest” dan masukkan nama domain yang akan digunakan pada Root Domain Name. Misalnya disini saya menggunakan domain “Monica.com”
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\13.PNG)

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\14.PNG)

         

         ```markdown
         Lalu klik “next”
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\15.PNG)

         

         ```markdown
         Pilih “Windows Server 2016” pada functional level, beri tanda centang pada “Domain Name System (DNS) server” dan ”Global Catalog (GC)”. Serta mengisi password Directory Services Restore Mode dengan kriteria strong password.
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\16.PNG)

         

         ```markdown
         Lewati bagian DNS Options, lalu klik “Next”.
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\17.PNG)

         

         ```markdown
         Lalu, Langkah selanjutnya yaitu mengisi “The NetBIOS domain name” sesuai dengan nama domain yang digunakan
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\18.PNG)

         

         ```markdown
         Lewati bagian Paths, klik “Next”.
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\19.PNG)

         

         ```markdown
         Cek konfigurasi yang ditentukan pada Review Options, jika suda ok. Klik “Next”.
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\20.PNG)

         

         ```markdown
         Jika sudah ada tulisan All prerequisite checks passed successfully. Klik “Install” untuk apply konfigurasi yang sudah ditentukan.
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\21.PNG)

         

         ```markdown
         Lalu tunggu hingga proses intstalasi selesai
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\22.PNG)

         

         ```markdown
         Selanjutnya yaitu klik cloes untuk restart Active Directory Domain Services
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\23.PNG)

         

         ```markdown
         Kemudian Langkah selanjutnya yaitu login menggunakan password administrator
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\24.PNG)

         

         ```markdown
         Untuk mengecek hasil konfigurasi, buka cmd dan ketikkan “netdom query fsmo”
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\25.PNG)

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\26.PNG)

         

         ```markdown
         Setelah itu masuk ke Network dan Internet Settings
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\27.PNG)

         

         ```markdown
         Setelah login dengan Active Directory Domain Controller Anda, buka properti TCP/IP koneksi jaringan Anda. Anda dapat melihat Alamat IP server DNS yang disukai
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\28.PNG)

         

         ```markdown
         Lalu disini dapat dilihat bahawa IP telah berubah
         ```

         

         ![](C:\Users\TRIA YULITA\Downloads\UTS SAS\2E\29.PNG)

         

      

   

   

   



