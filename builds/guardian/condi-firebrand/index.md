---
title: Condi Firebrand
sections:
  - type: mdx
    title: Overview
    content: >-
      The **<Specialization text="Condi Firebrand" name="Firebrand"/>** can
      provide permanent <Boon name="Quickness"/> (if necessary) to the party
      while dealing high consistent DPS. Your tomes are by far your most
      important skills, they enable you to do great DPS as well as support and
      heal your allies. Thanks to those, the build is able to adapt to various
      situations with <Boon name="Stability"/>, <Boon name="Resistance"/>,
      reflects and pulls.


      This build has tremendous amounts of self-sustain and is therefore also a great build for soloing content:


      - Permanent <Boon name="Quickness"/>.


      - Some <Boon name="Might"/> uptime.


      - <Skill id="41780"/> for heals.


      - <Skill id="42259"/> for <Boon name="Stability"/>, <Boon name="Resistance"/>, reflects and damage reduction.


      - Optionally: <Skill name="litanyofwrath"/> for a 6s long high HP regeneration.


      Overall this build is one of the best picks for newer players, for PuGs as <Boon name="Quickness"/> provider or for people that want to be more independent of their groups.
  - type: null
    title: Equipment
    content: >-
      <CharacterWithAr> 

      <Character title="162 Agony Resistance" 
                 gear={{ "profession": "Guardian",
                  "weight":"Heavy", "gear":[
                  "Viper",
                  "Viper",
                  "Viper",
                  "Viper",
                  "Viper",
                  "Viper",
                  "Sinister",
                  "Sinister",
                  "Viper",
                  "Sinister",
                  "Sinister",
                  "Sinister",
                  "Viper",
                  "Viper"
              ], "attributes":{
                  "Health": 14145,
                  "Armor": 2514,
                  "Power": 2869,
                  "Precision": 2085,
                  "Toughness": 1243,
                  "Vitality": 1250,
                  "Ferocity": 300,
                  "Condition Damage": 3188,
                  "Expertise": 451,
                  "Concentration": 243,
                  "Healing Power": 250,
                  "Agony Resistance": 162,
                  "Condition Duration": 0.30066666666666666,
                  "Boon Duration": 0.162,
                  "Critical Chance": 0.8666666666666666,
                  "Critical Damage": 1.70,
                  "Burning Duration": 0.70,
                  "Resolution Duration": 0.25,
                  "Effective Power": 7222.552095833332,
                  "Power DPS": 6674.672710820176,
                  "Burning Damage": 1078.3664999999999,
                  "Burning Stacks": 30.8,
                  "Burning DPS": 33213.6882,
                  "Bleeding Damage": 319.92,
                  "Bleeding Stacks": 6.113133333333334,
                  "Bleeding DPS": 1955.7136160000002,
                  "Poison Damage": 337.17,
                  "Poison Stacks": 0,
                  "Poison DPS": 0,
                  "Torment Damage": 478.08000000000004,
                  "Torment Stacks": 1.5608,
                  "Torment DPS": 746.187264,
                  "Confusion Damage": 319.92,
                  "Confusion Stacks": 0,
                  "Confusion DPS": 0,
                  "Damage": 42590.26179082017,
                  "Effective Health": 48895728.75,
                  "Survivability": 24858.021733604473,
                  "Effective Healing": 465,
                  "Healing": 465
              }, "runeId":24765, "runeName":"Balthazar", "infusions":[
                  37130,
                  37130,
                  37130,
                  37130,
                  37130,
                  37130,
                  37130,
                  37130,
                  37130,
                  37130,
                  37130,
                  37130,
                  37130,
                  37130,
                  37130,
                  37130,
                  37130,
                  37130
              ], "weapons":{
                  "weapon1MainType": "Axe",
                  "weapon1MainSigil1": "Earth",
                  "weapon1OffType": "Torch",
                  "weapon1OffSigil": "Bursting",
                  "weapon2MainType": "Scepter",
                  "weapon2MainSigil1": "Geomancy"
              }, "consumables":{
                  "foodId": "91878",
                  "utility": "toxic-focusing-crystal",
                  "infusion": "Malign +9 Agony Infusion"
              },
                "skills": {
                  "heal": "Mantra of Solace",
                  "utility1": "Mantra of Potence",
                  "utility2": "Purging Flames",
                  "utility3": "Sanctuary",
                  "elite": "Feel my Wrath"
                } 
              }}
      > 


      Note that this build variant gains boon duration from the <Item id="79722"/> and <Item id="48916"/>. To keep up permanent <Boon name="Quickness"/> you will need to reach 24.6% boon duration. For longer fights drop <Item id="24560"/> for <Item id="72339"/>.

      You will want the following weapons to swap to durning fractal runs:

      - Greatsword for pulling adds in Nightmare CM after MAMA and some T4s

      - A staff for <Boon name="Might"/> pre-stacking. 

      - If you have low might uptime you can change <Item id="24560"/> to <Item id="24562"/>. 


      </Character> 

      </CharacterWithAr>
  - type: mdx
    title: Build
    content: >-
      <Grid>

      <GridItem sm="7">

      <Traits traits1="Radiance" traits1Selected="Right-Hand Strength,Radiant Fire,Amplified Wrath" traits2="Virtues" traits2Selected="masterofconsecrations,glacialheart,permeatingwrath" traits3="Firebrand" traits3Selected="Liberators Vow,Stalwart Speed,Loremaster"/>If your team has a hard time applying <Condition name="Vulnerability"/> you can swap Virtues trait line with Zeal and replace <Skill name="purgingflames"/> with <Skill name="swordofjustice"/>. This will help you to maintain <Condition name="Vulnerability"/> on enemies better.<Traits traits1Id="42" traits1="Zeal" traits1SelectedIds="1925,1556,635" unembossed/>


      <Warning>

      This build provides permanent <Boon name="Quickness"/>. For different variants, such as organized Sunqua Peak groups or full DPS, please scroll down.

      </Warning>


      <Card title="Defiance Bar Damage">


      |                                              |                                                                                |

      | -------------------------------------------- | ------------------------------------------------------------------------------ |

      | <Skill id="45402"/>                          | 150 damage                                                                     |

      | <Skill name="Hammer of Wisdom"/>             | 200 damage                                                                     |

      | <TomeSkill name="Chapter 3: Heated Rebuke"/> in <Skill name="Tome of Justice"/> | 150 damage                                  |

      | <Skill name="Sanctuary"/>                    | 1050 damage over 7 seconds (thanks to <Trait name="Master of Consecrations"/>) |
       
      | <Skill name="Chains of light"/>              | <Condition name="Immobile"/> 50/s                                              |
        
      | <TomeSkill name="Chapter 2: Daring Challenge"/> | <Condition name="Taunt"/> 75/s |


      </Card>

      </GridItem>


      <GridItem sm="5">

      <Card title="Situational Skills">


      |                                                        |                                                                                     |

      | ------------------------------------------------------ | ----------------------------------------------------------------------------------- |

      | <Skill id="9246" size="big" disableText/>              | A 1,200 range teleport to an ally.                                                  |

      | <Skill name="Hallowed Ground" size="big" disableText/> | When <Boon name="Stability"/> is needed.                                            |

      | <Skill id="9153" size="big" disableText/>              | When <Boon name="Stability"/> or a stunbreak is needed.                             |

      | <Skill id="9125" size="big" disableText/>              | Deals an additional 200 defiance bar damage.                                        |

      | <Skill id="9251" size="big" disableText/>              | A stationary reflect lasting for 10 seconds.                                        |

      | <Skill id="43357" size="big" disableText/>             | When <Boon name="Stability"/> or a stunbreak is needed.                             |

      | <Skill id="9247" size="big" disableText/>              | A 1200 range teleport to an enemy.                                                  |

      | <Skill name="Purging flames" size="big" disableText/>  | Cleanses conditions.                                                                |

      | <Skill name="Sanctuary" size="big" disableText/>       | Huge CC and projectile destruction.                                                 |

      | <Skill name="Mantra of lore" size="big" disableText/>  | Cleanses multiple conditions thanks to charges.                                     |

      | <Skill name="renewed focus" size="big" disableText/>   | Recharges all virtue skills, grants <Effect name="Invulnerability"/> for 3 seconds. |


      </Card>

      </GridItem>

      </Grid>


      <Divider text="Build Variants"/>


      <Card title="Full DPS variant">


      You can play <Specialization text="Condi Firebrand" name="Firebrand"/> as a DPS by making minor adjustments to the build.


      <Grid>

      <GridItem sm="4">

      <Skills heal="Mantra of Solace" utility1="purgingflames" utility2="" utility3="Sanctuary" elite="Renewed Focus" unembossed/>

      </GridItem>


      <GridItem sm="8">

      <Traits traits1="Firebrand" traits1Selected="Unrelenting Criticism,Legendary Lore,Loremaster" unembossed/>

      </GridItem>

      </Grid>

      </Card>


      <Card title="Multiple DPS Firebrands">


      This build assumes you are playing in a comp with multiple <Specialization name="Firebrand" text="Condi Firebrands"/> and allows <Trait name="Legendary Lore"/> and <Skill name="Renewed Focus"/> to be played for more DPS and an additional Tome reset. You need at least 2 <Specialization name="Firebrand" text="Firebrands"/> to play this build to maintain <Boon name="Quickness"/>!


      <Grid>

      <GridItem sm="4">

      <Skills heal="Mantra of Solace" utility1="purgingflames" utility2="Mantra of Potence" utility3="Sanctuary" elite="Renewed Focus" unembossed/>

      </GridItem>


      <GridItem sm="8">

      <Traits traits1="Firebrand" traits1Selected="Liberators Vow,Legendary Lore,Loremaster" unembossed/>

      </GridItem>

      </Grid>

      </Card>
  - type: mdx
    title: Details
    content: >-
      To keep up <Boon name="Quickness"/>:


      - Use <Skill name="Feel My Wrath"/> whenever ready


      - Use <Skill name=" mantraofsolace"/> and <Skill name="mantraofpotence"/>. Keep in mind that <Skill name="mantraofsolace"/> does <Boon name="Quickness"/> only every seven seconds (<Trait name="liberatorsvow"/>)!


      - Only use these skills close to your allies - try to "puke" on them with the mantras


      - Keep in mind that equipping or stowing a tome grants you 3 seconds of <Boon name="Quickness"/> every 8 seconds thanks to <Trait name="swift scholar"/>!


      Tomes are very useful when no other skills are ready. <Skill name="Tome of Justice"/> also gets refreshed every time an enemy dies (works with anomalies at Artsariiv/Arkk, knights at MAMA and hallucinations at Siax).


      <Skill name="Tome of Courage"/> and <Skill name="Tome of Resolve"/> are great for high incoming damage scenarios.


      - <Skill name="Tome of Justice"/> (F1):

        - <TomeSkill name="Chapter 1: Searing Spell"/>

        - <TomeSkill name="Chapter 2: Ignite Burst"/>

        - <TomeSkill name="Chapter 3: Heated Rebuke"/>

        - <TomeSkill name="Chapter 4: Scorched Aftermath"/>

        - <TomeSkill name="Epilogue: Ashes of the Just"/>

      - <Skill name="Tome of Resolve"/> (F2):

        - <TomeSkill name="Chapter 1: Desert Bloom"/>

        - <TomeSkill name="Chapter 2: Radiant Recovery"/>

        - <TomeSkill name="Chapter 3: Azure Sun"/>

        - <TomeSkill name="Chapter 4: Shining River"/>

        - <TomeSkill name="Epilogue: Eternal Oasis"/>

      - <Skill name="Tome of Courage"/> (F3):

        - <TomeSkill name="Chapter 1: Unflinching Charge"/>

        - <TomeSkill name="Chapter 2: Daring Challenge"/>

        - <TomeSkill name="Chapter 3: Valiant Bulwark"/>

        - <TomeSkill name="Chapter 4: Stalwart Stand"/>

        - <TomeSkill name="Epilogue: Unbroken Lines"/>

rating: Meta
role: Condi Damage
profession: Guardian
specialization: Firebrand
skills: []
conditions:
  - Burning
  - Vulnerability
  - Crippled
  - Bleeding
boons:
  - name: Quickness
    uptime: 100%
    variant: party
  - name: Stability
    uptime: on demand
    variant: party
  - name: Aegis
    uptime: on demand
    variant: party
code: "[&DQEQGi4fPjpLF0sXTAFIAXoWehYxATYBiRKJEgAAAAAAAAAAAAAAAAAAAAA=]"
classification:
  - 5
  - 4
  - 5
  - 2
  - 3
compositions:
  - name: _CRGB
hasCMGuide: false
date: 2021-10-03T12:25:49.308Z
benchmark:
  small:
    dps: 36732
    by: TJ [SC]
    youtube: U1yYDskt3Cw
---

<Divider text="Rotation / Skill usage"/>

<Grid>
<GridItem sm="6">
<Card title="Rotation">

<Warning>

**Make sure to only press <Skill id="9089"/> three times (twice to throw the projectile and once to activate the skill initially) or you will cancel a wasted cast! Never interrupt your axe auto attack chain! Keep <Skill name="purgingflames"/> on cooldown!**
</Warning>

Starting on Axe:

1.  <Skill name="purgingflames"/>

2.  <Skill id="9104"/> (Torch 4)

3.  <Skill name="Symbol of Vengeance"/> (Axe 2)

4.  <Skill id="9089"/> (Torch 4)

5.  Weapon Swap

6.  <Skill name="Symbol of Punishment"/> (Scepter 2)

7.  <Skill id="9089"/> (Torch 4)

8.  <Skill name="Tome of Justice"/> (F1)

9.  <TomeSkill name="Chapter 2: Ignite Burst"/>

10. <TomeSkill name="Chapter 4: Scorched Aftermath"/>

11. <TomeSkill name="Epilogue: Ashes of the Just"/>

12. <TomeSkill name="Chapter 1: Searing Spell"/>

13. <TomeSkill name="Chapter 2: Ignite Burst"/>

14. <Skill name="Cleansing Flame"/> (Torch 5)

15. <Skill name="Symbol of Punishment"/> (Scepter 2)

16. <Skill id="9104"/> (Torch 4)

17. **Two <Skill id="9089"/>** (Torch 4)

18. Weapon Swap

19. <Skill name="Symbol of Vengeance"/> (Axe 2)

20. <Skill name="Blazing Edge"/> (Axe 3)

When <Skill name="Tome of Justice"/> is off cd you just repeat this rotation.
</Card>
</GridItem>

<GridItem sm="6">
<Card title="Golem rotation">

<Video youtube="XbbfgCUGwlY" caption="by Frenzy"/>
</Card>

<Card title="Precasting">

<Warning>

The most important part is to get the precast of Ashes of the Just right! You have to start the fight quickly to not lose the stacks since they only last 10 seconds!
</Warning>

1.  Use <Skill name="hallowedground"/>

2.  Blast a firefield with <Skill name="holystrike"/> and/or <Skill name="Hammer of Wisdom"/>

3.  While casting: Use 3 charges of <Skill name="mantraofpotence"/> and share <Skill name="mantraofsolace"/> (keep in mind that <Skill name="mantraofsolace"/> only shares <Boon name="Quickness"/> once every 7 seconds thanks to <Trait name=" liberators vow"/>)

4.  Use <Skill name="Feelmywrath"/>

5.  Open <Skill id="44364"/> and use <TomeSkill name="Epilogue: Ashes of the Just"/>

6.  Take the _Mistlock Singularity_

7.  Use <Skill name="Feelmywrath"/> again

On <Instability name="Boon Overload"/> days you can drop <Skill name="Feelmywrath"/> for <Skill name="Renewed Focus"/>:

</Card>
</GridItem>
</Grid>
