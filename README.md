# ActorRuntime
Behavioral actor runtime where agents propose and express outcomes without owning world authority.

Actor Runtime is a behavioral layer for NPCs that separates perception and expression from world authority. Actors operate within structural constraints, proposing intents and expressing approved outcomes without owning simulation truth.
Purpose
Actor Runtime defines stable behavior through fixed identity, bounded knowledge, and behavioral inertia. It enables consistent interaction patterns while preventing actors from controlling world state or governance decisions.
Core Principles
Actors propose actions but never commit state changes.
Behavior is constrained by identity passport and knowledge scope.
Expression is separated from world decision-making.
LLMs act only as proposer and performer, never as a source of truth.
The layer remains domain-agnostic.
High-Level Architecture
Actor Runtime interprets structural outcomes produced by external governance layers and translates them into behavior and expression. It operates above execution governance and does not participate in arbitration or simulation updates.
What Actor Runtime Is Not
not a simulation controller;
not an arbitration layer;
not a truth authority;
not an agent orchestration framework.
Applicability
NPC systems, social simulations, agent interfaces, persistent worlds, and multi-agent environments requiring constrained behavior without granting actors authority over world state.
