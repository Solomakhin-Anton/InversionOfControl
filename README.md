# InversionOfControl

*  `Music music = context.getBean("musicBean", Music.class);` - создаем бин.

* `MusicPlayer musicPlayer = new MusicPlayer(music);` - создаем экземпляр класса и передает music.

* `context.close();` - не забываем всегда выключать контекст!
