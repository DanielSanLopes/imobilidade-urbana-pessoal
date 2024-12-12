Imobilidade Urbana
---

Eu e mais alguns colegas fizemos este jogo. Colaborei como o principal programador e uma dos game designers, desenvolvendo e implementando mecânicas, sistema de quests, gerencimento de inputs, animações por script, correções de assets/códigos/cenas/animações, entre outros. 

Foi desenvolvido com preferência para telas mobile, mas funcionam também inputs de teclado e de joystick.

Link do jogo:

https://danielsanlopes.github.io/imobilidade-urbana-pessoal


## Como publicar

Basta compilar o jogo com o target `WebGL` e salvar os arquivos
na pasta `docs/`. Ao realizar o `git push` da pasta `docs/` o
site automaticamente atualizará em menos de 5 minutos.

Para compilar via CLI, use o seguinte comando:

```
Unity -quit -batchmode -buildTarget WebGL -force-free -executeMethod Build.BuildWebGL
```

Note que `Unity` se refere ao binário do seu Unity Editor e assume que ele está
presente na sua variável `$PATH`. Corrija o caminho do binário se necessário.

