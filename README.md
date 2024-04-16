# QuietDrift

## Setup

Add the following line to config.yaml:

```
quietdrift:
```

## Usage:

Set position this way:

```
service: cover.set_switchbot_position
data:
  speed: 1
  position: 90
  entity_id: cover.curtain_3_XXXX
```
