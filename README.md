Calculator C#



int sayi1, sayi2;
double işlem;
Console.WriteLine("Lütfen İlk Sayıyı Giriniz");
sayi1 = int.Parse(Console.ReadLine());
Console.WriteLine("Lütfen ikinci Sayıyı Giriniz");
sayi2 = int.Parse(Console.ReadLine());
Console.WriteLine("Lütfen İşlem Seçiniz 1Toplama 2Çıkarma 3Çarpma 4Bölme");
işlem = int.Parse(Console.ReadLine());


if (işlem == 1)
{
    işlem = sayi1 + sayi2;
}
if (işlem == 2)
{
    işlem = sayi1 - sayi2;
}
if (işlem == 3)
{
    işlem = sayi1 * sayi2;
}
if (işlem == 4)
{
    işlem = sayi1 / sayi2;
}
Console.WriteLine(işlem);
