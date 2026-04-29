# Демиург — Memory

Персональная память между сессиями. Append-only. Агент пишет сам после каждой сборки/аудита.

## Decisions (что решил и почему)

### 2026-04-22 16:46 — Update office
- Было: commit `8419d93` (snapshot перед задачей)
- Стало: commit `1665bf6` (origin/main)
- Что изменилось: 1 новый коммит — "Install Designer as core agent + onboarding v2 (visual mocks)". В офисе появился новый помощник Designer (`office/agents/designer/`), обновлён AGENTS.md.
- Восстановлено из backup: `office/strategy/strategy.md` (живая 9248b), `strategist/memory.md` (6951b), `inbox/prework.md` (13897b), `knowledge/customer-insights.md` (14168b), вся папка `projects/neuroshtab/`, overrides/memory/failures всех 3 агентов.
- Backup: `/tmp/office-backup-20260422-164630/` (71 файл, 512K)
- Status: OK — все 12 sha256-чеков пройдены, клиентские данные побайтово сохранены.
## Decisions (что решил)

<!-- Формат:
### YYYY-MM-DD: Заголовок решения

- **What:** что было сделано
- **Why:** почему именно так
- **Result:** что получилось / какой score
-->

## Patterns (закономерности)

<!-- Что узнал про предпочтения пользователя в архитектуре, повторяющиеся выборы, удачные решения. -->

## Failures (что не сработало)

<!-- Короткие записи: что предложил → почему не подошло → правило на будущее. Полные кейсы — в failures.md. -->

## Context (что помнить)

<!-- Активные сборки, открытые вопросы, конвенции данного офиса. -->
