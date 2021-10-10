# RSShool2021-Android-task6-Music-App

## Цель - реализовать простой музыкальный плеер на Android

Требования:
- Данные о треках считываются с JSON-файла. Пример файла находится [тут](data/playlist.json). Можете использовать данный или создать свой.
- Плеер должен проигрывать медиа-файлы. Минимум поддерживаемых контроллов: Play, Pause, PlayNext & PlayPrevious. Плеер показывает данные о текущем треке - название, автор и картинка.
- Если трек играет, приложение показывает нотификацию (MediaStyle) с данными о треке (название, автор, картинка) и контроллами (Play/Pause, PlayNext & PlayPrevious)
- Реализация поддержки rotation (состояние не сбрасывается). Реализация поддержки разных версий layout для portrait и landscape режимов
- Вы должны выбрань одну из архитектур - MVP или MVVM - и реализовать её. View не должно хранить состояния, а получать их из Presenter (MVP) или ViewModel (MVVM). 

Дополнительные требования:
- Поддержка AudioFocus
- реализация DI (e.g. Dagger)

См. best partices тут: https://developer.android.com/guide/topics/media-apps/audio-app/building-an-audio-app
для нотификаций: https://developer.android.com/reference/android/app/Notification.MediaStyle

Пример: см. демо-видео https://youtu.be/NYMURgYAibg

Пример экранов:
<img alt="quiz app" src="/img/port_1.png" width="250" height="500" />

<img alt="quiz app" src="/img/land_1.png" width="500" height="250" />
