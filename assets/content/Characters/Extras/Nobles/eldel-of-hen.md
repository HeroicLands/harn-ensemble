---
tags:
  - character
name:
  full: Eldel of Hen
  title: ""
  given: Eldel
  clan: Hen
  aliases: []
id: oBRwLnjmXRalWGiW
packFolder: extrasnobles
shortcode: eldelofhen
type: being
social:
  occupation: Chieftan
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual: []
data:
  templatePriority: 1
  gender: female
  species: human
  age: 59
  birthday: 661/1/17
  height: 1.75
  weight: 131.09
  frame: medium
  appearance:
    eye_color: brown
    hair_color: brown
    skin_color: dark
    complexion: ugly
    extra_features:
      - "*Parasites"
hm3:
  type: character
  attributes:
    str: 17
    sta: 8
    dex: 10
    agl: 16
    int: 10
    aur: 16
    wil: 6
    eye: 16
    hrg: 13
    sml: 13
    voi: 10
    cml: 5
    mor: 9
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 64 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 66 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 64 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: language, type: skill, name: "Language, Serf", system: { masteryLevel: 58 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 16 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 33 } }
    - { shortcode: bow, type: skill, system: { masteryLevel: 98 } }
    - { shortcode: dagger, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 64 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 96 } }
    - { shortcode: fletching, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: foraging, type: skill, system: { masteryLevel: 104 } }
    - { shortcode: hidework, type: skill, system: { masteryLevel: 20 } }
    - { shortcode: survival, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: tracking, type: skill, system: { masteryLevel: 98 } }
    - { shortcode: pence, type: miscgear, system: { quantity: 1845 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: LtCBoot, type: armorgear }
    - { shortcode: CvCloak, type: armorgear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: CShoe, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
    - name: Arrow, dozen
      type: miscgear
      data:
        icon: sohl-none-icon-miscgear
      system:
        weight: 1
    - { shortcode: backbagsmcanvas, type: containergear }
    - { shortcode: beltpouchl3, type: containergear }
    - { shortcode: LtCap, type: armorgear }
    - { shortcode: quiverlgsh, type: miscgear }
    - name: Ring, Copper
      type: miscgear
      data:
        icon: sohl-none-icon-miscgear
      system:
        value: 1
        weight: 0.03
    - { shortcode: spoonwooden, type: miscgear }
    - { shortcode: tankardwooden, type: miscgear }
  system:
    sunsign: ulandus
    move: 12
sohl:
  kbcat: archetype
  items:
    - { model: attribute-str, system: { scoreBase: 17 } }
    - { model: attribute-end, system: { scoreBase: 8 } }
    - { model: attribute-dex, system: { scoreBase: 10 } }
    - { model: attribute-agl, system: { scoreBase: 16 } }
    - { model: attribute-per, system: { scoreBase: 16 } }
    - { model: attribute-snt, system: { scoreBase: 13 } }
    - { model: attribute-cml, system: { scoreBase: 5 } }
    - { model: attribute-aur, system: { scoreBase: 16 } }
    - { model: attribute-wil, system: { scoreBase: 6 } }
    - { model: attribute-rea, system: { scoreBase: 10 } }
    - { model: attribute-cre, system: { scoreBase: 12 } }
    - { model: attribute-emp, system: { scoreBase: 10 } }
    - { model: attribute-elo, system: { scoreBase: 8 } }
    - { model: attribute-mor, system: { scoreBase: 9 } }
    - { model: attribute-voi, system: { scoreBase: 10 } }
    - { model: skill-archery, system: { masteryLevelBase: 98 } }
    - { model: skill-awar, system: { masteryLevelBase: 56 } }
    - { model: skill-chrm }
    - { model: skill-clmb, system: { masteryLevelBase: 64 } }
    - { model: skill-cmd }
    - { model: skill-cook }
    - { model: skill-dnce }
    - { model: skill-dscr }
    - { model: skill-draw }
    - { model: skill-folklr }
    - { model: skill-guil }
    - { model: skill-init, system: { masteryLevelBase: 36 } }
    - { model: skill-shok }
    - { model: skill-intr, system: { masteryLevelBase: 60 } }
    - { model: skill-jump, system: { masteryLevelBase: 64 } }
    - { model: skill-melee, system: { masteryLevelBase: 60 } }
    - { model: skill-dge }
    - { model: skill-pysn }
    - { model: skill-ridg }
    - { model: skill-sing, system: { masteryLevelBase: 33 } }
    - { model: skill-stlth, system: { masteryLevelBase: 44 } }
    - { model: skill-srvl, system: { masteryLevelBase: 56 } }
    - { model: skill-spirit }
    - { model: skill-swim }
    - { model: skill-thtcs }
    - { model: skill-thro, system: { masteryLevelBase: 56 } }
    - { model: skill-bflkbite }
    - { model: skill-bflkgrab }
    - { model: skill-bflkheadbutt }
    - { model: skill-bflkkick }
    - { model: skill-limbblock }
    - { model: skill-press }
    - { model: skill-bflkpunch }
    - { model: skill-trip }
    - { model: mysticalability-sprt }
    - { model: skill-lang, name: "Language, Serf", system: { masteryLevelBase: 58 } }
    - { model: skill-fltch, system: { masteryLevelBase: 36 } }
    - { model: skill-hide, system: { masteryLevelBase: 20 } }
    - { model: skill-trak, system: { masteryLevelBase: 98 } }
    - { model: miscgear-pence, system: { quantity: 1845 } }
    - { model: containergear-pouchbuckram }
    - { model: armorgear-LtCBoot }
    - { model: armorgear-CvCloak }
    - { model: armorgear-LLeg }
    - { model: armorgear-CShoe }
    - { model: armorgear-LTunic }
    - { model: weapongear-Kni }
    - { model: projectilegear-ArwStd, system: { quantity: 12 } }
    - { model: containergear-bgsmcvs }
    - { model: containergear-beltpouchl3 }
    - { model: armorgear-LtCap }
    - { model: containergear-quiverlgsh }
    - { model: miscgear-ringcopper }
    - { model: miscgear-spoonpewte }
    - { model: miscgear-tankardpew }
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

**Height**: 5' 9"
**Frame**: Medium
**Weight**: 289
**Size**: 10
**Comeliness**: Ugly
**Complexion**: Dark
**Hair Color**: Brown
**Eye Color**: Brown
**Voice**: Average

# Dossier {#dossier}

**Age**: 59
**Birthday**: 17 Nuzyael 661
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: 3rd child of 3
**Siblings**: mfF
**Parentage**: Offspring
**Offspring**: Mother dead, father remarried
**Estrangement**: Unpopular
**Clanhead**: Great Great Grandfather's Distant Relation
**Medical**: *Parasites

## Notes

Modifier to Frame of -3 (from 13) {Sex=Female, Species=Human}

Modifier to AttributesAUR of +2 (from 14) {Sex=Female, Species=Human}

Modifier to HairColor of -25 (from 63) {Complexion=Dark, Species=Human}

Modifier to EyeColor of +25 (from 72) {Complexion=Dark, Species=Human}

Parastites cause special penalty to Rhetoric and Lovecraft until cured.

157lbs weight resulted in +1 strength mod.

Modifier to StartingEquipment of +100 (from 52) {SocialClass=Serf}
