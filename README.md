# WordReplace

Bu Python kodu, kullanıcının bir metin dizisi içinde belirli bir kelimeyi değiştirmesine olanak tanır.

Kod, öncelikle bir metin dizesi olan `str` değişkenine bir değer atar. Bu metin dizisi "hi guys, i am tomi, and hi hi hi hi" şeklinde bir örnektir.

Daha sonra, kullanıcıya hangi kelimenin değiştirileceğini sormak için `input()` fonksiyonu kullanılır ve girilen kelime, `word_to_replace` değişkenine atanır. Ardından, hangi kelimeyle değiştirileceğini sormak için tekrar `input()` fonksiyonu kullanılır ve girilen kelime, `word_replacement` değişkenine atanır.

Son olarak, `str.replace()` yöntemi kullanılarak, `word_to_replace` değişkenindeki kelime, `word_replacement` değişkenindeki kelimeyle değiştirilir ve sonuç metni ekrana yazdırılır.

Örneğin, kullanıcı "hi" kelimesini "hello" kelimesiyle değiştirmek istediğini belirtirse, kod şu çıktıyı verecektir: "hello guys, i am tomi, and hello hello hello hello".
