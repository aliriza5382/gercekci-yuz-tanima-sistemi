# Gelişmiş Yüz Tanıma ve Gerçeklik Kontrol Sistemi

Bu sistem, bir yüzün canlı (gerçek kişi) mi yoksa sahte (fotoğraf vs.) mi olduğunu belirleyebilen gelişmiş bir yüz tanıma çözümüdür. Flask tabanlı web arayüzü ile canlı görüntü sunar ve sirenle uyarı verir.

## Özellikler
- Yüz tanıma (face_recognition ile)
- Göz kırpma ve baş hareketi ile gerçeklik kontrolü (MediaPipe)
- 15 saniye boyunca göz kırpılmıyorsa alarm
- Tanınmayan biri algılanırsa alarm
- Siren sesi (pygame ile)
- Canlı video yayını (Flask)

## Gereksinimler
- Python 3.x
- `opencv-python`, `face_recognition`, `pygame`, `flask`, `mediapipe`, `numpy`
