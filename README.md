# GMC-ALS
## Blueprint version of Advanced Locomotion System port into General Movement Component
https://github.com/Dixon6/GMC-ALS/assets/103589964/6f5ca87f-d0f1-4211-adfe-8fd757289905

## Install Steps
Be sure to have GMCv2 V2 from the FAB store. Works in UE 5.5
[FAB Link](https://www.fab.com/listings/7e786da1-35e1-458e-96e0-7b1bdb333b39)
1. Download Zip.
2. Extract "GMC-ALS-Demo" to your projects folder.
3. Launch the .uproject file.
5. Go to the content drawer settings and enable "Show plugin content".
   
The GMC Pawn and Component is found inside "Plugins/ALSReplicatedContent/AdvancedLocomotionV4/Blueprints/CharacterLogic".

____________________________________
### Here are the remaining issues I am trying to fix/implement:
      
**Turn in Place:**
- Need to fix the feet's animation twisting too much.
   
**Ragdoll/Get Up:**
- Ragdoll is now set but still lacks a bit of polish. Using an impulse on the mesh to keep it alligned with the root which can feel a bit unatural right now.
