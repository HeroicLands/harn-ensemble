---
tags:
  - character
name:
  full: Kora of Serdica
  title: ""
  given: Kora
  clan: Serdica
  aliases: []
id: jW8F24E2EwEro9xh
packFolder: fffunguilded
shortcode: koraofserdica
type: being
social:
  occupation: Wise Woman
  class: freeman
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual:
    - "custom|Old Jarin"
data:
  icon: fff4991tok
  templatePriority: 1
  gender: female
  species: human
  age: 59
  birthday: 660/11/24
  height: 1.55
  weight: 49.9
  frame: medium
  appearance:
    eye_color: blue
    hair_color: grey
    skin_color: medium
    complexion: attractive
    extra_features:
      - Hand tremor
hm3:
  type: character
  attributes:
    str: 10
    sta: 13
    dex: 11
    agl: 9
    int: 15
    aur: 12
    wil: 14
    eye: 12
    hrg: 13
    sml: 12
    voi: 15
    cml: 15
    mor: 14
  items:
    - { shortcode: skull, type: armorlocation }
    - { shortcode: face, type: armorlocation }
    - { shortcode: neck, type: armorlocation }
    - { shortcode: lshoulder, type: armorlocation }
    - { shortcode: rshoulder, type: armorlocation }
    - { shortcode: luparm, type: armorlocation }
    - { shortcode: ruparm, type: armorlocation }
    - { shortcode: lelb, type: armorlocation }
    - { shortcode: relb, type: armorlocation }
    - { shortcode: lhand, type: armorlocation }
    - { shortcode: rhand, type: armorlocation }
    - { shortcode: thorax, type: armorlocation }
    - { shortcode: abdm, type: armorlocation }
    - { shortcode: groin, type: armorlocation }
    - { shortcode: lhip, type: armorlocation }
    - { shortcode: rhip, type: armorlocation }
    - { shortcode: lthigh, type: armorlocation }
    - { shortcode: rthigh, type: armorlocation }
    - { shortcode: lknee, type: armorlocation }
    - { shortcode: rknee, type: armorlocation }
    - { shortcode: lcalf, type: armorlocation }
    - { shortcode: rcalf, type: armorlocation }
    - { shortcode: lfoot, type: armorlocation }
    - { shortcode: rfoot, type: armorlocation }
    - { shortcode: climbing, type: skill, system: { masteryLevel: 38, skillBase: { value: 10 } } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 64, skillBase: { value: 13 } } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 34, skillBase: { value: 9 } } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 25, skillBase: { value: 12 } } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 44, skillBase: { value: 11 } } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 52, skillBase: { value: 12 } } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 83, skillBase: { value: 14 } } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 31, skillBase: { value: 15 } } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 75, skillBase: { value: 15 } } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 47, skillBase: { value: 15 } } }
    - shortcode: language
      type: skill
      name: "Language: Jarinese (Pagaelin)"
      system:
        masteryLevel: 56
        skillBase:
          value: 15
    - shortcode: language
      type: skill
      name: "Language: Jarinese (Bujoc)"
      system:
        masteryLevel: 68
        skillBase:
          value: 15
    - shortcode: language
      type: skill
      name: "Language: Jarinese (Hodiri)"
      system:
        masteryLevel: 47
        skillBase:
          value: 15
    - name: Old Jarin
      type: skill
      data:
        icon: sohl-none-icon-circle
      system:
        type: Ritual
        skillBase.value: 15
        masteryLevel: 75
        ritual.piety: 98
        skillBase:
          value: 15
    - { shortcode: initiative, type: skill, system: { masteryLevel: 48, skillBase: { value: 12 } } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 46, skillBase: { value: 12 } } }
    - { shortcode: dodge, type: skill, system: { masteryLevel: 45, skillBase: { value: 9 } } }
    - { shortcode: club, type: skill, system: { masteryLevel: 58, skillBase: { value: 10 } } }
    - { shortcode: astrology, type: skill, system: { masteryLevel: 45, skillBase: { value: 13 } } }
    - { shortcode: folklore, type: skill, system: { masteryLevel: 115, skillBase: { value: 15 } } }
    - { shortcode: foraging, type: skill, system: { masteryLevel: 71, skillBase: { value: 13 } } }
    - { shortcode: herblore, type: skill, system: { masteryLevel: 98, skillBase: { value: 13 } } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 86, skillBase: { value: 15 } } }
    - { shortcode: survival, type: skill, system: { masteryLevel: 88, skillBase: { value: 12 } } }
    - shortcode: weatherlore
      type: skill
      system:
        masteryLevel: 56
        skillBase:
          value: 14
    - { shortcode: Clb, type: weapongear }
    - { shortcode: beltpouchl3, type: containergear }
    - { shortcode: LRobe, type: armorgear }
    - { shortcode: CvCloak, type: armorgear }
    - { shortcode: CHood, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: pence, type: miscgear, system: { quantity: 24 } }
  system:
    sunsign: masara
    move: 9
sohl:
  kbcat: archetype
  items:
    - { model: attribute-str, system: { scoreBase: 10 } }
    - { model: attribute-end, system: { scoreBase: 13 } }
    - { model: attribute-dex, system: { scoreBase: 11 } }
    - { model: attribute-agl, system: { scoreBase: 9 } }
    - { model: attribute-per, system: { scoreBase: 13 } }
    - { model: attribute-snt, system: { scoreBase: 12 } }
    - { model: attribute-cml, system: { scoreBase: 15 } }
    - { model: attribute-aur, system: { scoreBase: 12 } }
    - { model: attribute-wil, system: { scoreBase: 14 } }
    - { model: attribute-rea, system: { scoreBase: 15 } }
    - { model: attribute-cre, system: { scoreBase: 16 } }
    - { model: attribute-emp, system: { scoreBase: 11 } }
    - { model: attribute-elo, system: { scoreBase: 15 } }
    - { model: attribute-mor, system: { scoreBase: 14 } }
    - { model: attribute-voi, system: { scoreBase: 15 } }
    - { model: skill-archery }
    - { model: skill-awar, system: { masteryLevelBase: 52 } }
    - { model: skill-chrm }
    - { model: skill-clmb, system: { masteryLevelBase: 38 } }
    - { model: skill-cmd }
    - { model: skill-cook }
    - { model: skill-dnce }
    - { model: skill-dscr }
    - { model: skill-draw }
    - { model: skill-folklr, system: { masteryLevelBase: 115 } }
    - { model: skill-guil }
    - { model: skill-init, system: { masteryLevelBase: 48 } }
    - { model: skill-shok }
    - { model: skill-intr, system: { masteryLevelBase: 83 } }
    - { model: skill-jump, system: { masteryLevelBase: 34 } }
    - { model: skill-melee, system: { masteryLevelBase: 58 } }
    - { model: skill-dge, system: { masteryLevelBase: 45 } }
    - { model: skill-pysn, system: { masteryLevelBase: 86 } }
    - { model: skill-ridg }
    - { model: skill-sing, system: { masteryLevelBase: 47 } }
    - { model: skill-stlth, system: { masteryLevelBase: 25 } }
    - { model: skill-srvl, system: { masteryLevelBase: 88 } }
    - { model: skill-spirit }
    - { model: skill-swim }
    - { model: skill-thtcs }
    - { model: skill-thro, system: { masteryLevelBase: 44 } }
    - { model: skill-bflkbite }
    - { model: skill-bflkgrab }
    - { model: skill-bflkheadbutt }
    - { model: skill-bflkkick }
    - { model: skill-limbblock }
    - { model: skill-press }
    - { model: skill-bflkpunch }
    - { model: skill-trip }
    - { model: mysticalability-sprt }
    - model: skill-lang
      name: "Language: Jarinese (Hodiri)"
      system:
        masteryLevelBase: 47
    - { model: mysticalability-astr, system: { masteryLevelBase: 45 } }
    - { model: skill-herb, system: { masteryLevelBase: 98 } }
    - { model: weapongear-Clb }
    - { model: containergear-beltpouchl3 }
    - { model: armorgear-LRobe }
    - { model: armorgear-CvCloak }
    - { model: armorgear-CHood }
    - { model: armorgear-LtShoe }
    - { model: miscgear-pence, system: { quantity: 24 } }
  system:
    body:
      structure:
        zones:
          - name: Head
            shortcode: headzone
            probWeight: 1
          - name: Arms
            shortcode: armszone
            probWeight: 4
          - name: Torso
            shortcode: torsozone
            probWeight: 4
          - name: Legs
            shortcode: legszone
            probWeight: 6
        parts:
          - name: Head
            shortcode: headpart
            bodyZoneCode: headzone
            roles:
              - vital
            canHoldItem: false
            probWeight: 1
          - name: Right Arm
            shortcode: rarmpart
            bodyZoneCode: armszone
            roles:
              - manipulator
            canHoldItem: true
            probWeight: 2
          - name: Left Arm
            shortcode: larmpart
            bodyZoneCode: armszone
            roles:
              - manipulator
            canHoldItem: true
            probWeight: 2
          - name: Torso
            shortcode: torsopart
            bodyZoneCode: torsozone
            roles:
              - core
            canHoldItem: false
            probWeight: 4
          - name: Right Leg
            shortcode: rlegpart
            bodyZoneCode: legszone
            roles:
              - locomotor
            canHoldItem: false
            probWeight: 3
          - name: Left Leg
            shortcode: llegpart
            bodyZoneCode: legszone
            roles:
              - locomotor
            canHoldItem: false
            probWeight: 3
        locations:
          - name: Skull
            shortcode: skullloc
            bodyPartCode: headpart
            bleedingSusceptibility: low
            amputability: none
            shockValue: 5
            probWeight: 500
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Left Eye
            shortcode: leyeloc
            bodyPartCode: headpart
            bleedingSusceptibility: medium
            amputability: none
            shockValue: 5
            probWeight: 15
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Right Eye
            shortcode: reyeloc
            bodyPartCode: headpart
            bleedingSusceptibility: medium
            amputability: none
            shockValue: 5
            probWeight: 15
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Nose
            shortcode: noseloc
            bodyPartCode: headpart
            bleedingSusceptibility: medium
            amputability: none
            shockValue: 5
            probWeight: 30
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Left Cheek
            shortcode: lcheekloc
            bodyPartCode: headpart
            bleedingSusceptibility: medium
            amputability: none
            shockValue: 4
            probWeight: 60
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Right Cheek
            shortcode: rcheekloc
            bodyPartCode: headpart
            bleedingSusceptibility: medium
            amputability: none
            shockValue: 4
            probWeight: 60
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Left Ear
            shortcode: learloc
            bodyPartCode: headpart
            bleedingSusceptibility: medium
            amputability: none
            shockValue: 4
            probWeight: 15
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Right Ear
            shortcode: rearloc
            bodyPartCode: headpart
            bleedingSusceptibility: medium
            amputability: none
            shockValue: 4
            probWeight: 15
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Mouth
            shortcode: mouthloc
            bodyPartCode: headpart
            bleedingSusceptibility: medium
            amputability: none
            shockValue: 4
            probWeight: 30
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Jaw
            shortcode: jawloc
            bodyPartCode: headpart
            bleedingSusceptibility: medium
            amputability: none
            shockValue: 4
            probWeight: 60
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Neck
            shortcode: neckloc
            bodyPartCode: headpart
            bleedingSusceptibility: high
            amputability: low
            shockValue: 5
            probWeight: 200
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Right Shoulder
            shortcode: rshldloc
            bodyPartCode: rarmpart
            bleedingSusceptibility: medium
            amputability: none
            shockValue: 3
            probWeight: 30
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Right Upper Arm
            shortcode: rupaloc
            bodyPartCode: rarmpart
            bleedingSusceptibility: low
            amputability: medium
            shockValue: 1
            probWeight: 30
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Right Elbow
            shortcode: relbloc
            bodyPartCode: rarmpart
            bleedingSusceptibility: low
            amputability: medium
            shockValue: 2
            probWeight: 10
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Right Forearm
            shortcode: rfraloc
            bodyPartCode: rarmpart
            bleedingSusceptibility: low
            amputability: medium
            shockValue: 1
            probWeight: 20
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Right Hand
            shortcode: rhandloc
            bodyPartCode: rarmpart
            bleedingSusceptibility: none
            amputability: high
            shockValue: 2
            probWeight: 10
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Left Shoulder
            shortcode: lshldloc
            bodyPartCode: larmpart
            bleedingSusceptibility: medium
            amputability: none
            shockValue: 3
            probWeight: 30
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Left Upper Arm
            shortcode: lupaloc
            bodyPartCode: larmpart
            bleedingSusceptibility: low
            amputability: medium
            shockValue: 1
            probWeight: 30
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Left Elbow
            shortcode: lelbloc
            bodyPartCode: larmpart
            bleedingSusceptibility: low
            amputability: medium
            shockValue: 2
            probWeight: 10
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Left Forearm
            shortcode: lfraloc
            bodyPartCode: larmpart
            bleedingSusceptibility: low
            amputability: medium
            shockValue: 1
            probWeight: 20
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Left Hand
            shortcode: lhandloc
            bodyPartCode: larmpart
            bleedingSusceptibility: none
            amputability: high
            shockValue: 2
            probWeight: 10
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Thorax
            shortcode: thrxloc
            bodyPartCode: torsopart
            bleedingSusceptibility: medium
            amputability: none
            shockValue: 4
            probWeight: 40
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Abdomen
            shortcode: abdmnloc
            bodyPartCode: torsopart
            bleedingSusceptibility: high
            amputability: none
            shockValue: 4
            probWeight: 40
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Pelvis
            shortcode: plvisloc
            bodyPartCode: torsopart
            bleedingSusceptibility: medium
            amputability: none
            shockValue: 4
            probWeight: 20
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Right Thigh
            shortcode: rthghloc
            bodyPartCode: rlegpart
            bleedingSusceptibility: medium
            amputability: low
            shockValue: 3
            probWeight: 40
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Right Knee
            shortcode: rkneeloc
            bodyPartCode: rlegpart
            bleedingSusceptibility: low
            amputability: medium
            shockValue: 2
            probWeight: 10
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Right Calf
            shortcode: rcalfloc
            bodyPartCode: rlegpart
            bleedingSusceptibility: low
            amputability: medium
            shockValue: 1
            probWeight: 30
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Right Foot
            shortcode: rfootloc
            bodyPartCode: rlegpart
            bleedingSusceptibility: none
            amputability: medium
            shockValue: 2
            probWeight: 20
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Left Thigh
            shortcode: lthghloc
            bodyPartCode: llegpart
            bleedingSusceptibility: medium
            amputability: low
            shockValue: 3
            probWeight: 40
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Left Knee
            shortcode: lkneeloc
            bodyPartCode: llegpart
            bleedingSusceptibility: low
            amputability: medium
            shockValue: 2
            probWeight: 10
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Left Calf
            shortcode: lcalfloc
            bodyPartCode: llegpart
            bleedingSusceptibility: low
            amputability: medium
            shockValue: 1
            probWeight: 30
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
          - name: Left Foot
            shortcode: lfootloc
            bodyPartCode: llegpart
            bleedingSusceptibility: none
            amputability: medium
            shockValue: 2
            probWeight: 20
            protectionBase:
              blunt: 0
              edged: 0
              piercing: 0
              fire: 0
      weight:
        base: null
        calc: (9 * str) + 50
      reachBase: 0
      bodyScaleBase: 1
      personalFatigue: enc + 5
    currentMoveMedium: terrestrial
    movementProfiles:
      - medium: terrestrial
        feetPerRound: 50
        leaguesPerWatch: 5
        encumbrance: floor(wt/4)
        strMod: -5 * floor((str - 10) / 2)
        disabled: false
---

# Appearance {#appearance}

![[fff4991|Kora of Serdica]]{float: top-left}

**Apparent Age**: Elderly
**Culture**: Feudal
**Social Class**: Freeman (unguilded)
**Height**: 5 ft 1 in
**Frame**: Medium
**Weight**: 110 lb
**Appearance**: Attractive
**Hair Colour**: Grey
**Eye Colour**: Blue
**Voice**: Pleasant
**Obvious Medical Traits**: Hand tremor
**Apparent Occupation**: Not obvious
**Apparent Wealth**: Some
**Weapons**: None
**Armour**: None
**Companions**: Hus, a wiry terrier
**Other obvious features**: None

# Dossier {#dossier}

**Title**: FFF 499-1 Misc Unguilded
**Birthday**: 24 Navek 660
**Appearance**: Age 59, height 5' 1", medium frame, weight 110 lb, attractive appearance, medium complexion, grey hair, blue eyes
**Medical/Psyche**: Tremors in her hands
**Size**: 4
**Armor**: Rough cloth robe, cloth cloak with hood, leather shoes, wooden walking cane
**Other Equipment**: Belt pouch
**Valuables**: 24d in silver
**Notes**:

## Biography

In her youth, Kora was an attractive woman, but age and a life spent mostly outdoors have taken their toll. Her hair is steel grey, her skin tanned and wrinkled, and her attire seems to be little more than rags layered upon rags. She is accompanied by a grey and white, wiry hair terrier named Hus; he never leaves her side.

Although Peoni's missionaries were largely successful in converting the peoples of Harn, there are still places where the old ways are followed and where the old beliefs are part of the folklore of even the most devout Peonians. In these places, the self-styled keepers of the ancient lore are as welcome as any mendicant priest of Peoni. Kora of Serdica is one such mystic.

Some call her a midwife, others call her a wise woman, but every village between Harden and Kobing knows Kora. Born to a widow of the Treasure War, Kora followed in her mother's footsteps as she travelled from village to village along Genin's Trail, repeating the oral histories of the peoples of the Horka, Ulmerien and Osel valleys and, at the right times and places, leading the ancient rites. Now the last of her line, Kora continues the tradition as she travels Genin's Trail on her own. She never takes payment for her religious services, but earns what coin she can, aiding births, tending the sick and telling fortunes.

Kora knows the ways and languages of the barbarians, and knows more of the region's ancient lore than any 'civilised' scholar. Her forays into the forest in search of herbs for her potions have led her to discover places and things lost to common knowledge centuries ago.

## Adventure Hooks

Trail Guide & Interpreter. Kora is as familiar with Genin's Trail and its hazards as any mercenary guard or caravan master. She might seek to join PCs travelling with the caravan or, for a fee, be persuaded to guide PCs travelling the trail between caravans.

Folklorist & Historian. The PCs are in search of an ancient site in eastern Harn. Surprisingly, their inquiries take them to Kora as the best source of information on pre-Migration War cultures and civilisation. She insists on accompanying the PCs.

Access. Kora is well known in the settlements along Genin's Trail as both a healer and one wise in the "old ways." Most of her clients are peasants - the descendants of the region's early settlers - but even the nobility som times call on her for aid in time of need. In some noble houses, Kora can sometimes gain an audience denied to others.

## Credits

This character is taken from "Friends, Foes, and Followers, Vol. 1" on Lythia.com (<https://www.lythia.com/game_aides/friends-foes-followers-volume-1/>), by Kerry Mould, with illustrations by Richard Luscheck and Juha Makkonen, and is "fanon", a derivative work of copyrighted material by Columbia Games Inc. and N. Robin Crossby.
