# Judul Praktikum

Interfacing Laboratory (Teknik Antarmuka)

## Deskripsi

Program Antarmuka dengan VS Code dan bahasa C++
* Download VS Code disini (https://code.visualstudio.com/download)
* Download MinGW-x64 disini (https://github.com/msys2/msys2-installer/releases/download/2024-12-08/msys2-x86_64-20241208.exe)

## Langkah-Langkah
1) Download, install, dan jalankan Visual Studio Code.
2) Pilih ikon ekstensi.
3) Cari "C++".
4) Pilih install.
   ![alt text](https://github.com/jatisides/jatisides/blob/main/cpp-extension.png)
5) Donwload dan jalankan MinGW-x64
   
   ![alt text](https://github.com/jatisides/jatisides/blob/main/image_2025-02-09_105748383.png)
7) Pada installer, pilih folder instalasi yang diinginkkan dan catat (disarankan menggunakan direktori yang direkomendasikan)
8) Setelah selesai instalasi, pastikan kotak Run MSYS2 now tercentang dan pilih "Finish". Terminal MSYS2 otomatis akan terbuka.
9) Pada terminal ketikkan kode berikut "pacman -S --needed base-devel mingw-w64-ucrt-x86_64-toolchain"
10) Tekan Enter kemudian ketik "Y"
   ![alt text](https://github.com/jatisides/jatisides/blob/main/cpp-install-msys2-toolchain.png)
11) Tambahkan path MinGW-w64 bin folder ke Windows PATH environment variable dengan menggunakan langkah berikut:
    *  Pada windows search bar ketik "Edit environment"
    *  Pada variabel User, pilih variable Path dan pilih Edit
       ![alt text]
    *  Pilih New dan tambahkan folder destinasi MinGW-w64 yang sudah Anda cata pada proses instalasi ke dalam list. Path defaultnya adalah C:\msys64\ucrt64\bin
    *  Pilih OK kemudian OK kembali
   
    
In your User variables, select the Path variable and then select Edit.
Select New and add the MinGW-w64 destination folder you recorded during the installation process to the list. If you selected the default installation steps, the path is: C:\msys64\ucrt64\bin.
Select OK, and then select OK again in the Environment Variables window to update the PATH environment variable. You have to reopen any console windows for the updated PATH environment variable to be available.

11)
### Dependencies

* Describe any prerequisites, libraries, OS version, etc., needed before installing program.
* ex. Windows 10

### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders

### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)
