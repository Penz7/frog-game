# 🐸 Ếch Pha Lê — Crystal Frog Adventure

Platformer 2D cuộn ngang chạy trên HTML5 Canvas. Không cần framework, không cần build.

## Chơi ngay

👉 [Play Demo](https://penz7.github.io/frog-game/)

## Cách chạy local

```bash
# Cách 1: Mở trực tiếp
open index.html

# Cách 2: Local server
python3 -m http.server 8000
# Truy cập http://localhost:8000
```

## Điều khiển

| Phím | Hành động |
|------|-----------|
| `←` `→` | Di chuyển trái/phải |
| `Space` / `↑` | Nhảy |
| `R` | Restart màn hiện tại |

## Gameplay

- Thu thập ⭐ ngôi sao và 💎 pha lê
- Đạp lên đầu quái để tiêu diệt
- Tránh gai, lỗ rơi, và kẻ địch bay
- Đứng trên bệ di chuyển
- Tìm checkpoint (cờ xanh) để lưu tiến trình
- Đạt đến ⭐ vàng để qua màn

## Worlds

| World | Tên | Độ khó |
|-------|-----|--------|
| 1-1 | Đồng Cỏ Xanh | Dễ — học điều khiển |
| 1-2 | Hang Động Pha Lê | Trung bình — bệ di chuyển, nhiều quái |
| 1-3 | Đỉnh Cây Cổ Thụ | Khó — boss fight, kết hợp mechanic |

## Kỹ thuật

- Pure HTML5 Canvas + JavaScript
- Không dependencies
- Tile-based collision
- Camera follow + parallax
- Particle effects
- Responsive input (jump buffer, coyote time)

## License

MIT
