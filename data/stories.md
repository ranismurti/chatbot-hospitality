## stories 1 
* greet
  - utter_greet
* inform_extra
  - utter_ask_room
* inform_extra{"room":"123"}
  - slot{"room":"123"}
  - action_extra
* thanks
  - utter_thanks
  - export
## Generated Story 6615660281202338813
* greet
    - utter_greet
* inform{"extra": "kasur"}
    - slot{"extra": "kasur"}
    - utter_ask_room
* inform_room{"room": "123"}
    - slot{"room": "123"}
    - action_extra

## Generated Story 4421105365298901563
* greet
    - utter_greet
* inform_extra{"extra": "kasur"}
    - slot{"extra": "kasur"}
    - utter_ask_room
* inform_room{"room": "712"}
    - slot{"room": "712"}
    - action_extra
    - slot{"room": "712"}
* greet
    - utter_greet
* inform_extra{"extra": "kasur"}
    - slot{"extra": "kasur"}
    - action_extra
    - slot{"room": "712"}
* thanks
    - action_default_fallback
    - rewind

## Generated Story 2223085079320825746
* greet
    - utter_greet
* inform_extra{"extra": "sikat gigi"}
    - slot{"extra": "sikat gigi"}
    - utter_ask_room
* inform_room{"room": "467"}
    - slot{"room": "467"}
    - action_extra
    - slot{"room": "467"}
* thanks
    - utter_thanks

