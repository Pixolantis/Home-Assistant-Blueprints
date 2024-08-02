# Home-Assistant-Blueprints
Own and third party Blueprints as Backup

## Copyright and Informations
### Zigbee2MQTT - Philips Hue smart button
**Copyright:** [golles](https://github.com/golles/Home-Assistant-Blueprints/blob/main/zigbee2mqtt_hue_smart_button_press_and_hold_actions.yaml)

### Zigbee2MQTT - Philips Hue Tap Dial Switch
**Copyright:** [smarthomegeeks.io](https://smarthomegeeks.io/hue-tap-dial-switch/)

**Instructions**
```
Create the two helpers in the Blueprint
Name: Philips Hue Dial Switch MyRoom - Last Pressed
Icon: mdi:knob
Minimum lenght: 0
Maximum lenght: 1
Display Mode: Text
Regex pattern: [1-4]
entity ID: input_text.philips_hue_dial_switch_myroom_last_pressed
```

```
Name: Philips Hue Dial Switch MyRoom - Counter
Icon: mdi:knob
Minimum lenght: 0
Maximum lenght: 5
Initial value: 0
Step size: 1
Restore the last known value when Home Assistant starts: no
entity ID: input_text.philips_hue_dial_switch_myroom_counter
```

### Check power sensor and do something
**Copyright:** [sbyx](https://gist.githubusercontent.com/sbyx/6d8344d3575c9865657ac51915684696/raw/e5de83ad51d8f7eb6c0bc74dd8a45c010638453b/notify-or-do-something-when-an-appliance-like-a-dishwasher-or-washing-machine-finishes.yaml)
