## GPT-Autosrun
### Automatic writing of practical works

### Это ультра-ранняя версия тестового скрипта только для курса `Новые информационные технологии в научной и профессиональной деятельности (ЭОР)`

1. Установите Python https://www.python.org/downloads/release/python-390/
2. Склонируйте или скачайте репозисторий
3. Откройте командную строку внутри папки GPT-Autosrun и убедитесь в наличии python `python --version`
4. Установите зависимости `pip install -r requirements.txt`
5. Откройте файл `main.py` в любом редакторе (рекомендуется Notepad++)
6. Укажите вашу группу и имя в `GROUP_REPLACE_WITH`, `NAME_REPLACE_WITH` и `OUTPUT_FILE_FORMAT`
7. Убедитесь что у вас есть доступ к chatGPT, откройте ссылку https://platform.openai.com/account/api-keys, создайте новый API ключ и скопируйте его в `OPENAI_API_KEY`
8. В `SKIP_TASKS` укажите сделанные вами работы (которые нужно пропустить)
9. Сохраните файл
10. Запустите скрипт командой `python main.py`
