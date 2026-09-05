# 🎨 AIS-Server 공식 커스텀 GUI 리소스팩 (Official Custom GUI ResourcePack)

에타 친목 야생 & EvenMoreFish 해양 낚시 특화 마인크래프트 서버 **AIS-Server**의 공식 커스텀 GUI 리소스팩입니다.

---

## 📌 주요 특징
- **마인크래프트 감성 픽셀아트**: 바닐라의 투박한 회색 상자 GUI를 대체하는 청량한 오크 원목 & 산호초 테마 디자인
- **업계 표준 폰트 시프트 기술**: 마인크래프트 네이티브 `space` 프로바이더 음수 공백(`\uF801` ~ `\uF80C`) 및 비트맵(`\uE001`) 완벽 매핑
- **버전 호환성**: 1.20 ~ 1.21.4+ 전 버전 무경고 호환 (`supported_formats: [15, 60]`)
- **초경량 최적화**: 100KB 미만의 초경량 ZIP 패키지로 인게임 로딩 지연 0초

---

## 🛠️ 기술 규격
- **컨테이너 규격**: Generic 9x3 (27 슬롯, 176 × 166 픽셀)
- **폰트 설정 (`default.json`)**:
  - `ascent: 13`
  - `height: 166`
  - `chars: ["\uE001"]`
  - `file: minecraft:gui/custom/main_menu_bg.png`
- **DeluxeMenus 타이틀 문법**:
  ```yaml
  menu_title: "&f\uF808\uE001\uF80C\uF80A\uF808"
  open_command: menu
  size: 27
  ```

---

## 📦 패키지 구조
```text
AIS_Server_ResourcePack.zip
├── pack.mcmeta
├── pack.png
└── assets/
    └── minecraft/
        ├── font/
        │   └── default.json
        └── textures/
            └── gui/
                └── custom/
                    └── main_menu_bg.png
```
