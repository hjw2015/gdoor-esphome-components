# esphome-components
ESPHome-External-Components for GDoor Adapters

[gdoor](components/gdoor/README.md) Basic GDoor component

Find more details and config examples on component README pages.
```commandline
esphome-components
├── components
│   ├── gdoor
```

Put this in your .yaml configuration to use gdoor:

```yaml
external_components:
  - source:
      type: git
      url: https://github.com/gdoor-org/esphome-components
      ref: main           # branch
    components: [gdoor]
    refresh: 0s           # ensures ESPHome will grab the latest code from github on every install hit.
```
Keep in mind, this is still an early stage esphome-component. Any contribution /issues /comments are welcome. 
