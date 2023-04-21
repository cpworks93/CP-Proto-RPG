# CP-Proto-RPG-Set

Simple Casual RPG Proto
Vertical Top View 2D / 3D RPG.




# Architencure
## ECS

### Entity

1. PlayerEntity
2. MonsterEntity

### Component

1. RegisterComponent
2. InputComponent
3. ActionComponent
4. MovementComponent
5. StatusComponent
6. DamageComponent
7. TargetComponent

### System

#### ControlSystems
1. ManualControlSystem
2. AIControlSystem

#### EventSystems 
1. ActionSystem   - InputComponent / ActionComponent / Controller Event
2. MovementSystem - InputComponent / MovementComponent / Controller Event
3. StatusSystem   - StatusComponent / DamageComponent / Status Event / Damage Event
4. TargetSystem   - InputComponent / TargetComponent / Controller Event

---
## MVVM

### User Data Models
#### AccountData
#### SkillData

### UI View Models
#### WorldHUD
