## 📊 **Key Comparisons**

Compared the wiki page https://www.poe2wiki.net/wiki/Spark against raw data from PoE-Revelation tool.

|**Attribute**|**Raw Data**|**Wiki Data**|**Match Status**|
|---|---|---|---|
|**Id**|`spark`|`Spark`|✅ Yes|
|**DisplayedName**|`Spark`|`Spark`|✅ Yes|
|**Description**|`Launches unpredictable sparks that move randomly until they hit an enemy or expire.`|`Launches a spray of sparking Projectiles that travel erratically along the ground until they hit an enemy or expire.`|🟡 Partial (Wording difference)|
|**WebsiteDescription**|`Lightning is a fickle servant...`|_(Stat text instead)_|❌ No (Different type of description)|
|**Tags/Gem Tags**|`Lightning, Duration, Projectile` (via ActiveSkillTypes)|`Projectile, Lightning, Duration`|✅ Yes|
|**Drop Level**|_(Not provided)_|`1`|❌ Missing|
|**Required Level**|_(Not provided explicitly)_|`1`|❌ Missing|
|**Cast Time**|_(Not provided)_|`0.70`|❌ Missing|
|**Critical Strike Chance**|_(Not provided)_|`9`|❌ Missing|
|**Mana Cost**|_(Not provided)_|`6`|❌ Missing|
|**Projectile Speed Increase**|`spark_projectile_speed_+%`|`(0–19)% increased Projectile Speed`|✅ Yes (Needs mapping validation)|
|**Projectiles Fired**|`spark_num_of_additional_projectiles`|`(6–13)`|✅ Yes (Needs mapping validation)|
|**Projectile Duration**|`spark_skill_effect_duration_+%`|`2 seconds`|✅ Yes (Needs mapping validation)|
|**Additional Projectiles in Chain**|`spark_num_of_additional_projectiles_in_chain`|_(Not explicitly stated in wiki)_|🟡 Extra in raw data|
|**Nova Behavior**|`spark_projectiles_nova`|_(Not explicitly stated in wiki)_|🟡 Extra in raw data|
|**Totem Support**|`spark_totems_from_this_skill_grant_totemified_lightning_tendrils_larger_pulse_interval_-X_to_parent`|_(Not explicitly stated in wiki)_|🟡 Extra in raw data|
|**Weapon Restriction**|_(Empty in raw data)_|_(Not specified on wiki)_|✅ Equivalent (assumed no restriction)|
|**AI Behavior (Column 25)**|`[3, 18, 29, 10, 11...]`|_(Not mentioned in wiki)_|🟡 Extra in raw data|
|**Stat Scaling**|`IsScalable: true` in stats|`Scaling implied by level values`|✅ Yes|
|**Skill Icon**|`Art/2DArt/SkillIcons/spark.dds`|`Spark`|✅ Yes|
|**Skill Image URL**|`http://s3.amazonaws.com/pathofexile/image/skills/intelligence/spark.jpg`|_(Not provided explicitly on wiki)_|🟡 Extra in raw data|
|**Level Progression Stats**|Detailed stats per level in raw data via `Input_StatKeys`|Detailed level breakdown on wiki|✅ Yes (Mapping required for validation)|
|**Release Version**|_(Not provided in raw data)_|`0.1.0`|❌ Missing|
