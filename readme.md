# Surf-Llama

## Proje Tanımı
Surf-Llama, Windsurf IDE'sinde çalışan AI kod editörleri ile kullanıcılar arasında daha net, yapısal ve verimli bir iletişim katmanı oluşturmayı hedefleyen bir projedir.

## Temel Amaç
Yazılım geliştirme süreçlerinde iletişimi kolaylaştıran, standart bir ara katman oluşturmak.

## Özellikler
- Özgün bir syntax sistemi
- İletişim süreçlerini standartlaştıran yaklaşım
- Kod geliştirme görevlerini daha anlaşılır kılma

## Dosya Uzantısı: .srfllm

`.srfllm` uzantısı, Surf-Llama projesinin özgün syntax'ını temsil eden özel bir dosya uzantısıdır. 

- `srf`: Surf kelimesinin kısaltması
- `llm`: Large Language Model (Büyük Dil Modeli) ifadesinin kısaltması

Bu uzantı, projenin temel amacını yansıtır: Windsurf IDE'sinde çalışan AI kod editörleri ile kullanıcılar arasında daha net bir iletişim katmanı oluşturmak.

## Syntax Yapısı
```srfllm
/klasör-adı {
    @dosya-adı.py {
        +: "pozitif talimat"     #: "yorum satırı"
        =: "nötr talimat"
        -: "negatif talimat"
    }
}
```

### Syntax Detayları
- `+:` Pozitif talimatlar
- `-:` Negatif talimatlar
- `=:` Nötr talimatlar
- `#:` Yorum satırları

### Parent-Child İlişkisi
Syntax, talimatların iç içe ve hiyerarşik bir şekilde tanımlanmasına olanak sağlar. Her talimat, alt talimatları içerebilir.

#### Örnek Syntax
```srfllm
/proje-adı {
    @dosya-adı {
        +: "üst seviye talimat" {
            +: "alt seviye talimat 1"
            +: "alt seviye talimat 2"
                #: "açıklama satırı"
        }
    }
}
```

#### Gerçek Dünya Örneği
```srfllm
/halilsak.com {
    @index.html {
        +: "doctype etiketini ekle"
        +: "html etiketini ekle" {
            +: "head etiketini ekle"
                +: "meta etiketlerini tanımla"
                +: "title etiketini ekle"
            +: "body etiketini ekle"
                +: "ana içeriği oluştur"
                +: "footer bölümünü ekle"
        }
    }
}
```

Bu yapı, kod oluşturma sürecini daha yapısal ve net bir şekilde tanımlamaya olanak sağlar.

## Kullanım
Proje henüz geliştirme aşamasındadır.

## Gelecek Vizyonu
Windsurf ekosisteminde:
- İletişim kalitesini artırmak
- Kod geliştirme süreçlerini optimize etmek
- AI ile kullanıcı arasında net bir iletişim katmanı oluşturmak

## Katkıda Bulunma
Proje geliştirme sürecindedir. Katkılar memnuniyetle karşılanacaktır.

## İletişim
Proje sahibi ile doğrudan iletişime geçebilirsiniz.