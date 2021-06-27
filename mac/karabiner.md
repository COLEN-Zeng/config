[Karabiner](https://karabiner-elements.pqrs.org/)

~/.config/karabiner/assets/complex_modifications

```json
// 修改~键为esc
{
    "title": "Change ctrl+` is `",
    "rules": [
        {
            "description": "Change grave accent and tilde to escape",
            "manipulators": [
                {
                    "type": "basic",
                    "from": {
                        "key_code": "grave_accent_and_tilde"
                    },
                    "to": [
                        {
                            "key_code": "escape"
                        }
                    ]
                }
            ]
        },
        {
            "description": "change left_control + escape to accent`",
            "manipulators": [
                {
                    "type": "basic",
                    "from": {
                        "key_code": "grave_accent_and_tilde",
                        "modifiers": {
                            "mandatory": [
                                "left_control"
                            ],
                            "optional": [
                                "any"
                            ]
                        }
                    },
                    "to": [
                        {
                            "key_code": "grave_accent_and_tilde"
                        }
                    ]
                }
            ]
        },
        {
            "description": "Change shift escape to grave accent and tilde",
            "manipulators": [
                {
                    "type": "basic",
                    "from": {
                        "key_code": "grave_accent_and_tilde",
                        "mandatory": [
                            "left_shift"
                        ],
                        "modifiers": {
                            "optional": [
                                "any"
                            ]
                        }
                    },
                    "to": [
                        {
                            "key_code": "grave_accent_and_tilde",
                            "mandatory": [
                                "left_shift"
                            ]
                        }
                    ]
                }
            ]
        }
    ]
}
```

```json
{
    "title": "Change ctrl+` is `",
    "rules": [
        {
            "description": "Change caps_lock to control if pressed with other keys, to escape if pressed alone.",
            "manipulators": [
                {
                    "type": "basic",
                    "from": {
                        "key_code": "caps_lock",
                        "modifiers": {
                            "optional": [
                                "any"
                            ]
                        }
                    },
                    "to": [
                        {
                            "key_code": "left_control"
                        }
                    ],
                    "to_if_alone": [
                        {
                            "key_code": "escape"
                        }
                    ]
                }
            ]
        },
        {
            "description": "Change caps_lock to control if pressed with other keys. (rev 2)",
            "manipulators": [
                {
                    "type": "basic",
                    "from": {
                        "key_code": "caps_lock",
                        "modifiers": {
                            "optional": [
                                "any"
                            ]
                        }
                    },
                    "to": [
                        {
                            "key_code": "left_control"
                        }
                    ],
                    "to_if_alone": [
                        {
                            "key_code": "caps_lock",
                            "hold_down_milliseconds": 500
                        }
                    ]
                }
            ]
        }
    ]
}
```

```json
// right-cmd-and-number-to-fun-number.json
// 更改右侧command+数字为Fn+数字
{
  "title": "Change Right command + number to FNumber",
  "rules": [
    {
      "description": "Change Right command + number to FNumber",
      "manipulators": [
        {
          "type": "basic",
          "from": {
            "key_code": "1",
            "modifiers": {
              "mandatory": ["right_command"],
              "optional": ["any"]
            }
          },
          "to": [
            {
              "key_code": "f1"
            }
          ]
        },
        {
          "type": "basic",
          "from": {
            "key_code": "2",
            "modifiers": {
              "mandatory": ["right_command"],
              "optional": ["any"]
            }
          },
          "to": [
            {
              "key_code": "f2"
            }
          ]
        },
        {
          "type": "basic",
          "from": {
            "key_code": "3",
            "modifiers": {
              "mandatory": ["right_command"],
              "optional": ["any"]
            }
          },
          "to": [
            {
              "key_code": "f3"
            }
          ]
        },
        {
          "type": "basic",
          "from": {
            "key_code": "4",
            "modifiers": {
              "mandatory": ["right_command"],
              "optional": ["any"]
            }
          },
          "to": [
            {
              "key_code": "f4"
            }
          ]
        },
        {
          "type": "basic",
          "from": {
            "key_code": "5",
            "modifiers": {
              "mandatory": ["right_command"],
              "optional": ["any"]
            }
          },
          "to": [
            {
              "key_code": "f5"
            }
          ]
        },
        {
          "type": "basic",
          "from": {
            "key_code": "6",
            "modifiers": {
              "mandatory": ["right_command"],
              "optional": ["any"]
            }
          },
          "to": [
            {
              "key_code": "f6"
            }
          ]
        },
        {
          "type": "basic",
          "from": {
            "key_code": "7",
            "modifiers": {
              "mandatory": ["right_command"],
              "optional": ["any"]
            }
          },
          "to": [
            {
              "key_code": "f7"
            }
          ]
        },
        {
          "type": "basic",
          "from": {
            "key_code": "8",
            "modifiers": {
              "mandatory": ["right_command"],
              "optional": ["any"]
            }
          },
          "to": [
            {
              "key_code": "f8"
            }
          ]
        },
        {
          "type": "basic",
          "from": {
            "key_code": "9",
            "modifiers": {
              "mandatory": ["right_command"],
              "optional": ["any"]
            }
          },
          "to": [
            {
              "key_code": "f9"
            }
          ]
        },
        {
          "type": "basic",
          "from": {
            "key_code": "0",
            "modifiers": {
              "mandatory": ["right_command"],
              "optional": ["any"]
            }
          },
          "to": [
            {
              "key_code": "f10"
            }
          ]
        },
        {
          "type": "basic",
          "from": {
            "key_code": "-",
            "modifiers": {
              "mandatory": ["right_command"],
              "optional": ["any"]
            }
          },
          "to": [
            {
              "key_code": "f11"
            }
          ]
        },
        {
          "type": "basic",
          "from": {
            "key_code": "=",
            "modifiers": {
              "mandatory": ["right_command"],
              "optional": ["any"]
            }
          },
          "to": [
            {
              "key_code": "f12"
            }
          ]
        }
      ]
    }
  ]
}
```
