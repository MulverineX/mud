# Macro UUID Directory

This is a utility that allows you to run commands directly on entities based on UUID

## Use

to summon an entity directly into the system you can do 

> `execute summon <entity> run function ut:summon {command:"<command to run on this entity every tick>"}`

to register a pre-existing entity into the system you call

> `function ut:summon {command:"<command to run on this entity every tick>"}`

## Other functions

`gu:generate` takes the UUID of the current entity and outputs it into the storage `gu:main out`