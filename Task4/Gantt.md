```mermaid
gantt
    title План-график открытия депозитов (6 месяцев)
    dateFormat YYYY-MM-DD
    
    section 1. Адаптация текущей системы
    Адаптация текущей системы (АБС) :a1, 2027-01-01, 28d
    
    section 2. Rate Service
    Rate Service :a2, after a1, 21d
    
    section 3. Deposit Service
    Deposit Service :a3, after a1, 28d
    
    section 4. Notification Service
    Notification Service :a4, after a3, 14d
    
    section 5. Инфраструктура
    Инфраструктура :a5, 2027-01-01, 14d
    
    section 6. Сайт
    Сайт :a6, after a3, 21d
    
    section 7. Интернет-банк
    Интернет-банк :a7, after a3, 28d
    
    section 8. Админка бэк-офиса
    Админка бэк-офиса :a8, after a2, 21d
    
    section 9. API Gateway
    API Gateway :a9, after a5, 14d
    
    section 10. Кол-центр
    Кол-центр :a10, after a8, 14d
    
    section 11. Доработка Rate Service
    Доработка Rate Service :a11, after a2, 21d
    
    section 12. Интеграционное тестирование
    Интеграционное тестирование :a12, after a6 a7 a8 a10, 21d
    
    section 13. Нагрузочное тестирование
    Нагрузочное тестирование :a13, after a12, 14d
    
    section 14. Пилотный запуск
    Пилотный запуск :a14, after a13, 14d
    
    section 15. Полный запуск
    Полный запуск :a15, after a14, 14d
```