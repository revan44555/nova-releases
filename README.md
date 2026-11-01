# nova-releases

Bu repo yalnizca uygulamanin APK guncellemelerini icerir.
Kaynak kod burada YOKTUR ve elle bir sey eklemeniz gerekmez.

## Ne oluyor?

Ana (private) repo'daki CI is akisi her push'ta:

1. APK'yi derler ve `nova.apk` olarak yeniden adlandirir,
2. Bu repo'da `v1.0.<run-no>` etiketiyle bir Release olusturur,
3. APK'yi bu Release'e yukler.

Uygulamalar bu repo'daki en son surumu gorur ve icinden guncellenir.

## Elle yapilmasi gereken tek sey

Hicbir sey. Bu README disinda dosya eklemeyin.
