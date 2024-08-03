# C# Temel Veri Tipleri

Bu repository, C# dilinde temel veri tipleri hakkında bilgiler ve örnek kodlar içermektedir. Her bir veri tipi için kısa açıklamalar ve kullanımları aşağıda verilmiştir.

## İçindekiler

- [int](#int)
- [byte](#byte)
- [short](#short)
- [long](#long)
- [float](#float)
- [double](#double)
- [char](#char)
- [boolean](#boolean)

### int

`int` (integer), 32-bitlik işaretli tamsayıyı temsil eder. -2,147,483,648 ile 2,147,483,647 arasında değer alabilir.

#### Örnek:

```csharp
int sayi = 100;
Console.WriteLine(sayi); // 100


### byte

`byte`, 8-bitlik işaretsiz tamsayıyı temsil eder. 0 ile 255 arasında değer alabilir.

#### Örnek:

```csharp

byte yas = 25;
Console.WriteLine(yas); // 25


### short

`short`, 16-bitlik işaretli tamsayıyı temsil eder. -32,768 ile 32,767 arasında değer alabilir.

#### Örnek:

```csharp


short sicaklik = -10;
Console.WriteLine(sicaklik); // -10


### long

`long`, 64-bitlik işaretli tamsayıyı temsil eder. -9,223,372,036,854,775,808 ile 9,223,372,036,854,775,807 arasında değer alabilir.

#### Örnek:

```csharp

long mesafe = 15000000000;
Console.WriteLine(mesafe); // 15000000000

### float


'float', 32-bitlik kayan noktalı sayıyı temsil eder. Kesirli sayıları tutmak için kullanılır ve genellikle f ile sonlandırılır.

#### Örnek:

```csharp

float pi = 3.14f;
Console.WriteLine(pi); // 3.14

### double

'double' 64-bitlik kayan noktalı sayıyı temsil eder. Kesirli sayıları tutmak için kullanılır ve daha yüksek hassasiyet sağlar.

#### Örnek:

```csharp

double e = 2.718281828459045;
Console.WriteLine(e); // 2.718281828459045

### char

'char', tek bir 16-bit Unicode karakteri temsil eder. Tek tırnak işaretleri (' ') içinde kullanılır.

#### Örnek:

```csharp

char harf = 'A';
Console.WriteLine(harf); // A

### boolean

'boolean' (bool), doğru veya yanlış değerini temsil eder. true veya false değerlerini alabilir.

#### Örnek:

```csharp

bool dogruMu = true;
Console.WriteLine(dogruMu); // true

bool yanlisMi = false;
Console.WriteLine(yanlisMi); // false