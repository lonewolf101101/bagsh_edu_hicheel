# bagsh_edu_hicheel

this is a repo for sending basgh.edu.mn tasks

## Task 2 — Усны төлөвийн өөрчлөлт (Интерактив самбар)

- Нээх файл: task2.html
- Ашиглах заавар:
  1.  Файлыг хөтөчид (Chrome, Safari, Edge, Firefox) шууд нээнэ.
  2.  Слайдерийг −50°C → 150°C хооронд хөдөлгөж үз.
  3.  Дүрслэл нь 0°C-аас доош мөс, 0–99°C ус, 100°C-аас дээш уурын төлөвт шилжинэ.
- Онцлог:
  - 3D үзүүлэн (Three.js) + SVG fallback (интернетгүй үед ажиллана).
  - JavaScript идэвхгүй үед `noscript` хэсгээр ойлгомжтой тайлбар гарна.
  - Accessibility: `aria-live` гаралт, товч/слайдерт шошго нэмсэн.

### Internet/CDN тэмдэглэл

- 3D хувилбар нь CDN-ээр Three.js-ийг ачаална. Интернетгүй бол SVG fallback автоматаар идэвхжинэ.
