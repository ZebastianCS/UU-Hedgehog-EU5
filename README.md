# A collection of UU developed mods for UU MP Gameplay and Balancing

## Current Features:

- Global
  - General
    - Removed crownpower malus from having debt
    - Expensive education upfront cost removed, 3% cost of court instead
    - Max fort limit from number of locations halved
    - Stability cost of deleting markets reduced to 10
    - Base diplo-annexation cost changed from 200 to 125
    - GP score from country ranks halved
    - Rivers now visible in Road/Road Builder mapmodes
  - Multiplayer/Combat
    - Removed hour ticks, combat adjusted accordingly
    - Low relations no longer blocks players from forming alliances
    - Secure Flanks bonus for infantry changed to 35% from 5%
    - Correct Section chance set to 100%
    - Players cannot have forts on adjacent locations
  - Societal Values and Advances
    - Offensive gives up to +20% siege ability and assault ability, and -10% fort defense
    - Defensive gives up to +33% fort defense, and -10% siege ability. No longer affects army movement speed. 
    - Age of Renaissance diplo focus buffed: +2.5% income from vassals, +250 trade range
    - Theocracy mil tactics advance increase from 0.025 to 0.1
- Regional
  - Asia
    - Ottomans starts with every location cored
    - Players can't become a Middle Kingdom tributary or get money from them
    - Delhi disaster now releases Jaunpur, Malwa, Gujarat, Bahmanis as independent nations
  - W. Europe
    - Added strait crossing between Calais and Dover
    - Western Schism Removed, PAP French Cardinals privilege removed (Hussite wars can still occur)
    - France and England can't hold parliament until the end of the 100yr War
    - Flanders starts independent and as an HRE prince
    - Brittany is a vassal of England instead of France
    - French unique govt. reforms both give 1 cultures_capacity
    - Catholics can form Empires
    - HRE imperial manpower contribution has been reduced to 1/5th of vanilla
    - Naples event for succession law now fires immediately on game start
  - E. Europe
    - Czech culture removed from German culture Group
    - Bohemian regional silver and 2 gold removed. Added 1 gold in Berchtesgaten, 1 silver in Prüm
    - Silesia starts independent and united, and outside the HRE
  - Africa
    - Morocco starts with every location cored




## Temporary features:

- Monthly literacy gain rate increased to 10x, until the new pops literacy bug is fixed


## Integration of mods:

- LazyIcarus' **Expanded Build View**
  - *NOTE: Temporarily removed for 1.1.0 Update*
  - Files changed (1):
    - in_game\gui\build_location_lateralview_expanded.gui
- Mazutaki's **Dense Tech Tree**
  - Files changed (1):
    - in_game\gui\technology_lateralview.gui
- nqwery's **Remove Start Game Smoke Effect**
  - Files changed (8):
    - main_menu\gfx\interface\animations\enter_game_smoke_center.dds
    - main_menu\gfx\interface\animations\enter_game_smoke_left.dds
    - main_menu\gfx\interface\animations\enter_game_smoke_right.dds
    - main_menu\gfx\interface\animations\enter_game_smoke_mask.dds
    - main_menu\gfx\interface\animations\rotate_glow_mask.dds
    - main_menu\gfx\interface\animations\standard_appear_effect_animated_mask.dds
    - main_menu\gfx\interface\animations\standard_appear_effect_texture.dds
    - main_menu\gfx\interface\animations\standard_appear_effect_texture_mask.dds
- Zorange's **Mapmodes Collection**
  - *NOTE: Average Literacy and Location Size mapmodes not included*
  - Files changed (21): 
    - in_game\common\on_action\zmc_on_game_start.txt
    - in_game\common\script_values\zmc_urbanisation_suitability_calc.txt
    - in_game\common\script_values\zmc_used_building_slots_percentage.txt
    - in_game\events\zmc_debug\zmc_debug_events.txt
    - in_game\gfx\map\map_modes\zmc_map_modes.txt
    - in_game\gui\zmc_textformatting.gui
    - main_menu\common\game_concepts\zmc_concepts.txt
    - main_menu\gfx\interface\icons\map_modes\zmc_building_cap_percentage.dds
    - main_menu\gfx\interface\icons\map_modes\zmc_control_difference.dds
    - main_menu\gfx\interface\icons\map_modes\zmc_control_times_market_access.dds
    - main_menu\gfx\interface\icons\map_modes\zmc_local_monthly_development.dds
    - main_menu\gfx\interface\icons\map_modes\zmc_local_production_efficiency.dds
    - main_menu\gfx\interface\icons\map_modes\zmc_pop_cap.dds
    - main_menu\gfx\interface\icons\map_modes\zmc_pop_cap_percentage.dds
    - main_menu\gfx\interface\icons\map_modes\zmc_pop_growth_percentage.dds
    - main_menu\gfx\interface\icons\map_modes\zmc_province_tax_base.dds
    - main_menu\gfx\interface\icons\map_modes\zmc_tax_base_per_population.dds
    - main_menu\gfx\interface\icons\map_modes\zmc_time_until_100_development.dds
    - main_menu\gfx\interface\icons\map_modes\zmc_urbanisation_suitability.dds
    - main_menu\gui\zmc_textformatting.gui
    - main_menu\localization\english\zmc_loc_l_english.yml

# Working in this Repo

### Please create a new branch to make your changes in. When you have completed your branch and want to merge them into everyone elses changes please create a Pull Request and add a few Discord members as reviewers. 
### This helps us keep our code clean and reduces conflicts between peoples changes.
