# Case-study оптимизации

# Находка
### Данные по всем пользователям хранятся в памяти
- vallgrind massiv
- Сохранение данных userStats отдельно по каждому пользователю
- с 998 мб до 37 мб

### Checklist
- [x] Построить и проанализировать отчёт гемом memory_profiler (данные не совпадали с тем что выводит наш puts, другие профайлеры и vallgrind massif)
- [x] Построить и проанализировать отчёт ruby-prof в режиме Flat;
- [x] Построить и проанализировать отчёт ruby-prof в режиме Graph;
- [x] Построить и проанализировать отчёт ruby-prof в режиме CallStack;
- [x] Построить и проанализировать отчёт ruby-prof в режиме CallTree c визуализацией в QCachegrind;
- [x] Построить и проанализировать текстовый отчёт stackprof;
- [x] Построить и проанализировать отчёт flamegraph с помощью stackprof и визуализировать его в speedscope.app;
- [x] Построить график потребления памяти в valgrind massif visualier и включить скриншот в описание вашего PR;
- [ ] Написать тест, на то что программа укладывается в бюджет по памяти

Отчет vallgrind-massif:
![massif](massif.jpg)
