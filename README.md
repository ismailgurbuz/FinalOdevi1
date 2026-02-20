# TinyML Dynamic Tensor Implementation in C

## Proje Amacı
Bu proje, bellek kısıtlı mikrodenetleyiciler (Arduino, ESP32) üzerinde TinyML modellerini çalıştırmak için tasarlanmış dinamik bir tensör veri yapısını içerir. C dilinde yazılmış olup, `union` kullanarak FP32, FP16 ve INT8 veri tiplerini tek bir yapıda yönetir.

## Özellikler
* **Dinamik Bellek Yönetimi:** C `struct` ve `union` mimarisi.
* **Kuantizasyon Desteği:** FP32'den INT8'e (Symmetric Quantization) dönüşüm fonksiyonları.
* **Düşük Bellek Ayak İzi:** Gömülü sistemler için optimize edilmiş işaretçi (pointer) yönetimi.

## Gereksinimler ve Kurulum
* **IDE:** CLion (macOS / Windows / Linux)
* **Derleyici:** GCC / Clang
* **Build Sistemi:** CMake (min version 3.10)

### Nasıl Çalıştırılır?
1. Repoyu klonlayın: `git clone <repo_url>`
2. CLion ile projeyi açın ve CMake profili oluşturun.
3. `main.c` dosyasını derleyin ve çalıştırın.

## Agentic Kodlama Süreci
Bu projenin mimari tasarımı ve kuantizasyon algoritmalarının matematiksel temelleri [Gemini 3] kullanılarak Agentic yönlendirme yöntemleriyle tasarlanmıştır.
