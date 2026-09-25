---
tags:
  - character
name:
  full: Masyne of Charaen
  title: ""
  given: Masyne
  clan: Charaen
  aliases: []
id: KCkLUsp4GkjhKQX2
packFolder: extrasclergy
shortcode: masyneofcharaen
type: being
social:
  occupation: Cleric/Morgath
  class: serf
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
  age: 22
  born: 698/8/28
  height: 1.57
  weight: 110.22
  frame: light
  appearance:
    eye_color: hazel
    hair_color: blonde
    skin_color: medium
    complexion: average
    extra_features: []
hm3:
  type: character
  attributes:
    str: 6
    sta: 11
    dex: 5
    agl: 10
    int: 13
    aur: 14
    wil: 16
    eye: 17
    hrg: 17
    sml: 10
    voi: 15
    cml: 9
    mor: 7
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 28 } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 55 } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 32 } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 48 } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 40 } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 64 } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: language, type: skill, name: Language(Azeri), system: { masteryLevel: 42 } }
    - shortcode: language
      type: skill
      name: Language(Ormauk)
      system:
        shortcode: languageormauk
        masteryLevel: 42
    - shortcode: language
      type: skill
      name: Language, Serf
      system:
        shortcode: languageserf
        masteryLevel: 64
    - { shortcode: mentalconflict, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 39 } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 60 } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 45 } }
    - { shortcode: script, type: skill, name: Script(Lakaise), system: { masteryLevel: 82 } }
    - shortcode: script
      type: skill
      name: Script(Nuvesarl)
      system:
        shortcode: scriptnuvesarl
        masteryLevel: 82
    - { shortcode: dagger, type: skill, system: { masteryLevel: 36 } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 28 } }
    - { shortcode: drawing, type: skill, system: { masteryLevel: 26 } }
    - { shortcode: embalming, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: folklore, type: skill, system: { masteryLevel: 39 } }
    - { shortcode: heraldry, type: skill, system: { masteryLevel: 24 } }
    - shortcode: hidework
      type: skill
      name: Human Skin (Hidework)
      system:
        masteryLevel: 20
    - { shortcode: law, type: skill, system: { masteryLevel: 30 } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 22 } }
    - { shortcode: tarotry, type: skill, system: { masteryLevel: 32 } }
    - { shortcode: woodcraft, type: skill, name: Masks (Woodcraft), system: { masteryLevel: 16 } }
    - { shortcode: morgath, type: skill, system: { masteryLevel: 56 } }
    - { shortcode: morgathbaptism, type: invocation }
    - { shortcode: morgathblessing, type: invocation }
    - { shortcode: morgathcommune, type: invocation }
    - { shortcode: morgathliturgy, type: invocation }
    - { shortcode: morgathmarriage, type: invocation }
    - { shortcode: morgathpassageofthesoul, type: invocation }
    - { shortcode: myvriaskiss, type: invocation }
    - { shortcode: eyesofklyss, type: invocation }
    - { shortcode: heartofdarkness, type: invocation }
    - { shortcode: throatofklyss, type: invocation }
    - { shortcode: speakwithdead, type: invocation }
    - { shortcode: pence, type: miscgear, system: { quantity: 80 } }
    - { shortcode: pursebuckram, type: containergear }
    - { shortcode: LLeg, type: armorgear }
    - { shortcode: CShoe, type: armorgear }
    - { shortcode: LTunic, type: armorgear }
    - { shortcode: Kni, type: weapongear }
  system:
    species: human
    sunsign: tarael
    move: 12
sohl:
  kbcat: archetype
  items:
    - { model: sohl-sohl-attribute-str, system: { scoreBase: 6 } }
    - { model: sohl-sohl-attribute-end, system: { scoreBase: 11 } }
    - { model: sohl-sohl-attribute-dex, system: { scoreBase: 5 } }
    - { model: sohl-sohl-attribute-agl, system: { scoreBase: 10 } }
    - { model: sohl-sohl-attribute-per, system: { scoreBase: 17 } }
    - { model: sohl-sohl-attribute-snt, system: { scoreBase: 10 } }
    - { model: sohl-sohl-attribute-cml, system: { scoreBase: 9 } }
    - { model: sohl-sohl-attribute-aur, system: { scoreBase: 14 } }
    - { model: sohl-sohl-attribute-wil, system: { scoreBase: 16 } }
    - { model: sohl-sohl-attribute-rea, system: { scoreBase: 13 } }
    - { model: sohl-sohl-attribute-cre, system: { scoreBase: 18 } }
    - { model: sohl-sohl-attribute-emp, system: { scoreBase: 15 } }
    - { model: sohl-sohl-attribute-elo, system: { scoreBase: 17 } }
    - { model: sohl-sohl-attribute-mor, system: { scoreBase: 7 } }
    - { model: sohl-sohl-attribute-voi, system: { scoreBase: 15 } }
    - { model: sohl-sohl-skill-archery }
    - { model: sohl-sohl-skill-awar, system: { masteryLevelBase: 64 } }
    - { model: sohl-sohl-skill-chrm }
    - { model: sohl-sohl-skill-clmb, system: { masteryLevelBase: 28 } }
    - { model: sohl-sohl-skill-cmd }
    - { model: sohl-sohl-skill-cook }
    - { model: sohl-sohl-skill-dnce }
    - { model: sohl-sohl-skill-dscr }
    - { model: sohl-sohl-skill-draw, system: { masteryLevelBase: 26 } }
    - { model: sohl-sohl-skill-folklr, system: { masteryLevelBase: 39 } }
    - { model: sohl-sohl-skill-guil }
    - { model: sohl-sohl-skill-init, system: { masteryLevelBase: 56 } }
    - { model: sohl-sohl-skill-shok }
    - { model: sohl-sohl-skill-intr, system: { masteryLevelBase: 60 } }
    - { model: sohl-sohl-skill-jump, system: { masteryLevelBase: 32 } }
    - { model: sohl-sohl-skill-melee, system: { masteryLevelBase: 36 } }
    - { model: sohl-sohl-skill-dge }
    - { model: sohl-sohl-skill-pysn, system: { masteryLevelBase: 22 } }
    - { model: sohl-sohl-skill-ridg }
    - { model: sohl-sohl-skill-sing, system: { masteryLevelBase: 45 } }
    - { model: sohl-sohl-skill-stlth, system: { masteryLevelBase: 48 } }
    - { model: sohl-sohl-skill-srvl }
    - { model: sohl-sohl-skill-spirit }
    - { model: sohl-sohl-skill-swim }
    - { model: sohl-sohl-skill-thtcs }
    - { model: sohl-sohl-skill-thro, system: { masteryLevelBase: 40 } }
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
    - { model: sohl-sohl-skill-script, name: Script(Nuvesarl), system: { masteryLevelBase: 82 } }
    - { model: sohl-sohl-skill-embl, system: { masteryLevelBase: 30 } }
    - { model: sohl-sohl-skill-hrld, system: { masteryLevelBase: 24 } }
    - model: sohl-sohl-skill-hide
      name: Human Skin (Hidework)
      system:
        masteryLevelBase: 20
    - { model: sohl-sohl-skill-law, system: { masteryLevelBase: 30 } }
    - { model: sohl-sohl-mysticalability-tarot, system: { masteryLevelBase: 32 } }
    - { model: sohl-sohl-miscgear-pence, system: { quantity: 80 } }
    - { model: sohl-sohl-containergear-pouchbuckram }
    - { model: sohl-sohl-armorgear-LLeg }
    - { model: sohl-sohl-armorgear-CShoe }
    - { model: sohl-sohl-armorgear-LTunic }
    - { model: sohl-sohl-weapongear-Kni }
    - { name: Morgath, type: affiliation, system: { shortcode: morgath, subType: divine } }
    - name: Morgath
      type: skill
      system:
        subType: mystical
        shortcode: morgath
        skillBaseFormula: sb(attr.wil, attr.rea)
        masteryLevelBase: 56
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
    - name: Eyes of Klyss
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
    - name: Throat of Klyss
      type: mysticalability
      system:
        subType: divineincantation
        assocSkillCode: morgath
        assocAffiliationCode: morgath
        levelBase: 3
    - name: Speak with Dead
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

**Height**: 5' 2"
**Frame**: Light
**Weight**: 243
**Size**: 9
**Comeliness**: Average
**Complexion**: Medium
**Hair Color**: Blond
**Eye Color**: Hazel
**Voice**: Pleasant

# Dossier {#dossier}

**Age**: 22
**Birthday**: 28 Halane 698
**Culture**: Feudal
**Social Class**: Serf
**Sibling Rank**: 5th child of 5
**Siblings**: MmMmF
**Parentage**: Fostered
**Estrangement**: Average
**Clanhead**: Aunt/Uncle

## Notes

Modifier to Frame of -3 (from 9) {Sex=Female, Species=Human}

Modifier to AttributesAGL of +1 (from 8) {Frame=Light}

Modifier to AttributesAUR of +2 (from 12) {Sex=Female, Species=Human}

117lbs weight resulted in -2 strength mod.

Light frame resulted in +1 agility mod.

Modifier to StartingEquipment of +100 (from 34) {SocialClass=Serf}
