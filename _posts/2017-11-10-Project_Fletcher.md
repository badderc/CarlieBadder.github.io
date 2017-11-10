---
layout: post
title: Wine Recommender
---

Does this app work in a blog?

<script src="https://unpkg.com/jupyter-js-widgets@~2.1.4/dist/embed.js"></script>
<script type="application/vnd.jupyter.widget-state+json">
{
    "version_major": 1,
    "version_minor": 0,
    "state": {
        "fb3d8f13645d4372903fd118e9822210": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "401de205d33c48fdb351534a6a848ba7": {
            "model_name": "ToggleButtonsModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "Red",
                    "White",
                    "Surprise Me"
                ],
                "_view_module_version": "~2.1.4",
                "button_style": "",
                "description": "Select Wine Type:",
                "icons": [],
                "layout": "IPY_MODEL_fb3d8f13645d4372903fd118e9822210",
                "tooltips": [
                    "Red",
                    "White",
                    "Surprise Me"
                ],
                "value": "Red"
            }
        },
        "9a6f1b4899ae4bcba761baaef873e66f": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "3e128f6f75364e50b95f8f54ef1eb275": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "apple",
                    "apricot",
                    "banana",
                    "berry",
                    "blackberry",
                    "chard",
                    "cherry",
                    "flower",
                    "grapefruit",
                    "kiwi",
                    "lemon",
                    "lime",
                    "mango",
                    "melon",
                    "nectarine",
                    "orange",
                    "peach",
                    "pear",
                    "pineapple",
                    "plum",
                    "raspberry",
                    "tangerine"
                ],
                "_view_module_version": "~2.1.4",
                "description": "fruit flavors",
                "layout": "IPY_MODEL_9a6f1b4899ae4bcba761baaef873e66f",
                "value": [
                    "apricot"
                ]
            }
        },
        "f13f90bb4c184f6492b5caf753325cf7": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "64cb138d5fcb4c819676cbcd4107102e": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "almond",
                    "buttered",
                    "caramel",
                    "chocolate",
                    "citrus",
                    "coffee",
                    "cola",
                    "floral",
                    "fruity",
                    "grass",
                    "herbal",
                    "honeysuckle",
                    "leather",
                    "licorice",
                    "mineral",
                    "oak",
                    "pepper",
                    "rose",
                    "spice",
                    "sugar",
                    "toast",
                    "tobacco",
                    "vanilla"
                ],
                "_view_module_version": "~2.1.4",
                "description": "other flavors",
                "layout": "IPY_MODEL_f13f90bb4c184f6492b5caf753325cf7",
                "value": [
                    "oak"
                ]
            }
        },
        "764c4f75c5574064846d4098454a9ccc": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "display": "flex"
            }
        },
        "eef4d5d5582c4c13a21182c197a7b532": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "balanced",
                    "bright",
                    "brisk",
                    "citrusy",
                    "clean",
                    "creamy",
                    "crisp",
                    "dark",
                    "delicate",
                    "dense",
                    "dry",
                    "firm",
                    "fragrant",
                    "fresh",
                    "fullbodied",
                    "green",
                    "juicy",
                    "light",
                    "lively",
                    "refreshing",
                    "rich",
                    "ripe",
                    "simple",
                    "smoky",
                    "smooth",
                    "spicy",
                    "steely",
                    "structure",
                    "sweet",
                    "tangy",
                    "tannic",
                    "tart",
                    "tropical",
                    "zest"
                ],
                "_view_module_version": "~2.1.4",
                "description": "descriptive terms",
                "layout": "IPY_MODEL_764c4f75c5574064846d4098454a9ccc",
                "value": [
                    "sweet"
                ]
            }
        },
        "068984fcd2864207aae49335df8431e8": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "c7ef0856769142228c756aff23ead970": {
            "model_name": "AccordionModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_titles": {
                    "0": "Choose a type of wine",
                    "1": "Choose one or more fruit flavors",
                    "2": "Choose one or more other flavors",
                    "3": "Choose one or more descriptive terms"
                },
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_401de205d33c48fdb351534a6a848ba7",
                    "IPY_MODEL_3e128f6f75364e50b95f8f54ef1eb275",
                    "IPY_MODEL_64cb138d5fcb4c819676cbcd4107102e",
                    "IPY_MODEL_eef4d5d5582c4c13a21182c197a7b532"
                ],
                "layout": "IPY_MODEL_068984fcd2864207aae49335df8431e8"
            }
        },
        "41e206f711894917ae7a26e4a8bd2edc": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "02952ceed8cf4702abf2b7046ff7d5e9": {
            "model_name": "VBoxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [
                    "widget-interact"
                ],
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_624478ba705c40deac1a9e8b5bcb2049",
                    "IPY_MODEL_7a816994f4e34561858026f99d14cb1c",
                    "IPY_MODEL_da9105752c64430e8eb319acfb7b95e8"
                ],
                "layout": "IPY_MODEL_41e206f711894917ae7a26e4a8bd2edc"
            }
        },
        "54be54652ba346ffbbb0a726ff1924fd": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "624478ba705c40deac1a9e8b5bcb2049": {
            "model_name": "CheckboxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Submit",
                "disabled": false,
                "layout": "IPY_MODEL_54be54652ba346ffbbb0a726ff1924fd",
                "value": true
            }
        },
        "b9c5366c98bb429b92cd8755175068e9": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "d5e1e11fcde84df69345208aaed0a856": {
            "model_name": "ButtonStyleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "7a816994f4e34561858026f99d14cb1c": {
            "model_name": "ButtonModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Run Interact",
                "layout": "IPY_MODEL_b9c5366c98bb429b92cd8755175068e9",
                "style": "IPY_MODEL_d5e1e11fcde84df69345208aaed0a856"
            }
        },
        "1c583061d0a84853b1619b2f07c7e80f": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "da9105752c64430e8eb319acfb7b95e8": {
            "model_name": "OutputModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [],
                "_model_module": "jupyter-js-widgets",
                "_model_module_version": "~2.1.4",
                "_view_module": "jupyter-js-widgets",
                "_view_module_version": "~2.1.4",
                "layout": "IPY_MODEL_1c583061d0a84853b1619b2f07c7e80f",
                "msg_throttle": 1
            }
        },
        "497d76e3d72c4359b4fba768769a5271": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "ffd920ed52f545308eb82072d1186088": {
            "model_name": "ToggleButtonsModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "Red",
                    "White",
                    "Surprise Me"
                ],
                "_view_module_version": "~2.1.4",
                "button_style": "",
                "description": "Select Wine Type:",
                "icons": [],
                "layout": "IPY_MODEL_497d76e3d72c4359b4fba768769a5271",
                "tooltips": [
                    "Red",
                    "White",
                    "Surprise Me"
                ],
                "value": "Red"
            }
        },
        "e3aee047114f4af6b34d46de59182a71": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "bdb894ee230542c1bbe811fa338fcf98": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "apple",
                    "apricot",
                    "banana",
                    "berry",
                    "blackberry",
                    "chard",
                    "cherry",
                    "flower",
                    "grapefruit",
                    "kiwi",
                    "lemon",
                    "lime",
                    "mango",
                    "melon",
                    "nectarine",
                    "orange",
                    "peach",
                    "pear",
                    "pineapple",
                    "plum",
                    "raspberry",
                    "tangerine"
                ],
                "_view_module_version": "~2.1.4",
                "description": "fruit flavors",
                "layout": "IPY_MODEL_e3aee047114f4af6b34d46de59182a71",
                "value": [
                    "apricot"
                ]
            }
        },
        "44604386f0aa44f598818342301d94fa": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "188f574f8f2945f49f56608b2c19a381": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "almond",
                    "buttered",
                    "caramel",
                    "chocolate",
                    "citrus",
                    "coffee",
                    "cola",
                    "floral",
                    "fruity",
                    "grass",
                    "herbal",
                    "honeysuckle",
                    "leather",
                    "licorice",
                    "mineral",
                    "oak",
                    "pepper",
                    "rose",
                    "spice",
                    "sugar",
                    "toast",
                    "tobacco",
                    "vanilla"
                ],
                "_view_module_version": "~2.1.4",
                "description": "other flavors",
                "layout": "IPY_MODEL_44604386f0aa44f598818342301d94fa",
                "value": [
                    "oak"
                ]
            }
        },
        "33c6f897ac824f8292fc45fda9c363c2": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "display": "flex"
            }
        },
        "cb3c6702061a4f9fa8db398f6de077f8": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "balanced",
                    "bright",
                    "brisk",
                    "citrusy",
                    "clean",
                    "creamy",
                    "crisp",
                    "dark",
                    "delicate",
                    "dense",
                    "dry",
                    "firm",
                    "fragrant",
                    "fresh",
                    "fullbodied",
                    "green",
                    "juicy",
                    "light",
                    "lively",
                    "refreshing",
                    "rich",
                    "ripe",
                    "simple",
                    "smoky",
                    "smooth",
                    "spicy",
                    "steely",
                    "structure",
                    "sweet",
                    "tangy",
                    "tannic",
                    "tart",
                    "tropical",
                    "zest"
                ],
                "_view_module_version": "~2.1.4",
                "description": "descriptive terms",
                "layout": "IPY_MODEL_33c6f897ac824f8292fc45fda9c363c2",
                "value": [
                    "sweet"
                ]
            }
        },
        "6c1b339aa5434266ac1d598b26b5d795": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "b12c8689db634ccb91bb098692e6b510": {
            "model_name": "AccordionModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_titles": {
                    "0": "Choose a type of wine",
                    "1": "Choose one or more fruit flavors",
                    "2": "Choose one or more other flavors",
                    "3": "Choose one or more descriptive terms"
                },
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_ffd920ed52f545308eb82072d1186088",
                    "IPY_MODEL_bdb894ee230542c1bbe811fa338fcf98",
                    "IPY_MODEL_188f574f8f2945f49f56608b2c19a381",
                    "IPY_MODEL_cb3c6702061a4f9fa8db398f6de077f8"
                ],
                "layout": "IPY_MODEL_6c1b339aa5434266ac1d598b26b5d795"
            }
        },
        "246c23a677594fb9b6f63deaffaec7ca": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "db8fbba16cea419d858bac9c2668e47b": {
            "model_name": "VBoxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [
                    "widget-interact"
                ],
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_a121de106cd342ee90d55362885acd95",
                    "IPY_MODEL_d5b2569843254e71a0ea9796e59b83d8",
                    "IPY_MODEL_52a4f7e666634772bd510b354dd9fa5a"
                ],
                "layout": "IPY_MODEL_246c23a677594fb9b6f63deaffaec7ca"
            }
        },
        "3c6df27c75bb42b28e3e15f048df82e4": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "a121de106cd342ee90d55362885acd95": {
            "model_name": "CheckboxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Submit",
                "disabled": false,
                "layout": "IPY_MODEL_3c6df27c75bb42b28e3e15f048df82e4",
                "value": true
            }
        },
        "3938ceaeffb24101b9475c4b1721362a": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "92c556452b7b4311a1479b0956ea6220": {
            "model_name": "ButtonStyleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "d5b2569843254e71a0ea9796e59b83d8": {
            "model_name": "ButtonModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Run Interact",
                "layout": "IPY_MODEL_3938ceaeffb24101b9475c4b1721362a",
                "style": "IPY_MODEL_92c556452b7b4311a1479b0956ea6220"
            }
        },
        "bff0543805684d17bb610ba6f3a49f1a": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "52a4f7e666634772bd510b354dd9fa5a": {
            "model_name": "OutputModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [],
                "_model_module": "jupyter-js-widgets",
                "_model_module_version": "~2.1.4",
                "_view_module": "jupyter-js-widgets",
                "_view_module_version": "~2.1.4",
                "layout": "IPY_MODEL_bff0543805684d17bb610ba6f3a49f1a",
                "msg_throttle": 1
            }
        },
        "becddb45fd364111b38a39f354c275f5": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "8333622c668f4108b4eee07c3881f91d": {
            "model_name": "ToggleButtonsModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "Red",
                    "White",
                    "Surprise Me"
                ],
                "_view_module_version": "~2.1.4",
                "button_style": "",
                "description": "Select Wine Type:",
                "icons": [],
                "layout": "IPY_MODEL_becddb45fd364111b38a39f354c275f5",
                "tooltips": [
                    "Red",
                    "White",
                    "Surprise Me"
                ],
                "value": "Red"
            }
        },
        "1a1094cfd8964127805e1cff56398b8f": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "a06c19a25350416b9044b36cb0201ab1": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "apple",
                    "apricot",
                    "banana",
                    "berry",
                    "blackberry",
                    "chard",
                    "cherry",
                    "flower",
                    "grapefruit",
                    "kiwi",
                    "lemon",
                    "lime",
                    "mango",
                    "melon",
                    "nectarine",
                    "orange",
                    "peach",
                    "pear",
                    "pineapple",
                    "plum",
                    "raspberry",
                    "tangerine"
                ],
                "_view_module_version": "~2.1.4",
                "description": "fruit flavors",
                "layout": "IPY_MODEL_1a1094cfd8964127805e1cff56398b8f",
                "value": [
                    "apricot"
                ]
            }
        },
        "f62b541024f94ebbac408699a8f6163e": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "3eaa7f11a60445c2a62b29427061e0a1": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "almond",
                    "buttered",
                    "caramel",
                    "chocolate",
                    "citrus",
                    "coffee",
                    "cola",
                    "floral",
                    "fruity",
                    "grass",
                    "herbal",
                    "honeysuckle",
                    "leather",
                    "licorice",
                    "mineral",
                    "oak",
                    "pepper",
                    "rose",
                    "spice",
                    "sugar",
                    "toast",
                    "tobacco",
                    "vanilla"
                ],
                "_view_module_version": "~2.1.4",
                "description": "other flavors",
                "layout": "IPY_MODEL_f62b541024f94ebbac408699a8f6163e",
                "value": [
                    "oak"
                ]
            }
        },
        "6b70de4f5f8d47eb98df295f6c80f843": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "display": "flex"
            }
        },
        "f5b1e2595f6243c5bb3f307a75c6aa60": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "balanced",
                    "bright",
                    "brisk",
                    "citrusy",
                    "clean",
                    "creamy",
                    "crisp",
                    "dark",
                    "delicate",
                    "dense",
                    "dry",
                    "firm",
                    "fragrant",
                    "fresh",
                    "fullbodied",
                    "green",
                    "juicy",
                    "light",
                    "lively",
                    "refreshing",
                    "rich",
                    "ripe",
                    "simple",
                    "smoky",
                    "smooth",
                    "spicy",
                    "steely",
                    "structure",
                    "sweet",
                    "tangy",
                    "tannic",
                    "tart",
                    "tropical",
                    "zest"
                ],
                "_view_module_version": "~2.1.4",
                "description": "descriptive terms",
                "layout": "IPY_MODEL_6b70de4f5f8d47eb98df295f6c80f843",
                "value": [
                    "sweet"
                ]
            }
        },
        "5000724cce4f4179b5868f89fc2a15da": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "449841df2346418585a8853ba70b02e8": {
            "model_name": "AccordionModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_titles": {
                    "0": "Choose a type of wine",
                    "1": "Choose one or more fruit flavors",
                    "2": "Choose one or more other flavors",
                    "3": "Choose one or more descriptive terms"
                },
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_8333622c668f4108b4eee07c3881f91d",
                    "IPY_MODEL_a06c19a25350416b9044b36cb0201ab1",
                    "IPY_MODEL_3eaa7f11a60445c2a62b29427061e0a1",
                    "IPY_MODEL_f5b1e2595f6243c5bb3f307a75c6aa60"
                ],
                "layout": "IPY_MODEL_5000724cce4f4179b5868f89fc2a15da"
            }
        },
        "b926ac04d9684f82a44dddad411434c9": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "36de1634c35c401fbabad27e8f6c47c5": {
            "model_name": "VBoxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [
                    "widget-interact"
                ],
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_77fcc3d08b9c4289a1fe992ef74af8f4",
                    "IPY_MODEL_e848d9307b85450781a9c99456e9a2c0",
                    "IPY_MODEL_1747c680b6d1454181ff82a097e9d62a"
                ],
                "layout": "IPY_MODEL_b926ac04d9684f82a44dddad411434c9"
            }
        },
        "75b6bb9d8d4a4596a1d36000f1911b89": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "77fcc3d08b9c4289a1fe992ef74af8f4": {
            "model_name": "CheckboxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Submit",
                "disabled": false,
                "layout": "IPY_MODEL_75b6bb9d8d4a4596a1d36000f1911b89",
                "value": true
            }
        },
        "20f015d0c6104308aabf5b2af14e5f42": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "0705f775a65b411e82356659c154f971": {
            "model_name": "ButtonStyleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "e848d9307b85450781a9c99456e9a2c0": {
            "model_name": "ButtonModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Run Interact",
                "layout": "IPY_MODEL_20f015d0c6104308aabf5b2af14e5f42",
                "style": "IPY_MODEL_0705f775a65b411e82356659c154f971"
            }
        },
        "cfeb533a7f534bcdb58d8b739d0c9899": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "1747c680b6d1454181ff82a097e9d62a": {
            "model_name": "OutputModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [],
                "_model_module": "jupyter-js-widgets",
                "_model_module_version": "~2.1.4",
                "_view_module": "jupyter-js-widgets",
                "_view_module_version": "~2.1.4",
                "layout": "IPY_MODEL_cfeb533a7f534bcdb58d8b739d0c9899",
                "msg_throttle": 1
            }
        },
        "c91fd501e26842a3bc119a4787052419": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "d189acefb724487facce6c6451ffe6f1": {
            "model_name": "ToggleButtonsModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "Red",
                    "White",
                    "Surprise Me"
                ],
                "_view_module_version": "~2.1.4",
                "button_style": "",
                "description": "Select Wine Type:",
                "icons": [],
                "layout": "IPY_MODEL_c91fd501e26842a3bc119a4787052419",
                "tooltips": [
                    "Red",
                    "White",
                    "Surprise Me"
                ],
                "value": "Red"
            }
        },
        "0c7d52f6580f430aab75599e2ae78b33": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "db8818b1435d4a82bcd14c3942487f09": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "apple",
                    "apricot",
                    "banana",
                    "berry",
                    "blackberry",
                    "chard",
                    "cherry",
                    "flower",
                    "grapefruit",
                    "kiwi",
                    "lemon",
                    "lime",
                    "mango",
                    "melon",
                    "nectarine",
                    "orange",
                    "peach",
                    "pear",
                    "pineapple",
                    "plum",
                    "raspberry",
                    "tangerine"
                ],
                "_view_module_version": "~2.1.4",
                "description": "fruit flavors",
                "layout": "IPY_MODEL_0c7d52f6580f430aab75599e2ae78b33",
                "value": [
                    "apricot"
                ]
            }
        },
        "4289934e58134935bae53f0f9c79fdb0": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "2fe599a31cb8477db2b3d0d343db7e87": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "almond",
                    "buttered",
                    "caramel",
                    "chocolate",
                    "citrus",
                    "coffee",
                    "cola",
                    "floral",
                    "fruity",
                    "grass",
                    "herbal",
                    "honeysuckle",
                    "leather",
                    "licorice",
                    "mineral",
                    "oak",
                    "pepper",
                    "rose",
                    "spice",
                    "sugar",
                    "toast",
                    "tobacco",
                    "vanilla"
                ],
                "_view_module_version": "~2.1.4",
                "description": "other flavors",
                "layout": "IPY_MODEL_4289934e58134935bae53f0f9c79fdb0",
                "value": [
                    "oak"
                ]
            }
        },
        "9f59aa09f77342a8acb7a430cbfe21c2": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "display": "flex"
            }
        },
        "996b172fa6774796ae69180e1611136d": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "balanced",
                    "bright",
                    "brisk",
                    "citrusy",
                    "clean",
                    "creamy",
                    "crisp",
                    "dark",
                    "delicate",
                    "dense",
                    "dry",
                    "firm",
                    "fragrant",
                    "fresh",
                    "fullbodied",
                    "green",
                    "juicy",
                    "light",
                    "lively",
                    "refreshing",
                    "rich",
                    "ripe",
                    "simple",
                    "smoky",
                    "smooth",
                    "spicy",
                    "steely",
                    "structure",
                    "sweet",
                    "tangy",
                    "tannic",
                    "tart",
                    "tropical",
                    "zest"
                ],
                "_view_module_version": "~2.1.4",
                "description": "descriptive terms",
                "layout": "IPY_MODEL_9f59aa09f77342a8acb7a430cbfe21c2",
                "value": [
                    "sweet"
                ]
            }
        },
        "d32d611f1620475cb97f91e8fa7cd15a": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "7eb89093adb0464cbd5c9d62c27387ad": {
            "model_name": "AccordionModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_titles": {
                    "0": "Choose a type of wine",
                    "1": "Choose one or more fruit flavors",
                    "2": "Choose one or more other flavors",
                    "3": "Choose one or more descriptive terms"
                },
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_d189acefb724487facce6c6451ffe6f1",
                    "IPY_MODEL_db8818b1435d4a82bcd14c3942487f09",
                    "IPY_MODEL_2fe599a31cb8477db2b3d0d343db7e87",
                    "IPY_MODEL_996b172fa6774796ae69180e1611136d"
                ],
                "layout": "IPY_MODEL_d32d611f1620475cb97f91e8fa7cd15a"
            }
        },
        "66b7350b099143949add4d9e9a98bdee": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "3d5d5d957621412588da7f3fb8e4c6c7": {
            "model_name": "VBoxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [
                    "widget-interact"
                ],
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_4ec0a72cc1e14a318f5e3691c5ee262b",
                    "IPY_MODEL_f9c818d33f4d479590a13017a51db4c6",
                    "IPY_MODEL_3d4d0b6d425d414fb5b1a5c5576ba9ad"
                ],
                "layout": "IPY_MODEL_66b7350b099143949add4d9e9a98bdee"
            }
        },
        "c3a2a94733374c0e95668571970680bc": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "4ec0a72cc1e14a318f5e3691c5ee262b": {
            "model_name": "CheckboxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Submit",
                "disabled": false,
                "layout": "IPY_MODEL_c3a2a94733374c0e95668571970680bc",
                "value": true
            }
        },
        "d4f4d455703f44c892341b9ab7735c3d": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "db7e262d25c148ddac798a2cd55cd8e0": {
            "model_name": "ButtonStyleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "f9c818d33f4d479590a13017a51db4c6": {
            "model_name": "ButtonModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Run Interact",
                "layout": "IPY_MODEL_d4f4d455703f44c892341b9ab7735c3d",
                "style": "IPY_MODEL_db7e262d25c148ddac798a2cd55cd8e0"
            }
        },
        "ee3ffd67598543f6bac2468eeda6ff46": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "3d4d0b6d425d414fb5b1a5c5576ba9ad": {
            "model_name": "OutputModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [],
                "_model_module": "jupyter-js-widgets",
                "_model_module_version": "~2.1.4",
                "_view_module": "jupyter-js-widgets",
                "_view_module_version": "~2.1.4",
                "layout": "IPY_MODEL_ee3ffd67598543f6bac2468eeda6ff46",
                "msg_throttle": 1
            }
        },
        "9785a84e80a04fd7976ea2c3d1690eef": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "2d2be20f3bcb463e954aabd4905ab53e": {
            "model_name": "ToggleButtonsModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "Red",
                    "White",
                    "Surprise Me"
                ],
                "_view_module_version": "~2.1.4",
                "button_style": "",
                "description": "Select Wine Type:",
                "icons": [],
                "layout": "IPY_MODEL_9785a84e80a04fd7976ea2c3d1690eef",
                "tooltips": [
                    "Red",
                    "White",
                    "Surprise Me"
                ],
                "value": "Red"
            }
        },
        "f0453a42cbf544b0b389998caa122522": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "42c7c83b6bc544c59ab156b47db51ccc": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "apple",
                    "apricot",
                    "banana",
                    "berry",
                    "blackberry",
                    "chard",
                    "cherry",
                    "flower",
                    "grapefruit",
                    "kiwi",
                    "lemon",
                    "lime",
                    "mango",
                    "melon",
                    "nectarine",
                    "orange",
                    "peach",
                    "pear",
                    "pineapple",
                    "plum",
                    "raspberry",
                    "tangerine"
                ],
                "_view_module_version": "~2.1.4",
                "description": "fruit flavors",
                "layout": "IPY_MODEL_f0453a42cbf544b0b389998caa122522",
                "value": [
                    "apricot"
                ]
            }
        },
        "f406fbcd1ebd43428d09b0e96db88a7d": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "0d65014b2c054089890a03401f51d06d": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "almond",
                    "buttered",
                    "caramel",
                    "chocolate",
                    "citrus",
                    "coffee",
                    "cola",
                    "floral",
                    "fruity",
                    "grass",
                    "herbal",
                    "honeysuckle",
                    "leather",
                    "licorice",
                    "mineral",
                    "oak",
                    "pepper",
                    "rose",
                    "spice",
                    "sugar",
                    "toast",
                    "tobacco",
                    "vanilla"
                ],
                "_view_module_version": "~2.1.4",
                "description": "other flavors",
                "layout": "IPY_MODEL_f406fbcd1ebd43428d09b0e96db88a7d",
                "value": [
                    "oak"
                ]
            }
        },
        "b14111e660b6439b8d6d433908e3526b": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "display": "flex"
            }
        },
        "094af4737ccf45c9b2c7d31f45a0a7a0": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "balanced",
                    "bright",
                    "brisk",
                    "citrusy",
                    "clean",
                    "creamy",
                    "crisp",
                    "dark",
                    "delicate",
                    "dense",
                    "dry",
                    "firm",
                    "fragrant",
                    "fresh",
                    "fullbodied",
                    "green",
                    "juicy",
                    "light",
                    "lively",
                    "refreshing",
                    "rich",
                    "ripe",
                    "simple",
                    "smoky",
                    "smooth",
                    "spicy",
                    "steely",
                    "structure",
                    "sweet",
                    "tangy",
                    "tannic",
                    "tart",
                    "tropical",
                    "zest"
                ],
                "_view_module_version": "~2.1.4",
                "description": "descriptive terms",
                "layout": "IPY_MODEL_b14111e660b6439b8d6d433908e3526b",
                "value": [
                    "sweet"
                ]
            }
        },
        "7dd698a5f9034913ab04a56310d466f2": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "b61c4d14cd9a455fb1930f2c83d96ef7": {
            "model_name": "AccordionModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_titles": {
                    "0": "Choose a type of wine",
                    "1": "Choose one or more fruit flavors",
                    "2": "Choose one or more other flavors",
                    "3": "Choose one or more descriptive terms"
                },
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_2d2be20f3bcb463e954aabd4905ab53e",
                    "IPY_MODEL_42c7c83b6bc544c59ab156b47db51ccc",
                    "IPY_MODEL_0d65014b2c054089890a03401f51d06d",
                    "IPY_MODEL_094af4737ccf45c9b2c7d31f45a0a7a0"
                ],
                "layout": "IPY_MODEL_7dd698a5f9034913ab04a56310d466f2"
            }
        },
        "36d02fe2c4e94d4ca216173a9d10a038": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "6a350d9389ad4ca3921fa687df1d1174": {
            "model_name": "VBoxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [
                    "widget-interact"
                ],
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_9b8ec5f420394eae94809b313e1678fc",
                    "IPY_MODEL_8d0b88fe4a434ee5aba5d061139c9282",
                    "IPY_MODEL_7d43f43d5fcc4f568dc297935fce8a3a"
                ],
                "layout": "IPY_MODEL_36d02fe2c4e94d4ca216173a9d10a038"
            }
        },
        "75e4d48799c94c2fbe6e735955ad8679": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "9b8ec5f420394eae94809b313e1678fc": {
            "model_name": "CheckboxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Submit",
                "disabled": false,
                "layout": "IPY_MODEL_75e4d48799c94c2fbe6e735955ad8679",
                "value": true
            }
        },
        "1a52ff0b626e48aa8344f3ccad69d8d8": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "3ce3d4c1d05b48609e6a6c3b7620c79e": {
            "model_name": "ButtonStyleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "8d0b88fe4a434ee5aba5d061139c9282": {
            "model_name": "ButtonModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Run Interact",
                "layout": "IPY_MODEL_1a52ff0b626e48aa8344f3ccad69d8d8",
                "style": "IPY_MODEL_3ce3d4c1d05b48609e6a6c3b7620c79e"
            }
        },
        "81d75a6102a24bae9996dba9ceb4c559": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "7d43f43d5fcc4f568dc297935fce8a3a": {
            "model_name": "OutputModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [],
                "_model_module": "jupyter-js-widgets",
                "_model_module_version": "~2.1.4",
                "_view_module": "jupyter-js-widgets",
                "_view_module_version": "~2.1.4",
                "layout": "IPY_MODEL_81d75a6102a24bae9996dba9ceb4c559",
                "msg_throttle": 1
            }
        },
        "2970b0af36f94b46a1400214e0fc0195": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "0f08059d5ed340f386b46061e4d696a2": {
            "model_name": "VBoxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [
                    "widget-interact"
                ],
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_761803e516fd426fa803d162aed3c468",
                    "IPY_MODEL_38b2e5cbecd843f3ab55d729022fa9a6",
                    "IPY_MODEL_2ee828ad7cbe483cb727e89d7a26fa53"
                ],
                "layout": "IPY_MODEL_2970b0af36f94b46a1400214e0fc0195"
            }
        },
        "0f01e6cd3e4c48098ed8f9bf7d596eb0": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "761803e516fd426fa803d162aed3c468": {
            "model_name": "CheckboxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Submit",
                "disabled": false,
                "layout": "IPY_MODEL_0f01e6cd3e4c48098ed8f9bf7d596eb0",
                "value": false
            }
        },
        "3e8eeabffc0944de84a572beff83ea69": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "cb2da1aeb19e4a8c838cb3c923d9fddb": {
            "model_name": "ButtonStyleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "38b2e5cbecd843f3ab55d729022fa9a6": {
            "model_name": "ButtonModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Run Interact",
                "layout": "IPY_MODEL_3e8eeabffc0944de84a572beff83ea69",
                "style": "IPY_MODEL_cb2da1aeb19e4a8c838cb3c923d9fddb"
            }
        },
        "a75869fd2b304c8d92217913a1ebbc0e": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "2ee828ad7cbe483cb727e89d7a26fa53": {
            "model_name": "OutputModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [],
                "_model_module": "jupyter-js-widgets",
                "_model_module_version": "~2.1.4",
                "_view_module": "jupyter-js-widgets",
                "_view_module_version": "~2.1.4",
                "layout": "IPY_MODEL_a75869fd2b304c8d92217913a1ebbc0e",
                "msg_throttle": 1
            }
        },
        "ba07fc9ef503424db760ab6dc687daef": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "6328cafdd5014a59b948eab112b8c696": {
            "model_name": "ToggleButtonsModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "Red",
                    "White",
                    "Surprise Me"
                ],
                "_view_module_version": "~2.1.4",
                "button_style": "",
                "description": "Select Wine Type:",
                "icons": [],
                "layout": "IPY_MODEL_ba07fc9ef503424db760ab6dc687daef",
                "tooltips": [
                    "Red",
                    "White",
                    "Surprise Me"
                ],
                "value": "White"
            }
        },
        "892feb0dbff642ab87954e63a054ec14": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "04653c62863d46a1b58a9e39459d6055": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "apple",
                    "apricot",
                    "banana",
                    "berry",
                    "blackberry",
                    "chard",
                    "cherry",
                    "flower",
                    "grapefruit",
                    "kiwi",
                    "lemon",
                    "lime",
                    "mango",
                    "melon",
                    "nectarine",
                    "orange",
                    "peach",
                    "pear",
                    "pineapple",
                    "plum",
                    "raspberry",
                    "tangerine"
                ],
                "_view_module_version": "~2.1.4",
                "description": "fruit flavors",
                "layout": "IPY_MODEL_892feb0dbff642ab87954e63a054ec14",
                "value": [
                    "apricot"
                ]
            }
        },
        "dfa9374290fa45b98bf96eaaf3a3a487": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "e708816dba2e472e8b5ed29b35c88649": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "almond",
                    "buttered",
                    "caramel",
                    "chocolate",
                    "citrus",
                    "coffee",
                    "cola",
                    "floral",
                    "fruity",
                    "grass",
                    "herbal",
                    "honeysuckle",
                    "leather",
                    "licorice",
                    "mineral",
                    "oak",
                    "pepper",
                    "rose",
                    "spice",
                    "sugar",
                    "toast",
                    "tobacco",
                    "vanilla"
                ],
                "_view_module_version": "~2.1.4",
                "description": "other flavors",
                "layout": "IPY_MODEL_dfa9374290fa45b98bf96eaaf3a3a487",
                "value": [
                    "oak"
                ]
            }
        },
        "96fc05f7b409419fbac7744f8ace2754": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "display": "flex"
            }
        },
        "5593a4b84ad246f59c7f869d02a57f8d": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "balanced",
                    "bright",
                    "brisk",
                    "citrusy",
                    "clean",
                    "creamy",
                    "crisp",
                    "dark",
                    "delicate",
                    "dense",
                    "dry",
                    "firm",
                    "fragrant",
                    "fresh",
                    "fullbodied",
                    "green",
                    "juicy",
                    "light",
                    "lively",
                    "refreshing",
                    "rich",
                    "ripe",
                    "simple",
                    "smoky",
                    "smooth",
                    "spicy",
                    "steely",
                    "structure",
                    "sweet",
                    "tangy",
                    "tannic",
                    "tart",
                    "tropical",
                    "zest"
                ],
                "_view_module_version": "~2.1.4",
                "description": "descriptive terms",
                "layout": "IPY_MODEL_96fc05f7b409419fbac7744f8ace2754",
                "value": [
                    "sweet"
                ]
            }
        },
        "8313778aa6d34c10a440dd87fcc1f5fe": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "7338e5bae72a4bceb52b1585c1d214a3": {
            "model_name": "AccordionModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_titles": {
                    "0": "Choose a type of wine",
                    "1": "Choose one or more fruit flavors",
                    "2": "Choose one or more other flavors",
                    "3": "Choose one or more descriptive terms"
                },
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_6328cafdd5014a59b948eab112b8c696",
                    "IPY_MODEL_04653c62863d46a1b58a9e39459d6055",
                    "IPY_MODEL_e708816dba2e472e8b5ed29b35c88649",
                    "IPY_MODEL_5593a4b84ad246f59c7f869d02a57f8d"
                ],
                "layout": "IPY_MODEL_8313778aa6d34c10a440dd87fcc1f5fe",
                "selected_index": 3
            }
        },
        "64295c97649e48f692fbde9d2557026f": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "700d2aa2c745428292d1df073b9817fb": {
            "model_name": "VBoxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [
                    "widget-interact"
                ],
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_948e25669bcd4ca78c4402410e391b83",
                    "IPY_MODEL_2a71d524c38046349ca3580507aad815",
                    "IPY_MODEL_31fadcd8aaf54f2b84a73e848ddedac6"
                ],
                "layout": "IPY_MODEL_64295c97649e48f692fbde9d2557026f"
            }
        },
        "78a6c2c07a524f3c847660fac5aa3392": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "948e25669bcd4ca78c4402410e391b83": {
            "model_name": "CheckboxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Submit",
                "disabled": false,
                "layout": "IPY_MODEL_78a6c2c07a524f3c847660fac5aa3392",
                "value": true
            }
        },
        "0d7e9db5fe2a4947825e4c7d3758811a": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "d2afabd1ea32446db80fb12beb854ce3": {
            "model_name": "ButtonStyleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "2a71d524c38046349ca3580507aad815": {
            "model_name": "ButtonModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Run Interact",
                "layout": "IPY_MODEL_0d7e9db5fe2a4947825e4c7d3758811a",
                "style": "IPY_MODEL_d2afabd1ea32446db80fb12beb854ce3"
            }
        },
        "39704728db2944b89aa37fed083ccf6f": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "31fadcd8aaf54f2b84a73e848ddedac6": {
            "model_name": "OutputModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [],
                "_model_module": "jupyter-js-widgets",
                "_model_module_version": "~2.1.4",
                "_view_module": "jupyter-js-widgets",
                "_view_module_version": "~2.1.4",
                "layout": "IPY_MODEL_39704728db2944b89aa37fed083ccf6f",
                "msg_throttle": 1
            }
        },
        "e29fe058f200487290668e3e81bd9785": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "5b5f6812fb544dcf83cd96dd28920917": {
            "model_name": "ToggleButtonsModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "Red",
                    "White",
                    "Surprise Me"
                ],
                "_view_module_version": "~2.1.4",
                "button_style": "",
                "description": "Select Wine Type:",
                "icons": [],
                "layout": "IPY_MODEL_e29fe058f200487290668e3e81bd9785",
                "tooltips": [
                    "Red",
                    "White",
                    "Surprise Me"
                ],
                "value": "White"
            }
        },
        "939bad46f39f416dbd1f19500bb24660": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "09c309e848ca492397c386bf75c376c7": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "apple",
                    "apricot",
                    "banana",
                    "berry",
                    "blackberry",
                    "chard",
                    "cherry",
                    "flower",
                    "grapefruit",
                    "kiwi",
                    "lemon",
                    "lime",
                    "mango",
                    "melon",
                    "nectarine",
                    "orange",
                    "peach",
                    "pear",
                    "pineapple",
                    "plum",
                    "raspberry",
                    "tangerine"
                ],
                "_view_module_version": "~2.1.4",
                "description": "fruit flavors",
                "layout": "IPY_MODEL_939bad46f39f416dbd1f19500bb24660",
                "value": [
                    "lemon",
                    "pear",
                    "pineapple"
                ]
            }
        },
        "fb2a131f2d054123aa6579f66fb505c6": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "78722d3febbc41b59cc1a66ddf8d669f": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "almond",
                    "buttered",
                    "caramel",
                    "chocolate",
                    "citrus",
                    "coffee",
                    "cola",
                    "floral",
                    "fruity",
                    "grass",
                    "herbal",
                    "honeysuckle",
                    "leather",
                    "licorice",
                    "mineral",
                    "oak",
                    "pepper",
                    "rose",
                    "spice",
                    "sugar",
                    "toast",
                    "tobacco",
                    "vanilla"
                ],
                "_view_module_version": "~2.1.4",
                "description": "other flavors",
                "layout": "IPY_MODEL_fb2a131f2d054123aa6579f66fb505c6",
                "value": [
                    "citrus",
                    "oak",
                    "vanilla"
                ]
            }
        },
        "32a8e860591e4653b3571c018f01e811": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "display": "flex"
            }
        },
        "847ddaba34e34ca1a214d5c0440cdf57": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "balanced",
                    "bright",
                    "brisk",
                    "citrusy",
                    "clean",
                    "creamy",
                    "crisp",
                    "dark",
                    "delicate",
                    "dense",
                    "dry",
                    "firm",
                    "fragrant",
                    "fresh",
                    "fullbodied",
                    "green",
                    "juicy",
                    "light",
                    "lively",
                    "refreshing",
                    "rich",
                    "ripe",
                    "simple",
                    "smoky",
                    "smooth",
                    "spicy",
                    "steely",
                    "structure",
                    "sweet",
                    "tangy",
                    "tannic",
                    "tart",
                    "tropical",
                    "zest"
                ],
                "_view_module_version": "~2.1.4",
                "description": "descriptive terms",
                "layout": "IPY_MODEL_32a8e860591e4653b3571c018f01e811",
                "value": [
                    "green",
                    "light",
                    "smooth",
                    "sweet"
                ]
            }
        },
        "96dcefaa076c41329b799a30e47a5495": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "9d577d3674204673a98771bb136afa80": {
            "model_name": "AccordionModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_titles": {
                    "0": "Choose a type of wine",
                    "1": "Choose one or more fruit flavors",
                    "2": "Choose one or more other flavors",
                    "3": "Choose one or more descriptive terms"
                },
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_5b5f6812fb544dcf83cd96dd28920917",
                    "IPY_MODEL_09c309e848ca492397c386bf75c376c7",
                    "IPY_MODEL_78722d3febbc41b59cc1a66ddf8d669f",
                    "IPY_MODEL_847ddaba34e34ca1a214d5c0440cdf57"
                ],
                "layout": "IPY_MODEL_96dcefaa076c41329b799a30e47a5495",
                "selected_index": 3
            }
        },
        "147ffd141a264d4d9f7c4f6779f157ca": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "6c4c8f4d5dcf4d8fa2ac0d14c0af463d": {
            "model_name": "VBoxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [
                    "widget-interact"
                ],
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_81f84ec808cf48a0bc3ea4af5a51a436",
                    "IPY_MODEL_6f2e9326629249b9aada2754fdad359f",
                    "IPY_MODEL_521024d679f54052af16402316589c91"
                ],
                "layout": "IPY_MODEL_147ffd141a264d4d9f7c4f6779f157ca"
            }
        },
        "66450478dc5e49e79d68f234d9f67f75": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "81f84ec808cf48a0bc3ea4af5a51a436": {
            "model_name": "CheckboxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Submit",
                "disabled": false,
                "layout": "IPY_MODEL_66450478dc5e49e79d68f234d9f67f75",
                "value": true
            }
        },
        "008cb27acc1c42e09b0b7847e5799c23": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "2977b81138684795b71296cabf9016e6": {
            "model_name": "ButtonStyleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "6f2e9326629249b9aada2754fdad359f": {
            "model_name": "ButtonModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Run Interact",
                "layout": "IPY_MODEL_008cb27acc1c42e09b0b7847e5799c23",
                "style": "IPY_MODEL_2977b81138684795b71296cabf9016e6"
            }
        },
        "9ea2306b999148a2aa9f5a38e52a9d43": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "521024d679f54052af16402316589c91": {
            "model_name": "OutputModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [],
                "_model_module": "jupyter-js-widgets",
                "_model_module_version": "~2.1.4",
                "_view_module": "jupyter-js-widgets",
                "_view_module_version": "~2.1.4",
                "layout": "IPY_MODEL_9ea2306b999148a2aa9f5a38e52a9d43",
                "msg_throttle": 1
            }
        },
        "624f7e18b9cd465fbcdb863c47343c17": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "8fb85550313a494a9e4a48c600299c24": {
            "model_name": "ToggleButtonsModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "Red",
                    "White",
                    "Surprise Me"
                ],
                "_view_module_version": "~2.1.4",
                "button_style": "",
                "description": "Select Wine Type:",
                "icons": [],
                "layout": "IPY_MODEL_624f7e18b9cd465fbcdb863c47343c17",
                "tooltips": [
                    "Red",
                    "White",
                    "Surprise Me"
                ],
                "value": "White"
            }
        },
        "b00c19772f9042c0bc785c4ecadb5d39": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "e4f0eb36e70c41f0bc646ec78f099b59": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "apple",
                    "apricot",
                    "banana",
                    "berry",
                    "blackberry",
                    "chard",
                    "cherry",
                    "flower",
                    "grapefruit",
                    "kiwi",
                    "lemon",
                    "lime",
                    "mango",
                    "melon",
                    "nectarine",
                    "orange",
                    "peach",
                    "pear",
                    "pineapple",
                    "plum",
                    "raspberry",
                    "tangerine"
                ],
                "_view_module_version": "~2.1.4",
                "description": "fruit flavors",
                "layout": "IPY_MODEL_b00c19772f9042c0bc785c4ecadb5d39",
                "value": [
                    "apricot",
                    "banana",
                    "berry",
                    "blackberry",
                    "chard"
                ]
            }
        },
        "399988162f2d44259e7a51d7716e5ef4": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "202642ce6975473297c348a257116b49": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "almond",
                    "buttered",
                    "caramel",
                    "chocolate",
                    "citrus",
                    "coffee",
                    "cola",
                    "floral",
                    "fruity",
                    "grass",
                    "herbal",
                    "honeysuckle",
                    "leather",
                    "licorice",
                    "mineral",
                    "oak",
                    "pepper",
                    "rose",
                    "spice",
                    "sugar",
                    "toast",
                    "tobacco",
                    "vanilla"
                ],
                "_view_module_version": "~2.1.4",
                "description": "other flavors",
                "layout": "IPY_MODEL_399988162f2d44259e7a51d7716e5ef4",
                "value": [
                    "herbal",
                    "licorice",
                    "oak"
                ]
            }
        },
        "33178f9f3b3046cb8f5fb4451dbb3200": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "display": "flex"
            }
        },
        "11bf39cf88d64a92bd9a329f46db0304": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "balanced",
                    "bright",
                    "brisk",
                    "citrusy",
                    "clean",
                    "creamy",
                    "crisp",
                    "dark",
                    "delicate",
                    "dense",
                    "dry",
                    "firm",
                    "fragrant",
                    "fresh",
                    "fullbodied",
                    "green",
                    "juicy",
                    "light",
                    "lively",
                    "refreshing",
                    "rich",
                    "ripe",
                    "simple",
                    "smoky",
                    "smooth",
                    "spicy",
                    "steely",
                    "structure",
                    "sweet",
                    "tangy",
                    "tannic",
                    "tart",
                    "tropical",
                    "zest"
                ],
                "_view_module_version": "~2.1.4",
                "description": "descriptive terms",
                "layout": "IPY_MODEL_33178f9f3b3046cb8f5fb4451dbb3200",
                "value": [
                    "juicy",
                    "ripe",
                    "spicy",
                    "tannic"
                ]
            }
        },
        "ad175bf86c974afb837ddfcde9233e2d": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "6649222005d941d8bc7c6c04765407ff": {
            "model_name": "AccordionModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_titles": {
                    "0": "Choose a type of wine",
                    "1": "Choose one or more fruit flavors",
                    "2": "Choose one or more other flavors",
                    "3": "Choose one or more descriptive terms"
                },
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_8fb85550313a494a9e4a48c600299c24",
                    "IPY_MODEL_e4f0eb36e70c41f0bc646ec78f099b59",
                    "IPY_MODEL_202642ce6975473297c348a257116b49",
                    "IPY_MODEL_11bf39cf88d64a92bd9a329f46db0304"
                ],
                "layout": "IPY_MODEL_ad175bf86c974afb837ddfcde9233e2d",
                "selected_index": 3
            }
        },
        "5ff77c526df84f55aba541a547d3d2ff": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "c49ef9ca0e6f4e16a2c3d9d887b2d916": {
            "model_name": "VBoxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [
                    "widget-interact"
                ],
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_1df084a8662043d3abb65331a29335fb",
                    "IPY_MODEL_a8c90718b06a486fa8102fefa91772a4",
                    "IPY_MODEL_bea5379feb7d4c968494fad2b63bcd72"
                ],
                "layout": "IPY_MODEL_5ff77c526df84f55aba541a547d3d2ff"
            }
        },
        "00749760a07c432188ffa572ebd06e7d": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "1df084a8662043d3abb65331a29335fb": {
            "model_name": "CheckboxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Submit",
                "disabled": false,
                "layout": "IPY_MODEL_00749760a07c432188ffa572ebd06e7d",
                "value": true
            }
        },
        "7e8da24bdd8145a09528ac1baddabe61": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "8c8c9843d1d344ee9f47cb263c1e6cea": {
            "model_name": "ButtonStyleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "a8c90718b06a486fa8102fefa91772a4": {
            "model_name": "ButtonModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Run Interact",
                "layout": "IPY_MODEL_7e8da24bdd8145a09528ac1baddabe61",
                "style": "IPY_MODEL_8c8c9843d1d344ee9f47cb263c1e6cea"
            }
        },
        "55dea321928946c7a345c8556bdc71ea": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "bea5379feb7d4c968494fad2b63bcd72": {
            "model_name": "OutputModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [],
                "_model_module": "jupyter-js-widgets",
                "_model_module_version": "~2.1.4",
                "_view_module": "jupyter-js-widgets",
                "_view_module_version": "~2.1.4",
                "layout": "IPY_MODEL_55dea321928946c7a345c8556bdc71ea",
                "msg_throttle": 1
            }
        },
        "ee56e32af7894582a2f0166973dc9f38": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "7924cc3aaa784906ac29a05abe5a0d1e": {
            "model_name": "ToggleButtonsModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "Red",
                    "White",
                    "Surprise Me"
                ],
                "_view_module_version": "~2.1.4",
                "button_style": "",
                "description": "Select Wine Type:",
                "icons": [],
                "layout": "IPY_MODEL_ee56e32af7894582a2f0166973dc9f38",
                "tooltips": [
                    "Red",
                    "White",
                    "Surprise Me"
                ],
                "value": "Red"
            }
        },
        "6474d6351739447b8d11520ca6173240": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "7b2676e8c0834b6f9cf881f057aac6a8": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "apple",
                    "apricot",
                    "banana",
                    "berry",
                    "blackberry",
                    "chard",
                    "cherry",
                    "flower",
                    "grapefruit",
                    "kiwi",
                    "lemon",
                    "lime",
                    "mango",
                    "melon",
                    "nectarine",
                    "orange",
                    "peach",
                    "pear",
                    "pineapple",
                    "plum",
                    "raspberry",
                    "tangerine"
                ],
                "_view_module_version": "~2.1.4",
                "description": "fruit flavors",
                "layout": "IPY_MODEL_6474d6351739447b8d11520ca6173240",
                "value": [
                    "apricot",
                    "berry",
                    "blackberry"
                ]
            }
        },
        "8907df6eee3640318ffbe51deb072cdf": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "c3db899af5b54de1bf6e07ebdee8f9b8": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "almond",
                    "buttered",
                    "caramel",
                    "chocolate",
                    "citrus",
                    "coffee",
                    "cola",
                    "floral",
                    "fruity",
                    "grass",
                    "herbal",
                    "honeysuckle",
                    "leather",
                    "licorice",
                    "mineral",
                    "oak",
                    "pepper",
                    "rose",
                    "spice",
                    "sugar",
                    "toast",
                    "tobacco",
                    "vanilla"
                ],
                "_view_module_version": "~2.1.4",
                "description": "other flavors",
                "layout": "IPY_MODEL_8907df6eee3640318ffbe51deb072cdf",
                "value": [
                    "herbal",
                    "leather",
                    "licorice",
                    "oak"
                ]
            }
        },
        "e1df6b8011df4af0ad2cc359cf58c107": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "display": "flex"
            }
        },
        "6f823abfd8ea40bf86519ddce9d422ba": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "balanced",
                    "bright",
                    "brisk",
                    "citrusy",
                    "clean",
                    "creamy",
                    "crisp",
                    "dark",
                    "delicate",
                    "dense",
                    "dry",
                    "firm",
                    "fragrant",
                    "fresh",
                    "fullbodied",
                    "green",
                    "juicy",
                    "light",
                    "lively",
                    "refreshing",
                    "rich",
                    "ripe",
                    "simple",
                    "smoky",
                    "smooth",
                    "spicy",
                    "steely",
                    "structure",
                    "sweet",
                    "tangy",
                    "tannic",
                    "tart",
                    "tropical",
                    "zest"
                ],
                "_view_module_version": "~2.1.4",
                "description": "descriptive terms",
                "layout": "IPY_MODEL_e1df6b8011df4af0ad2cc359cf58c107",
                "value": [
                    "refreshing",
                    "simple",
                    "spicy"
                ]
            }
        },
        "42d2bfcd642d4b40bb2b1d7edad307b1": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "c88d8228aecb44ee9f49abe82d3d9b96": {
            "model_name": "AccordionModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_titles": {
                    "0": "Choose a type of wine",
                    "1": "Choose one or more fruit flavors",
                    "2": "Choose one or more other flavors",
                    "3": "Choose one or more descriptive terms"
                },
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_7924cc3aaa784906ac29a05abe5a0d1e",
                    "IPY_MODEL_7b2676e8c0834b6f9cf881f057aac6a8",
                    "IPY_MODEL_c3db899af5b54de1bf6e07ebdee8f9b8",
                    "IPY_MODEL_6f823abfd8ea40bf86519ddce9d422ba"
                ],
                "layout": "IPY_MODEL_42d2bfcd642d4b40bb2b1d7edad307b1",
                "selected_index": 3
            }
        },
        "adba831f617d48d7b8345b1d0a47a42c": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "c4c9ce30588a4d49a35c3b54210bfc57": {
            "model_name": "VBoxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [
                    "widget-interact"
                ],
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_d65e7f4ec40741fea0c2a8986ddd650a",
                    "IPY_MODEL_9c2ad752ebca4473a6d30533c41ba641",
                    "IPY_MODEL_62429556faf5455c9e66b6693fdd151d"
                ],
                "layout": "IPY_MODEL_adba831f617d48d7b8345b1d0a47a42c"
            }
        },
        "3cf97392b4234e4585eb23e184d67cd7": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "d65e7f4ec40741fea0c2a8986ddd650a": {
            "model_name": "CheckboxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Submit",
                "disabled": false,
                "layout": "IPY_MODEL_3cf97392b4234e4585eb23e184d67cd7",
                "value": true
            }
        },
        "10878b5832c64b07af7729b88bc42b29": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "942373ac361843a68399052cd28f198b": {
            "model_name": "ButtonStyleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "9c2ad752ebca4473a6d30533c41ba641": {
            "model_name": "ButtonModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Run Interact",
                "layout": "IPY_MODEL_10878b5832c64b07af7729b88bc42b29",
                "style": "IPY_MODEL_942373ac361843a68399052cd28f198b"
            }
        },
        "80835d7466304b7eb217e0f674588939": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "62429556faf5455c9e66b6693fdd151d": {
            "model_name": "OutputModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [],
                "_model_module": "jupyter-js-widgets",
                "_model_module_version": "~2.1.4",
                "_view_module": "jupyter-js-widgets",
                "_view_module_version": "~2.1.4",
                "layout": "IPY_MODEL_80835d7466304b7eb217e0f674588939",
                "msg_throttle": 1
            }
        },
        "808d6ea2360841bdb7746415e94e059e": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "4dd38728a0ad42a487f9fa1e48ccd621": {
            "model_name": "ToggleButtonsModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "Red",
                    "White",
                    "Surprise Me"
                ],
                "_view_module_version": "~2.1.4",
                "button_style": "",
                "description": "Select Wine Type:",
                "icons": [],
                "layout": "IPY_MODEL_808d6ea2360841bdb7746415e94e059e",
                "tooltips": [
                    "Red",
                    "White",
                    "Surprise Me"
                ],
                "value": "White"
            }
        },
        "88d86bd1bf8d47b7ae67da2a2c17d2ff": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "d9f18b084b314cb7aed4cab781ad5a47": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "apple",
                    "apricot",
                    "banana",
                    "berry",
                    "blackberry",
                    "chard",
                    "cherry",
                    "flower",
                    "grapefruit",
                    "kiwi",
                    "lemon",
                    "lime",
                    "mango",
                    "melon",
                    "nectarine",
                    "orange",
                    "peach",
                    "pear",
                    "pineapple",
                    "plum",
                    "raspberry",
                    "tangerine"
                ],
                "_view_module_version": "~2.1.4",
                "description": "fruit flavors",
                "layout": "IPY_MODEL_88d86bd1bf8d47b7ae67da2a2c17d2ff",
                "value": [
                    "cherry",
                    "lemon",
                    "pear"
                ]
            }
        },
        "a8aa92f58ea4446688626f8f0cfbba40": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "75c8bec0f5614d778629d251c52491ff": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "almond",
                    "buttered",
                    "caramel",
                    "chocolate",
                    "citrus",
                    "coffee",
                    "cola",
                    "floral",
                    "fruity",
                    "grass",
                    "herbal",
                    "honeysuckle",
                    "leather",
                    "licorice",
                    "mineral",
                    "oak",
                    "pepper",
                    "rose",
                    "spice",
                    "sugar",
                    "toast",
                    "tobacco",
                    "vanilla"
                ],
                "_view_module_version": "~2.1.4",
                "description": "other flavors",
                "layout": "IPY_MODEL_a8aa92f58ea4446688626f8f0cfbba40",
                "value": [
                    "citrus",
                    "herbal"
                ]
            }
        },
        "81c8b0fb420f4f66a32b645a6ebd55c4": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "display": "flex"
            }
        },
        "a6a7a74ff601473dbac53ddd0be2a87c": {
            "model_name": "SelectMultipleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_options_labels": [
                    "None",
                    "balanced",
                    "bright",
                    "brisk",
                    "citrusy",
                    "clean",
                    "creamy",
                    "crisp",
                    "dark",
                    "delicate",
                    "dense",
                    "dry",
                    "firm",
                    "fragrant",
                    "fresh",
                    "fullbodied",
                    "green",
                    "juicy",
                    "light",
                    "lively",
                    "refreshing",
                    "rich",
                    "ripe",
                    "simple",
                    "smoky",
                    "smooth",
                    "spicy",
                    "steely",
                    "structure",
                    "sweet",
                    "tangy",
                    "tannic",
                    "tart",
                    "tropical",
                    "zest"
                ],
                "_view_module_version": "~2.1.4",
                "description": "descriptive terms",
                "layout": "IPY_MODEL_81c8b0fb420f4f66a32b645a6ebd55c4",
                "value": [
                    "bright",
                    "refreshing",
                    "smooth",
                    "tannic"
                ]
            }
        },
        "2b308d2217874cd3a500465ad80ce72d": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "5026031c487d42509f2af82bd3c38df5": {
            "model_name": "AccordionModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_titles": {
                    "0": "Choose a type of wine",
                    "1": "Choose one or more fruit flavors",
                    "2": "Choose one or more other flavors",
                    "3": "Choose one or more descriptive terms"
                },
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_4dd38728a0ad42a487f9fa1e48ccd621",
                    "IPY_MODEL_d9f18b084b314cb7aed4cab781ad5a47",
                    "IPY_MODEL_75c8bec0f5614d778629d251c52491ff",
                    "IPY_MODEL_a6a7a74ff601473dbac53ddd0be2a87c"
                ],
                "layout": "IPY_MODEL_2b308d2217874cd3a500465ad80ce72d",
                "selected_index": 3
            }
        },
        "be252057b4db42ae8a4f12bd51e8231b": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "68b570ade1e8466a83fef8bf8f9a8b25": {
            "model_name": "VBoxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [
                    "widget-interact"
                ],
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "children": [
                    "IPY_MODEL_31323b557c8e45bf8a7e0e0d858cc764",
                    "IPY_MODEL_f2aa6478bf8845de8f0df0137189f77e",
                    "IPY_MODEL_c1ebafaff658480a8a84be2f7fc681c5"
                ],
                "layout": "IPY_MODEL_be252057b4db42ae8a4f12bd51e8231b"
            }
        },
        "a8613032e9a44640a48af382b4a29b73": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "31323b557c8e45bf8a7e0e0d858cc764": {
            "model_name": "CheckboxModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Submit",
                "disabled": false,
                "layout": "IPY_MODEL_a8613032e9a44640a48af382b4a29b73",
                "value": true
            }
        },
        "89f5ae638ff2401b8ea9244da9c1a9cf": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "7cb53f60262a48f4acd7dcddfccde334": {
            "model_name": "ButtonStyleModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "f2aa6478bf8845de8f0df0137189f77e": {
            "model_name": "ButtonModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4",
                "description": "Run Interact",
                "layout": "IPY_MODEL_89f5ae638ff2401b8ea9244da9c1a9cf",
                "style": "IPY_MODEL_7cb53f60262a48f4acd7dcddfccde334"
            }
        },
        "3c530ebb69004b90960c05585e031a01": {
            "model_name": "LayoutModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_model_module_version": "~2.1.4",
                "_view_module_version": "~2.1.4"
            }
        },
        "c1ebafaff658480a8a84be2f7fc681c5": {
            "model_name": "OutputModel",
            "model_module": "jupyter-js-widgets",
            "model_module_version": "~2.1.4",
            "state": {
                "_dom_classes": [],
                "_model_module": "jupyter-js-widgets",
                "_model_module_version": "~2.1.4",
                "_view_module": "jupyter-js-widgets",
                "_view_module_version": "~2.1.4",
                "layout": "IPY_MODEL_3c530ebb69004b90960c05585e031a01",
                "msg_throttle": 1
            }
        }
    }
}
</script>
<script type="application/vnd.jupyter.widget-view+json">
{
    "model_id": "5026031c487d42509f2af82bd3c38df5"
}
</script>
<script type="application/vnd.jupyter.widget-view+json">
{
    "model_id": "68b570ade1e8466a83fef8bf8f9a8b25"
}
</script>

Maybe?
