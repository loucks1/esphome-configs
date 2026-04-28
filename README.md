use like this:

packages:
  esphome_configs:
    url: https://github.com/loucks1/esphome-configs
    ref: main
    files:
      - deck_blinds.yaml
      - living_room_fan.yaml
      - speaker.yaml
    refresh: 1s
