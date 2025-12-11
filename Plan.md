FIX1: Removed the dark "flashlight" overlay so the menu stays fully visible(`menu/mainMenu.py`)
      - By removing the draw__black_screen_effect function, fixed it.
    
FIX2: Reworked crater carving to normalize every egournd column isndie the blast radius, eliminating stray pixels (`game_core/ground.py`)

FEAT1: I'd try to add MIRV fire mode on key M; the shell splits into four offset wareheads at apex, each dealing 25% damage, using shared trajectory helper(game_core/game_manager.py and constant.py)

