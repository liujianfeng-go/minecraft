## 下面是 Minecraft 中实体生成规则的组件。

| 组件 | 描述 |
| --- | --- |
| [minecraft:biome_filter](./list/biome_filter.md) |  许创建者指定实体在哪个生物群系中生成。游戏中的每个生物群系都有一个或多个标签，用于确定实体在哪些生物群系中生成。 |
| [minecraft:brightness_filter](./list/brightness_filter.md) |  允许玩家设置导致给定实体生成的光照级别范围。 |
| [minecraft:delay_filter](./list/delay_filter.md) |  允许玩家在实体生成之前设置特定的时间延迟。 |
| [minecraft:density_limit](./list/density_limit.md) |  该组件允许玩家指定在给定位置生成的实体数量。 |
| [minecraft:difficulty_filter](./list/difficulty_filter.md) |  允许玩家设置特定实体在特定难度级别生成。 最小值是和平难度，最大值是困难难度。 |
| [minecraft:entity_types](./list/entity_types.md) |  是 Minecraft：基岩版使用的一种特定类型的 JSON 对象，用于封装某些行为和组件中使用的实体数据。 |
| [minecraft:height_filter](./list/height_filter.md) |  允许玩家设置实体生成的特定高度。 |
| [minecraft:herd](./list/herd.md) |  允许玩家确定动物群的大小。 |
| [minecraft:mob_event_filter](./list/mob_event_filter.md) |  允许玩家在特定事件中生成实体。 |
| [minecraft:operator](./list/operator.md) |  Minecraft：基岩版中的某些行为和过滤器可以使用算术运算符来比较两个给定数据点的值。 |
| [minecraft:permute_type](./list/permute_type.md) |  允许玩家指定将生成的实体的排列。 |
| [minecraft:player_in_village](./list/player_in_village.md) |  允许使用距离和村庄边界定义来过滤玩家是否在村庄中。 |
| [minecraft:spawns_lava](./list/spawns_lava.md) |  该组件确定实体是否生成岩浆。 |
| [minecraft:spawns_on_block_filter](./list/spawns_on_block_filter.md) |  允许实体在特定块上生成。 包括它们可能生成的块的字符串或字符串数组。 |
| [minecraft:spawns_on_block_prevented_filter](./list/spawns_on_block_prevented_filter.md) |  允许实体不在特定块上生成。 包含它们可能不会在其上生成的块的字符串或字符串数组。 |
| [minecraft:spawns_on_surface](./list/spawns_on_surface.md) |  允许实体在地面上生成。 添加组件会导致其为真，而删除组件会导致实体停止生成。 |
| [minecraft:spawns_underwater](./list/spawns_on_surface.md) |  允许实体在水下生成。 添加组件会导致其为真，而删除组件会导致实体停止生成。 |
| [minecraft:weight](./list/weight.md) |  允许玩家设置实体生成频率的优先级。 权重值较低的实体比权重值较高的实体生成的机会较低。 |
| [minecraft:world_age_filter](./list/world_age_filter.md) |  允许玩家根据世界中已经过去的时间来安排实体的生成。 |
