## 以下是 Minecraft：基岩版中可用于实体 JSON 文件的所有可用过滤器的列表。

| 组件 | 描述 |
| --- | --- |
| [actor_health](./list/actor_health.md) |  允许创建者测试实体的健康状况。 |
| [all_slots_empty](./list/all_slots_empty.md) |  当主题实体的指定设备位置完全为空时返回 true。 |
| [any_slot_empty](./list/any_slot_empty.md) |  当主题实体的指定设备位置有任何空槽时返回 true。 |
| [bool_property](./list/bool_property.md) |  允许创建者将实体属性与布尔值进行比较。 |
| [clock_time](./list/clock_time.md) |  允许创建者将当前时间与范围 (0.0, 1.0) 内的浮点值进行比较。 |
| [distance_to_nearest_player](./list/distance_to_nearest_player.md) |  将到最近玩家的距离与浮点值进行比较。 |
| [distance_to_nearest_player](./list/distance_to_nearest_player.md) |  将到最近玩家的距离与浮点值进行比较。 |
| [enum_property](./list/enum_property.md) |  当枚举实体属性与提供的值匹配时返回 true。 |
| [float_property](./list/float_property.md) |  当浮点实体属性与提供的值匹配时返回 true。 |
| [has_ability](./list/has_ability.md) |  当主题实体具有指定能力时返回 true。 |
| [has_biome_tag](./list/has_biome_tag.md) |  测试对象所在的生物群落是否具有指定的标签。 |
| [has_component](./list/has_component.md) |  当主题实体包含命名组件时返回 true。 |
| [has_container_open](./list/has_container_open.md) |  当主体 Player 实体打开容器时返回 true。 |
| [has_damage](./list/has_damage.md) |  当主体实体收到指定的伤害类型时返回 true。 |
| [has_equipment](./list/has_equipment.md) |  测试主题实体的指定槽中是否存在命名项。 |
| [has_mob_effect](./list/has_mob_effect.md) |  测试受试者是否具有指定的生物效果。 |
| [has_nametag](./list/has_nametag.md) | 当主题实体包含命名组件时返回 true。 |
| [has_property](./list/has_property.md) | 测试主题实体的属性是否存在。 |
| [has_ranged_weapon](./list/has_ranged_weapon.md) | 当主体实体持有弓或十字弓等远程武器时返回 true。 |
| [has_silk_touch](./list/has_silk_touch.md) | 测试受试者是否持有具有丝绸触感的物品。 |
| [has_tag](./list/has_tag.md) | 如果主题实体具有提供的标签，则返回 true。 |
| [has_target](./list/has_target.md) | 如果主题实体具有有效目标，则返回 true。 |
| [has_trade_supply](./list/has_trade_supply.md) | 测试目标是否还有剩余贸易供应。 如果目标无法交易，则返回 false。 |
| [hourly_clock_time](./list/hourly_clock_time.md) | 将当前 24 小时时间与 [0, 24000] 范围内的 int 值进行比较 |
| [in_block](./list/in_block.md) |  当主题实体位于指定的块类型内时返回 true。 |
| [in_caravan](./list/in_caravan.md) |  如果主体实体位于商队中，则返回 true。 |
| [in_clouds](./list/in_clouds.md) |  当主题实体位于云中时返回 true。 |
| [in_contact_with_water](./list/in_contact_with_water.md) |  当主体实体与任何水接触时返回 true：水、雨水、溅水瓶。 |
| [in_lava](./list/in_lava.md) |  当主体实体位于岩浆中时返回 true。 |
| [in_nether](./list/in_nether.md) |  当主体实体位于下界时返回 true。 |
| [in_water_or_rain](./list/in_water_or_rain.md) |  当主体实体处于水中或雨中时返回 true。 |
| [in_water](./list/in_water.md) |  当主体实体在水中时返回 true。 |
| [inactivity_timer](./list/inactivity_timer.md) |  测试指定的不活动持续时间（以秒为单位）。 |
| [int_property](./list/int_property.md) |  当 int 实体属性与提供的值匹配时返回 true。 |
| [is_altitude](./list/is_altitude.md) |  根据提供的值测试当前高度。 |
| [is_avoiding_mobs](./list/is_avoiding_mobs.md) |  如果主体实体正在逃离其他生物，则返回 true。 |
| [is_baby](./list/is_baby.md) |  当主体实体是婴儿时返回 true。 |
| [is_biome](./list/is_biome.md) |  测试对象当前是否位于指定的生物群系中。 |
| [is_block](./list/is_block.md) |  当方块具有给定名称时返回 true。 |
| [is_brightness](./list/is_brightness.md) |  对照 (0.0, 1.0) 范围内提供的值测试当前亮度。 |
| [is_climbing](./list/is_climbing.md) |  如果主题实体正在攀爬，则返回 true。 |
| [is_color](./list/is_color.md) |  如果主题实体是指定颜色，则返回 true。 |
| [is_daytime](./list/is_daytime.md) |  白天返回 true。 |
| [is_difficulty](./list/is_difficulty.md) |  测试游戏当前的难度级别。 |
| [is_family](./list/is_family.md) |  当主题实体是命名族的成员时返回 true。 |
| [is_game_rule](./list/is_game_rule.md) |  测试指定的游戏规则是否处于活动状态。 |
| [is_humid](./list/is_humid.md) |  测试对象是否处于潮湿的区域。 |
| [is_immobile](./list/is_immobile.md) |  如果主体实体不动则返回 true。 如果一个实体缺乏人工智能目标组件、刚刚改变了维度，或者它是一个生物并且没有生命值，那么该实体是不可移动的。 |
| [is_in_village](./list/is_in_village.md) |  测试主体是否在村庄范围内。 |
| [is_leashed](./list/is_leashed.md) |  如果主体实体受到束缚，则返回 true。 |
| [is_leashed_to](./list/is_leashed_to.md) |  如果主题实体与调用实体相连，则返回 true。 |
| [is_mark_variant](./list/is_mark_variant.md) |  如果主题实体是提供的标记变体编号，则返回 true。 |
| [is_missing_health](./list/is_missing_health.md) |  测试对象是否不完全健康。 |
| [is_moving](./list/is_moving.md) | 如果主体实体正在移动，则返回 true。|
| [is_owner](./list/is_owner.md) | 如果主题实体是调用实体的所有者，则返回 true。|
| [is_persistent](./list/is_persistent.md) | 测试主体的持久性是否与传入的布尔值匹配。|
| [is_raider](./list/is_raider.md) | 如果主体实体是袭击者，则返回 true。|
| [is_riding](./list/is_riding.md) | 如果主体实体骑在另一个实体上，则返回 true。|
| [is_skin_id](./list/is_skin_id.md) | 如果主题实体使用提供的皮肤 ID 号，则返回 true。|
| [is_sleeping](./list/is_sleeping.md) | 测试对象是否正在睡觉。|
| [is_sneak_held](./list/is_sneak_held.md) | 如果主题实体持有潜行输入，则返回 true。|
| [is_sneaking](./list/is_sneaking.md) | 测试对象是否潜行。|
| [is_snow_covered](./list/is_snow_covered.md) | 测试对象是否处于被雪覆盖的区域。|
| [is_target](./list/is_target.md) | 如果主题实体是调用实体的目标，则返回 true。|
| [is_temperature_type](./list/is_temperature_type.md) | 测试当前温度是否为给定类型。|
| [is_temperature_value](./list/is_temperature_value.md) | 根据 (0.0, 1.0) 范围内提供的值测试当前温度，其中 0.0 是最冷温度，1.0 是最热温度。|
| [is_underground](./list/is_underground.md) | 当主体实体位于地下时返回 true。 如果实体上方有非固体块，则该实体被视为位于地下。|
| [is_underwater](./list/is_underwater.md) | 当主体实体位于水下时返回 true。|
| [is_variant](./list/is_variant.md) | 如果主题实体是提供的变体编号，则返回 true。|
| [is_visible](./list/is_visible.md) | 如果主题实体可见，则返回 true。|
| [is_waterlogged](./list/is_waterlogged.md) | 测试主题块是否浸入水中。|
| [light_level](./list/light_level.md) | 测试实体是否超出指定的光照级别范围。 范围设置在 0 到 16 之间。|
| [moon_intensity](./list/moon_intensity.md) | 将当前月亮强度与 0.0 和 1.0 范围内的浮点值进行比较 |
| [moon_phase](./list/moon_intensity.md) | 将当前月亮强度与 0.0 和 1.0 范围内的浮点值进行比较 |
| [on_fire](./list/on_fire.md) | 测试对象是否着火。 |
| [on_ground](./list/on_ground.md) | 当主体实体位于地面时返回 true。 |
| [on_hot_block](./list/on_hot_block.md) | 测试对象是否处于热状态。 |
| [on_ladder](./list/on_ladder.md) | 当主题实体位于梯子上时返回 true。 |
| [random_chance](./list/random_chance.md) | 如果随机概率为 0 超出指定的最大范围，则返回 true。 |
| [rider_count](./list/rider_count.md) | 返回该实体的乘客数量。 |
| [surface_mob](./list/surface_mob.md) | 测试对象是否是地表生物。 |
| [target_distance](./list/target_distance.md) | 测试调用实体与其目标之间的距离。 |
| [trusts](./list/trusts.md) | 如果实体信任主体，则返回 true。 |
| [weather_at_position](./list/weather_at_position.md) | 根据提供的天气值测试实体位置的当前天气。 |
| [weather](./list/weather.md) | 测试实体当前正在经历的天气状态。 |
