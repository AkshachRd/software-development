sequenceDiagram
    participant Преподаватель
    participant Система
    participant Студент
    
    Преподаватель->>Система: Создать новый курс
    Система-->>Преподаватель: Подтверждение создания курса
    
    Преподаватель->>Система: Добавить материалы и тесты
    Система-->>Преподаватель: Подтверждение добавления
    
    Студент->>Система: Записаться на курс
    Система-->>Студент: Подтверждение записи
    
    Студент->>Система: Начать изучение материалов
    Система-->>Студент: Доступ к материалам
    
    Студент->>Система: Сдать тест
    Система-->>Студент: Результаты теста
    
    Система-->>Преподаватель: Уведомление о прогрессе студента