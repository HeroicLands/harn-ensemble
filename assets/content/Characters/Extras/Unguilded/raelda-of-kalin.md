---
tags:
  - character
name:
  full: Raelda of Kalin
  title: ""
  given: Raelda
  clan: Kalin
  aliases: []
id: 0IOUb4WIgHTGsCh8
packFolder: extrasunguilded
shortcode: raeldaofkalin
type: being
social:
  occupation: Shaman
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual:
    - "custom|Tribal"
data:
  templatePriority: 1
  gender: female
  species: humanflk
  age: 43
  born: 677/2/14
  height: 1.78
  weight: 79.83
  frame: heavy
  appearance:
    eye_color: green
    hair_color: auburn
    skin_color: pale
    complexion: plain
    extra_features:
      - Left-Handed
hm3:
  type: character
  attributes:
    str: 16
    sta: 15
    dex: 17
    agl: 6
    int: 14
    aur: 15
    wil: 10
    eye: 9
    hrg: 13
    sml: 10
    voi: 5
    cml: 8
    mor: 13
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 78 } }
    - { shortcode: dancing, type: skill, system: { masteryLevel: 27 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 45 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 84 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 50 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 91 } }
    - { shortcode: language, type: skill, name: "Language, Serf", system: { masteryLevel: 59 } }
    - { shortcode: mentalconflict, type: skill, system: { masteryLevel: 66 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 45 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 54 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 28 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: spear, type: skill, system: { masteryLevel: 51 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: embalming, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: folklore, type: skill, system: { masteryLevel: 77 } }
    - { shortcode: foraging, type: skill, system: { masteryLevel: 45 } }
    - { shortcode: herblore, type: skill, system: { masteryLevel: 104 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 39 } }
    - { shortcode: survival, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: tracking, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: weatherlore, type: skill, system: { masteryLevel: 44 } }
    - name: Tribal
      type: skill
      data:
        icon: sohl-none-icon-circle
      system:
        type: Ritual
        skillBase.value: 12
        masteryLevel: 72
        ritual.piety: 18
    - { shortcode: pence, type: miscgear, system: { quantity: 0 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: CvCloak, type: armorgear }
    - { shortcode: LtCloak, type: armorgear }
    - { shortcode: CHood, type: armorgear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: CShoe, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: Spr, type: weapongear, system: { quantity: 0 } }
    - { shortcode: SprThr, type: missilegear, name: Spear (thrown) }
    - { shortcode: beltpouchl3, type: containergear }
    - { shortcode: cookingkitportable, type: miscgear }
    - name: "Debt to Money Lender: Barid of Ewel for 258d"
      type: miscgear
      data:
        icon: sohl-none-icon-miscgear
      system:
        weight: 1
    - { shortcode: LtCap, type: armorgear }
    - name: Necklace, Silver
      type: miscgear
      data:
        icon: sohl-none-icon-miscgear
      system:
        value: 240
        weight: 0.25
    - { shortcode: ropehempperft330lbcap, type: miscgear }
  system:
    species: human
    sunsign: aralius
    move: 7
sohl:
  kbcat: archetype
  items:
    - { model: sohl-sohl-attribute-str, system: { scoreBase: 16 } }
    - { model: sohl-sohl-attribute-end, system: { scoreBase: 15 } }
    - { model: sohl-sohl-attribute-dex, system: { scoreBase: 17 } }
    - { model: sohl-sohl-attribute-agl, system: { scoreBase: 6 } }
    - { model: sohl-sohl-attribute-per, system: { scoreBase: 10 } }
    - { model: sohl-sohl-attribute-snt, system: { scoreBase: 10 } }
    - { model: sohl-sohl-attribute-cml, system: { scoreBase: 8 } }
    - { model: sohl-sohl-attribute-aur, system: { scoreBase: 15 } }
    - { model: sohl-sohl-attribute-wil, system: { scoreBase: 10 } }
    - { model: sohl-sohl-attribute-rea, system: { scoreBase: 14 } }
    - { model: sohl-sohl-attribute-cre, system: { scoreBase: 13 } }
    - { model: sohl-sohl-attribute-emp, system: { scoreBase: 10 } }
    - { model: sohl-sohl-attribute-elo, system: { scoreBase: 6 } }
    - { model: sohl-sohl-attribute-mor, system: { scoreBase: 13 } }
    - { model: sohl-sohl-attribute-voi, system: { scoreBase: 5 } }
    - { model: sohl-sohl-skill-archery }
    - { model: sohl-sohl-skill-awar, system: { masteryLevelBase: 50 } }
    - { model: sohl-sohl-skill-chrm }
    - { model: sohl-sohl-skill-clmb, system: { masteryLevelBase: 60 } }
    - { model: sohl-sohl-skill-cmd }
    - { model: sohl-sohl-skill-cook }
    - { model: sohl-sohl-skill-dnce, system: { masteryLevelBase: 27 } }
    - { model: sohl-sohl-skill-dscr }
    - { model: sohl-sohl-skill-draw }
    - { model: sohl-sohl-skill-folklr, system: { masteryLevelBase: 77 } }
    - { model: sohl-sohl-skill-guil }
    - { model: sohl-sohl-skill-init, system: { masteryLevelBase: 40 } }
    - { model: sohl-sohl-skill-shok }
    - { model: sohl-sohl-skill-intr, system: { masteryLevelBase: 91 } }
    - { model: sohl-sohl-skill-jump, system: { masteryLevelBase: 45 } }
    - { model: sohl-sohl-skill-melee, system: { masteryLevelBase: 51 } }
    - { model: sohl-sohl-skill-dge }
    - { model: sohl-sohl-skill-pysn, system: { masteryLevelBase: 39 } }
    - { model: sohl-sohl-skill-ridg }
    - { model: sohl-sohl-skill-sing, system: { masteryLevelBase: 28 } }
    - { model: sohl-sohl-skill-stlth, system: { masteryLevelBase: 36 } }
    - { model: sohl-sohl-skill-srvl, system: { masteryLevelBase: 48 } }
    - { model: sohl-sohl-skill-spirit }
    - { model: sohl-sohl-skill-swim }
    - { model: sohl-sohl-skill-thtcs }
    - { model: sohl-sohl-skill-thro, system: { masteryLevelBase: 84 } }
    - { model: sohl-sohl-skill-bflkbite }
    - { model: sohl-sohl-skill-bflkgrab }
    - { model: sohl-sohl-skill-bflkheadbutt }
    - { model: sohl-sohl-skill-bflkkick }
    - { model: sohl-sohl-skill-limbblock }
    - { model: sohl-sohl-skill-press }
    - { model: sohl-sohl-skill-bflkpunch }
    - { model: sohl-sohl-skill-trip }
    - { model: sohl-sohl-mysticalability-sprt }
    - { model: sohl-sohl-skill-lang, name: "Language, Serf", system: { masteryLevelBase: 59 } }
    - { model: sohl-sohl-skill-embl, system: { masteryLevelBase: 24 } }
    - { model: sohl-sohl-skill-herb, system: { masteryLevelBase: 104 } }
    - { model: sohl-sohl-skill-trak, system: { masteryLevelBase: 36 } }
    - { model: sohl-sohl-miscgear-pence, system: { quantity: 0 } }
    - { model: sohl-sohl-containergear-pouchbuckram }
    - { model: sohl-sohl-armorgear-CvCloak }
    - { model: sohl-sohl-armorgear-LtCloak }
    - { model: sohl-sohl-armorgear-CHood }
    - { model: sohl-sohl-armorgear-LLeg }
    - { model: sohl-sohl-armorgear-CShoe }
    - { model: sohl-sohl-armorgear-LTunic }
    - { model: sohl-sohl-weapongear-Kni }
    - { model: sohl-sohl-weapongear-Spr, system: { quantity: 0 } }
    - { model: sohl-sohl-containergear-beltpouchl3 }
    - { model: sohl-sohl-miscgear-cookkit }
    - { model: sohl-sohl-armorgear-LtCap }
    - { model: sohl-sohl-miscgear-necklacesilver }
    - { model: sohl-sohl-miscgear-rope12hemp }
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

**Height**: 5' 10"
**Frame**: Heavy
**Weight**: 176
**Size**: 7
**Comeliness**: Plain
**Complexion**: Pale
**Hair Color**: Auburn
**Eye Color**: Green
**Voice**: Unpleasant

# Dossier {#dossier}

**Age**: 43
**Birthday**: 14 Peonu 677
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: 2nd child of 4
**Siblings**: MFmm
**Parentage**: Orphan
**Estrangement**: Unpopular
**Clanhead**: Grandfather's Cousin
**Medical**: Left-Handed

## Notes

Modifier to Frame of -3 (from 16) {Sex=Female, Species=Human}

Modifier to AttributesAGL of -1 (from 8) {Frame=Heavy}

Modifier to AttributesAUR of +2 (from 13) {Sex=Female, Species=Human}

Modifier to EyeColor of -25 (from 81) {Complexion=Pale, Species=Human}

Left-Handed mod to Dexterity: +2

176lbs weight resulted in +2 strength mod.

Heavy frame resulted in -1 agility mod.

Modifier to StartingEquipment of +100 (from 34) {SocialClass=Serf}
