----------------------------------
Settings
----------------------------------

----------------------------------
General
----------------------------------

You can modify the behaviour of XXX Inspector by adding an xxl_inspector_config.txt file next to the d3d9.dll file.

The file must use the follwing format:
setting_key = value

----------------------------------
Available settings
----------------------------------
keymap_ui = <keymap_value>
   Key-Mapping for showing/hiding the ui
   Default: 572 (F1)
   
keymap_switch_character = <keymap_value>
   Key-Mapping for switching the active chracter
   Default: 573 (F2)

keymap_drop_bomb = <keymap_value>
  Key-Mapping for bomb-dropping-cheat
  Default: 575 (F4)

show_ui_on_start = <0|1>
  Show the XXL Inspector UI on start
  Default: 0

show_info_on_start = <0|1>
  Show greeting message and keymaps on start
  Default: 0


------------------
Type information
------------------

<keymap_value>
keymap_value is an integer ranging from 512 onwards.
The follwoing map shows the relationship betweeen the physical key and the corresponding integer value.

ImGuiKey_None = 0,
ImGuiKey_Tab = 512,             // == ImGuiKey_NamedKey_BEGIN
ImGuiKey_LeftArrow = 513,
ImGuiKey_RightArrow = 514,
ImGuiKey_UpArrow = 515,
ImGuiKey_DownArrow = 516,
ImGuiKey_PageUp = 517,
ImGuiKey_PageDown = 518,
ImGuiKey_Home = 519,
ImGuiKey_End = 520,
ImGuiKey_Insert = 521,
ImGuiKey_Delete = 522,
ImGuiKey_Backspace = 523,
ImGuiKey_Space = 524,
ImGuiKey_Enter = 525,
ImGuiKey_Escape = 526,
ImGuiKey_LeftCtrl = 527,
ImGuiKey_LeftShift = 528,
ImGuiKey_LeftAlt = 529,
ImGuiKey_LeftSuper = 530,
ImGuiKey_RightCtrl = 531,
ImGuiKey_RightShift = 532,
ImGuiKey_RightAlt = 533,
ImGuiKey_RightSuper = 534,
ImGuiKey_Menu = 535,
ImGuiKey_0 = 536,
ImGuiKey_1 = 537,
ImGuiKey_2 = 538,
ImGuiKey_3 = 539,
ImGuiKey_4 = 540,
ImGuiKey_5 = 541,
ImGuiKey_6 = 542,
ImGuiKey_7 = 543,
ImGuiKey_8 = 544,
ImGuiKey_9 = 545,
ImGuiKey_A = 546,
ImGuiKey_B = 547,
ImGuiKey_C = 548,
ImGuiKey_D = 549,
ImGuiKey_E = 550,
ImGuiKey_F = 551,
ImGuiKey_G = 552,
ImGuiKey_H = 553,
ImGuiKey_I = 554,
ImGuiKey_J = 555,
ImGuiKey_K = 556,
ImGuiKey_L = 557,
ImGuiKey_M = 558,
ImGuiKey_N = 559,
ImGuiKey_O = 560,
ImGuiKey_P = 561,
ImGuiKey_Q = 562,
ImGuiKey_R = 563,
ImGuiKey_S = 564,
ImGuiKey_T = 565,
ImGuiKey_U = 566,
ImGuiKey_V = 567,
ImGuiKey_W = 568,
ImGuiKey_X = 569,
ImGuiKey_Y = 570,
ImGuiKey_Z = 571,
ImGuiKey_F1 = 572,
ImGuiKey_F2 = 573,
ImGuiKey_F3 = 574,
ImGuiKey_F4 = 575,
ImGuiKey_F5 = 576,
ImGuiKey_F6 = 577,
ImGuiKey_F7 = 578,
ImGuiKey_F8 = 579,
ImGuiKey_F9 = 580,
ImGuiKey_F10 = 581,
ImGuiKey_F11 = 582,
ImGuiKey_F12 = 583,
ImGuiKey_F13 = 584, 
ImGuiKey_F14 = 585, 
ImGuiKey_F15 = 586, 
ImGuiKey_F16 = 587, 
ImGuiKey_F17 = 588, 
ImGuiKey_F18 = 589,
ImGuiKey_F19 = 590, 
ImGuiKey_F20 = 591, 
ImGuiKey_F21 = 592, 
ImGuiKey_F22 = 593, 
ImGuiKey_F23 = 594, 
ImGuiKey_F24 = 595,
ImGuiKey_Apostrophe = 596,        // '
ImGuiKey_Comma = 597,             // ,
ImGuiKey_Minus = 598,             // -
ImGuiKey_Period = 599,            // .
ImGuiKey_Slash = 600,             // /
ImGuiKey_Semicolon = 601,         // ;
ImGuiKey_Equal = 602,             // =
ImGuiKey_LeftBracket = 603,       // [
ImGuiKey_Backslash = 604,         // \ (this text inhibit multiline comment caused by backslash)
ImGuiKey_RightBracket = 605,      // ]
ImGuiKey_GraveAccent = 606,       // `
ImGuiKey_CapsLock = 607,
ImGuiKey_ScrollLock = 608,
ImGuiKey_NumLock = 609,
ImGuiKey_PrintScreen = 610,
ImGuiKey_Pause = 611,
ImGuiKey_Keypad0 = 612,
ImGuiKey_Keypad1 = 613,
ImGuiKey_Keypad2 = 614,
ImGuiKey_Keypad3 = 615,
ImGuiKey_Keypad4 = 616,
ImGuiKey_Keypad5 = 617,
ImGuiKey_Keypad6 = 618,
ImGuiKey_Keypad7 = 619,
ImGuiKey_Keypad8 = 620,
ImGuiKey_Keypad9 = 621,
ImGuiKey_KeypadDecimal = 622,
ImGuiKey_KeypadDivide = 623,
ImGuiKey_KeypadMultiply = 624,
ImGuiKey_KeypadSubtract = 625,
ImGuiKey_KeypadAdd = 626,
ImGuiKey_KeypadEnter = 627,
ImGuiKey_KeypadEqual = 628,
ImGuiKey_AppBack = 629,               // Available on some keyboard/mouses. Often referred as "Browser Back"
ImGuiKey_AppForward = 630,

// Gamepad (some of those are expected to be analog values from 0.0f to 1.0f) ..............// NAVIGATION action
ImGuiKey_GamepadStart = 631,          // Menu (Xbox)          + (Switch)      Start/Options (PS)  // --
ImGuiKey_GamepadBack = 632,           // View (Xbox)          - (Switch)      Share (PS)          // --
ImGuiKey_GamepadFaceUp = 633,         // Y (Xbox)             X (Switch)      Triangle (PS)       // -> ImGuiNavInput_Input
ImGuiKey_GamepadFaceDown = 634,       // A (Xbox)             B (Switch)      Cross (PS)          // -> ImGuiNavInput_Activate
ImGuiKey_GamepadFaceLeft = 635,       // X (Xbox)             Y (Switch)      Square (PS)         // -> ImGuiNavInput_Menu
ImGuiKey_GamepadFaceRight = 636,      // B (Xbox)             A (Switch)      Circle (PS)         // -> ImGuiNavInput_Cancel
ImGuiKey_GamepadDpadUp = 637,         // D-pad Up                                                 // -> ImGuiNavInput_DpadUp
ImGuiKey_GamepadDpadDown = 638,       // D-pad Down                                               // -> ImGuiNavInput_DpadDown
ImGuiKey_GamepadDpadLeft = 639,       // D-pad Left                                               // -> ImGuiNavInput_DpadLeft
ImGuiKey_GamepadDpadRight = 640,      // D-pad Right                                              // -> ImGuiNavInput_DpadRight
ImGuiKey_GamepadL1 = 641,             // L Bumper (Xbox)      L (Switch)      L1 (PS)             // -> ImGuiNavInput_FocusPrev + ImGuiNavInput_TweakSlow
ImGuiKey_GamepadR1 = 642,             // R Bumper (Xbox)      R (Switch)      R1 (PS)             // -> ImGuiNavInput_FocusNext + ImGuiNavInput_TweakFast
ImGuiKey_GamepadL2 = 643,             // L Trigger (Xbox)     ZL (Switch)     L2 (PS) [Analog]
ImGuiKey_GamepadR2 = 644,             // R Trigger (Xbox)     ZR (Switch)     R2 (PS) [Analog]
ImGuiKey_GamepadL3 = 645,             // L Thumbstick (Xbox)  L3 (Switch)     L3 (PS)
ImGuiKey_GamepadR3 = 646,             // R Thumbstick (Xbox)  R3 (Switch)     R3 (PS)
ImGuiKey_GamepadLStickUp = 647,       // [Analog]                                                 // -> ImGuiNavInput_LStickUp
ImGuiKey_GamepadLStickDown = 648,     // [Analog]                                                 // -> ImGuiNavInput_LStickDown
ImGuiKey_GamepadLStickLeft = 649,     // [Analog]                                                 // -> ImGuiNavInput_LStickLeft
ImGuiKey_GamepadLStickRight = 650,    // [Analog]                                                 // -> ImGuiNavInput_LStickRight
ImGuiKey_GamepadRStickUp = 651,       // [Analog]
ImGuiKey_GamepadRStickDown = 652,     // [Analog]
ImGuiKey_GamepadRStickLeft = 653,     // [Analog]
ImGuiKey_GamepadRStickRight = 654,    // [Analog]