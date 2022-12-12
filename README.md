#  Git
### Клонирование репозитория

    cd Developer/
    git clone git@github.com:Fenestr0n/Examples.git

### Создание шаблона "Консольное приложение"

    cd Ex000/
    dotnet new console
    dotnet run

### Фиксация изменений
    cd ..
    git status
    git add Ex000/
    git commit -m "Hello, World!"

### Отправка изменений в удаленный репозиторий
    git remote add origin git@github.com:Fenestr0n/Examples.git
    git push -u origin master

# .Net

### Создать новый проект
    dotnet new console

### Запустить проект
    dotnet run

### Вывод в одну строку
    Console.Write();

### В конце перейти на новую строку
    Console.WriteLine();

### Считать строку из терминала
    Console.ReadLine();

### Сгенерировать случайное число в диапазоне [min, max)
    new Random().Next(min, max);
