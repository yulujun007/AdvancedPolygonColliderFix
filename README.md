# AdvancedPolygonColliderFix
about AdvancedPolygonCollider Fix

unity Asset Store 的插件 AdvancedPolygonCollider；
使用Atlas图集，在运行时出现问题。
原理：unity sprite在运行时，texture会替换为图集的texture,导致了碰撞的错位。

atlas 需要设置:
Tight Packing=false;
Read Enabled=true;
