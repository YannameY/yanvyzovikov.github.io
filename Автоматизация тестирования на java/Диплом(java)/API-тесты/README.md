# Диплом
# Задание: API тестирование

## 🧪 Тестирование REST API

## 📚 Технологии

### 🌐 Основной стек
| Технология       | Версия   | Назначение |
|------------------|----------|------------|
| Java             | 11       | Базовый язык |
| Maven            | 3.9.0    | Сборка проекта |
| REST Assured     | 5.3.0    | Главная библиотека для API тестов |

### 📊 Отчетность и анализ
| Библиотека       | Версия   | Назначение |
|------------------|----------|------------|
| Allure Framework | 2.15.0   | Генерация красивых отчетов |
| JaCoCo           | 0.8.10   | Покрытие кода тестами |

### 🛠 Вспомогательные инструменты
| Библиотека       | Версия   | Назначение |
|------------------|----------|------------|
| JavaFaker        | 1.0.2    | Генерация тестовых данных |
| Gson             | 2.8.9    | Работа с JSON |
| Lombok           | 1.18.30  | Упрощение POJO-классов |

## ⚙️ Настройка и запуск

1. **Требования**:
    - JDK 11+
    - Maven 3.9.0+
    - Доступ к тестируемому API

2. **Запуск тестов**:
```bash
mvn clean test

# Отчет Allure (откроется в браузере)
mvn allure:serve

# Отчет JaCoCo (покрытие кода)
mvn jacoco:report
open target/site/jacoco/index.html