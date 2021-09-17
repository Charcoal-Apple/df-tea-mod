## To Do
- [ ] convert jupyter notebooks to hydrogen
  - [ ] update file paths
  - [ ] rerun them
- [ ] (private?) version control! 
  - via Charcoal-Apple ?
- [ ] add to df world, see what works
  - [ ] document
## Project structure
- data lives in `PyDwarf/scripts/charcoalapple/raw`
  - `building_processtea.txt` (has generator)
  - `material_template_teatime` (has generator)

  - `plant_tea_charcoalapple.txt`

  - `item_teatools.txt`
  - `reaction_brew.txt`
  - `reaction_processtea.txt`
  - `GENERATOR ... .txt` contains shortcuts that get expanded (somehow? generic find and replace? python?)

- shortcuts are defined in `PyDwarf/scripts/charcoalapple/raw_aliases`
  - `aliases_buildings.txt`
  - `aliases_material.txt`
  - set up as `KEY : REPLACE_WITH`
    - `KEY` delimted as `<KEY>{default_workshop}<END_KEY>`
    - `REPLACE_WITH` delimited as `<REPLACE_WITH>[DF_STUFF]<END_REPLACE_WITH>`

- `code/`
  - `reaction_generator.ipynb`
  - `reaction_chain_script.ipynb`

- `tile_art/` : supporting art assets
- `reference/` : misc files about tea processing
- `docs/` : screenshots


## Other Scripts
- `amphibiate.py`: makes all aquatic animals amphibious, so you can play as more stuff in adventure mode
- `teatime.py`: loads tea related mods (?)
