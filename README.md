<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
  </head>
  <body>
    <h1>ft_printf Fonksiyonu</h1>
    <p>Bu proje, C programlama dilinde yazılmış basit bir <code>printf</code> fonksiyonu implementasyonunu içermektedir. Projenin amacı, <code>printf</code> fonksiyonunun nasıl çalıştığını anlamak ve benzer bir işlevi kendimiz yazarak C programlama dilinde daha fazla deneyim kazanmaktır.</p>
    <h2>Kullanım</h2>
    <p><code>ft_printf</code> fonksiyonu, standart C kütüphanesindeki <code>printf</code> fonksiyonuna benzer şekilde kullanılabilir. Fonksiyonun prototipi şu şekildedir:</p>
    <pre><code>int ft_printf(const char *format, ...);</code></pre>
    <p><code>format</code> parametresi, yazdırılacak metnin formatını belirtir ve tıpkı standart <code>printf</code> fonksiyonunda olduğu gibi, özel biçimlendirme özellikleri kullanılabilir. Örneğin:</p>
    <pre><code>ft_printf("Merhaba, %s! Bugün %d derece sıcaklık var.", "Ahmet", 23);</code></pre>
    <p>Bu kod, ekrana "Merhaba, Ahmet! Bugün 23 derece sıcaklık var." şeklinde yazı yazdıracaktır.</p>
    <h2>Desteklenen Biçimlendirme Özellikleri</h2>
    <p>Bu proje, aşağıdaki biçimlendirme özelliklerini desteklemektedir:</p>
    <ul>
      <li><code>%c</code> - Karakter yazdırma</li>
      <li><code>%s</code> - Karakter dizisi yazdırma</li>
      <li><code>%d</code> - Ondalık sayı yazdırma</li>
      <li><code>%i</code> - Ondalık sayı yazdırma (alternatif)</li>
      <li><code>%o</code> - Sekizli sayı yazdırma</li>
      <li><code>%u</code> - İkili sayı yazdırma</li>
      <li><code>%x</code> - Onaltılı sayı yazdırma (küçük harf)</li>
      <li><code>%X</code> - Onaltılı sayı yazdırma (büyük harf)</li>
      <li><code>%%</code> - Yüzde işareti yazdırma</li>
    </ul>
    <ul>
      <li
