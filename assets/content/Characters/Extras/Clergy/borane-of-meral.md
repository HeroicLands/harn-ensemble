---
tags:
  - character
name:
  full: Borane of Meral
  title: ""
  given: Borane
  clan: Meral
  aliases: []
id: 45hzVh4KgtbuMj1T
packFolder: extrasclergy
shortcode: boraneofmeral
type: being
social:
  occupation: Cleric/Morgath
  class: guilded
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual:
    - morgath
data:
  templatePriority: 1
  gender: female
  species: humanflk
  age: 27
  born: 693/8/25
  height: 1.73
  weight: 69.4
  frame: medium
  appearance:
    eye_color: brown
    hair_color: black
    skin_color: dark
    complexion: attractive
    extra_features:
      - Left-Handed
hm3:
  type: character
  attributes:
    str: 9
    sta: 4
    dex: 11
    agl: 11
    int: 17
    aur: 14
    wil: 7
    eye: 12
    hrg: 7
    sml: 13
    voi: 14
    cml: 14
    mor: 6
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: language, type: skill, name: Language(Azeri), system: { masteryLevel: 36 } }
    - shortcode: language
      type: skill
      name: Language(Ormauk)
      system:
        shortcode: languageormauk
        masteryLevel: 36
    - shortcode: language
      type: skill
      name: Language, Guilded
      system:
        shortcode: languageguilded
        masteryLevel: 72
    - { shortcode: mentalconflict, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 33 } }
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevel: 84 } }
    - shortcode: script
      type: skill
      name: Script(Nuvesarl)
      system:
        shortcode: scriptnuvesarl
        masteryLevel: 84
    - { shortcode: dagger, type: skill, system: { masteryLevel: 44 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 32 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: drawing, type: skill, system: { masteryLevel: 22 } }
    - { shortcode: embalming, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: folklore, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: heraldry, type: skill, system: { masteryLevel: 20 } }
    - shortcode: hidework
      type: skill
      name: Human Skin (Hidework)
      system:
        masteryLevel: 20
    - { shortcode: law, type: skill, system: { masteryLevel: 26 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 26 } }
    - { shortcode: tarotry, type: skill, system: { masteryLevel: 28 } }
    - { shortcode: woodcraft, type: skill, name: Masks (Woodcraft), system: { masteryLevel: 18 } }
    - { shortcode: morgath, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: morgathbaptism, type: invocation }
    - { shortcode: morgathblessing, type: invocation }
    - { shortcode: morgathcommune, type: invocation }
    - { shortcode: morgathliturgy, type: invocation }
    - { shortcode: morgathmarriage, type: invocation }
    - { shortcode: morgathpassageofthesoul, type: invocation }
    - { shortcode: myvriaskiss, type: invocation }
    - { shortcode: throatofklyss, type: invocation }
    - { shortcode: heartofdarkness, type: invocation }
    - { shortcode: eyesofklyss, type: invocation }
    - { shortcode: necrosy, type: invocation }
    - { shortcode: pence, type: miscgear, system: { quantity: 135 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: BLeg, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: CTunic, type: armorgear }
    - { shortcode: Dgr, type: weapongear }
  system:
    species: human
    sunsign: tarael
    move: 8
sohl:
  kbcat: archetype
  items:
    - { model: sohl-sohl-attribute-str, system: { scoreBase: 9 } }
    - { model: sohl-sohl-attribute-end, system: { scoreBase: 4 } }
    - { model: sohl-sohl-attribute-dex, system: { scoreBase: 11 } }
    - { model: sohl-sohl-attribute-agl, system: { scoreBase: 11 } }
    - { model: sohl-sohl-attribute-per, system: { scoreBase: 10 } }
    - { model: sohl-sohl-attribute-snt, system: { scoreBase: 13 } }
    - { model: sohl-sohl-attribute-cml, system: { scoreBase: 14 } }
    - { model: sohl-sohl-attribute-aur, system: { scoreBase: 14 } }
    - { model: sohl-sohl-attribute-wil, system: { scoreBase: 7 } }
    - { model: sohl-sohl-attribute-rea, system: { scoreBase: 17 } }
    - { model: sohl-sohl-attribute-cre, system: { scoreBase: 11 } }
    - { model: sohl-sohl-attribute-emp, system: { scoreBase: 9 } }
    - { model: sohl-sohl-attribute-elo, system: { scoreBase: 9 } }
    - { model: sohl-sohl-attribute-mor, system: { scoreBase: 6 } }
    - { model: sohl-sohl-attribute-voi, system: { scoreBase: 14 } }
    - { model: sohl-sohl-skill-archery }
    - { model: sohl-sohl-skill-awar, system: { masteryLevelBase: 48 } }
    - { model: sohl-sohl-skill-chrm }
    - { model: sohl-sohl-skill-clmb, system: { masteryLevelBase: 40 } }
    - { model: sohl-sohl-skill-cmd }
    - { model: sohl-sohl-skill-cook }
    - { model: sohl-sohl-skill-dnce }
    - { model: sohl-sohl-skill-dscr }
    - { model: sohl-sohl-skill-draw, system: { masteryLevelBase: 22 } }
    - { model: sohl-sohl-skill-folklr, system: { masteryLevelBase: 48 } }
    - { model: sohl-sohl-skill-guil }
    - { model: sohl-sohl-skill-init, system: { masteryLevelBase: 32 } }
    - { model: sohl-sohl-skill-shok }
    - { model: sohl-sohl-skill-intr, system: { masteryLevelBase: 52 } }
    - { model: sohl-sohl-skill-jump, system: { masteryLevelBase: 40 } }
    - { model: sohl-sohl-skill-melee, system: { masteryLevelBase: 44 } }
    - { model: sohl-sohl-skill-dge }
    - { model: sohl-sohl-skill-pysn, system: { masteryLevelBase: 26 } }
    - { model: sohl-sohl-skill-ridg }
    - { model: sohl-sohl-skill-sing, system: { masteryLevelBase: 33 } }
    - { model: sohl-sohl-skill-stlth, system: { masteryLevelBase: 30 } }
    - { model: sohl-sohl-skill-srvl }
    - { model: sohl-sohl-skill-spirit }
    - { model: sohl-sohl-skill-swim }
    - { model: sohl-sohl-skill-thtcs }
    - { model: sohl-sohl-skill-thro, system: { masteryLevelBase: 44 } }
    - { model: sohl-sohl-skill-bflkbite }
    - { model: sohl-sohl-skill-bflkgrab }
    - { model: sohl-sohl-skill-bflkheadbutt }
    - { model: sohl-sohl-skill-bflkkick }
    - { model: sohl-sohl-skill-limbblock }
    - { model: sohl-sohl-skill-press }
    - { model: sohl-sohl-skill-bflkpunch }
    - { model: sohl-sohl-skill-trip }
    - { model: sohl-sohl-mysticalability-sprt }
    - { model: sohl-sohl-skill-lang, name: "Language, Guilded", system: { masteryLevelBase: 72 } }
    - { model: sohl-sohl-skill-script, name: Script(Nuvesarl), system: { masteryLevelBase: 84 } }
    - { model: sohl-sohl-skill-embl, system: { masteryLevelBase: 36 } }
    - { model: sohl-sohl-skill-hrld, system: { masteryLevelBase: 20 } }
    - model: sohl-sohl-skill-hide
      name: Human Skin (Hidework)
      system:
        masteryLevelBase: 20
    - { model: sohl-sohl-skill-law, system: { masteryLevelBase: 26 } }
    - { model: sohl-sohl-mysticalability-tarot, system: { masteryLevelBase: 28 } }
    - { model: sohl-sohl-miscgear-pence, system: { quantity: 135 } }
    - { model: sohl-sohl-containergear-pouchbuckram }
    - { model: sohl-sohl-armorgear-BLeg }
    - { model: sohl-sohl-armorgear-LtShoe }
    - { model: sohl-sohl-armorgear-CTunic }
    - { model: sohl-sohl-weapongear-Dgr }
    - { name: Morgath, type: affiliation, system: { shortcode: morgath, subType: divine } }
    - name: Morgath
      type: skill
      system:
        subType: mystical
        shortcode: morgath
        skillBaseFormula: sb(attr.wil, attr.rea)
        masteryLevelBase: 60
    - name: Baptism
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 2
    - name: Blessing
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 2
    - name: Commune
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 2
    - name: Liturgy
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 2
    - name: Marriage
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 2
    - name: Passage of the Soul
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 2
    - name: Myvria's Kiss
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 4
    - name: Throat of Klyss
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 3
    - name: Heart of Darkness
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 2
    - name: Eyes of Klyss
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 3
    - name: Necrosy
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 2
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

**Height**: 5' 8"
**Frame**: Medium
**Weight**: 153
**Size**: 6
**Comeliness**: Attractive
**Complexion**: Dark
**Hair Color**: Black
**Eye Color**: Brown
**Voice**: Pleasant

# Dossier {#dossier}

**Age**: 27
**Birthday**: 25 Halane 693
**Culture**: Feudal
**Social Class**: Guilded
**Sibling Rank**: 3rd child of 9
**Siblings**: MmFfFmfFF
**Parentage**: Orphan
**Estrangement**: Favorite
**Clanhead**: Father/Mother
**Medical**: Left-Handed

## Notes

Modifier to Frame of -3 (from 15) {Sex=Female, Species=Human}

Modifier to AttributesAUR of +2 (from 12) {Sex=Female, Species=Human}

Modifier to HairColor of -25 (from 29) {Complexion=Dark, Species=Human}

Modifier to EyeColor of +25 (from 90) {Complexion=Dark, Species=Human}

Left-Handed mod to Dexterity: +1

Modifier to StartingEquipment of +300 (from 59) {SocialClass=Guilded}
