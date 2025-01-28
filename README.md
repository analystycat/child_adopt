- create envoiment
```conda create --prefix \env pandas numpy matplotlib scikit-learn jupyter```

- for activation env
```conda activate [path]```

- to deactivate env
```conda deactivate```


# Як це працює

- ##### Щоб оновити дані з сайту слід виконати файл "ChildrenBase". Результатом роботи є два json файла:
    -  diferences.json - з id тих хто змінився (або дадався, або видалився) 
    - all_children.json - оновлений список дітей

- ##### Щоб софрмувати csv файл, зручний для користування - слід запустити файл createReadeableFile

- ##### для роботи з базою дітей файл - childDF
    - якщо у тебе є якісь напрацювання, або відмітки по дітях, слід загрузити csv з відмітками. csv повинен містити колонки: 
        - статус: 1 - не цікаво, 2 - цікаво, 3 - інше;
        - id, 
        - імя
        - коментар
