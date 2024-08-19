Este projeto implementa um relógio digital com a funcionalidade de alarme, onde o usuário pode definir um tempo para o alarme tocar.

Exibição da Data: A data atual é exibida no formato `DD/MM/YYYY` no elemento `div_data`.

- Relógio Digital: Exibe a hora atual, atualizando em tempo real no elemento `div_relogio`.

- Configuração do Alarme:
  - O usuário pode definir o tempo em segundos para o alarme tocar usando o campo `tmp_alarme`.
  - Após ativar o alarme, o horário em que ele vai tocar é mostrado em `hora_alarme`.

- Alarme:
  - Quando o tempo definido é alcançado, o alarme toca, e uma animação visual é ativada.
  - O som do alarme é um arquivo de áudio `alarme.mp3` que toca em loop até ser parado.
