![Stars](https://img.shields.io/github/stars/ebrar-M/css-beginner-notes?style=flat&logo=github)
![Forks](https://img.shields.io/github/forks/ebrar-M/css-beginner-notes?style=flat&logo=github)
![Last Commit](https://img.shields.io/github/last-commit/ebrar-M/css-beginner-notes?color=brightgreen)
![C++](https://img.shields.io/badge/C++-Programming-00599C?logo=c%2B%2B&logoColor=white)



**---**

## 🌍 Languages
- 🇹🇷 [Türkçe](#-tr-türkçe)
- 🇬🇧 [English](#-gb-english)

---

## 🇹🇷 TR Türkçe


# 🟥 C++ Programlama Dili - Temelleri

## 1. 📖 C++ Nedir?
- **C++**, Bjarne Stroustrup tarafından 1980’lerde C dili üzerine geliştirilmiş bir programlama dilidir.  
- C’nin hızını korurken, **Nesne Yönelimli Programlama (OOP)** özellikleri eklenmiştir.  
- Sistem yazılımı, oyun motorları, yapay zeka, yüksek performanslı uygulamalarda sıkça kullanılır.  

---

## 2. 🏗️ İlk C++ Programı
```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "Merhaba C++ 🚀" << endl;
    return 0;
}
```

📌 Açıklama:  
- `#include <iostream>` → giriş/çıkış kütüphanesini ekler.  
- `cout` → ekrana yazdırır.  
- `endl` → yeni satır ekler.  

---

## 3. 🔑 Değişkenler ve Veri Tipleri
```cpp
int sayi = 10;        // Tam sayı
float pi = 3.14;      // Ondalık sayı
double buyukPi = 3.14159; // Daha hassas ondalık
char harf = 'A';      // Tek karakter
string isim = "Ebrar"; // Metin
bool dogruMu = true;  // Mantıksal değer
```

---

## 4. 🧮 Operatörler
```cpp
int a = 5, b = 2;
cout << a + b << endl; // Toplama
cout << a - b << endl; // Çıkarma
cout << a * b << endl; // Çarpma
cout << a / b << endl; // Bölme
cout << a % b << endl; // Mod
```

---

## 5. 🔁 Koşullar ve Döngüler

### If - Else
```cpp
int yas = 18;
if (yas >= 18) {
    cout << "Reşitsiniz ✅" << endl;
} else {
    cout << "Reşit değilsiniz ❌" << endl;
}
```

### Switch
```cpp
int gun = 3;
switch (gun) {
    case 1: cout << "Pazartesi" << endl; break;
    case 2: cout << "Salı" << endl; break;
    case 3: cout << "Çarşamba" << endl; break;
    default: cout << "Bilinmiyor" << endl;
}
```

### For Döngüsü
```cpp
for (int i = 1; i <= 5; i++) {
    cout << i << endl;
}
```

### While Döngüsü
```cpp
int sayac = 0;
while (sayac < 3) {
    cout << "Sayaç: " << sayac << endl;
    sayac++;
}
```

---

## 6. 📦 Fonksiyonlar
```cpp
#include <iostream>
using namespace std;

int kare(int x) {
    return x * x;
}

int main() {
    cout << kare(5) << endl;
    return 0;
}
```

---

## 7. 🏗️ Sınıflar ve Nesneler (OOP)
```cpp
#include <iostream>
using namespace std;

class Ogrenci {
public:
    string isim;
    int yas;

    void bilgi() {
        cout << "Ad: " << isim << ", Yas: " << yas << endl;
    }
};

int main() {
    Ogrenci ogr;
    ogr.isim = "Ebrar";
    ogr.yas = 20;
    ogr.bilgi();
    return 0;
}
```

---

## 8. 🚀 Diziler ve Vektörler

### Dizi
```cpp
int sayilar[5] = {1, 2, 3, 4, 5};
for (int i = 0; i < 5; i++) {
    cout << sayilar[i] << endl;
}
```

### Vektör (C++ STL)
```cpp
#include <iostream>
#include <vector>
using namespace std;

int main() {
    vector<string> meyveler = {"Elma", "Armut", "Muz"};
    for (string meyve : meyveler) {
        cout << meyve << endl;
    }
    return 0;
}
```

---

## 9. 🌈 İpuçları
✔️ `using namespace std;` → kolaylık sağlar ama büyük projelerde dikkatli kullan.  
✔️ Bellek yönetimini öğren (`new`, `delete`).  
✔️ Modern C++ ile `std::vector`, `std::string` gibi STL (Standard Template Library) yapıları kullan.  
❌ Çiğ işaretçiler (`raw pointer`) → başlangıç için kafa karıştırabilir.  

---

## 🎯 Mini Alıştırmalar
1. Kullanıcıdan 2 sayı al → toplamasını, çıkarmasını, çarpmasını ve bölmesini ekrana yazdır.  
2. 1’den 100’e kadar olan sayıların toplamını bulan program yaz.  
3. Bir `Araba` sınıfı oluştur → markası ve modeli olsun, nesne üzerinden ekrana yazdır.  
4. Bir vektör oluştur (`int` tipinde) → eleman ekle, sil, yazdır.  

---

## 📌 Son Söz
C++ dili, hem **sistem programlamada** hem de **yüksek seviyeli uygulamalarda** kullanılabilen güçlü bir dildir.  
OOP (Sınıflar, Kalıtım, Polimorfizm) özellikleri sayesinde büyük projelerde tercih edilir.  
Kısacası: **C’nin gücü + OOP = C++ 🚀**

---

## 🇬🇧 GB English

# 🟥 C++ Programming Language - Fundamentals

## 1. 📖 What is C++?
- **C++** is a programming language developed by Bjarne Stroustrup based on the C language in the 1980s.
- While maintaining the speed of C, it adds **Object-Oriented Programming (OOP)** features.
- It is frequently used in system software, game engines, artificial intelligence, and high-performance applications.

---

## 2. 🏗️ First C++ Program
```cpp
#include <iostream>
using namespace std;

int main() {
cout << "Hello C++ 🚀" << endl;
return 0;
}
```

📌 Description:
- `#include <iostream>` → adds the input/output library.
- `cout` → prints to the screen.
- `endl` → adds a new line.

---

## 3. 🔑 Variables and Data Types
```cpp
int number = 10; // Integer
float pi = 3.14; // Decimal number
double bigPi = 3.14159; // More precise decimal
char letter = 'A'; // Single character
string name = "Ebrar"; // Text
bool true = true; // Logical value
```

---

## 4. 🧮 Operators
```cpp
int a = 5, b = 2;
cout << a + b << endl; // Addition
cout << a - b << endl; // Subtraction
cout << a * b << endl; // Multiplication
cout << a / b << endl; // Division
cout << a % b << endl; // Mode
```

---

## 5. 🔁 Conditions and Loops

### If - Else
```cpp
int age = 18;
if (age >= 18) {
cout << "You are a minor ✅" << endl;
} else {
cout << "You are a minor ❌" << endl;
}
```

### Switch
```cpp
int day = 3;
switch (day) {
case 1: cout << "Monday" << endl; break;
case 2: cout << "Tuesday" << endl; break;
case 3: cout << "Wednesday" << endl; break;
default: cout << "Unknown" << endl;
}
```

### For Loop
```cpp
for (int i = 1; i <= 5; i++) { 
cout << i << endl;
}
```

### While Loop
```cpp
int counter = 0;
while (counter < 3) { 
cout << "Counter: " << counter << endl; 
counter++;
}
```

---

## 6. 📦 Functions
```cpp
#include <iostream>
using namespace std;

int square(int x) { 
return x * x;
}

int main() { 
cout << square(5) << endl; 
return 0;
}
```

---

## 7. 🏗️ Classes and Objects (OOP)
```cpp
#include <iostream>
using namespace std;

class Student {
public:
string name;
int age;

void info() {
cout << "Name: " << name << ", Age: " << age << endl;
}
};

int main() {
Student student;
student.name = "Ebrar";
student.age = 20;
student.info();
return 0;
}
```

---

## 8. 🚀 Arrays and Vectors

### Array
```cpp
int numbers[5] = {1, 2, 3, 4, 5};
for (int i = 0; i < 5; i++) {
cout << numbers[i] << endl;
}
```

### Vector (C++ STL)
```cpp
#include <iostream>
#include <vector>
using namespace std;

int main() {
vector<string> fruits = {"Apple", "Pear", "Banana"};
for (string fruit : fruits) {
cout << fruit << endl;
}
return 0;
}
```

---

## 9. 🌈 Tips
✔️ `using namespace std;` → is convenient, but use it carefully in large projects.
✔️ Learn memory management (`new`, `delete`).
✔️ Use STL (Standard Template Library) structures like `std::vector` and `std::string` with modern C++.

❌ Raw pointers → can be confusing at first.

---

## 🎯 Mini Exercises
1. Receive 2 numbers from the user → print their addition, subtraction, multiplication, and division.
2. Write a program that finds the sum of numbers from 1 to 100.
3. Create a `Car` class → print the make and model from the object.
4. Create a vector (of type `int`) → add, delete, and print elements.

---

## 📌 Final Word
C++ is a powerful language that can be used in both **system programming** and **high-level applications**.
Its OOP (Classes, Inheritance, Polymorphism) features make it a popular choice for large projects. In short: **The Power of C + OOP = C++ 🚀**
