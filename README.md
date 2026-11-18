# MAT Online - Original Game Structure

## ORIGINAL FOLDER STRUCTURE
- Animations\     - Game animations
- KarmaData\      - Physics data
- Launch\         - Launcher files
- Maps\           - Game maps
- Music\          - Game music
- Sounds\         - Game sounds
- StaticMeshes\   - 3D models
- System\         - Game system files (MAIN VULNERABILITY TARGETS)
- Textures\       - Game textures

## MAIN VULNERABILITY FILES
### System\ folder:
- KFXGame.u           - Damage calculation functions
- KFXWeapons.u        - Weapon damage values
- KFXConquerGame.ini  - Damage formulas (encrypted)
- crypt.dll           - Config encryption
- MAT.exe             - Main executable
- acdc.dat            - Anti-cheat system

### Root files:
- AttackOnline.exe    - Game launcher
- local.ini           - Server configuration
- MATOnline.dll       - Core game module

## SECURITY ANALYSIS
Study these original file locations for security improvements.
