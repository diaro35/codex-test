# Yazım talimatları

Bu projede Codex, bütün doğal dil yanıtlarını, açıklamalarını ve metin düzenleme işlemlerini hazırlamadan önce `.agents/skills/humanizer/SKILL.md` dosyasını okumalı ve içerdiği 26 yazım kuralından bağlama uygun olanları otomatik uygulamalıdır. Kullanıcının Humanizer becerisini ayrıca çağırması gerekmez.

Kuralları hem Türkçe hem İngilizce metinlere uygula. İngilizce örneklerin Türkçe karşılıklarını anlam ve kullanım açısından değerlendir; İngilizceye özgü dilbilgisi kurallarını Türkçeye mekanik biçimde aktarma. Beceri dosyasındaki bağlam, yazarın sesi ve istisna hükümlerini koru.

Yanıtlar, açıklamalar, belgeler, yorumlar, commit mesajları ve diğer görevlerin içindeki doğal dil metinleri için becerinin embedded mode yaklaşımını kullan: kullanıcı özellikle istemedikçe ara taslakları ve kural analizini gösterme, yalnızca son metni sun.

Yazım düzenlemeleri kodun işlevini, teknik sözdizimini veya doğrulanabilir bilgileri değiştirmemelidir. Kod bloklarını, satır içi kodu, komutları, tanımlayıcıları, dosya yollarını, URL hedeflerini, yapılandırma anahtarlarını ve veri biçimlerini koru. İsimleri, sayıları, tarihleri, alıntıları, kaynakları, iddiaları ve belirsizlik düzeyini koru; bilgi ekleme veya uydurma. Teknik doğruluk ile üslup tercihi çatışırsa teknik doğruluğu koru.

`.agents/skills/humanizer/` altındaki üçüncü taraf beceri dosyalarını kısaltma, çevirme veya üslup amacıyla değiştirme. Özgün içerikleri ve lisans bildirimini koru.

Beceri kaynağı: https://github.com/blader/humanizer
Alınan sürüm: 3.1.0
Kaynak commit: 0ef9fe5bc3572734fd3ae6c448fe00a30cd5dcf0
