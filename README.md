# Hesap Makinesi Uygulaması

Bu PyQt6 ile geliştirilmiş basit bir hesap makinesi uygulamasıdır.

## Kullanılan PyQt6 Özellikleri

Bu projede PyQt6 kullanılarak aşağıdaki önemli özellikler kullanılmıştır:

### QMainWindow

Uygulamanın ana penceresini temsil eder. Pencerenin başlığı, boyutu ve düzeni bu sınıf aracılığıyla ayarlanmıştır.

### QLineEdit

Sonuçları görüntülemek için kullanılan okunabilir bir QLineEdit öğesidir. Bu öğe aynı zamanda sonuç alanına yazılan metni temsil eder.

### QPushButton

Uygulamadaki tüm butonlar bu sınıf kullanılarak oluşturulmuştur. Butonlara tıklama olayları bu sınıf ile yönetilir.

### QVBoxLayout ve QHBoxLayout

Dikey ve yatay düzenleri oluşturmak için kullanılmıştır. Bu düzenler, butonlar, temizleme butonu ve sonuç alanını düzenlemek için kullanılmıştır.

### QFont

Metin fontunu belirlemek için kullanılmıştır. Sonuç alanındaki metni büyük ve kalın yapmak için QFont sınıfı kullanılmıştır.

### try-except Bloğu

Hesaplama sırasında olası hataları ele almak için try-except bloğu kullanılmıştır. Eğer bir hata oluşursa, kullanıcıya "Hata!" mesajı gösterilir.

## Kurulum

1. Proje dizinine gidin: `cd hesap-makinesi-uygulamasi`
2. Sanal bir ortam oluşturun: `python -m venv venv`
3. Sanal ortamı etkinleştirin:
   - Windows: `venv\Scripts\activate`
   - Linux/Mac: `source venv/bin/activate`
4. Gerekli paketleri yükleyin: `pip install -r requirements.txt`

## Kullanım

Uygulamayı çalıştırmak için terminalde şu komutu kullanın:

```bash
python main.py
