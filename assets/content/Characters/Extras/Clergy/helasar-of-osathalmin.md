---
tags:
  - character
name:
  full: Helasar of Osathalmin
  title: ""
  given: Helasar
  clan: Osathalmin
  aliases: []
id: 2QobfI8V2g0BRzqn
packFolder: extrasclergy
shortcode: helasarofosathalmin
type: being
social:
  occupation: Cleric/Agrik
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual:
    - agrik
data:
  templatePriority: 1
  gender: female
  species: humanflk
  age: 24
  born: 696/3/1
  height: 1.7
  weight: 53.98
  frame: scant
  appearance:
    eye_color: blue
    hair_color: black
    skin_color: swarthy
    complexion: plain
    extra_features:
      - "*Poxmarks (healed)"
hm3:
  type: character
  attributes:
    str: 16
    sta: 13
    dex: 10
    agl: 16
    int: 15
    aur: 14
    wil: 13
    eye: 10
    hrg: 5
    sml: 13
    voi: 16
    cml: 6
    mor: 8
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
    - { shortcode: condition, type: skill, system: { masteryLevel: 70 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 64 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 33 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: language, type: skill, name: Language(Azeryani), system: { masteryLevel: 42 } }
    - shortcode: language
      type: skill
      name: Language(Surikal)
      system:
        shortcode: languagesurikal
        masteryLevel: 42
    - shortcode: language
      type: skill
      name: Language, Serf
      system:
        shortcode: languageserf
        masteryLevel: 64
    - { shortcode: mentalconflict, type: skill, system: { masteryLevel: 52 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevel: 81 } }
    - shortcode: script
      type: skill
      name: Script(Zerin)
      system:
        shortcode: scriptzerin
        masteryLevel: 81
    - { shortcode: axe, type: skill, name: Sickle (Axe), system: { masteryLevel: 60 } }
    - { shortcode: club, type: skill, name: Mace (Club), system: { masteryLevel: 75 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 98 } }
    - { shortcode: shield, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: drawing, type: skill, system: { masteryLevel: 20 } }
    - { shortcode: embalming, type: skill, system: { masteryLevel: 22 } }
    - { shortcode: folklore, type: skill, system: { masteryLevel: 45 } }
    - { shortcode: heraldry, type: skill, system: { masteryLevel: 33 } }
    - { shortcode: law, type: skill, system: { masteryLevel: 28 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 22 } }
    - { shortcode: agrik, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: agrikbaptism, type: invocation }
    - { shortcode: agrikblessing, type: invocation }
    - { shortcode: agrikcommune, type: invocation }
    - { shortcode: agrikliturgy, type: invocation }
    - { shortcode: agrikmarriage, type: invocation }
    - { shortcode: agrikpassageofthesoul, type: invocation }
    - { shortcode: agriksrespite, type: invocation }
    - { shortcode: mamakascry, type: invocation }
    - { shortcode: aksytspeace, type: invocation }
    - { shortcode: touchofthevhir, type: invocation }
    - { shortcode: emynscut, type: invocation }
    - { shortcode: shieldofamana, type: invocation }
    - { shortcode: pence, type: miscgear, system: { quantity: 122 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: CShoe, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
  system:
    species: human
    sunsign: aralius-feniri
    move: 13
sohl:
  kbcat: archetype
  items:
    - { model: sohl-sohl-attribute-str, system: { scoreBase: 16 } }
    - { model: sohl-sohl-attribute-end, system: { scoreBase: 13 } }
    - { model: sohl-sohl-attribute-dex, system: { scoreBase: 10 } }
    - { model: sohl-sohl-attribute-agl, system: { scoreBase: 16 } }
    - { model: sohl-sohl-attribute-per, system: { scoreBase: 8 } }
    - { model: sohl-sohl-attribute-snt, system: { scoreBase: 13 } }
    - { model: sohl-sohl-attribute-cml, system: { scoreBase: 6 } }
    - { model: sohl-sohl-attribute-aur, system: { scoreBase: 14 } }
    - { model: sohl-sohl-attribute-wil, system: { scoreBase: 13 } }
    - { model: sohl-sohl-attribute-rea, system: { scoreBase: 15 } }
    - { model: sohl-sohl-attribute-cre, system: { scoreBase: 8 } }
    - { model: sohl-sohl-attribute-emp, system: { scoreBase: 11 } }
    - { model: sohl-sohl-attribute-elo, system: { scoreBase: 15 } }
    - { model: sohl-sohl-attribute-mor, system: { scoreBase: 8 } }
    - { model: sohl-sohl-attribute-voi, system: { scoreBase: 16 } }
    - { model: sohl-sohl-skill-archery }
    - { model: sohl-sohl-skill-awar, system: { masteryLevelBase: 36 } }
    - { model: sohl-sohl-skill-chrm }
    - { model: sohl-sohl-skill-clmb, system: { masteryLevelBase: 64 } }
    - { model: sohl-sohl-skill-cmd }
    - { model: sohl-sohl-skill-cook }
    - { model: sohl-sohl-skill-dnce }
    - { model: sohl-sohl-skill-dscr }
    - { model: sohl-sohl-skill-draw, system: { masteryLevelBase: 20 } }
    - { model: sohl-sohl-skill-folklr, system: { masteryLevelBase: 45 } }
    - { model: sohl-sohl-skill-guil }
    - { model: sohl-sohl-skill-init, system: { masteryLevelBase: 98 } }
    - { model: sohl-sohl-skill-shok }
    - { model: sohl-sohl-skill-intr, system: { masteryLevelBase: 56 } }
    - { model: sohl-sohl-skill-jump, system: { masteryLevelBase: 64 } }
    - { model: sohl-sohl-skill-melee, system: { masteryLevelBase: 61 } }
    - { model: sohl-sohl-skill-dge }
    - { model: sohl-sohl-skill-pysn, system: { masteryLevelBase: 22 } }
    - { model: sohl-sohl-skill-ridg }
    - { model: sohl-sohl-skill-sing, system: { masteryLevelBase: 36 } }
    - { model: sohl-sohl-skill-stlth, system: { masteryLevelBase: 33 } }
    - { model: sohl-sohl-skill-srvl }
    - { model: sohl-sohl-skill-spirit }
    - { model: sohl-sohl-skill-swim }
    - { model: sohl-sohl-skill-thtcs }
    - { model: sohl-sohl-skill-thro, system: { masteryLevelBase: 48 } }
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
    - { model: sohl-sohl-skill-script, name: Script(Zerin), system: { masteryLevelBase: 81 } }
    - { model: sohl-sohl-skill-embl, system: { masteryLevelBase: 22 } }
    - { model: sohl-sohl-skill-hrld, system: { masteryLevelBase: 33 } }
    - { model: sohl-sohl-skill-law, system: { masteryLevelBase: 28 } }
    - { model: sohl-sohl-miscgear-pence, system: { quantity: 122 } }
    - { model: sohl-sohl-containergear-pouchbuckram }
    - { model: sohl-sohl-armorgear-LLeg }
    - { model: sohl-sohl-armorgear-CShoe }
    - { model: sohl-sohl-armorgear-LTunic }
    - { model: sohl-sohl-weapongear-Kni }
    - { name: Agrik, type: affiliation, system: { shortcode: agrik, subType: divine } }
    - name: Agrik
      type: skill
      system:
        subType: mystical
        shortcode: agrik
        skillBaseFormula: sb(attr.wil, attr.rea)
        masteryLevelBase: 60
    - name: Baptism
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 2
    - name: Blessing
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 2
    - name: Commune
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 2
    - name: Liturgy
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 2
    - name: Marriage
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 2
    - name: Passage of the Soul
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 2
    - name: Agrik's Respite
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 4
    - name: Mamaka's Cry
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 3
    - name: Ak-Syt's Peace
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 2
    - name: Touch of the V'hir
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 3
    - name: Emyn's Cut
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
        levelBase: 2
    - name: Shield of Amana
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: agrik
        assocAffiliationCode: agrik
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

**Height**: 5' 7"
**Frame**: Scant
**Weight**: 119
**Size**: 5
**Comeliness**: Plain
**Complexion**: Swarthy
**Hair Color**: Black
**Eye Color**: Blue
**Voice**: Excellent

# Dossier {#dossier}

**Age**: 24
**Birthday**: 1 Kelen 696
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: 2nd child of 5
**Siblings**: FFFff
**Parentage**: Adopted
**Estrangement**: Unpopular
**Clanhead**: Aunt/Uncle
**Medical**: *Poxmarks (healed)

## Notes

Modifier to Frame of -3 (from 7) {Sex=Female, Species=Human}

Modifier to AttributesAGL of +2 (from 12) {Frame=Scant}

Modifier to AttributesAUR of +2 (from 12) {Sex=Female, Species=Human}

Modifier to EyeColor of +15 (from 13) {Complexion=Swarthy, Species=Human}

Poxmarks mod to Comeliness: -1

119lbs weight resulted in -2 strength mod.

Scant frame resulted in +2 agility mod.

Modifier to StartingEquipment of +100 (from 18) {SocialClass=Serf}
