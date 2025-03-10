# Homework 4: Singleton & Adapter Patterns

## **Описание**
Этот проект демонстрирует использование двух структурных паттернов проектирования:
1. **Singleton**: Глобальный конфигурационный менеджер `ConfigurationManager`.
2. **Adapter**: Адаптер `ChatServiceAdapter` для взаимодействия с устаревшей системой чата.

## **Как запустить?**
1. **Скомпилируйте все файлы** (в терминале внутри проекта):  
   ```sh
   javac *.java
   
**Запустите демонстрацию Singleton**(ConfigurationManager):
```sh
java ConfigManagerDemo
```
Запустите демонстрацию Adapter (ChatServiceAdapter):
```sh
javaChatAdapterDemo
```
Пример вывода
Singleton (ConfigurationManager)
rust
Max Players: 100
Default Language: en
Game Difficulty: medium
Configuration Settings:
maxPlayers -> 100
defaultLanguage -> en
gameDifficulty -> medium

Adapter (ChatServiceAdapter)
```yaml
Legacy Chat: Hello world!
```
Дополнительная информация
Singleton гарантирует единственный экземпляр ConfigurationManager, предотвращая дублирование настроек.
Adapter (ChatServiceAdapter) позволяет использовать LegacyChatService с новым интерфейсом ChatService без изменения его кода.
