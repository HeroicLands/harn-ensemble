---
tags:
  - character
name:
  full: Vadiryn of Enasta
  title: ""
  given: Vadiryn
  clan: Enasta
  aliases: []
id: FnoUiCXjoQ8UqSHT
packFolder: extrasunguilded
shortcode: vadirynofenasta
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
  gender: male
  species: humanflk
  age: 43
  born: 677/7/6
  height: 1.88
  weight: 81.65
  frame: medium
  appearance:
    eye_color: amber
    hair_color: blonde
    skin_color: fair
    complexion: plain
    extra_features:
      - Albinism
hm3:
  type: character
  attributes:
    str: 13
    sta: 16
    dex: 17
    agl: 16
    int: 12
    aur: 5
    wil: 13
    eye: 11
    hrg: 13
    sml: 15
    voi: 12
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
    - { shortcode: condition, type: skill, system: { masteryLevel: 70 } }
    - { shortcode: dancing, type: skill, system: { masteryLevel: 68 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 85 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 70 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 70 } }
    - { shortcode: language, type: skill, name: "Language, Serf", system: { masteryLevel: 62 } }
    - { shortcode: mentalconflict, type: skill, system: { masteryLevel: 50 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: spear, type: skill, system: { masteryLevel: 28 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 90 } }
    - { shortcode: embalming, type: skill, system: { masteryLevel: 28 } }
    - { shortcode: folklore, type: skill, system: { masteryLevel: 72 } }
    - { shortcode: foraging, type: skill, system: { masteryLevel: 42 } }
    - { shortcode: herblore, type: skill, system: { masteryLevel: 96 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 65 } }
    - { shortcode: survival, type: skill, system: { masteryLevel: 42 } }
    - { shortcode: tracking, type: skill, system: { masteryLevel: 26 } }
    - { shortcode: weatherlore, type: skill, system: { masteryLevel: 65 } }
    - name: Tribal
      type: skill
      data:
        icon: sohl-none-icon-circle
      system:
        type: Ritual
        skillBase.value: 10
        masteryLevel: 70
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
    - { shortcode: SBw, type: weapongear }
    - name: Arrow, dozen
      type: miscgear
      data:
        icon: sohl-none-icon-miscgear
      system:
        weight: 1
    - { shortcode: cookingkitportable, type: miscgear }
    - name: "Debt to Money Lender: Korin of Obelon for 206d"
      type: miscgear
      data:
        icon: sohl-none-icon-miscgear
      system:
        weight: 1
    - { shortcode: LtCap, type: armorgear }
    - { shortcode: quiverlgsh, type: miscgear }
    - { shortcode: ropehempperft330lbcap, type: miscgear }
  system:
    species: human
    sunsign: hirin-nadai
    move: 13
sohl:
  kbcat: archetype
  items:
    - { model: attribute-str, system: { scoreBase: 13 } }
    - { model: attribute-end, system: { scoreBase: 16 } }
    - { model: attribute-dex, system: { scoreBase: 17 } }
    - { model: attribute-agl, system: { scoreBase: 16 } }
    - { model: attribute-per, system: { scoreBase: 14 } }
    - { model: attribute-snt, system: { scoreBase: 15 } }
    - { model: attribute-cml, system: { scoreBase: 8 } }
    - { model: attribute-aur, system: { scoreBase: 5 } }
    - { model: attribute-wil, system: { scoreBase: 13 } }
    - { model: attribute-rea, system: { scoreBase: 12 } }
    - { model: attribute-cre, system: { scoreBase: 16 } }
    - { model: attribute-emp, system: { scoreBase: 6 } }
    - { model: attribute-elo, system: { scoreBase: 12 } }
    - { model: attribute-mor, system: { scoreBase: 13 } }
    - { model: attribute-voi, system: { scoreBase: 12 } }
    - { model: skill-archery }
    - { model: skill-awar, system: { masteryLevelBase: 70 } }
    - { model: skill-chrm }
    - { model: skill-clmb, system: { masteryLevelBase: 60 } }
    - { model: skill-cmd }
    - { model: skill-cook }
    - { model: skill-dnce, system: { masteryLevelBase: 68 } }
    - { model: skill-dscr }
    - { model: skill-draw }
    - { model: skill-folklr, system: { masteryLevelBase: 72 } }
    - { model: skill-guil }
    - { model: skill-init, system: { masteryLevelBase: 56 } }
    - { model: skill-shok }
    - { model: skill-intr, system: { masteryLevelBase: 70 } }
    - { model: skill-jump, system: { masteryLevelBase: 85 } }
    - { model: skill-melee, system: { masteryLevelBase: 28 } }
    - { model: skill-dge }
    - { model: skill-pysn, system: { masteryLevelBase: 65 } }
    - { model: skill-ridg }
    - { model: skill-sing, system: { masteryLevelBase: 36 } }
    - { model: skill-stlth, system: { masteryLevelBase: 48 } }
    - { model: skill-srvl, system: { masteryLevelBase: 42 } }
    - { model: skill-spirit }
    - { model: skill-swim }
    - { model: skill-thtcs }
    - { model: skill-thro, system: { masteryLevelBase: 60 } }
    - { model: skill-bflkbite }
    - { model: skill-bflkgrab }
    - { model: skill-bflkheadbutt }
    - { model: skill-bflkkick }
    - { model: skill-limbblock }
    - { model: skill-press }
    - { model: skill-bflkpunch }
    - { model: skill-trip }
    - { model: mysticalability-sprt }
    - { model: skill-lang, name: "Language, Serf", system: { masteryLevelBase: 62 } }
    - { model: skill-embl, system: { masteryLevelBase: 28 } }
    - { model: skill-herb, system: { masteryLevelBase: 96 } }
    - { model: skill-trak, system: { masteryLevelBase: 26 } }
    - { model: miscgear-pence, system: { quantity: 0 } }
    - { model: containergear-pouchbuckram }
    - { model: armorgear-CvCloak }
    - { model: armorgear-LtCloak }
    - { model: armorgear-CHood }
    - { model: armorgear-LLeg }
    - { model: armorgear-CShoe }
    - { model: armorgear-LTunic }
    - { model: weapongear-Kni }
    - { model: weapongear-Spr, system: { quantity: 0 } }
    - { model: projectilegear-ArwStd, system: { quantity: 12 } }
    - { model: miscgear-cookkit }
    - { model: armorgear-LtCap }
    - { model: containergear-quiverlgsh }
    - { model: miscgear-rope12hemp }
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

**Height**: 6' 2"
**Frame**: Medium
**Weight**: 180
**Size**: 7
**Comeliness**: Plain
**Complexion**: Fair
**Hair Color**: Blond
**Eye Color**: Amber
**Voice**: Average

# Dossier {#dossier}

**Age**: 43
**Birthday**: 6 Azura 677
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: 4th child of 6
**Siblings**: MMmMFm
**Parentage**: Fostered
**Estrangement**: Popular
**Clanhead**: Aunt/Uncle
**Medical**: Albinism

## Notes

Modifier to HairColor of +25 (from 60) {Complexion=Fair, Species=Human}

Modifier to EyeColor of -10 (from 83) {Complexion=Fair, Species=Human}

180lbs weight resulted in +2 strength mod.

Modifier to StartingEquipment of +100 (from 48) {SocialClass=Serf}
