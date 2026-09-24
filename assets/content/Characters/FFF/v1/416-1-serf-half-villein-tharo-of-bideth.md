---
tags:
  - character
name:
  full: Tharo of Bideth
  title: ""
  given: Tharo
  clan: Bideth
  aliases: []
id: zfHZeMOSxVjH1jmT
packFolder: fffunguilded
shortcode: tharoofbideth
type: being
social:
  occupation: Half-Villein
  class: serf
  society: feudal
  organizations: []
harnworld:
  realm: ""
  ritual:
    - peoni
data:
  icon: fff4161tok
  templatePriority: 1
  gender: male
  species: human
  age: 28
  born: 691/10/3
  height: 1.63
  weight: 55.79
  frame: light
  appearance:
    eye_color: hazel
    hair_color: black
    skin_color: medium
    complexion: average
    extra_features:
      - Moustache
      - scrawny beard
hm3:
  type: character
  attributes:
    str: 14
    sta: 8
    dex: 12
    agl: 16
    int: 18
    aur: 15
    wil: 10
    eye: 11
    hrg: 14
    sml: 10
    voi: 10
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
    - { shortcode: climbing, type: skill, system: { masteryLevel: 63, skillBase: { value: 14 } } }
    - { shortcode: condition, type: skill, system: { masteryLevel: 58, skillBase: { value: 11 } } }
    - { shortcode: jumping, type: skill, system: { masteryLevel: 63, skillBase: { value: 15 } } }
    - { shortcode: stealth, type: skill, system: { masteryLevel: 47, skillBase: { value: 15 } } }
    - { shortcode: throwing, type: skill, system: { masteryLevel: 53, skillBase: { value: 12 } } }
    - { shortcode: awareness, type: skill, system: { masteryLevel: 49, skillBase: { value: 12 } } }
    - { shortcode: intrigue, type: skill, system: { masteryLevel: 51, skillBase: { value: 15 } } }
    - { shortcode: oratory, type: skill, system: { masteryLevel: 33, skillBase: { value: 12 } } }
    - { shortcode: rhetoric, type: skill, system: { masteryLevel: 46, skillBase: { value: 14 } } }
    - { shortcode: singing, type: skill, system: { masteryLevel: 39, skillBase: { value: 11 } } }
    - shortcode: language
      type: skill
      name: "Language: Harnic"
      system:
        masteryLevel: 64
        skillBase:
          value: 14
    - { shortcode: peoni, type: skill, system: { masteryLevel: 13, skillBase: { value: 13 } } }
    - { shortcode: initiative, type: skill, system: { masteryLevel: 65, skillBase: { value: 12 } } }
    - { shortcode: unarmed, type: skill, system: { masteryLevel: 59, skillBase: { value: 14 } } }
    - { shortcode: dodge, type: skill, system: { masteryLevel: 86, skillBase: { value: 16 } } }
    - { shortcode: bow, type: skill, system: { masteryLevel: 45, skillBase: { value: 12 } } }
    - shortcode: bow
      type: skill
      name: Longbow (Bow)
      system:
        shortcode: longbowbow
        masteryLevel: 50
        skillBase:
          value: 12
    - { shortcode: dagger, type: skill, system: { masteryLevel: 64, skillBase: { value: 12 } } }
    - shortcode: agriculture
      type: skill
      system:
        masteryLevel: 48
        skillBase:
          value: 11
    - shortcode: agriculture
      type: skill
      name: Cowcraft (Agriculture)
      system:
        shortcode: cowcraftagriculture
        masteryLevel: 41
        skillBase:
          value: 12
    - { shortcode: foraging, type: skill, system: { masteryLevel: 58, skillBase: { value: 13 } } }
    - { shortcode: heraldry, type: skill, system: { masteryLevel: 31, skillBase: { value: 12 } } }
    - { shortcode: physician, type: skill, system: { masteryLevel: 36, skillBase: { value: 15 } } }
    - { shortcode: survival, type: skill, system: { masteryLevel: 68, skillBase: { value: 15 } } }
    - shortcode: weaponcraft
      type: skill
      system:
        masteryLevel: 30
        skillBase:
          value: 12
    - shortcode: weatherlore
      type: skill
      system:
        masteryLevel: 45
        skillBase:
          value: 13
    - { shortcode: Dgr, type: weapongear }
    - { shortcode: LBw, type: weapongear }
    - { shortcode: beltpouchl3, type: containergear }
    - { shortcode: CvTunic, type: armorgear }
    - { shortcode: CvLeg, type: armorgear }
    - { shortcode: LCap, type: armorgear }
    - { shortcode: LtShoe, type: armorgear }
    - { shortcode: ArwLbw, type: missilegear, name: Arrow (Longbow), system: { quantity: 12 } }
    - { shortcode: quiverlgsh, type: miscgear }
    - { shortcode: pence, type: miscgear, system: { quantity: 54 } }
  system:
    sunsign: skorus-tai
    move: 16
sohl:
  kbcat: archetype
  items:
    - { model: attribute-str, system: { scoreBase: 14 } }
    - { model: attribute-end, system: { scoreBase: 8 } }
    - { model: attribute-dex, system: { scoreBase: 12 } }
    - { model: attribute-agl, system: { scoreBase: 16 } }
    - { model: attribute-per, system: { scoreBase: 12 } }
    - { model: attribute-snt, system: { scoreBase: 10 } }
    - { model: attribute-cml, system: { scoreBase: 9 } }
    - { model: attribute-aur, system: { scoreBase: 15 } }
    - { model: attribute-wil, system: { scoreBase: 10 } }
    - { model: attribute-rea, system: { scoreBase: 18 } }
    - { model: attribute-cre, system: { scoreBase: 12 } }
    - { model: attribute-emp, system: { scoreBase: 12 } }
    - { model: attribute-elo, system: { scoreBase: 10 } }
    - { model: attribute-mor, system: { scoreBase: 7 } }
    - { model: attribute-voi, system: { scoreBase: 10 } }
    - { model: skill-archery, name: Longbow (Bow), system: { masteryLevelBase: 50 } }
    - { model: skill-awar, system: { masteryLevelBase: 49 } }
    - { model: skill-chrm }
    - { model: skill-clmb, system: { masteryLevelBase: 63 } }
    - { model: skill-cmd }
    - { model: skill-cook }
    - { model: skill-dnce }
    - { model: skill-dscr }
    - { model: skill-draw }
    - { model: skill-folklr }
    - { model: skill-guil }
    - { model: skill-init, system: { masteryLevelBase: 65 } }
    - { model: skill-shok }
    - { model: skill-intr, system: { masteryLevelBase: 51 } }
    - { model: skill-jump, system: { masteryLevelBase: 63 } }
    - { model: skill-melee, system: { masteryLevelBase: 64 } }
    - { model: skill-dge, system: { masteryLevelBase: 86 } }
    - { model: skill-pysn, system: { masteryLevelBase: 36 } }
    - { model: skill-ridg }
    - { model: skill-sing, system: { masteryLevelBase: 39 } }
    - { model: skill-stlth, system: { masteryLevelBase: 47 } }
    - { model: skill-srvl, system: { masteryLevelBase: 68 } }
    - { model: skill-spirit }
    - { model: skill-swim }
    - { model: skill-thtcs }
    - { model: skill-thro, system: { masteryLevelBase: 53 } }
    - { model: skill-bflkbite }
    - { model: skill-bflkgrab }
    - { model: skill-bflkheadbutt }
    - { model: skill-bflkkick }
    - { model: skill-limbblock }
    - { model: skill-press }
    - { model: skill-bflkpunch }
    - { model: skill-trip }
    - { model: mysticalability-sprt }
    - { model: skill-lang, name: "Language: Harnic", system: { masteryLevelBase: 64 } }
    - model: skill-agri
      name: Cowcraft (Agriculture)
      system:
        masteryLevelBase: 41
    - { model: skill-hrld, system: { masteryLevelBase: 31 } }
    - { model: skill-wpnc, system: { masteryLevelBase: 30 } }
    - { model: weapongear-Dgr }
    - { model: weapongear-LBw50 }
    - { model: containergear-beltpouchl3 }
    - { model: armorgear-CvTunic }
    - { model: armorgear-CvLeg }
    - { model: armorgear-LCap }
    - { model: armorgear-LtShoe }
    - { model: containergear-quiverlgsh }
    - { model: miscgear-pence, system: { quantity: 54 } }
    - { name: Peoni, type: affiliation, system: { shortcode: peoni, subType: divine } }
    - name: Peoni
      type: skill
      system:
        subType: mystical
        shortcode: peoni
        skillBaseFormula: sb(attr.wil, attr.rea)
        masteryLevelBase: 13
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

![[fff4161|Tharo of Bideth]]{float: top-left}

**Apparent Age**: Adult
**Culture**: Feudal
**Social Class**: Serf
**Height**: 5 ft 4 in
**Frame**: Light
**Weight**: 123 lb
**Appearance**: Average
**Hair Colour**: Black
**Eye Colour**: Hazel
**Voice**: Average
**Obvious Medical Traits**: None
**Apparent Occupation**: Half-villein
**Apparent Wealth**: Some
**Weapons**: Longbow, Dagger
**Armour**: None
**Companions**: None
**Other obvious features**: Moustache and scrawny beard

# Dossier {#dossier}

**Title**: FFF 416-1 Serf Half Villein
**Birthday**: 3 Ilvin 691
**Appearance**: Age 28, height 5' 4", light frame, weight 123 lb, average appearance, medium complexion, black hair, hazel eyes
**Medical/Psyche**: None
**Size**: 5
**Armor**: Rough cloth tunic, leggings and cap, leather shoes, longbow and dagger
**Other Equipment**: Belt pouch
**Valuables**: 54d in silver
**Notes**:

## Biography

Born on a small Chybisan manor, Tharo is the only child of half-villein parents. They died when he was twenty-two and he inherited his father's acres. He is an uninspired farmer, but gets by. His twelve acres easily support him in comfort. He is unmarried.

Three years ago, word reached the manor lord that there was a group of hostile Pagaelin threatening the village. The knight summoned two yeomen and six militia, including Tharo, and rode out to track them down. Unfortunately, they were ambushed and all but Tharo and the knight were killed. Tharo survived because he turned coward and fled, though in the chaos no one noticed. Eventually, he returned to find the men slaughtered and the knight badly injured and left for dead. He managed to carry his lord home, where with luck and a good Peonian physician he survived. Unaware of Tharo's cowardice, the knight hailed him a great hero.

Since then, Tharo has been relieved of all work obligations on his lord's land. He has become the lord's favourite, often being chosen as a messenger. While Tharo is away, the Reeve must find other people to work his land. This has made him unpopular with the other villagers, already struggling after the loss of so many of the best and strongest men. Tharo worries constantly that someone will discover his secret and so has developed severe stomach ulcers, which cause recurrent nausea. Despite his failings, Tharo is a very imaginative, clever and resourceful person. A barracks room lawyer, he has developed a very arrogant front when dealing with the other villagers (especially the Reeve). This hides grave insecurities.

## Adventure Hooks

Personal Messenger. Tharo's lord has heard of the PC's reputation, is a distant relation or shares past history with them. He dispatches Tharo to find the PCs to ask them to come help him hunt down the Pagaelin that slaughtered the militia. Tharo has spent weeks trying to catch up with them and is anxious to return to the village.

Village Hero. The PCs are passing through the village and are invited to dine with the lord. If one of the PCs has a bow, he suggests a "friendly" wager against the local "hero". Tharo is not much of a challenge and looses. The lord becomes upset, refusing to make good his wager.

Reinforcements. The PCs need help. They ask the local lord and he volunteers Tharo. He tells them he is an outstanding longbowman and solid soldier. If the PCs are foolish enough to trust him, he turns coward and flees at a critical moment.

## Credits

This character is taken from "Friends, Foes, and Followers, Vol. 1" on Lythia.com (<https://www.lythia.com/game_aides/friends-foes-followers-volume-1/>), by Kerry Mould, with illustrations by Richard Luscheck and Juha Makkonen, and is "fanon", a derivative work of copyrighted material by Columbia Games Inc. and N. Robin Crossby.
