# begin_misollar
Begin_1. Kvadratning tomoni a berilgan. Uning perimetri aniqlansin. P=4*a.
<?php
$toMoni = 5; 
$perimetri = 4 * $toMoni; 
echo perimetri: . $perimetri;
?>

Begin_2. Kvadratning tomoni a berilgan. Uning yuzasi aniqlansin. S=a2.
<?php
$A = 5; 
$yuzi = $A * $A;
echo yuzi: . $yuzi;
?>

Begin_3. To'g'ri to'rtburchakning tomonlari a va b berilgan. Uning yuzasi S = a*b; va P=2(a+b) perimetri aniqlansin.
<?php
$a = 5; // to'rtburchakning bir tomoni a deb ataymiz
$b = 8; // to'rtburchakning ikki tomoni b deb ataymiz
$S = $a * $b; // to'rtburchakning yuzasini hisoblaymiz
$P = 2 * ($a + $b); // to'rtburchakning perimetri hisoblaymiz
echo "To'rtburchakning yuzasi: " . $S . "<br>";
echo "To'rtburchakning perimetri: " . $P;
?>

Begin_4. Aylananing diametri d berilgan. Uning uzunligi aniqlansin
<?php
function aylanaUzunligi($d) {
  $r = $d / 2;
  $uzunlik = 2 * 3.14 * $r;
  return $uzunlik;

}
$d = 10; // Aylananing diametri
$uzunlik = aylanaUzunligi($d);
echo "Aylananing uzunligi: " . $uzunlik;
?>

Begin_5. Kubning yon tomoni a berilgan. Uning hajmini va to'la sirti  aniqlansin
<?php
$yon_tomon = 5; // Kubning yon tomoni (a)
$hajmi = $yon_tomon ** 3; // Kubning hajmi (a^3)
$to'la_sirt = 6 * ($yon_tomon ** 2); // Kubning to'la sirti  (6 * a^2)
echo "Kubning hajmi: " . $hajmi . "<br>";
echo "Kubning to'la sirti: " . $to'la_sirt;
?>

Begin_6. Paralelepepidning tomonlari a, b, c berilgan. Uning hajminia-bic va to'la sirti S=2(ab+bc+ac) aniqlansin.
<?php
function calculateVolumeAndSurfaceArea($a, $b, $c) {
    $volume = $a * $b * $c;
    $surfaceArea = 2 * ($a * $b + $b * $c + $a * $c); 
    return array($volume, $surfaceArea);
}
$a = 3;
$b = 4;
$c = 5;
list($volume, $surfaceArea) = calculateVolumeAndSurfaceArea($a, $b, $c);
echo "Hajm: $volume\n";
echo "To'la sirt: $surfaceArea\n";
?>


Begin_7. Doiraning radiusi R berilgan. Uning uzunligi L va yuzasi S aniqlansın.
<?php
$R = 5;
$L = 2 * M_PI * $R;
$S = M_PI * $R * $R;
echo "Doiraning radiusi: $R \n";
echo "Doiraning uzunligi: $L \n";
echo "Doiraning yuzasi: $S \n";
?>

Begin_8. Ikkita son a va b berilgan. Ularning o`rta arifmetigi aniqlansin,
<?php
$a = 10;
$b = 5;
$orta_arifmetik = ($a + $b) / 2;
echo "Ikkita sonning o'rta arifmetigi: " . $orta_arifmetik;
?>

Begin_10. Nolga teng bo'lmagan ikkita son berilgan. Ularning yig'indisini, ko'paytmasini va har birining kvadrati aniqlansin.
<?php
$son1 = 5;
$son2 = 7;
$yigindi = $son1 + $son2;
echo "Ikki sonning yig'indisi: " . $yigindi . "<br>";
$kupaytma = $son1 * $son2;
echo "Ikki sonning ko'paytmasi: " . $kupaytma . "<br>";
$kvadrat1 = $son1 * $son1;
echo "Birinchi sonning kvadrati: " . $kvadrat1 . "<br>";
$kvadrat2 = $son2 * $son2;
echo "Ikkinchi sonning kvadrati: " . $kvadrat2 . "<br>";
?>
INTEGER
1.Uzunlik L santimetrda berilgan. Undagi to'liq metrlar sonini aniqlovchi programma tuzilsin. (1m-100cm)
<?php
$uzunlik_cm = 150;
$metr = $uzunlik_cm / 100;
echo "Berilgan uzunlik " . $uzunlik_cm . " santimetrda.\n";
echo "Total " . $metr . " metr mavjud.\n";
?>

2.Og'irlik M kilogramda berilgan. Undagi to'liq tonnalar sonini aniqlovchi programma tuzilsin. (1t=1000kg)
<?php
$ogirlikM = // Og'irlik M (kg)ni kiriting;
$tonna = $ogirlikM / 1000;
echo "Og'irlik $ogirlikM kg = $tonna tonnalar";
?>

3.Faylning hajmi baytlarda berilgan. Bo'lib butunni olish operatsiyasidan foydalanib fayl hajmining to'liq kilobaytlarda ifodalovchi programma tuzilsin. (1Kb=1024 bayt)
<?php
$file_size_in_bytes = 3072; 
$file_size_in_kb = $file_size_in_bytes / 1024;
$file_size_in_kb_rounded = round($file_size_in_kb);
echo "Fayl hajmi: $file_size_in_kb_rounded Kb";
?>

4.A va B (A> B) musbat sonları berilgan A kesmada, B kesmani necha marta joylashtirish mumkinligini aniqlovchi programma tuzilsin.
<?php
function joylashtirishMarta($a, $b) {

    if ($a <= 0  $b <= 0  $a <= $b) {
        return 0;
    }
    $marta = floor($a / $b);
    return $marta;
}
$a = 20;
$b = 5;
echo "A: $a, B: $b\n";
echo "Joylashuvlar soni: " . joylashtirishMarta($a, $b);
?>

5.A va B (A > B) musbat sonlar berilgan. A kesmada B kesmani necha marta joylashtirish mumkin. A kesmada B kesmaning joylashmagan qismini aniqlovchi programma tuzilsin.
<?php
$A = 10;
$B = 5;
if ($A > $B) {
    $kesmalar_soni = $A / $B;
    echo "A kesmada B kesmani $kesmalar_soni marta joylashtirish mumkin\n";
    $qisqartirilgan_qism = $A % $B;
    echo "A kesmada B kesmaning joylashmagan qismi: $qisqartirilgan_qism\n";
} else {
    echo "Xatolik: A katta emas B dan\n";
}
?>

6.Ikki xonali son berilgan. Oldin uning o'nliklar xonasidagi raqamni, so'ng birlar xonasidagi raqamni chiqaruvchi programma tuzilsin
<?php

$s = "23";
$onliklarXonasi = (int)($s / 10);
$birlarXonasi = (int)($s % 10);
echo "Ushbu sonning o'nliklar xonasidagi raqami: $onliklarXonasi\n";
echo "Ushbu sonning birlar xonasidagi raqami: $birlarXonasi\n";
?>

7.Ikki xonali son berilgan. Uning raqamları yig'indisini aniqlovchi programma tuzilsın
<?php
$son = 25;
$birinchi_raqam = (int)($son / 10);
$ikkinchi_raqam = $son % 10;
$yigindisi = $birinchi_raqam + $ikkinchi_raqam;
echo "Ikki xonali sonning raqamlari yig'indisi: " . $yigindisi;
?>

8.Ikki xonali son berilgan. Uning raqamlari o'mini almashtirishdan hosil bo'lgan sonni aniqlovchi programma tuzilsın
<?php
$son = 54;
$o_m = $son % 10 * 10 + (int)($son / 10);
echo "Berilgan son: " . $son . "\n";
echo "O'mini almashtirilgan son: " . $o_m;
?>

9.Uch xonali son berilgan. Uning yuzlar xonasidagi raqamını aniqlovchi programma tuzılsın.
<?php
function yuzlar_xonasi($son) {
    $yuzlar = floor(($son % 1000) / 100);
    echo "Ushbu sonning yuzlar xonasidagi raqami: " . $yuzlar;

}
$son = 265;
yuzlar_xonasi($son);
?>

10.Uch xonali son berilgan. Oldin uni birliklar xonasidagi raqamni so'ng o'nliklar xonasidagi raqamni chiqaruvchi programma tuzilsın.
<?php
$son = 346; // Uch xonali son
$uchliklar = $son % 10; 
$onliklar = (($son - $uchliklar) % 100) / 10;
echo "Uch xonali son: " . $son . "\n";
echo "Uchliklar xonasidagi raqam: " . $uchliklar . "\n";
echo "Onliklar xonasidagi raqam: " . $onliklar . "\n";
?>
