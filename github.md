# Git vs Github 


# birnichi navbatga git ni kompyuterga o'rnatib github.com dan online akkount ochib olamiz

*** git ni o'rnatgandan keyin (git bash) ni ochasiz
*** git bash da username va email ni sozlab olishimiz kerak
*** git config  --global  user.name "Github.com dagi username ni kiriting"
*** git config --global user.email "sizning emailingiz"



Git va Github nima o'zi?

1. Git bu nima?

Git bu Version Control System yani (VCS) - kod versiyasini nazorat qiluvchi tizm

---------------  Gitni ustunlik tomonlari  -------------------

1. Kod versiyasini nazorat qilish
2. Qanday o'zgarishlar bo'layotganini bilib turadi.
3. Qachon va kim tomonidan kodga o'zgarish kiritilganini bilish mumkin
4. Loyihani jamoviy ishlash mumkin
5. Open Sourse loyihalarga yordam beradi

---------------- Github nima? ------------------

 ! Github - Online Version Control System hosting hizmati

---------------- Git komandalari  ---------------

1. git add . ----> loyihadagi yangi fayllar va o'zgartirilgan va o'chirilgan xotiraga olish uchun navbatga qo'yadi 
2.  (.) nuqta git add . yani nuqta bu hammsi degani hamma faylni qo'sh degani 
-------------   terminlda  ------------------
1. git status
   index.html - qizil rangda turgan bo'ladi
2. git add index.html yoki . 
3. git status
   index.html - yashil rangda bo'ladi

------------ Fayl o'zgarishlarini bekor qilish ---------------
* git checkout --<filename>-- faylda bo'lgan o'zgarishlarni bekor qiladi
* git chechout --.-- bu barcha fayldagi o'zgarishlarni bekor qiladi

--------------- Terminlada -----------------

fayl yaratish

* touch index.html

------------ Git comanda -----------------

* git init - Bu yani .git yaratish uchun ishlatiladi
* git clone repazitor_url - Bu comanda mavjud url dan repazitorni olish uchun ishlatiladi [clone - yaratish]
* git add filename yoki . dan foydalaning Bu komanda fayl yoki fayllarni qo'shish mumkin stajn arrayga qo'shadi
* git commit -m "izoh yozish" - Bu komanda versiyalar tarixida fayllarimizni doimiy yozib qoladi
* git commit -a - Bu komanda git add va git commit komandalarini birgalikda bajaradi
* git dif - Bu komanda stajn arrayga qo'shilmagan fayllarni farqini topadi
* git reset [file] - Bu komanda stajn arraydan qaytarish uchun