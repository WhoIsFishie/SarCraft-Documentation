---
tags:
  - lore
  - AXIS
draft: false
---
# DECLASSIFIED SARCRAFT INTELLIGENCE DIRECTIVE

## AXIS OPERATIONS: SEASON 10

**Document No:** S10-AX-OPS-003  
**Classification:** TOP SECRET//NOFORN (Declassified 2025-04-01)  
**Distribution:** AUTHORIZED SARCRAFT PERSONNEL ONLY

> [!warning] DECLASSIFICATION NOTICE
> This document has been declassified by [[Players/WhoIsFishie|WhoIsFishie]], Head of AXIS Operations, effective April 1st, 2025. Unauthorized dissemination of contained information prior to this date remains prohibited under server code §4.18.2.

## 1. EXECUTIVE SUMMARY

This document details secret operations run by AXIS, a hidden group within the [[Factions/Chicken Factory|Chicken Factory]] faction during Season 10. AXIS operated to manipulate server events while keeping their activities hidden.

Their main activities included:

- Mass producing illegal items
- Creating custom mods
- Building weapons of mass destruction
- Exploiting server weaknesses
- Planning targeted assassinations

## 2. ORGANIZATIONAL STRUCTURE

AXIS functioned as a covert group with an undisclosed number of members. Their operational security depended on code words, secure communication channels, and strict information compartmentalization.

### 2.0.1 HIERARCHY

- Leader
- CIA 
- FBI
- Helpers

> [!info] CIA Clearance
> Members with CIA clearance had access to all operational plans and all exploits.

> [!info] FBI Clearance
> Members with FBI clearance had limited access to exploits and mods. Intelligence was shared on a need-to-know basis.

> [!info] Helpers Role
> Helpers were members aware of duplication methods but weren't given complete methods or mods. They assisted with organizing duped items and providing operational support.

### 2.1 SECRET LANGUAGE

The group developed specialized terminology to maintain operational security:

| TERM                | MEANING                           | PURPOSE                                                          |
| ------------------- | --------------------------------- | ---------------------------------------------------------------- |
| COLLECTION          | Duplicating items                 | Prevent accidental references to duplication exploits            |
| FLIP                | Activating a pearl stasis chamber | Code for teleporting players                                     |
| Enhanced Individual | Hacked Player                     | Reference to players using unauthorized modifications            |
| CHILD               | PRINCIPLE OF AIS                  | Reference to the alternate account that simulated a young player |
| MAGIC CARPET        | Boat Fly                          | Reference to enhanced transportation methods                     |

## 3. EXPLOITS AND HACKS
### 3.1 DOG EXPLOIT

[[Players/WhoIsFishie|WhoIsFishie]] identified a significant vulnerability in a classified mod during test server evaluations.

#### 3.1.1 The Pirate Exploit

The initial version of this exploit operated as follows:

1. Place a dog on water
2. Open the dog's inventory
3. Boat away 250-300 blocks while keeping the inventory open
4. Take items out
5. Come back to the dog

The exploit worked because the DOG would unload from memory at sufficient distance, while you boat away. This prevented the dog from recognizing that items had been removed from its inventory.

#### 3.1.2 Groomer Method

The team discovered an enhanced technique - using sheers on a dog would separate the inventory while maintaining item accessibility.

Two implementation methods were developed:

- **Two-player method:** One player accesses the inventory while another player applies sheer to the dog
- **Solo method:** A single player performs both actions in rapid succession (requiring precise timing)

### 3.2 dog_days.jar

A team member suggested that [[Players/WhoIsFishie|WhoIsFishie]] create a specialized mod to manage these interactions. Within three hours, a custom tool named `dog_days.jar` was developed.

This modification allowed for such rapid item collection that standard hopper systems would become overwhelmed.

A specialized collection station was constructed to automatically collect dropped items:

![[collection_station.webp]]

The team enhanced efficiency through specialized roles:

- Prep team: Prepared, named, and color-coded shulkers with items for collection
- Duper: Operated the collection mod while positioned at the dog
- Organizer: Managed collected items to prevent system congestion

Later versions of the mod supported fully automated operation with simple command activation.

### 3.3 OTHER DUPES

*pending declassification* 

### 3.4 TELEPORTATION

Research began on a teleportation system that would allow players to travel to specific locations by looking at specific coords which would lead to a enderpearl being loaded

This technology was being developed by [[Players/WhoIsFishie|WhoIsFishie]] and ==REDACTED MEMBER==

> [!note] Teleportation Function
> If successfully implemented, this system would have provided functionality equivalent to a `/home` command without administrative permission.

## 4. SECRET BASES

### 4.1 EXPLOIT ISLAND

![[exploit_island1.jpg]]

A secure location north of the [[Factions/Chicken Factory|Chicken Factory]] base served as the primary site for AXIS covert activities. This location was selected for several strategic advantages:

- Water surroundings (required for the original collection method)
- Distance from player activity
- Natural terrain features that minimized the need for suspicious modifications

This island witnessed the first successful admin command breach when [[Players/WhoIsFishie|WhoIsFishie]] generated a lightning strike during clear weather. This demonstration confirmed to the team that server security had been compromised.

The team later stored unauthorized items in item frames to avoid detection by ESP hacks or administrative inventory checks.

### 4.2 Seed Vault

The Seed Vault, named after the Svalbard Global Seed Vault (Norway), was established as a classified repository deep within the icy mountains of Sarcraft. A single dog named "Condom" was stationed at this location.

> [!info] Seed Vault Purpose
> The dog carried a chest containing a backup of every illegal item, securing these assets against potential administrative purges.
> 
> The name "Condom" referenced the dog's role as a protective layer between AXIS operations and administrative detection when transporting illegal items that couldn't be stored in player inventories or ender chests.

The name also served as wordplay that amused team members.

### 4.3 AXIS HIDEOUT

![[AXIS HIDEOUT.webp]]  

![[AXIS HIDEOUT1.webp]]

[[Players/WhoIsFishie|WhoIsFishie]] converted a drained ocean monument near Exploit Island into a storage facility with several features:

- The draining process increased guardian spawns outside the structure, creating a natural security system
- The facility housed stasis chambers and collection stations
- Numerous illegal items were stored at this location

![[stash_house.jpg]]

This base was later abandoned due to security concerns and was considered a prototype for more secure facilities.

![[stash_house_damaged.jpg]]

### 4.4 Fishie's Base

*pending declassification* 

![[collection_storage.webp]]

![[collection_station2.webp]]


## 5. SERVER BACKDOOR ACCESS

Following the discovery of the [[Lore/Exploits#Telegram Command Injection|Telegram Command Injection]], administrators disabled the Minecraft-to-Telegram chat bridge to prevent anyone from abusing the exploit.

> [!important] Critical Security Oversight
> Administrators  ailed to recognize that the exploit actually operated through the Telegram-to-Minecraft bridge. This meant they closed the wrong communication channel, leaving the vulnerability completely intact and even harder to detect.

Initial testing took place on Exploit Island, but operations shifted unexpectedly when [[Players/WhoIsFishie|WhoIsFishie]] had to log off due to a medical emergency. Operations continued uninterrupted, with [[Players/WhoIsFishie|WhoIsFishie]] coordinating with the team while executing server commands from a hospital via mobile device, demonstrating the exploit's versatility.

During this period, AXIS maintained extensive server control capabilities, including:
### Surveillance Capabilities 
- Real-time player login tracking
- Comprehensive position monitoring without detection 

![[ibat_coord_leak_command.png]]

### Manufactured Illegal Items 
The team created numerous unauthorized items documented in server evidence: 

1. **Self-Deleting Ender Chests** 
- Modified ender chests programmed to delete upon player death 
- [[Players/Perhaps|Perhaps]] received 64 of these ([[Seasons/Season 10/Evidence/Evidence Catalog#Exhibit M - Perhaps' Multiple Ender Chests|Exhibit M - Perhaps' Multiple Ender Chests]]) 

2. **Spawning Tools** 
- Elder guardian eggs, with 64 provided to [[Players/Perhaps|Perhaps]] ([[Seasons/Season 10/Evidence/Evidence Catalog#Exhibit N - Perhaps' Guardian Eggs|Exhibit N - Perhaps' Guardian Eggs]]) 

![[fishie_running_commands.png]]

3. **Weaponry** - [[Lore/Exploits#cokestone|cokestone]] 
- A diamond sword with impossible enchantment was given to [[Players/Perhaps|Perhaps]] and documented in [[Seasons/Season 10/Evidence/Evidence Catalog#Exhibit K - Perhaps' Hacked Weapon|Exhibit K - Perhaps' Hacked Weapon]] 
- One-hit kill bow (created during this period but not documented in evidence) 

![[CockStone_hacked_Sword.jpg]]
![[stoneCock_onehit_bow.jpg]]

4. **Armor** - [[Lore/Exploits#Hacked Helmet|Hacked Helmet]] for [[Players/Anoojfunaid|Anoojfunaid]] ([[Seasons/Season 10/Evidence/Evidence Catalog#Exhibit P - Anooj's Hacked Helmet|Exhibit P - Anooj's Hacked Helmet]] and [[Seasons/Season 10/Evidence/Evidence Catalog#Exhibit U - Admin Evidence of Hacked Helmet|Exhibit U - Admin Evidence of Hacked Helmet]]) 
![[admin_finds_hacked_helmet_beloning_to_anooj.jpg]]


- Diamond chestplate with Protection 100, Thorns 100, and Unbreaking 100 for [[Players/Perhaps|Perhaps]] ([[Seasons/Season 10/Evidence/Evidence Catalog#Exhibit O - Perhaps' Hacked Chestplate|Exhibit O - Perhaps' Hacked Chestplate]]) 
	![[hacked_chestplate.jpg]]

> [!info] Item Manufacturing
> Exploit Island served as the production center for these unauthorized items. With [[Players/WhoIsFishie|WhoIsFishie]] coordinating remotely via mobile device from the hospital, the team maintained production and distribution operations throughout this period.

### Administrative Access

Using the same exploit, AXIS gained operator privileges: 
- Two randomly selected players were temporarily granted administrative access, with plans to manipulate them into executing specific commands
- This strategy ultimately failed when server permissions were reset during recovery efforts
 
The exploit was particularly effective because executed commands appeared to originate from the server itself rather than individual players, complicating administrative tracking.

### Patched Backdoor

Discussions occurred between [[Players/WhoIsFishie|WhoIsFishie]] and [[Players/FlameXode|FlameXode]] regarding a potential backdoor in authentication plugin updates.
The security status of the updated plugin remains unconfirmed.

### Shadow Server

> [!info] Server Protection Measures
> Administrators implemented anti-xray modifications and structure offset plugins to prevent seed cracking attempts during the season, but AXIS persisted in their efforts.

The server seed was extracted using administrative access, and work began on reversing the structure offset plugin. When this proved challenging, the team opted to download the entire world file instead.

This investigation led to the discovery of the [[Lore/Ocean Monument Conspiracy|Ocean Monument Conspiracy]].
Analysis revealed that when the plugin offset a structure to an invalid ocean location, it would default to spawning an ocean monument instead.

The world download was subsequently used for testing builds in creative mode before implementation on the live server.

## 6. SPY OPERATIONS
### 6.1 PRINCIPLE OF AIS (Artificial Intelligent Shihaam)

[[Players/PrincipleOf_AIS|PrincipleOf_AIS]] functioned as a remote account for intelligence gathering. This account maintained no connection to primary accounts and operated from separate IP addresses. Most activity on this account was automated to establish behavioral patterns.

A disposable Telegram account was used to obtain server whitelist access.

#### 6.1.1 RECON MISSIONS

AIS was deployed to [[Players/iBattus|iBattus]]'s base since no AXIS member could visit without explaining how they located it.

![[recon_screenshot.jpg]]

This strategy exceeded expectations because:

- AIS documented [[Players/Ssahan|Ssahan]] and [[Players/iBattus|iBattus]] using unauthorized jetpack and no-fall modifications
- [[Players/Ssahan|Ssahan]]'s elimination of AIS outside their base boundaries provided AIS with justification for complaint
- This provided a legitimate reason to disclose coordinates and gave the factory valid grounds to investigate the base

![[6k_6k.png]]

AIS also tracked [[Players/yeetuz|yeetuz]] and identified [[Factions/The Alliance|The Alliance]]'s hidden storage at coordinates 6000, 6000.

#### 6.1.2 SERVER MAPPING PROJECT

![[server_mapping_project.jpg]]

AIS was utilized to develop a comprehensive server map by:

- Systematically exploring the server
- Loading chunks to generate a complete map
- Creating detailed files showing the server layout

By project completion, more than 70% of the server had been mapped, with map files approaching 1GB in size.

### 6.2 OTHER SPY TOOLS
#### 6.2.1 PET OWNER TRACKER

![[pet_owner_mod.jpg]]

[[Players/WhoIsFishie|WhoIsFishie]] developed a modification that revealed the UUID (unique identifier) of pet owners.

The team would monitor player logins, record their UUIDs, and use this information to locate bases by identifying tamed animals with matching UUIDs.

#### 6.2.2 PLAYER SCHEDULE TRACKING

> [!info] Advanced Analytics
> The team developed a sophisticated data analysis system by processing the Telegram group chat history.

- Raw data extraction from Telegram logs
- Custom data processing scripts for JSON export cleaning
- Visualization tools for activity pattern analysis
- Capability to identify peak activity periods for individuals and factions

This analytical system enabled the team to:
- Identify optimal exploration windows when specific players were offline
- Schedule "collection missions" during lower-risk timeframes
- Plan operations around known activity patterns of potential opposition

The visualization component was crucial for strategic planning, converting temporal data into actionable intelligence about server activity.

This project was discontinued after [[Players/iBattus|iBattus]] left the server, as he had been a primary surveillance target.

#### 6.2.3 LightMap

![[server_lightmapping_project.jpg]]

[[Players/WhoIsFishie|WhoIsFishie]] developed an image processing technique to locate bases using server map exports.

The light map project processed map data from the server mapping initiative and rendered it at maximum resolution during night time.

This highlighted areas with artificial light sources on the map.

The process filtered out orange-colored light sources to prevent lava pools from being misidentified as potential bases.

After applying multiple color filters, the remaining pixels were marked with green rings.

By analyzing the clustering of these green indicators, the team could quickly identify areas of interest and locate bases.

## 7. PLOTS

AXIS developed multiple targeted operation plans.

#### Yeetuz Double Agent Psyop
[[yeetuz]] would have his own pearl stasis at all axis and chicken factory bases to make it look like hes a double agent. [[WhoIsFishie]] would also carry a fake diary that speaks of yeetuz's double agent work. all this was meant to be seen by [[iBattus]] and cause him to doubt 

#### Book Ban

> [!info] Combat Log Countermeasure
> AXIS established a contingency plan for [[Players/iBattus|iBattus]]'s combat logging through implementation of the book ban method.

This technique forces client disconnection by overloading a player's inventory with excessive data.

The plan called for placing numerous custom books at [[Players/iBattus|iBattus]]'s logout location if he attempted to combat log. Upon login, he would automatically collect these items and be disconnected from the server.

Only administrative inventory clearing could resolve this situation.

#### Anooj Wedding Bombing

![[idk.jpg]]

Contingency plans were developed to blow up [[Players/Anoojfunaid|Anoojfunaid]]'s wedding venue and blame it on [[Factions/The Alliance|The Alliance]].

#### Ibattus Killer 3000

The team developed multiple methods to eliminate [[Factions/The Alliance|The Alliance]] members, including:

- Unauthorized weapons
- Enhanced mace attacks

Plans to use illegal weapons were abandoned when it was discovered that players could inspect chat message item enchantments.

Later planning focused on TNT minecart deployment.

#### Ibattus Killer 6000

> [!important] Legal WMD
> During [[Players/Ssahan|Ssahan]]'s detainment, AXIS constructed a technically legal weapon of mass destruction targeting [[Players/iBattus|iBattus]].

This involved a specialized Mace capable of eliminating a player wearing enchanted diamond armor in a single strike. The weapon system included not just the Mace but also a designated operator who trained extensively with it to maximize effectiveness. A Telegram plugin vulnerability prevented mace eliminations from appearing in chat, allowing covert training. Within hours of acquiring the mace, it was fully enchanted and the operator had mastered timing adjustments for server latency.

AXIS successfully developed both a legal weapon and a qualified operative to deploy it.

#### Crossed-Bow

While reviewing modification documentation, [[WhoIsFishie]] identified a new enchantment called Ghasted that appeared exclusively in rare nether dungeons.

After several days of nether exploration, [[WhoIsFishie]] returned with a Ghasted III enchanted book, enabling crossbows to fire ghast fireballs.

![[ghasted.jpg]]

This weapon, when properly deployed, could launch multiple players airborne and create significant tactical confusion due to its rarity.

#### Ban Chunk

Another strategy involved creating "ban chunks" - areas filled with excessive data that prevented player entry or exit.

[[Players/WhoIsFishie|WhoIsFishie]] first observed this phenomenon when experiencing increased latency in [[Players/StrawBwabii|StrawBwabii]]'s residence.

Investigation revealed the house contained numerous high-resolution photographs taken with the camera modification.

Analysis confirmed that images were stored at full resolution with minimal compression, suggesting a potential vulnerability.

The proposed implementation method included:
- Creating a custom large images with custom metadata
- Reverse engineering the camera mod to create a modified version with capabilities to:
  - Upload custom images
  - Mass-place these images
  - Suppress client-side rendering
- Distributing this modified version to authorized personnel
- Constructing a chunk barrier to automatically restrict unauthorized access

This approach works because players without the modified camera mod would experience severe lag from processing the excessive data, effectively creating a chunk-based access restriction.

#### 6k6k Bombing 

Following the discovery of [[Factions/The Alliance|The Alliance]]'s storage at coordinates 6000, 6000, operational planning discussions occurred.

The proposed operation involved placing trapped chests connected to sufficient TNT to destroy the entire chunk.

The team determined that maintaining surveillance secrecy outweighed immediate tactical advantages.

#### [[Factions/The Alliance|The Alliance]] Base

Team members received instructions to target [[Factions/The Alliance|The Alliance]] base for destructive operations following [[Players/WhoIsFishie|WhoIsFishie]]'s server ban. The order included instructions to withdraw if a judicial system was established.

#### Dragon Heist 

> [!info] Egg Security
> To prevent another egg interception, a specialized mechanism was designed to manipulate dragon egg placement, ensuring [[Players/WhoIsFishie|WhoIsFishie]] would secure it regardless of player positioning.

![[dragon_death6.webp]]

AXIS developed a system to control egg placement following dragon elimination.

---

**AUTHENTICATION CODE:** AX-S10-DELTA-775  
**AUTHORIZATION:** FISHIE  
**DECLASSIFICATION DATE:** 2025-04-01

[END OF DOCUMENT]