### 1 вопрос
Классификатор C4.5 и три его модификации: с оптимизацией гиперпараметра m, гиперпараметра cf и с одновременной оптимизацией обоих гиперпараметров. Эти четыре классификатора сравнивались на 14 наборах данных. На каждом датасете был посчитан AUC каждого классификатора. Данные записаны в файле: *AUCs.txt*

Используя критерий знаковых рангов, проведите попарное сравнение каждого классификатора с каждым. Выберите два классификатора, различие между которыми наиболее статистически значимо.

- [ ] C4.5

- [ ] C4.5+m

- [ ] C4.5+cf

- [ ] C4.5+m+cf

### 2 вопрос
Сколько статистически значимых на уровне 0.05 различий мы обнаружили?

### 3 вопрос
Судя по данным из предыдущего опроса, настройка какого из параметров классификатора даёт более значимое увеличение качества? (Один ответ)

- [ ] m

- [ ] cf

- [ ] Только m и cf одновременно

- [ ] Настраивать m и cf бессмысленно, качество значимо не улучшается

### 4 вопрос
Сравнивая 4 классификатора между собой, мы проверили 6 гипотез. Давайте сделаем поправку на множественную проверку. Начнём с метода Холма. Сколько гипотез можно отвергнуть на уровне значимости 0.05 после поправки этим методом?

### 5 вопрос
Сколько гипотез можно отвергнуть на уровне значимости 0.05 после поправки методом Бенджамини-Хохберга?

### 6 вопрос
Насколько корректно, на ваш взгляд, применение метода Бенджамини-Хохберга в этой задаче? (Один ответ)

- [ ] Некорректно: статистики, соответствующие разным гипотезам, зависимы, так что предположения метода Бенджамини-Хохберга не выполняются

- [ ] Корректно: статистики, соответствующие разным гипотезам, независимы, так что предположения метода Бенджамини-Хохберга выполняются

- [ ] Всегда корректно, это же метод Бенджамини-Хохберга

### 7 вопрос
Мы подозреваем, что в проведённом с C4.5 эксперименте на самом деле классификаторы сильнее отличаются друг от друга, просто нам не удалось это заметить. Что можно сделать, чтобы увеличить вероятность обнаружения различий, если они действительно существуют? 

- [ ] Попробовать настроить больше гиперпараметров

- [ ] Взять больше датасетов

- [ ] Закрыть глаза на эффект множественной проверки гипотез и не делать никакой поправки
