### Жадібний алгоритм

- Часова складність: 𝑂(𝑛), де  𝑛 n - кількість номіналів монет.
- Просторова складність:  𝑂(1) 

- **Переваги**:
  - Дуже швидкий для більшості практичних цілей.
  - Простий у реалізації.
- **Недоліки**:
  - Може не завжди знаходити оптимальне рішення для всіх наборів монет.

### Алгоритм динамічного програмування

- Часова складність: 𝑂(n×amount), де n - кількість номіналів монет, а amount - сума, для якої треба знайти мінімальну кількість монет.
- Просторова складність:  𝑂(amount).

- **Переваги**:
  - Завжди знаходить оптимальне рішення.
  - Підходить для будь-якого набору монет.
- **Недоліки**:
  - Повільніший у порівнянні з жадібним алгоритмом, особливо для великих сум.
  - Складніший у реалізації.