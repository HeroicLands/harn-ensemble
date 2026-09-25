---
tags:
  - character
name:
  full: Owain of Eylosathan
  title: ""
  given: Owain
  clan: Eylosathan
  aliases: []
id: qNMGqh63BKPxpI0F
packFolder: extrasunguilded
shortcode: owainofeylosathan
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
  age: 36
  born: 684/6/4
  height: 1.7
  weight: 67.59
  frame: medium
  appearance:
    eye_color: violet
    hair_color: blonde
    skin_color: fair
    complexion: attractive
    extra_features:
      - "*Parasites"
hm3:
  type: character
  attributes:
    str: 9
    sta: 15
    dex: 7
    agl: 11
    int: 14
    aur: 7
    wil: 14
    eye: 8
    hrg: 15
    sml: 14
    voi: 15
    cml: 13
    mor: 10
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: dancing, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 50 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 78 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 32 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 55 } }
    - { shortcode: language, type: skill, name: "Language, Serf", system: { masteryLevel: 64 } }
    - { shortcode: mentalconflict, type: skill, system: { masteryLevel: 66 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 42 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 70 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: spear, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: embalming, type: skill, system: { masteryLevel: 27 } }
    - { shortcode: folklore, type: skill, system: { masteryLevel: 84 } }
    - { shortcode: foraging, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: herblore, type: skill, system: { masteryLevel: 72 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 27 } }
    - { shortcode: survival, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: tracking, type: skill, system: { masteryLevel: 24 } }
    - { shortcode: weatherlore, type: skill, system: { masteryLevel: 60 } }
    - name: Tribal
      type: skill
      data:
        icon: sohl-none-icon-circle
      system:
        type: Ritual
        skillBase.value: 13
        masteryLevel: 91
        ritual.piety: 15
    - { shortcode: pence, type: miscgear, system: { quantity: 0 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: CvCloak, type: armorgear }
    - { shortcode: LtCloak, type: armorgear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: CShoe, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
    - { shortcode: Spr, type: weapongear, system: { quantity: 0 } }
    - { shortcode: SprThr, type: missilegear, name: Spear (thrown) }
    - { shortcode: backbagsmcanvas, type: containergear }
    - { shortcode: cookingkitportable, type: miscgear }
    - name: "Debt to Money Lender: Charad of Chardras for 298d"
      type: miscgear
      data:
        icon: sohl-none-icon-miscgear
      system:
        weight: 1
    - { shortcode: tndrbx, type: miscgear }
    - name: Ring, Bone/Horn
      type: miscgear
      data:
        icon: sohl-none-icon-miscgear
      system:
        value: 1
        weight: 0.03
    - { shortcode: ropehempperft330lbcap, type: miscgear }
    - { shortcode: spoonwooden, type: miscgear }
  system:
    species: human
    sunsign: angberelius
    move: 9
sohl:
  kbcat: archetype
  items:
    - { model: sohl-sohl-attribute-str, system: { scoreBase: 9 } }
    - { model: sohl-sohl-attribute-end, system: { scoreBase: 15 } }
    - { model: sohl-sohl-attribute-dex, system: { scoreBase: 7 } }
    - { model: sohl-sohl-attribute-agl, system: { scoreBase: 11 } }
    - { model: sohl-sohl-attribute-per, system: { scoreBase: 13 } }
    - { model: sohl-sohl-attribute-snt, system: { scoreBase: 14 } }
    - { model: sohl-sohl-attribute-cml, system: { scoreBase: 13 } }
    - { model: sohl-sohl-attribute-aur, system: { scoreBase: 7 } }
    - { model: sohl-sohl-attribute-wil, system: { scoreBase: 14 } }
    - { model: sohl-sohl-attribute-rea, system: { scoreBase: 14 } }
    - { model: sohl-sohl-attribute-cre, system: { scoreBase: 12 } }
    - { model: sohl-sohl-attribute-emp, system: { scoreBase: 8 } }
    - { model: sohl-sohl-attribute-elo, system: { scoreBase: 14 } }
    - { model: sohl-sohl-attribute-mor, system: { scoreBase: 10 } }
    - { model: sohl-sohl-attribute-voi, system: { scoreBase: 15 } }
    - { model: sohl-sohl-skill-archery }
    - { model: sohl-sohl-skill-awar, system: { masteryLevelBase: 60 } }
    - { model: sohl-sohl-skill-chrm }
    - { model: sohl-sohl-skill-clmb, system: { masteryLevelBase: 36 } }
    - { model: sohl-sohl-skill-cmd }
    - { model: sohl-sohl-skill-cook }
    - { model: sohl-sohl-skill-dnce, system: { masteryLevelBase: 36 } }
    - { model: sohl-sohl-skill-dscr }
    - { model: sohl-sohl-skill-draw }
    - { model: sohl-sohl-skill-folklr, system: { masteryLevelBase: 84 } }
    - { model: sohl-sohl-skill-guil }
    - { model: sohl-sohl-skill-init, system: { masteryLevelBase: 52 } }
    - { model: sohl-sohl-skill-shok }
    - { model: sohl-sohl-skill-intr, system: { masteryLevelBase: 55 } }
    - { model: sohl-sohl-skill-jump, system: { masteryLevelBase: 50 } }
    - { model: sohl-sohl-skill-melee, system: { masteryLevelBase: 40 } }
    - { model: sohl-sohl-skill-dge }
    - { model: sohl-sohl-skill-pysn, system: { masteryLevelBase: 27 } }
    - { model: sohl-sohl-skill-ridg }
    - { model: sohl-sohl-skill-sing, system: { masteryLevelBase: 60 } }
    - { model: sohl-sohl-skill-stlth, system: { masteryLevelBase: 78 } }
    - { model: sohl-sohl-skill-srvl, system: { masteryLevelBase: 30 } }
    - { model: sohl-sohl-skill-spirit }
    - { model: sohl-sohl-skill-swim }
    - { model: sohl-sohl-skill-thtcs }
    - { model: sohl-sohl-skill-thro, system: { masteryLevelBase: 32 } }
    - { model: sohl-sohl-skill-bflkbite }
    - { model: sohl-sohl-skill-bflkgrab }
    - { model: sohl-sohl-skill-bflkheadbutt }
    - { model: sohl-sohl-skill-bflkkick }
    - { model: sohl-sohl-skill-limbblock }
    - { model: sohl-sohl-skill-press }
    - { model: sohl-sohl-skill-bflkpunch }
    - { model: sohl-sohl-skill-trip }
    - { model: sohl-sohl-mysticalability-sprt }
    - { model: sohl-sohl-skill-lang, name: "Language, Serf", system: { masteryLevelBase: 64 } }
    - { model: sohl-sohl-skill-embl, system: { masteryLevelBase: 27 } }
    - { model: sohl-sohl-skill-herb, system: { masteryLevelBase: 72 } }
    - { model: sohl-sohl-skill-trak, system: { masteryLevelBase: 24 } }
    - { model: sohl-sohl-miscgear-pence, system: { quantity: 0 } }
    - { model: sohl-sohl-containergear-pouchbuckram }
    - { model: sohl-sohl-armorgear-CvCloak }
    - { model: sohl-sohl-armorgear-LtCloak }
    - { model: sohl-sohl-armorgear-LLeg }
    - { model: sohl-sohl-armorgear-CShoe }
    - { model: sohl-sohl-armorgear-LTunic }
    - { model: sohl-sohl-weapongear-Kni }
    - { model: sohl-sohl-weapongear-Spr, system: { quantity: 0 } }
    - { model: sohl-sohl-containergear-bgsmcvs }
    - { model: sohl-sohl-miscgear-cookkit }
    - { model: sohl-sohl-miscgear-tndrbx }
    - { model: sohl-sohl-miscgear-ringbone }
    - { model: sohl-sohl-miscgear-rope12hemp }
    - { model: sohl-sohl-miscgear-spoonpewte }
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

**Height**: 5' 7"
**Frame**: Medium
**Weight**: 149
**Size**: 6
**Comeliness**: Attractive
**Complexion**: Fair
**Hair Color**: Blond
**Eye Color**: Violet
**Voice**: Pleasant

# Dossier {#dossier}

**Age**: 36
**Birthday**: 4 Agrazhar 684
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: 2nd child of 5
**Siblings**: FMmfF
**Parentage**: Offspring
**Offspring**: Both parents alive and living together
**Estrangement**: Average
**Clanhead**: Great Great Grandfather's Distant Relation
**Medical**: *Parasites

## Notes

Modifier to HairColor of +25 (from 60) {Complexion=Fair, Species=Human}

Modifier to EyeColor of -10 (from 6) {Complexion=Fair, Species=Human}

Parastites cause special penalty to Rhetoric and Lovecraft until cured.

Modifier to StartingEquipment of +100 (from 5) {SocialClass=Serf}
