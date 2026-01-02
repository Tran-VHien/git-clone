#  Dự án: Điều khiển 2 LED bằng OneButton trên ESP32

## 📖 Giới thiệu
Dự án này minh họa cách sử dụng thư viện **OneButton** để điều khiển **2 LED** chỉ bằng **một nút nhấn duy nhất**.

### Các chức năng chính
- **Single Click** → Bật/tắt LED hiện tại.
- **Double Click** → Chuyển quyền điều khiển qua lại giữa LED1 và LED2.
- **Long Press (>1s)** → Làm LED đang điều khiển nhấp nháy với chu kỳ 200ms.

---

##  Phần cứng
- ESP32 DevKit
- **LED1**: GPIO4 (qua điện trở 220Ω)
- **LED2**: GPIO5 (qua điện trở 220Ω)
- **Button**: GPIO18, cấu hình INPUT_PULLUP (1 chân → GND, 1 chân → GPIO18)

---

##  Phần mềm
- **PlatformIO** (Arduino framework)
- Thư viện: **OneButton**

---

##  Cách sử dụng
Clone dự án về máy và di chuyển vào thư mục:

```bash
git clone https://github.com/<tài-khoản-github>/Button_LED.git
cd Button_LED
