# Описание конфликта

## Где возник
Конфликт возник в файле `api-plan.md` при слиянии веток
`feature/api-plan` и `fix/conflict-demo` в `main`.

## Причина
В обеих ветках изменялась одна и та же строка:
- feature/api-plan: "GET /bookings — list all bookings (v1)"
- fix/conflict-demo: "GET /bookings — list all bookings (v2)"

## Как исправлен
Конфликт разрешён вручную: оставлена версия
"GET /bookings — list all bookings (final)", маркеры удалены.
Исправление зафиксировано отдельным коммитом:
`fix: resolve merge conflict in api-plan`.
